# Manual de Palpagos · The Palpagos Manual

Guía de **Palworld** en español e inglés, construida a partir de los datos del propio juego.
A **Palworld** guide in Spanish and English, built from the game's own data.

**→ [Ver la guía / Read the guide](https://mateogoncu.github.io/palworld-recommendations/)**

---

## Qué incluye

- **Seis partys listas** (minería, madera y piedra, captura, combate, exploración, botín), montadas sobre la
  distinción que de verdad importa: qué habilidades de compañero funcionan **desde la party** y cuáles exigen
  **sacar al Pal**.
- **Catálogo de ~90 habilidades de compañero** agrupadas por para qué sirven, con buscador.
- **Plantillas de base** y la tabla de *capataces*: los Pals cuya habilidad sube +1 nivel de aptitud a toda la base.
- **Las 114 pasivas** con su efecto numérico exacto y cuánto cuesta implantarlas en la Mesa de Cirugía.
- **Probabilidades reales de captura** por esfera y por vida restante.
- **Mapa interactivo** de los dos mapas del juego con 1.253 puntos: jefes alfa, torres, mercaderes, filones,
  efigies, mazmorras… y las zonas de aparición reales de cada Pal, separadas por día y noche.
- **Bases recomendadas** con el radio real de base (35 m) dibujado a escala y una ficha que explica por qué.
- **Los 288 Pals** con iconos, estadísticas, aptitudes, número de Paldex y coordenadas.
- **Calculadora de cría** (padres → cría, y a la inversa).

## What's inside

Same as above, in English: six ready-made parties, a ~90-entry partner-skill catalogue, base rosters and
foremen, all 114 passives with exact effects and implant costs, real catch probabilities, an interactive map
of both game maps with 1,253 points and real spawn zones, recommended base spots with the true 35 m radius,
all 288 Pals, and a breeding calculator.

---

## De dónde salen los datos

Los datos de Pals, aptitudes de trabajo, estadísticas, pasivas, habilidades de compañero, coordenadas de
aparición, nodos de recurso y probabilidades de captura se extrajeron de la base de datos comunitaria
**[paldb.cc](https://paldb.cc)**, que a su vez extrae los archivos del juego. Versión de datos: **v1.0.3 (12 ago 2026)**.

Las **bases recomendadas** no están copiadas de ninguna guía: se calcularon buscando, sobre las coordenadas de
los 4.136 nodos de recurso del juego, el centro de círculo de 35 m que cubre más nodos. El resultado se
contrastó después con [la guía de bases de game8](https://game8.co/games/Palworld/archives/440069) — donde
coinciden, está citado en la ficha de cada base; donde la recomendación es por terreno (llanura, defensas
naturales) y no por recursos, también se dice.

El radio de base (35 m) procede de [palworld.wiki.gg](https://palworld.wiki.gg/wiki/Base).

## Analítica de visitas

`index.html` trae, al final, un bloque comentado con dos opciones listas para activar
(**GoatCounter** y **Cloudflare Web Analytics**). Ambas son gratuitas y sin cookies, así que no necesitan
banner de consentimiento. Descomenta una y pon tu código de cuenta.

## Estructura

```
index.html                    la guía entera (429 KB, ~94 KB comprimido)
assets/map-palpagos.webp      mapa de Palpagos, 4096 px
assets/map-worldtree.webp     mapa del Árbol del Mundo, 3072 px
assets/pals-sprite.webp       los 288 iconos de Pal en un sprite
```

Es un sitio estático: no hay build, ni dependencias, ni servidor. Se puede abrir el `index.html` directamente.

---

## Créditos y aviso legal

**Palworld** es propiedad de **Pocketpair, Inc.** Este es material de fan sin ninguna relación con el estudio.
Los iconos de Pal y las texturas de mapa pertenecen a Pocketpair y se usan aquí con fines informativos.
Gracias a [paldb.cc](https://paldb.cc) por mantener la base de datos que hace posible esta guía.

*Palworld is owned by Pocketpair, Inc. This is fan-made material with no connection to the studio.
Pal icons and map textures belong to Pocketpair and are used here for informational purposes.
Thanks to [paldb.cc](https://paldb.cc) for maintaining the database that makes this guide possible.*
