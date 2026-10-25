# Penaltis 3D · prototipo

Sube `index.html`, `manifest.webmanifest` y `sw.js` a la raíz de un repositorio de GitHub. Después ve a Settings → Pages, selecciona Deploy from a branch, rama `main`, carpeta `/ (root)` y guarda. Abre el enlace publicado en Safari.

Este prototipo usa Three.js desde jsDelivr y construye la escena con formas 3D básicas. Incluye campo, portería, público simplificado, balón animado, lanzador y portero con estirada básica, elecciones ocultas y diez penaltis.

**Importante:** esta es una prueba visual 3D, no aún la versión realista final. Los jugadores están construidos con primitivas geométricas, no son modelos humanos profesionales. Para lograr el aspecto realista de un videojuego necesitamos incorporar modelos humanos 3D riggeados y animaciones de tiro/parada con licencias adecuadas. Three.js también se carga desde internet; aunque el service worker intenta cachear recursos, hay que probar offline y, para garantizarlo, empaquetar la biblioteca localmente.
