# RETO_20_2_2017_ALE

Esta tarea consiste en encontrar una manera de limitar el tiempo de vida de los containers de docker usando el API de docker o de Rancher.
Habra que lanzar un container en ejecucion de tal manera que a los X segundos se pare sin que el usuario intervenga.
El docker en ejecucion debe lanzarse desde Rancher.
La opcion con el tiempo de vida puede estar en cualquier punto de la configuracion, preferiblemente en un punto que se pueda modificar mediante el API y no "a mano".

Cuando se encuentre una solucion, se debe hacer un Pull Request a este repositorio con un fichero donde se muestre la opcion de configuracion que es necesaria (script, Dockerfile, docker-compose.yml, rancher-compose.yml o lo que sea).
