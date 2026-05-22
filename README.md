# GeoViewer Campo 🗺️

Visor de mapas GeoPDF y GeoTIFF para trabajo de campo con GPS.

## Funcionalidades
- ✅ Carga GeoPDF exportados desde ArcGIS Pro
- ✅ Carga GeoTIFF con georreferenciación
- ✅ Ubicación GPS en tiempo real sobre el mapa
- ✅ Tomar y guardar puntos con coordenadas
- ✅ Medición de distancias entre puntos
- ✅ Brújula con orientación en tiempo real
- ✅ Exportar puntos a CSV
- ✅ Funciona en Android e iOS
- ✅ Instalable como app (PWA)

## Cómo publicar en GitHub Pages (GRATIS)

### Paso 1: Crear cuenta en GitHub
- Ve a https://github.com y crea una cuenta gratuita

### Paso 2: Crear repositorio
- Click en "New repository"
- Nombre: `geoviewer`
- Marca "Public"
- Click "Create repository"

### Paso 3: Subir archivos
- Sube los archivos: `index.html`, `manifest.json`, `sw.js`
- Puedes arrastrarlos directamente en la página del repositorio

### Paso 4: Activar GitHub Pages
- Ve a Settings → Pages
- En "Source" selecciona "Deploy from a branch"
- Selecciona la rama "main"
- Click Save

### Paso 5: Compartir
- Tu app estará disponible en:
  `https://TU-USUARIO.github.io/geoviewer`
- Comparte ese enlace por WhatsApp con tus usuarios

## Cómo usan tus usuarios

1. Reciben el mapa GeoPDF o GeoTIFF por WhatsApp
2. Descargan el archivo al celular
3. Abren el enlace de la app en el navegador
4. Tocan "CARGAR MAPA" y seleccionan el archivo
5. El mapa aparece con su posición GPS en tiempo real

### Instalar como app (opcional)
- **Android**: Chrome → menú ⋮ → "Agregar a pantalla de inicio"
- **iOS**: Safari → botón compartir → "Agregar a pantalla de inicio"

## Flujo recomendado desde ArcGIS Pro

Para exportar GeoTIFF (mejor compatibilidad):
1. Share → Export Map
2. Formato: TIFF
3. Activar "Write GeoTIFF Tags"
4. Exportar y compartir por WhatsApp

## Soporte de formatos
| Formato | Georreferenciación | Recomendado |
|---------|-------------------|-------------|
| GeoTIFF (.tif) | ✅ Completa | ⭐ Sí |
| GeoPDF ArcGIS (.pdf) | ⚠ Parcial* | Sí |

*Los GeoPDF de ArcGIS usan un estándar propietario (LGIDict) que los navegadores no pueden leer directamente. Se recomienda exportar como GeoTIFF para máxima compatibilidad con la georreferenciación GPS.
