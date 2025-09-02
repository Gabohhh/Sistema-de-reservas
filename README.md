# Sistema-de-reservas
evaluacion 1 front-end



1.-
Servidor web vs servidor de aplicaciones
o Investiga qué hace un servidor web (ej: Nginx, Apache) y en qué se
diferencia de un servidor de aplicaciones (ej: Gunicorn, uWSGI).


El servidor web ejecuta de manera estatica el código html y css encambio el servidor de aplicaciones ejecuta el código de manera dinámica. por eso se podría decir que los servidores web son para contenido predefinido y los servidores de aplicaciones para cosas mas interactivas por asi decirlo 


2.-
Protocolo DNS
o Explica cómo traduce un nombre como reservasrestaurante.com en una
dirección IP real.

explicado burdamente los equipos se comunican mediante direcciones ip o mas bien en binario y luego el protocolo se encarga de traducir a alfanumerico. Técnicamente cuando uno ingresa una url al buscador el equipo lo primero que hace es buscar si tiene guardada dentro del cache la ip que corresponde si no la pide al mismo servidor dns 

3.-

Modelo vs Vista en Django
o Describe el rol de cada uno dentro del patrón MVT (Model-View-
Template)

la vista es la que se encarga de gestionar la lógica y los datos que van a ser mostrados.    La plantilla  corresponde a lo que es la interfaz de usuario, el modelo ve la estructura de los datos y interactuar con la BD

4.-

HTTPS vs HTTP
o Explica las ventajas de usar HTTPS en un sistema donde los clientes envían
datos sensibles

lo mas importante es que se cifran los datos y requiere autenticación por parte del servidor.

