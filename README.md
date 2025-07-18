# PROPIEDADES CSS3.
Partiendo de los documentos facilitados en este respositorio, realiza las siguientes actividades:
1. Aplicar un **borde de `2px de color #4D4D33` al #page**. Modificar los bordes del header para que solo quede el **borde inferior de `1px de color #8C8C8C`** y modificar el *nav* para que solo quede el **borde inferior también de `1px de color #8C8C8C`**. Modificar también el **ancho del `aside` a 200 píxeles.**

2. Introducir un nuevo elemento `<img>` dentro del elemento `<h1>` del `<header>` delante del título. Para que quede posicionado delante del título definiremos un margen interno en `h1` de **header, `padding: 0px 100px;`**
Pondremos el elemento `<h1>` que contendrá el `<img>` con posicionamiento relativo y el elemento `<img>` con posicionamiento absoluto y posición izquierda 15px y superior a 5px. La imagen se encuentra en la carpeta imgs. Investiga la propiedad position.

3. **Bordes redondeados**. Para el efecto de bordes redondeado que tiene la página utilizaremos un **radio de 20px** (en este caso, deberemos indicarlo en varias partes de más de un elemento para que tome el aspecto que podéis ver en la imagen *resultado.jpg* ). Investiga la propiedad border-radius. Revisa la compatibilidad con todos los navegadores.

4. **Sombras**. Para la sombra de la página utilizaremos 10px para los desplazamientos y el difuminado, y grey para el color. Investiga la propiedad *box-shadow*. Revisa la compatibilidad con todos los navegadores.

5. **Menú desplegable**. Crearemos un menú desplegable que se mostrará cuando coloquemos el ratón en la opción de menú Productos. El menú contendrá tres opciones: *Producto1, Producto2 y Producto3*. Para realizar el menú debes anidar una lista no numerada de enlaces dentro de la opción **Productos** del menú principal (html).

- ### Para dar estilo al menú
Con el selector del elemento correspondiente en cada caso.
- Para el contenido desplegable (oculto por defecto):

    > `{ display: none; position: absolute; z-index: 1; }`

Investiga cómo funciona la propiedad z-index.
- Para el fondo de los elementos del menú desplegable:

    > `background-color:#CCFFFF;`

- Para los elementos (enlaces) de la lista desplegable (submenú):

    > `{ padding:15px; color:grey; text-decoration:none; width: 90px;
    > display:block; }`

*Nota*: Debes tener en cuenta que al colocar el ratón encima del enlace de **Productos** el menú desplegable se muestra como un bloque (display: block;) y que los elementos de la barra de navegación deben tener la propiedad (display: inline-block).
- Cambiar el color de la fuente de los enlaces del menú desplegable a `#3D3D29` cuando
el ratón está sobre ellos. `color:#3D3D29;`

6. **Personaliza la página web del blog para que sea un blog de deportes de invierno**.
Para ello realiza los siguientes cambios:
- Cambia el texto de las dos entradas para adaptarlas al tema. Cambia también el logotipo.
- Menú desplegable: Substituye el menú **Productos** por el de **Deportes**. Modifica las opciones del menú para que muestre: *Esquí, Snowboard, Patinaje*. 
- No olvides pasar el validador de html y css antes de efectuar la entrega. 