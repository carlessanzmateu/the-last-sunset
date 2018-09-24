# Guía de estilos

## Generales

Los nombres de ficheros deben ir con `
- Ejemplo: `log.md`

## Versiones

La primera letra **v** es el diminutivo de `versión`

El primer dígito es la `versión mayor`: Este valor solo
debe subir cuando existan cambios transcendentales. En el caso del 1, sólo llegará cuando exista la primera versión utilizable. Hasta su llegada, será un versión beta.

El segundo dígito es la `versión menor`: Este valor debe aumentar cada vez que se aporta nuevo contenido al proyecto que no sea de tipo error.

El tercer dígito es la `versión de error`: Este valor incrementará cada vez que se solucione algún error conocido o detectado durante el aumento de la versión mayor o menor.

- Ejemplo: v1.10.5

1: Hace referencia a que estamos en la versión mayor: 1

10: Durante la versión mayor 1, hemos echo diez aportaciones de mejora que no suponen un cambio transcendental en el proyecto.

5: Este número indica que durante la versión mayor 1: hemos echo 5 aportaciones para resolver errores.

## Log

Al dar de alta un evento en el log, se debe poner la fecha en cursiva (dd/mm/yyyy) y en negrita la versión.

- Ejemplo: Un nuevo registro del log *(01/01/2018)* **v0.0.0**

Si se añade más de un registro en una versión, esta se añadirá solo en el último de ellos.

- Ejemplo:

Algo ha pasado 06 *(05/01/2018)* **v0.2.0**

Algo ha pasado 05 *(04/01/2018)*

Algo ha pasado 04 *(03/01/2018)*

Algo ha pasado 03 *(03/01/2018)*

Algo ha pasado 02 *(02/01/2018)* **v0.1.0**

Algo ha pasado 01 *(01/01/2018)*
