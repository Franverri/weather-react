## Henry Weather

### Instrucciones para correr el proyecto

Desde la carpeta raiz "weather-react" se pueden ejecutar los siguientes comandos:

#### `npm start`

Comienza a correr la aplicación de forma local por lo que se puede ver desde el navegador accediendo a
http://localhost:3000

No es necesario volver a correr el proyecto cada vez que se realice un cambio sino que se verá automáticamente reflejando en el navegador.

#### `npm test`

Ejecuta los tests indicando el resultado de cada uno de ellos por consola. Para más información sobre este tema se puede consultar el siguiente link: [running tests](https://facebook.github.io/create-react-app/docs/running-tests)

### Ejercitación

#### Título

1. Cambie el nombre actual del título por "Henry - Weather App"

2. Centrar el título utilizando el archivo "App.css"

#### Barra de búsqueda

4. Crear una carpeta llamada "componentes" dentro de la carpeta "src"

3. Crear un componente denominado "Busqueda" que va a utilizarse para luego poder encontrar las ciudades sobre las cuales se desee ver el clima actual. Para ello deberán crearse dentro de la carpeta de "componentes" los siguientes dos archivos:
  * Busqueda.js
  * Busqueda.css


4. Crear una barra de navegación en la cual se incluya el logo de "Henry" (Pueden encontrarlo en la carpeta "public"), el título previamente definido y un cuadro de búsqueda. La página final hasta este momento debería quedar similar a la siguiente:

![Alt](./img-screen/barra-busqueda.png)

*Nota: Recordar de importar el nuevo componente en el archivo "App.js" para poder utilizarlo desde allí*

#### Tarjeta de clima

5. Crear otro componente dentro de la carpeta "Componentes" denominado "Tarjeta" que va a utilizarse para mostrar el clima actual en alguna ciudad elegida

6. Agregar tres tarjetas de prueba para ver como quedarían en pantalla. Las mismas deben estar centradas. Debería verse similar a lo siguiente:

![Alt](./img-screen/tarjetas-clima.png)

*Luego estas tarjetas se irán agregando dinámicamente*

#### Tablero general

7. Para poder agrupar las tarjetas y facilitar luego la carga dinámica de las mismas es recomendable agruparlas dentro de un componente superior al que denominaremos "Tablero". Crearlo y asignarle un array con nombres de ciudades dentro del estado de dicho componente

*Por el momento utilzar de ejemplo los nombres que quieran, podrían ser: Buenos Aires, San Pablo, Bogota, Lima, Santigo*

8. Implementar un método dentro del componente de Tablero para renderizar una Tarjeta por cada elemento definido en el Array de ciudades. Debería quedar algo similar a lo siguiente:

![Alt](./img-screen/tablero.png)

*Ayuda: para poder asignarle el nombre de la ciudad correspondiente a cada Tarjeta va a ser necesario pasárselo como propiedad y modificar el archivo "Tarjeta.js" para que utilice dicho valor*

#### Adición/Eliminación dinámicamente

9.
