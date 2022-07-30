# After Sass I - 29300 - Seteo archivos, variables, mixins (mediaqueries)

## Seteo de Sass

:point_right: Instalamos Sass

```
npm install -g sass
```

:point_right: Preparamos script desde consola

```
sass [ruta-origen] [ruta-destino]
```

Y agregamos la flag --watch:

```
sass scss/main.scss css/main.css --watch
```

#### Creamos partials

![archivos scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/archivos.png?raw=true)

#### Imports en main.scss

![imports scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/imports.png?raw=true)

#### Preparamos algunas variables y mixins

![variables scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/variables.png?raw=true)

![mixin scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/mixin.png?raw=true)

#### Preparamos nuestros media queries dentro de un mixin

:point_right: palabres claves: `@mixin [nombre-mixin]`, `@include [nombre-mixin]`, `@content`

![breakpoints scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/breakpoints.png?raw=true)

#### Armamos un contenedor y componente para mostrar nuestros productos

![tienda scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/tienda.png?raw=true)

![producto scss](https://github.com/ratofante/after-tutorias/blob/main/after-sass-29300/assets/capturas/producto.png?raw=true)
