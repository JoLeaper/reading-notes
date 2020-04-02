# Reading 03 Important Terms for HTML and JS

## HTML
| Term   | Definition  |
|---|---|
| **link**  |  Wrapping text in  < a href ='url' > < /a > tags transforms it into a hyperlink, redirecting the user from the specified html.  |
| **relative link**  |  When creating a link, if the link is in the same domain, then you can direct to it using a relative link.  |
| **mail link**  |  Wrapping text in  < a href = > < /a >  will give you a link, but if href is pointing to an email address, it will open a window that will allow the user to send to the specified email. |
| **new window link** | After the url, you can set target to a value, which is where the webpage will open. By default it will open in the same tab, but if target='_blank' it will open up a new window. |
|**same page link** | If you want a link to take you to a different part of the same webpage, href should be set to the name of the section (ex: href=#sectionName).


## JavaScript
| Term   | Definition  |
|---|---|
| **function**  |  A code that can be called to perform a set of tasks or calculate a value, then returns a value. Declared like function name(parameters) {}  |
| **multi-return-function**  |  A function can return multiple things. To do this, what is being returned should be stored in an area. Then, to access the value, you must add the index of the area to the end of the function when it is called. (ex: if the function getSize returns [area, volume], then you can get the value by calling getSize(x, y, z)[0] or [1]) |
| **declared function**  |  When written as follows: function name(parameters) {}, this is considered a declared function. Before running any scrips, interpreters will find declared functions first. |

