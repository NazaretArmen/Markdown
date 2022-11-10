# Tipos de letras
`
@font-face {
    font-family: alias-de-la-fuente;
    src: url("url-de-la-fuente");
}
`
## Ejemplo almacenado en el mismo servidor
```
@font-face {
    font-family: fuente-local;
    src: url("fonts/Rubik-Bold.ttf");
}
```
## Ejemplo almacenado en otro servidor
```
@font-face {
    font-family: 'Hanalei Fill';
    src: url("https://fonts.gstatic.com/s/hanaleifill/v9/fC1mPYtObGbfyQznIaQzPQi8UAjA.woff2");
}
```
## Utilizando la regla @import
#### Esta regla permite obtener un recurso a partir de una URL.

```
@import url("https://fonts.googleapis.com/css2?family=Roboto");

body {
    font-family: 'Roboto', sans-serif;
}
```

```console
armen@bar ~
$ whoami
armen
armen@bar ~
$ ls
```