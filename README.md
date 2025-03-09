# Prototipo de Aplicación Inmobiliaria

Este es un prototipo de una aplicación para gestionar y buscar inmuebles usando mapas.

## Funcionalidades

### 1. Gestión de Inmuebles (index.html)
- **URL**: [Abrir Modo Gestión](https://amschajari.github.io/app-inmobiliarias/index.html)
- **Descripción**: Permite añadir, editar y eliminar inmuebles en un mapa. Podés exportar los datos como un archivo GeoJSON usando el botón "Guardar GeoJSON".
- **Instrucciones**:
  1. Hacé clic en "Añadir inmueble" para agregar un nuevo punto en el mapa.
  2. Completá el formulario con los datos del inmueble (dirección, tipo, precio, etc.).
  3. Guardá los cambios y exportá los datos con "Guardar GeoJSON".

### 2. Búsqueda de Inmuebles (buscar.html)
- **URL**: [Abrir Modo Búsqueda](https://amschajari.github.io/app-inmobiliarias/buscar.html)
- **Descripción**: Permite buscar inmuebles cargando un archivo GeoJSON y aplicando filtros (tipo, categoría, precio, localidad).
- **Instrucciones**:
  1. Hacé clic en "Cargar GeoJSON" y seleccioná el archivo `inmuebles.geojson` generado desde el modo gestión.
  2. Usá los filtros (tipo, categoría, precio, localidad) para buscar inmuebles.
  3. Hacé clic en un marcador para ver los detalles del inmueble.

## Notas
- Este es un prototipo. Algunas funcionalidades (como mover puntos) están desactivadas temporalmente.
- Para probar la búsqueda, primero generá un archivo GeoJSON en el modo gestión.

## Archivo de Ejemplo
Podés descargar un archivo GeoJSON de ejemplo aquí:  
<a href="https://raw.githubusercontent.com/amschajari/app-inmobiliarias/main/inmuebles.geojson" download="inmuebles.geojson">📥 inmuebles.geojson</a>  
Usalo en el modo búsqueda para probar los filtros.