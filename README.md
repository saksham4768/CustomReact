# CustomReact
Behind the scene how react rendor the element.

Step 1:- Create the root containter in which rendor the element. (i.e root div)

step 2:- Create Element which has a some properties (i.e type of Element(anchor, p, h1 etc tag), Properties(href, target), children of that element) which is want to rendor by the element.

step 3:- Create the custom Render function which rendor the react Element.

        Following steps to render the any element:- (a) Create the DomElement with the help of type of element
                                                   (b) Add the children in DomElement by using innerHTML or innerText
                                                   (c) Add Properties in DomElement using setAttributes
                                                   (d) At last append the DomElement in Root Element for render the Element


