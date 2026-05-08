# 🚌 TransiteCL – Paraderos Urbanos

App web de transporte público urbano chileno con GPS real, mapa OpenStreetMap y datos generados por IA (Claude).

## ✨ Características

- 📡 **GPS real** – detecta tu ubicación y centra el mapa en tu posición
- 🗺️ **OpenStreetMap** – mapa interactivo real con Leaflet.js
- 🤖 **Datos con IA** – Claude AI genera paraderos, micros y colectivos reales por ciudad
- 🚌 Filtros por **Micros**, **Colectivos** o **Todos**
- 🔍 Búsqueda por calle o número de ruta
- ⏱️ Tiempo estimado del próximo servicio

## 🏙️ Ciudades disponibles

Santiago, Rancagua, Valparaíso, Concepción, Temuco, Antofagasta, La Serena, Iquique

## 🚀 Cómo usar

### Opción 1 – GitHub Pages (recomendado)
1. Sube este repositorio a GitHub
2. Ve a **Settings → Pages → Source → main / root**
3. Tu app estará en `https://tuusuario.github.io/transitecl`

### Opción 2 – VS Code Live Server
1. Abre la carpeta en VS Code
2. Instala la extensión **Live Server**
3. Clic derecho en `index.html` → **Open with Live Server**

### Opción 3 – Python local
```bash
python -m http.server 8080
# Abre http://localhost:8080
```

> ⚠️ **El GPS requiere HTTPS o localhost.** No funciona abriendo el archivo con doble clic (`file://`).

## ⚙️ Requisitos

- Solo un navegador moderno (Chrome, Firefox, Edge)
- Sin instalaciones, sin backend, sin base de datos
- Usa la API de Anthropic (ya incluida en el código)

## 📁 Estructura

```
transitecl/
├── index.html   # App completa (HTML + CSS + JS en un solo archivo)
└── README.md    # Este archivo
```

## 🛠️ Tecnologías

- [Leaflet.js](https://leafletjs.com/) – Mapa interactivo
- [OpenStreetMap](https://openstreetmap.org/) – Tiles de mapa
- [Claude API](https://anthropic.com/) – Datos de paraderos con IA
- [Google Fonts](https://fonts.google.com/) – Tipografía Figtree + JetBrains Mono

## 📄 Licencia

MIT – libre para usar, modificar y distribuir.
