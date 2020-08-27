#-----COMO USAR A EXTENSÃO----#

- Dentro do painel de admin open cart > Extensões > Instalador

- Fazer o upload do OC_img_hover.ocmod.zip que irá rodar o arquivo .xml

- Em seguida adicione em seu stylesheet.css as classes css encontradas no arquivo oc-image-hover.css ou aqui em baixo:

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
