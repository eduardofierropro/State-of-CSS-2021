# ¿Qué hay en este repo?
Este repo está hecho en directo desde el canal de [Twitch de Eduardo Fierro Pro](https://twitch.tv/eduardofierropro) y estará resubido en 3 partes en mi canal de [Youtube](https://youtube.com/EduardoFierroPro?sub_confirmation=1)

Lo que hacemos en este repo es revisar y repasar la documentación oficial con pequeños ejemplos reales las próximas novedades de CSS que se ven en la encuesta de State of CSS 2021.

***Te agradecería que si usas este repo para mostrarlo en tu canal de Youtube o Streaming en Twitch me menciones porque es muy... ¡De frontends!🥰***

# ¿Qué es State of CSS?
Es una encuesta que se realiza cada año a diferentes desarrolladores (tú también puedes hacerla desde su web) y nos permite saber nuestros conocimientos como developers.

En este archivo tienes los diferentes enlaces más "oficiales" sobre cada una de las estas propiedades.

# 🚨 **¡No te preocupes!** 🚨
La gran mayoría de estas propiedades no se usarán hasta dentro de unos años.
Todas pasan por un proceso de validación de la W3C.

Si no sabes lo que es la W3C, entonces [mira este vídeo](https://www.youtube.com/watch?v=3dDr6hax31w).

## Leyenda

* 🧪 Experimental: Esta propiedad es experimental y la definición que escribo en este repo puede cambiar en el futuro.
* 🤷‍♂️ No he encontrado información: No he encontrado información sobre esta propiedad ni en documentos oficiales ni en "tutoriales". Si alguien encuentra o sabe del tema que nos avise por discord o aquí en Github.

## Diseño
### CSS Grid
Nos permite hacer rejillas dentro de una etiqueta 
* [Oficial Level 1](https://www.w3.org/TR/css-grid-1/)
* [Oficial Level 2](https://www.w3.org/TR/css-grid-2/)
* [Enlace a W3Schools](https://www.w3schools.com/css/css_grid.asp)
* [Enlace a CanIUse](https://caniuse.com/?search=grid)

### Subgrid
Es un valor que nos permite es "heredar" el número de columnas y rows de una etiqueta contenedora.
* [Oficial Level 2](https://www.w3.org/TR/css-grid-2/#subgrids)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Subgrid)
* [Enlace a CanIUse](https://caniuse.com/?search=subgrid)

### Flexbox
Es una forma de maquetación que nos permite organizar elementos en columnas y filas.
* [Enlace oficial a W3C](https://www.w3.org/TR/css-flexbox-1/)
* [Mozilla Developer](https://www.w3schools.com/css/css3_flexbox.asp)
* [Enlace a W3Schools](https://www.w3schools.com/css/css3_flexbox.asp)
* [Enlace a CanIUse](https://caniuse.com/flexbox)

### Multi-column
Es una forma de maquetación que nos permite organizar elementos hijos en columnas dentro de una contenedora.
* [Enlace oficial a W3C](https://www.w3.org/TR/css-multicol-1/)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Columns/Using_multi-column_layouts)
* [Enlace a W3Schools](https://www.w3schools.com/cssref/css3_pr_column-count.asp)
* [Enlace a CanIUse](https://caniuse.com/?search=column-count)

### Modos de escritura en CSS
Nos permiten cambiar la orientación de todo nuestro contenido web, en base a las formas de escritura "de mano".
* [Enlace oficial a W3C](https://www.w3.org/TR/css-writing-modes-3/)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/writing-mode)
* [Enlace a W3Schools](https://www.w3schools.com/cssref/css3_pr_writing-mode.asp)
* [🚨Enlace a CanIUse](https://caniuse.com/?search=writing-mode)

### position:sticky
Es un position que nos permite es hacer que una etiqueta sea relative al inicio y fixed cuando toca un borde de la ventana.
* [Enlace oficial a W3C](https://www.w3.org/TR/css-position-3/#sticky-positioning)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/position)
* [Enlace a W3Schools](https://www.w3schools.com/howto/howto_css_sticky_element.asp)
* [🚨Enlace a CanIUse](https://caniuse.com/?search=sticky)

### Propiedades Lógicas: margin-block-start, padding-inline-end
Nos permiten es "simplificar" el uso de propiedades de box-model (propiedades físicas) en base al writting-mode; es decir, con "propiedades lógicas".

* [Enlace oficial a W3C](https://drafts.csswg.org/css-logical/)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Logical_Properties)
* [Enlace a CanIUse](https://caniuse.com/?search=logical)
* [Enlace a CSS Tricks](https://css-tricks.com/css-logical-properties-and-values/)

### Aspect-ratio

Nos permite especificar el ratio de un elemento sin darle un tamaño previo. Se usa en conjunto a object-fit: cover.

* [Enlace oficial a W3C](https://www.w3.org/TR/css-sizing-4/#aspect-ratio)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio)
* [Enlace a Web.dev](https://web.dev/aspect-ratio/)
* [Enlace a Can I Use](https://caniuse.com/?search=aspect-ratio)

### Content-visibility

Mejora el rendimiento, haciendo que una etiqueta que no se encuentre en el viewport (no se vea) NO se renderize, mejorando así la carga de la web.

* [Enlace oficial a W3C](https://www.w3.org/TR/css-contain-2/#content-visibility)
* [Enlace a Can I Use](https://caniuse.com/?search=content-visi)


### Gap for Flexbox
Nos permite evitar usar "margin"

* [Enlace oficial a W3C](https://www.w3.org/TR/css-align-3/#gaps)
* [Enlace a Can I Use](https://caniuse.com/flexbox-gap)

### Break Rules

* [🚨Enlace oficial a W3C](https://www.w3.org/TR/css-text-4/)

### Container Queries

Es una regla de CSS3 que nos permite aplicar técnicas "responsive" a una etiqueta hija en base al tamaño de su contenedora.

* [Enlace oficial a W3C](https://drafts.csswg.org/css-contain-3/)
* [Enlace a Can I Use](https://caniuse.com/?search=%40container)

## Formas y gráficos

### Shapes

Nos permiten que el texto se adapte a la forma del elemento, en base a la propiedad "shape-outside".

* [Documentación W3C](https://drafts.csswg.org/css-shapes-2/)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-outside)
* [Enlace a CanIUse](https://caniuse.com/?search=shape)


### object-fit

Nos permite configurar el tamaño de la imagen dentro de una ```<img>``` y lo podemos combinar con la propiedad ```object-position```.

* [Documentación W3C](https://www.w3.org/TR/css-images-3/)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/object-fit)
* [Enlace a CanIUse](https://caniuse.com/?search=object-fit)
* [Ejemplo](https://bennettfeely.com/clippy/)

### clip-path

Nos permite generar formas (que pueden usarse como máscara) para etiquetas.

* [Documentación W3C](https://www.w3.org/TR/css-masking-1/#the-clip-path)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
* [Enlace a CanIUse](https://caniuse.com/?search=clip-path)

### CSS Masks

* [Documentación W3C](https://www.w3.org/TR/css-masking-1/)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
* [Enlace a CanIUse](https://caniuse.com/?search=mask)
* [Enlace a CSS Tricks](https://css-tricks.com/almanac/properties/m/mask-image/)

### Blend Modes

Son efectos para colocar en etiquetas o imágenes basadas en los efectos de capa de Photoshop. Y existen dos tipos, los ```mix-blend-mode``` y los ```blend-mode```.

* [Documentación W3C](https://www.w3.org/TR/compositing-1/#propdef-background-blend-mode)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/mix-blend-mode)
* [Enlace a CanIUse](https://caniuse.com/?search=blend-mode)

### CSS Filter Effects

Nos permite aplicar efectos de filtro a una imagen. Efectos como blur, grayscale, saturate, etc.

* [Documentación W3C](https://www.w3.org/TR/filter-effects-1/)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/filter)
* [Enlace a CanIUse](https://caniuse.com/?search=filter)
* [Generador online](https://www.cssfiltergenerator.com/)

### backdrop-filter

```backdrop-filter``` Nos permite aplicar un efecto de desenfoque al fondo de una imagen y se combina con un background en rgba().

* [Documentación W3C](https://drafts.fxtf.org/filter-effects-2/#BackdropFilterProperty)
* [Enlace a CanIUse](https://caniuse.com/?search=backdrop)

### color-gamut

Es una regla usada para configurar los colores segun el perfil de pantalla.

* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/color-gamut)
* [Enlace a CanIUse](https://caniuse.com/?search=color-gamut)

### perspective

Nos permite configurar el punto de fuga al hacer transformaciones.

* [Documentación W3C](https://drafts.csswg.org/css-transforms/#perspective)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/perspective)
* [Enlace a CanIUse](https://caniuse.com/?search=perspective)

### Intrinsic Sizing

Valores que podemos usar en las propiedades como width, height... y que no se centran en la etiqueta sino en su contenido.

* [Documentación W3C](https://www.w3.org/TR/css-sizing-3/#intrinsic-sizes)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Glossary/Intrinsic_Size)
* [Enlace a CanIUse](https://caniuse.com/?search=intri)

### conic-gradient

Son degradados de ángulo conocidos como conic gradients.

* [Documentación W3C](https://www.w3.org/TR/css-images-4/#conic-gradients)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient())
* [Enlace a CanIUse](https://caniuse.com/?search=conic-gradients)
* [Generator](https://learnui.design/tools/gradient-generator.html)

### color()

Es una función que nos permite configurar un color para un perfil de pantalla personalizado.

* [Documentación W3C](https://drafts.csswg.org/css-color/#color-function)
* [Enlace a CanIUse](https://caniuse.com/css-color-function#:~:text=The%20CSS%20color()%20function,the%20default%20sRGB%20color%20space.)


### accent-color

Nos permite cambiar el color por defecto de ciertos elementos en HTML como radius o checkboxes.

* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/accent-color)
* [Enlace a CanIUse](https://caniuse.com/?search=accent)

## Interacciones
### CSS Scroll Snap

Nos permite que cuando deslizemos / scroll en la página los elementos se centren sólo con CSS. Sustituto de Javascript.

* [Documentación W3C](https://www.w3.org/TR/css-scroll-snap-1/)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Scroll_Snap)
* [Enlace a CSS Tricks](https://css-tricks.com/practical-css-scroll-snapping/)
* [Enlace a CanIUse](https://caniuse.com/?search=snap)

### overscroll-behavior

Cuando hacemos scroll en una etiqueta con overflow-x / overlow-y en hidden, la rueda del ratón no afecta al scroll de una contenedora o la página.

* [Documentación W3C](https://drafts.csswg.org/css-overscroll-1/)
* [Enlace a CanIUse](https://caniuse.com/?search=overscroll)

### overflow-anchor

🚨 Esta propiedad está activada por defecto en los navegadores que lo soportan. *(No hay ejemplo de esta propiedad)*

En el caso de que añadamos contenido mediante Javascript a una <contenedora> con overflow-anchor el contenido se centra en lo que estábamos viendo: aunque cambie la altura de la <contenedora>.

* [Documentación W3C](https://drafts.csswg.org/css-scroll-anchoring/)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-anchor)
* [Enlace a CanIUse](https://caniuse.com/?search=overflow-anchor)

### touch-action

Nos permite configurar qué eventos de "pantalla" podemos usar con un elemento, es decir si podemos hacer scroll, pinch, etc.

🚨 A nivel de Accesibilidad es recomendable no usar ```touch-action: none```.

* [Documentación W3C](https://www.w3.org/TR/pointerevents/#the-touch-action-css-property)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/touch-action)
* [Enlace a CanIUse](https://caniuse.com/?search=touch-action)

### pointer-events

Nos sirve para desactiva o activar los punteros de ratón en un elemento mediante CSS.

* [Documentación W3C](https://wiki.csswg.org/spec/css4-ui#pointer-events)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events)
* [Enlace a CanIUse](https://caniuse.com/?search=pointer-events)

### scroll-timeline

Nos permite hacer efectos de Parallax en Scroll con CSS.

* [Documentación W3C](https://drafts.csswg.org/scroll-animations-1/)
* [Guía de CSS Tricks](https://css-tricks.com/practical-use-cases-for-scroll-linked-animations-in-css-with-scroll-timelines/)
* [Enlace a CanIUse](https://caniuse.com/css-scroll-timeline)
* [Vídeo en Youtube](https://www.youtube.com/watch?v=jpzG_WV6DBg)

## Tipografías
### font-variant-*

Nos permiten configurar cómo las ligaduras opciones de configuración de los textos.

* [Documentación W3C](https://drafts.csswg.org/css-fonts-4/#propdef-font-variant-alternates)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant)
* [Enlace a CanIUse](https://caniuse.com/?search=font-variant)

### initial-letter

Establece el nº de líneas que ocupa la primera letra.

🚨 No parece que funcione ni en Safari.

* [Documentación W3C](https://www.w3.org/TR/css-inline/#initial-letter-styling)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/initial-letter)
* [Enlace a CanIUse](https://caniuse.com/?search=initial-letter)


### font-variant-numeric

Nos permite configurar los glifos, fracciones... de una tipografía.

* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-numeric)

### font-display

Nos sirve para confirgurar la forma de cargar la fuente.

* [Documentación W3C](https://www.w3.org/TR/css-fonts-4/#font-display-desc)
* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/CSS/@font-face/font-display)
* [Enlace a CanIUse](https://developer.mozilla.org/es/docs/Web/CSS/@font-face/font-display)

### line-clamp

Nos permite definir por un lado el número de líneas que se pueden mostrar en un elemento. Y el símbolo de los ```...``` al final de esas líneas. Como un "Read More".

* [Documentación W3C](https://drafts.csswg.org/css-overflow-3/#propdef--webkit-line-clamp)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-line-clamp)
* [Enlace a CanIUse](https://caniuse.com/?search=line-clamp)
* [Enlace a CSS Tricks](https://css-tricks.com/almanac/properties/l/line-clamp/)


### Variable Fonts

Son propiedades para una tipografía editable que se añaden dentro del @media.

En vez de enlazar 20 tipografías podemos definir múltiples valores para una misma tipografía y ahorrar carga.

* [Documentación W3C](https://drafts.csswg.org/css-fonts-4/#font-variation-settings-def)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Fonts/Variable_Fonts_Guide)
* [Enlace a CanIUse](https://caniuse.com/?search=variable-font)

## Accesibility

### prefers-reduced-motion

Es un breakpoint de dispositivo que nos permite aplicar propiedades (normalmente animation) cuando el usuario ha seleccionado la opción de "Reducir movimiento".

* [Documentación W3C](https://drafts.csswg.org/mediaqueries-5/#prefers-reduced-motion)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion)
* [Enlace a CanIUse](https://caniuse.com/?search=prefers-reduced)

### prefers-color-scheme

Es un breakpoint de dispositivo que nos permite configurar propiedades CSS dependiendo de la configuración de color del sistema operativo, es decir del "Dark Mode".

* [Documentación W3C](https://drafts.csswg.org/mediaqueries-5/#prefers-color-scheme)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)
* [Enlace a CanIUse](https://caniuse.com/?search=prefers-color)

### prefers-reduced-data

Es un breakpoint de dispositivo que nos permite definir si algo en CSS (tipografía, ...) se carga o no dependiendo de si el usuario ha definido.

* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-data)
* [Enlace a CanIUse](https://caniuse.com/?search=prefers-reduced-data)

### color-contrast()

Nos permite de una lista de colores en CSS determinar el color que mejor con más contraste.

* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color-contrast())
* [Enlace a CanIUse](https://caniuse.com/?search=color-contrast())

### color-scheme 🧪

Se debería de usar en conjunto con `prefers-color-scheme` y nos permite que el navegador configure los colores que nosotros no podemos modificar de ciertos elementos como formulario o barras de scroll cuando el usuario esté usando el lightmode o darkmode.

* [Documentación W3C](https://drafts.csswg.org/css-color-adjust/#color-scheme-prop)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS/color-scheme)
* [Enlace a CanIUse](https://caniuse.com/?search=color-scheme)


### tabindex 🤷‍♂️

No he encontrado información sobre el tema, lo más relevante sería el `tabindex` de HTML pero es un atributo de HTML que funciona desde IE 7.

* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes/tabindex)


### ARIA HTML Attributes (role, aria-label, etc.)

Atributos usados para la accesibilidad de una web y son atributos que se colocan en los elementos HTML.

* [Mozilla Developer](https://developer.mozilla.org/es/docs/Web/Accessibility/ARIA)
* [Enlace a CanIUse](https://caniuse.com/?search=role)



## Otras características
### Variables (Propiedades Custom)
### Comprobando Características Soportadas (@supports)
### CSS Containment
### will-change
### calc()
### Houdini
### Funciones de Comparación
### Houdini Custom Properties
### ::marker

## Pre-/Post-procesadores
### Sass
### Less
### PostCSS
### Stylus
### Assembler CSS
### Assembler CSS

## CSS Frameworks
### Bootstrap
### Materialize CSS
### Ant Design
### Semantic UI
### Bulma
### Foundation
### UIKit
### Tachyons
### Primer
### Tailwind CSS
### PureCSS
### Halfmoon


## CSS-in-JS
### Styled Components
### JSS
### Styled JSX
### Emotion
### CSS Modules
### Styled System
### Stitches
### Fela
### Linaria
### Astroturf
### Twin
### Theme UI
### vanilla-extract
### Windi CSS
### Windi CSS

## Otras herramientas
### Utilities
#### Stylelint
#### PurgeCSS
#### PurifyCSS
#### Prettier
#### Autoprefixer
#### cssnano
#### ACSS

### Blogs:
#### CSS-Tricks
#### A List Apart
#### Smashing Magazine
#### Codrops
#### SitePoint
#### Dev.to
#### Sidebar
#### HeyDesigner
#### CSS Weekly
#### Frontend Horse
#### Frontend Focus
#### CSS { In Real Life }
#### Modern CSS Solutions
#### Medium


## Autor ✒️
**Eduardo Fierro** - *Documentación y trabajo inicial*
* [Youtube](https://youtube.com/EduardoFierroPro?sub_confirmation=1)
* [Twitch](https://twitch.tv/eduardofierropro)
* [TikTok](https://www.tiktok.com/@eduardofierro.pro?)
* [Github](https://github.com/eduardofierropro)
* [Instagram](https://instagram.com/eduardofierro.pro)
* [Twitter](https://twitter.com/edfierropro)

## Master/Cursos donde sor profesor 📚
Soy profesor en la Escuela Trazos donde impartimos Cursos y Másters sobre desarrollo web con una bolsa de trabajo con Alta Empleabilidad. ¡Píde información sobre los cursos donde soy profesor desde este enlace!

👉[https://trazos.net/contacto-eduardofierro](https://trazos.net/contacto-eduardofierro)

## Licencia 📄
MIT Public License v3.0
No puede usarse comencialmente.




* [Documentación W3C]()
* [Mozilla Developer]()
* [Enlace a Web.dev]()
* [Enlace a W3Schools]()
* [Enlace a CanIUse]()