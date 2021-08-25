# DHDE - Ejercicio Git/Github

## Sobre el repositorio

Este es un ejercicio de la diplomatura que estoy estudiando y se trata sobre el manejo de Git y Github.

No tiene nada del otro mundo, solamente estoy aprendiendo a manejar archivos por comandos Unix y Git.

## Comandos

Órdenes realizadas en el ejercicio:

**Momento 1**

    mkdir Ecommerce
    cd Ecommerce
    touch app.js
    touch config.js
    mkdir db
    git init
    git add .
    git commit -m "Primer Commit"

**Momento 2**

    cd db/
    touch producto_db.js
    touch carrito_db.js
    cd ..
    nano app.js
    git commit -m "Guardando lo importante"

**Momento 3**

    git add .

**Momento 4**

    git commit -m "Guardando una parte del proyecto"

**Momento 5**

    cd db
    rm producto_db.js
    git restore .
    rm ../config.js
    git add .
    git commit -m "Sacando la configuración"

## Problemas

1. Momento 1 Paso 8: ¿Qué pasó con el directorio db?
2. Momento 2 Paso 6: ¿Se guardó lo importante?
3. Momento 4 Paso 1: ¿Está bien el nombre del commit?
4. Momento 5 Paso 3: ¿Qué hace este paso?
5. Momento 5 Paso 6: ¿Qué pasó acá?

## Respuestas

- El directorio db pasó de ser creado a estar añadido y registrado en el repositorio por un commit llamado "Primer Commit"

- No se guardó lo importante porque no se añadió los cambios realizado en los archivos mediante "git add . "

- No, ya que se guardó todos los cambios del proyecto.

- Este paso restaura el archivo eliminado (producto_db.js) a su estado original del commit "Guardando una parte del Proyecto"

- Se realizó un commit "Sacando la configuración" de la eliminación del archivo config.js en el repositorio.