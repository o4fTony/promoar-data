# promoar-data

Feed de datos público de la app **PromoAR** (promociones bancarias de Argentina).

- `data.json` — lista completa de promos y cupones.
- `version.json` — archivo chico que la app consulta primero; si la `version` cambió, baja el `data.json` completo.

La app lee estos archivos desde `https://o4ftony.github.io/promoar-data/`.

Se actualiza desde el panel admin de PromoAR (botón *Publicar*). No editar a mano salvo emergencia.

Contenido: información de promociones que los bancos y fintechs publican en sus sitios oficiales.
