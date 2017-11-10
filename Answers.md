1. What is the difference between server side routing and client side routing?

    Server side routing is when you click on any website and it redirects you to an entire new page.

    Client side routing is happening when the user clicks on the website and it is loading internally by JavaScript. This could be the modification or creation of a new component, or a request of data. Some of the elements might change but not the entire website.

2. Mention some advantages of using cient side routing.
    The routing between views is faster beacuse usually less data is porcessed.
    The transitions and animations are easier to implement beause you can reuse cpda and data.
    The DOM elements can be reuse.

3. Which component is used to define a route and what props are commonly added to it?
    The React-Router

4. How can I make sure that the component associated with the "/" route us not displayed for every other route?
    With a contextual router that can be mounted under another router, but is not aware of the global router with location.parthname and they only unmatched part of the parent router.
    