[place styling into page header](./styling.css)

[source code for a full 3 wide layout (single row)](./html.html)

the HTML code is a 3 wide image display with hover text (going vertical on small screen size)

```<div class="containerHorizontal"> </div>```

this container div is the thing that makes stuff go horizontally / vertically (it must be on the outside of all the image blocks)

```
 <div class="imageOverlayContainer">
  <div class="overlayEffect">
    <div class="imageTitleTextContainer">
      <h1 class="imageTitleText">
        TEXT TO APPEAR ON THE HOVER
      </h1>
    </div>
  </div>
  <img
    class="imageWithOverlay"
    src="IMAGE SRC"
  />
</div>
```

this block above is a SINGLE image block.

change TEXT TO APPEAR ON THE HOVER to be the text you want to appear when hovering over the image

change IMAGE SRC to be the location of the image to appear.

copy and paste this block between the `<div class="containerHorizontal">` and `</div>` tags to make them appear horizontally or vertically

for a new row, add a new `<div class="containerHorizontal"> [IMAGES HERE] </div>`
