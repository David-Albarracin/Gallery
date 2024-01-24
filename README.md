# Galería Proyecto

En este proyecto, desarrollaremos una estructura de cuadrícula para crear una muestra de galería que sea totalmente receptiva en dispositivos móviles.

### Preguntas:



1. ***Que Función Cumple las Siguientes Propiedades (-transition -filter -transform):***

   - **TRANSITION**: En este caso, empleamos la propiedad "transition" con el propósito de evitar cambios bruscos en el tamaño de la imagen. En lugar de una alteración instantánea, hemos incorporado una pequeña demora de 0.3 segundos, proporcionando una experiencia más agradable al usuario.

     

   - **FILTER**: En esta ocasión, hemos implementado la propiedad "filter" para introducir una leve transparencia a la imagen. No obstante, es importante destacar que esta función también puede ser aprovechada para modificar los colores de las imágenes, otorgándonos un mayor control sobre la apariencia visual.

     

   - **TRANSFORM**: Hemos incorporado esta propiedad al evento "hover" con el fin de lograr que, al pasar el cursor sobre el objeto, experimente un aumenta su escala en 1.04 Esto no solo enfatiza la capacidad de interacción con la imagen, sino que también proporciona una indicación visual al usuario sobre la posibilidad de interactuar con el elemento.

     

2. ***Que funciones Cumple las Siguientes Propiedades(-grid-auto-flow: dense  -minmax):***

   - **grid-auto-flow: dense**: Esta propiedad nos proporciona fluidez al cargar las imágenes en la cuadrícula, asegurando que se adapten de manera armoniosa al espacio disponible en relación al tamaño del objeto.

     

   - **minmax**: Se ha añadido la especificación de tamaños mínimo y máximo para las celdas de la cuadrícula, con el propósito de evitar que el contenido contenido en ellas exceda estos límites predefinidos. Esto garantiza un control preciso sobre las dimensiones de las celdas, asegurando una presentación visual coherente.

     

3. ***Que es una MediaQuery :***Este método nos posibilita aplicar estilos de manera que se ajusten al tamaño de visualización del documento. Es una técnica efectiva para garantizar que la presentación de la información sea óptima y estéticamente agradable en diferentes dispositivos o resoluciones de pantalla.

   

4. ***Que hace min-width :*** En esta ocasión, lo estamos implementando dentro de la regla `@media (min-width: 600px):`, estableciendo una condición que activa ciertos estilos cuando la pantalla tiene un ancho mayor a 600 píxeles. Estos estilos se aplican específicamente a las clases "wide" y "tall", permitiendo una presentación adaptada y mejorada cuando la pantalla alcanza o supera dicho umbral.

   

5. ***Que funcion cumple span en la regla grid-column y grid-row :*** Esta propiedad se añade a clases específicas con el propósito de hacer que la columna o fila que tenga estas propiedades ocupe un espacio equivalente a dos o el valor que se requiera.

   

6. ***Que funciones cumplen las propiedades:***  

   Como las imágenes se están cargando como fondo de la celda, estas propiedades nos permiten modificarlas de diversas formas, tales como:

   - **background-size: cover:** Esta propiedad indica al fondo, en este caso la imagen, que se adapte y ocupe todo el espacio disponible en la celda.

     

   - **background-position:center:** Esta propiedad posiciona el fondo, en este caso la imagen, de manera que se centre en relación al centro de la celda o el contenedor.

     

   - **background-repeat: no-repeat: **Si la celda o el contenedor es más grande que la imagen. la imagen se repite automáticamente para llenar el contenedor, estas propiedades son útiles para evitar esta repetición automática, que es la opción predeterminada.