# Tarima Perfecta

Juego arcade 3D de paletizado en un almacén. Las cajas de producto terminado van llegando y tú las acomodas sobre una tarima de 48 × 40" (122 × 102 cm). Cada tarima llena se envuelve y un montacargas se la lleva a embarque.

**Juega aquí:** `https://CADTM.github.io/tarima-perfecta/`

## Cómo se juega

- **Mouse:** la caja sigue al puntero · clic para soltar · rueda o clic derecho para girar · clic central para parar/acostar.
- **Celular:** arrastra para mover · toca para soltar · botones de girar, parar y soltar.
- **Teclado:** flechas para mover · `Q` girar · `E` parar · `Shift` bajar · `Espacio` soltar · `1 2 3` ayudas · `P` pausa.
- **Plano de arriba:** toca un lugar para mover la caja ahí; toca la caja para soltarla.

## Reglas

- **Gravedad real:** si el centro de peso de una caja queda fuera de su apoyo, se voltea con lo que tenga encima.
- **Patrones de estiba:** Columnas, Amarre cruzado, Ladrillo, Mixto y Escalonado. Sigue las ranuras punteadas.
- **Etiquetas hacia afuera:** gira cada caja de la orilla para que su etiqueta quede hacia afuera.
- **Cajas especiales:** Frágil (nada encima), Pesada (directo en la tarima), Urgente (exacta vale doble).
- **Combos y ayudas:** cada combo x4 da una ayuda: Reacomodo, Cinta de amarre o Pausa de línea.
- **Turnos:** cada 2 tarimas sube la altura de la estiba (30 cm → 2.10 m), cambia el escenario y la caída se acelera.
- **Cascos:** tienes 3; cada derrumbe quita uno y cada tarima embarcada devuelve uno.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo llamado `tarima-perfecta`.
2. Sube estos archivos (`index.html`, `README.md`, `.nojekyll`) a la rama `main`.
3. En el repositorio ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
5. En uno o dos minutos el juego queda en `https://CADTM.github.io/tarima-perfecta/`.

## Técnico

- Un solo archivo HTML, sin compilación.
- 3D con [three.js r128](https://threejs.org/) desde cdnjs; tipografías de Google Fonts.
- El récord se guarda en el navegador de cada jugador (`localStorage`).

---

Hecho por **@cybercadtm**.
