# Fixed ratio CSS container:
```html
<div id="container">
    <div id="dummy"></div>
    <div id="element">
        some text
    </div>
</div>
```
```css
#container {
    display: inline-block;
    position: relative;
    width: 50%;
}
#dummy {
    margin-top: 75%; /* 4:3 aspect ratio */
}
#element {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: silver /* show me! */
}
```
