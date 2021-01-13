# readme

## html

- DSL
- HTML v5.x
- hypertext markup language
- structure and content
- semantic web
- element = tag + attribute + content
- tag = name of an element
- attribute = property of an element, defined at the open tag
- element = combination open and closed tag, can have self closed
- required html elements for basic page
    - <!doctype html>, <html>, <head>, <body>
- head = information about the web page
- body = content to be displayed to the user/viewer

- history
    - html 1
    - html 2
    - html 3
    - html 4
    - html 4.1 + xhtml1 = adobe dreamweaver, microsoft frontpage, wysiwyg tooling, 
    - html 4.1 + xhtml2
    - W3C + WHATWG (Apple, Google, Mozilla, Opera)
    - html v5
    - html
- features of HTML5 
    - semantic web, user proper tages to structure content
    - header, section, nav, atricle, aside, footer, small (smallprint/footnote), main, i (icon)
    - native support for <audio>, <video>, <media>
    - drawing using <canvas>
    - web accessibility, microdata, RDFa
    - spacing = block element, inline element
    - storage = session, local 
    - location
- block = width of viewport
- inline = only necessary width of viewpoint

## css

- cascading stylesheet
- styling and presentaiton
- precendence and specificity
- external < user stylesheet < browser < internal < inline
- (0, 0, 0, 0) = !important, id, class, tag
- adaptive web design = styling for specific screen sizes
- responsive web design = styling for any viewport
- media query = leverage the device properties/specification, (resolution, screen, print, aspect)
- box model = margin, border, padding, content
    - margin = spacing between elements
    - border = edge of the element
    - padding = space between edge and content
    - content = everything to be displayed
- box sizing = content size or border size
- selectors = <*>, <tag>, <.class>, <tag.class>, <#id>, select html element to style
- combinator selectors
    - <selector selector> = ancestor-descendant, all related
    - <selector1 > selector2> = parent-child, directlry related
    - <selector1 + selector2> = next sibling, direct-sibling
    - <selector1 ~ selector2> = any position sibling
- pseudo-class, pseudo-element
    - <a:link>, <a:active>, <a:hover>, <input:focus>, <input:blur>
    - <div::before>, <div::after> (styling purposes)

## dom

- document object model
- tree-like structure, where each elementis a node
- see css selectors
- events = event capturing, event bubbling (JS)

## mvc 

- http request lifecycle, mvc request lifecycle
- benefits = modularity (separation of concern)
- drawbacks = more complexity, competency, mid-to-large projects
- design pattern
- implementations for MSFT in ASP.NET MVC
- aspnet is server technology = web (html, css, static content), application (dynamic content, html, css, csharp)
- data binding = weak-typed view (viewbag, viewdata, tempdata), strong-typed view (viewmodel, model)
- view = partial view, view, layout 
- webpage = laout + view + 0 or more partial views 