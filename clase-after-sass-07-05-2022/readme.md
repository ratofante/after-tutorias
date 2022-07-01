1. Instalar Sass utilizando npm

   Inicializamos npm con :

   ```
   npm init
   ```

   :point_right: tenemos nuestro package.json

   ```
   Instalamos sass con: npm install -g sass
   ```

2. Armar nuestro script para compilar sass (package.json)

   :point_right: en package.json, vamos a "scripts"
   "nombre:script" : "sass --watch [origen] [destino]"

   Ejemplo: "compile:sass":"sass --watch scss/style.scss assets/css/style.css"

   :point_right: Corremos el script usando: npm run [nombre-script]

   ```
   npm run compile:sass
   ```

   ![script](https://github.com/ratofante/after-tutorias/blob/main/clase-after-sass-07-05-2022/script.jpg?raw=true)

3. Armar la estructura de nuestro archivos y carpetas (.scss)

   :point_right: Creamos directorios para organizar nuestros archivos .scss
   :point_right: Importamos en style.scss de manera ordenada (reset, variables, generales, secciones, componentes..)
   usando @import "./[ruta del archivo]";

   ![imports](https://github.com/ratofante/after-tutorias/blob/main/clase-after-sass-07-05-2022/imports.jpg?raw=true)

4. Usar nuestro .scss para estilizar un componente

   :point_right: Armamos nuestra maqueta en html:
   ![html](https://github.com/ratofante/after-tutorias/blob/main/clase-after-sass-07-05-2022/html.jpg?raw=true)

   :point_right: Usamos anidamiento para aplicar estilos:
   ![galeria](https://github.com/ratofante/after-tutorias/blob/main/clase-after-sass-07-05-2022/galeria-ejemplo.jpg?raw=true)

   :point_right: Utilizamos @mixin para aplicar nuestras media queries:
   ![breakpoints](https://github.com/ratofante/after-tutorias/blob/main/clase-after-sass-07-05-2022/breakpoints.jpg?raw=true)
