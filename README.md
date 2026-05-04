# Constelación Dinámica PLAN MARCO

Visualización interactiva y gestión de actores para el **Plan Marco**, desarrollada con **D3.js**.

## Características
- **Visualización en Red**: Mapeo de actores y sus vínculos relacionales (jerárquicos, positivos, negativos, etc.).
- **Gestión en Tiempo Real**: Panel lateral para añadir, renombrar o eliminar actores y vínculos.
- **Persistencia**: Los cambios se guardan automáticamente en el navegador (`localStorage`).
- **Exportación**: Funcionalidad para exportar el mapa a PDF (formato A3) o como una página web estática independiente.
- **Vistas Alternativas**: Vista de lista (inventario) para una gestión tabular de los datos.

## Desarrollo Local

Este proyecto utiliza **Vite** para el servidor de desarrollo.

### Requisitos
- [Node.js](https://nodejs.org/) (versión 18 o superior)

### Instalación
```bash
npm install
```

### Ejecución
```bash
npm run dev
```
La aplicación estará disponible en `http://localhost:5173/`.

## Estructura del Proyecto
- `index.html`: Contiene toda la lógica de la aplicación (HTML, CSS y JS con D3.js).
- `package.json`: Configuración de dependencias y scripts.
- `.gitignore`: Archivos excluidos del control de versiones.
