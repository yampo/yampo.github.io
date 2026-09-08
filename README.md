# Viajes

**https://yampo.github.io/**

La portada del taller de viajes: lista los viajes y enlaza al sitio de cada uno.
La genera `engine/build_portada.py`; acá no se edita nada a mano.

Cada viaje vive en su propio repo y se sirve en `yampo.github.io/<viaje>/`.
Este repo se llama `yampo.github.io` porque es la *user page* de GitHub, que es
la única que se sirve en la raíz del dominio.

Los sitios llevan `robots.txt` y `noindex`, así que no salen en buscadores —
pero **público no es privado**: cualquiera con la URL entra.
