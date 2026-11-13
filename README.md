# Pinta Peques — app para niños de 2 a 5 años

App Android de juegos creativos para niños pequeños: colorear, dibujar, música e instrumentos, rompecabezas y trazos. Funciona sin conexión y sin anuncios. Hecha para uso familiar.

> 🔒 Proyecto personal: el código y el APK son privados.

## Qué hace
- **Más de 130 páginas para colorear** generadas a partir de ilustraciones vectoriales: cada forma del dibujo es una región que se rellena con un toque.
- **Pintura libre**, stickers y globos de pintura.
- **Música:** piano, xilófono, guitarra y batería dibujados en SVG, con sonidos reales.
- **Rompecabezas, tangram y trazos** guiados, con dificultad que se ajusta a la edad.
- **Voz que guía y anima** al niño (frases pregrabadas con TTS en español de México) y una "manita" que enseña qué hacer si se queda sin tocar la pantalla.
- **Mis dibujos:** las obras se guardan en el dispositivo (IndexedDB) y se pueden reabrir.
- Pantalla completa en horizontal, botones grandes y sin textos que leer.

## Cómo está hecho
- HTML, CSS y JavaScript sin framework, empaquetado como app nativa con **Capacitor 7** (Android SDK 35, Java 21).
- Scripts de Python que convierten SVG en páginas rellenables, generan la voz y arman el paquete.
- Fuentes, imágenes y sonidos locales, así que funciona 100 % sin conexión.
