# Preprocesador SASS

Permite generar archivos css a partir de un archivo fuente SCSS

## Instruccion para generar el CSS

        sass archivo-fuente.scss archivo-destino.css

## Actualizacion automatica

    sass --watch scss/style.scss css/style.css
    sass --watch scss/style.scss css/style.css --style compressed

    sass --watch css/style.css:dist/style.min.css  --style compressed
