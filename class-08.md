# Reading 08 important Terms CSS
| Term   | Definition  |
|---|---|
| **normal flow**  |  The position property in CSS allows for the modification of page layout. If the property is unmodified, it is called 'normal flow.' Each block element appears on a new line, below the previous one. |
```css
{
    position: static;
}
```
|  |  |
|---|---|
| **relative positioning**  |  An element with relative positioning is shifted away (from the top, bottom, left, or right) from where it would have been placed. This does not affect the surrounding elements.  |
```css
{
    position: relative;
}
```
|  |  |
|---|---|
| **absolute positioning**  |  Positioning an element in relation to its containing element. This does not disrupt normal flow, and absolute positioned elements move up and down as the user scrolls. |
```css
    {
        position: absolute;
    }
```
|  |  |
|---|---|
| **fixed positioning**  |  a type of absolute positioning that fixes an element to the window, and not an element. Do not affect surrounding elements, but do not move when the user scrolls up and down.  |
```css
{
    position: fixed;
}
```
|  |  |
|---|---|
| **floating an element**  |  taking an element out of normal flox and putting it to the far left or right of a box.  |
```css

```
|  |  |
|---|---|
| **floating an element**  |  taking an element out of normal flox and putting it to the far left or right of a box.  |
```css
elementName {
    float: right;
}
```
|  |  |
|---|---|
| **clear**  |  elements with the clear style dictates that no element, in the same containing element, can touch the right, left, neither or both sides of the box.  |
```css
p {
    clear: both;
}

```
