# duo-web

## acerca de

sitio web de duo, estudio de diseño y fabricación digital hecho en chile.

el sitio está publicado en [emiguerra.github.io/duo-web](https://emiguerra.github.io/duo-web/) con github pages. es una sola página en html, css y javascript, sin frameworks ni proceso de compilación.

## subcarpetas

- [assets](./assets/)
  - [img](./assets/img/): fotografías de proyectos, productos y servicios
  - [firma](./assets/firma/): logo para la firma de correo
  - [absans-main](./assets/absans-main/): tipografía absans y su licencia
- [index.html](./index.html): el sitio completo

## secciones

| n°  | sección   | id           | contenido                                                         |
| --- | --------- | ------------ | ----------------------------------------------------------------- |
| —   | hero      | `#hero`      | hacemos objetos \*( ) únicos                                      |
| 01  | tienda    | `#tienda`    | productos disponibles, compra por whatsapp                        |
| 02  | servicios | `#servicios` | impresión 3d, corte láser, modelado 3d y renders, planimetrías, electrónica, sitios web |
| 03  | proyectos | `#proyectos` | floreros, uzu 001, uzu 002, wearable                              |
| 04  | nosotros  | `#nosotros`  | proceso de trabajo                                                |
| 05  | contacto  | `#contacto`  | formulario de pedidos                                             |

## pedidos

el formulario de contacto envía cada pedido a una planilla de google sheets mediante google apps script. el archivo que adjunta el cliente se guarda en google drive y duo recibe un aviso por correo. las cotizaciones se revisan, aprueban y envían desde la planilla, que es privada.

## tipografías

| nombre           | uso                                  | origen                                               |
| ---------------- | ------------------------------------ | ---------------------------------------------------- |
| pp neue bit      | logo, titulares pixelados            | pangram pangram, archivo local                       |
| absans           | textos, navegación, títulos          | collletttivo, sil open font license 1.1, archivo local |
| instrument serif | titulares y nombres de servicios     | google fonts                                         |
| ibm plex mono    | etiquetas en mayúscula, precios      | google fonts                                         |

## cómo actualizar

los archivos de trabajo están en la carpeta `web duo`. para publicar un cambio:

```bash
cd ~/Desktop/duo/duo-web-publicar
cp "../web duo/index.v0.0.5.html" index.html
cp -R "../web duo/assets/img" assets/
git add .
git commit -m "describe el cambio"
git push
```

github pages actualiza el sitio en uno o dos minutos. el link no cambia.

## licencia

© 2026 duo. todos los derechos reservados sobre la marca, las fotografías y los textos.
