<h3> HOW TO USE THE EXTENSION </h3>

- Inside the admin panel open cart> Extensions> Installer

- Upload OC_img_hover.ocmod.zip which will run the .xml file

- Then add in your stylesheet.css the css classes found in the file oc-image-hover.css or below:

<quote> Note: the image that will appear with the mouse hover will always be the second image for the product. </quote> 

```css
.product-thumb .image2 {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  opacity: 0;
  visibility: hidden;
  z-index: 1;
  transition: all 0.5s ease-in-out;
}
.product-thumb .image:hover .image2 {
  opacity: 1;
  visibility: visible;
}
```
