# Reading 11

## CSS
| Event  | Definition  |
|---|---|
| **Images**  |  CSS has the power to manipulate images in a number of ways. It can change size using the height and width properties, have their alignments to left, right, or center (and everything in between). If an image is in a background, CSS can be used to make it fill the entire background. By default, a background image will repeat until it fills the entire page. However, using background-repeat: repeat-x or repeat-y will repeat the image either horizontally or vertically respectively. Using no-repeat will prevent the image from repeating at all, fixed will keep it in place, and scroll will make the image move as the user scrolls. (examples below)
```cs
    img {
        width: 100px;
        height: 100px;
        float: left;
        margin-right: 10px;
    }
    img.center {
        width: 100px;
        height: 100px;
        display: block;
        margin: 0px auto;
    }

    body {
        background-image: url("goes.here");
        background-repeat: repeat-x;
    }

    /*below are examples of using CSS to add interactivity to a button or other parts of a site*/
    button:hover {
        background-position: 0px -40px; /*gives the impression that the user is pressing down on a button*/
    }
```












