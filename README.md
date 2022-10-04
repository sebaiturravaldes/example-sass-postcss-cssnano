# example-sass-postcss-cssnano

Ejemplo de minificación de tú código CSS utilizando [SASS](https://sass-lang.com/) + [PostCSS](https://postcss.org/) + [cssnano](https://cssnano.co/)

Ejecutar el siguiente comando:

```cli
npm run minify
```

Esto generará 2 directorios, `css/` y `dist/`:
- `css`, Lo generado compilando tú código SASS a CSS (sin comprimir).
- `dist`, Comprime el CSS previamente generado con SASS y lo minifica aplicando [PostCSS](https://postcss.org/) + [cssnano](https://cssnano.co/).