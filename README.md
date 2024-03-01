# Portafolio básico con JavaScript
___
## Primera estructura básica
___
### Estructura HTML (`index.html`)

1. **Doctype y Lenguaje**: La declaración `<!DOCTYPE html>` indica que este documento es HTML5. El atributo `lang="en"` en la etiqueta `<html>` especifica que el idioma principal del documento es el inglés.
    
2. **Head**:
    
    - **Meta Etiquetas**: Se establecen la codificación de caracteres como UTF-8 y la configuración de la ventana gráfica para dispositivos móviles.
    - **Enlaces Externos**: Se incluye un enlace a la hoja de estilos de Font Awesome para íconos y otro a tu hoja de estilos personalizada (`estilo.css`).
3. **Body**:
    
    - **Contenedor Principal `.inicio contenedor`**: Este div actúa como contenedor principal de tu portafolio, aplicando estilos para centrar su contenido y darle formato.
    - **Elementos de Texto**: Títulos (`h3`, `h1`) y párrafo (`p`) introducen al usuario, destacando tu nombre y tu rol como Desarrollador FullStack.
    - **Botones `.contenedor-botones`**: Dos botones ofrecen interacción, uno para descargar tu CV y otro para establecer contacto.
    - **Imagen `.contenedor-img`**: Un contenedor para una imagen que probablemente te represente o esté relacionada con tu trabajo.
    - **Redes Sociales `.contenedor-redes`**: Enlaces a tus perfiles de GitHub y LinkedIn, usando íconos de Font Awesome.

### Estilos CSS (`estilo.css`)

1. **Reset y Fuentes**: Se establece un reset básico (márgenes a 0, uso de `box-sizing`) y se importa la fuente 'Oxygen' de Google Fonts para usarla en todo el documento.
    
2. **Fondo y Comportamiento de Scroll**: El color de fondo de `body` se establece en un tono oscuro, y el comportamiento de desplazamiento (`scroll-behavior`) suave permite una transición fluida entre secciones del sitio.
    
3. **Estilos del Contenedor**:
    
    - `.contenedor`: Define el ancho máximo para centrar el contenido y aplicar márgenes automáticos.
    - `.inicio`: Configura el contenedor principal con flexbox para centrar vertical y horizontalmente su contenido, con un fondo, color y relleno específicos.
4. **Estilos de Texto y Botones**:
    
    - Títulos y párrafos (`h3`, `h1`, `p`) reciben estilos específicos para tamaño, color, y espaciado.
    - `.btn` y `.btn2`: Se definen estilos para los botones, incluyendo color, fondo, bordes, y transiciones. `.btn2` tiene estilos adicionales para diferenciarse, como un fondo de color verde y un color de texto contrastante.
    - `:hover` sobre `.btn`: Se añade un efecto de sombra al pasar el mouse para mejorar la interactividad.
5. **Imagen y Redes Sociales**:
    
    - `.contenedor-img` y `img`: Se aplican estilos para formatear la imagen y su contenedor, como un degradado, tamaño, y bordes redondeados.
    - `.contenedor-redes` y `a`: Los enlaces de redes sociales se posicionan de manera absoluta y se les aplica color, tamaño, y efectos de transición para mejorar la visibilidad y la interacción.

#### Recursos 
- **link de font awesome:** https://cdnjs.com/libraries/font-awesome
- **Iconos**: https://fontawesome.com/search
- **Fuente para importar en css:** https://fonts.google.com/
![Pasted image 20240227135758](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/8dc347a9-a7f6-4bce-b42c-3318d9ca7fbc)

![Pasted image 20240227152917](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/674a2d37-3f83-4d7a-aaa8-bb12747a6119)

## Menú de navegación
La sección nueva añadida al HTML es un menú de navegación, específicamente diseñado para mejorar la interactividad y la navegabilidad de tu sitio web. Este menú incluye enlaces a diferentes secciones de la página, como "Inicio", "Sobre mí", "Experiencia", "Portafolio" y "Contacto". Cada uno de estos enlaces está acompañado de un icono representativo, lo que mejora la experiencia del usuario al proporcionar pistas visuales sobre el contenido de cada sección. Aquí hay un desglose de los elementos clave añadidos:

 ***HTML***

- **`<nav class="navigation">...</nav>`**: Es el contenedor del menú de navegación. Se posiciona de manera fija en la parte inferior de la pantalla para que esté siempre accesible, sin importar dónde se encuentre el usuario en la página.
- **`<ul>...</ul>`**: Define la lista de enlaces de navegación. Cada item (`<li>`) de esta lista representa un enlace a una sección diferente del sitio web.
- **`<li class="list active">...</li>`**: Cada item de la lista contiene un enlace (`<a>`) con un icono (`<i>`) y texto descriptivo. La clase `active` indica el elemento actualmente activo o la sección en la que se encuentra el usuario.
- **`<div class="indicator"></div>`**: Este es un elemento visual que sirve como indicador del item activo en el menú de navegación, mejorando la experiencia de usuario al proporcionar una retroalimentación visual clara.

 ***CSS***

- **Estilización del `.navigation`**: Se define el estilo del contenedor del menú de navegación, incluyendo su posición fija, tamaño, color de fondo, y otros atributos visuales para hacerlo destacar y ser fácilmente accesible.
- **Estilización de `ul`, `li`, `a`, y `.text`**: Se establecen los estilos para la lista y sus elementos, incluyendo la disposición, el color, la tipografía, y las transiciones para los iconos y el texto. Estos estilos aseguran que el menú sea visualmente atractivo y que las interacciones (como pasar el mouse sobre los items) sean fluidas y respondan a las acciones del usuario.
- **`.indicator`**: El estilo para el indicador visual que muestra el item activo en el menú. Se utiliza para crear un efecto visual distintivo que se mueve y se adapta en respuesta a la interacción del usuario, destacando la sección actual del sitio web.
- 
![Pasted image 20240227180450](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/f6e4df81-45fd-4c23-8745-fbd7a6be8725)


***JavaScript***
![Pasted image 20240227183735](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/f0407a84-5fa9-4e3d-8201-1d45072a76ed)

![Pasted image 20240227184021](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/e0b127a3-ebd3-4387-8a04-8d877a03ff8c)




## Sobre mí

![Pasted image 20240228164757](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/4b68b1be-9970-44de-90ce-e843c361fc87)

![Pasted image 20240228165304](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/a24be9d5-7111-408e-8f21-6abac9a62eed)



## Experiencia

![Pasted image 20240228174346](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/43615d86-aa75-475d-8e67-a20529bbcc00)

![Pasted image 20240228174420](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/b822f696-42bf-4b02-819d-5e336149e71b)

## Portafolio

![Pasted image 20240229165202](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/acfbf466-a724-46eb-8157-3b33f99328f5)

![Pasted image 20240229175255](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/0f428226-2b04-45c2-8adc-5ec1ee402a4a)

## Contacto

![Pasted image 20240229171930](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/e7d41d3c-86d8-4072-866e-4568bd140f53)

![Pasted image 20240229175315](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/9c766f57-4a3a-40a2-a22e-9edbf1cbfeba)

## Footer

![Pasted image 20240229173002](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/f3c36da9-ef57-4c33-b962-d3ebffcb0015)

![Pasted image 20240229175336](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/ea8a2877-be81-4a7e-bedb-75d176458e45)

## Responsive HTML

![Pasted image 20240229175147](https://github.com/Mileccc/portafolios_basico_solo_javaScript/assets/121825748/c0474ada-a24b-4d0a-9fcb-e61acc1d0c53)






