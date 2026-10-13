# Control de Despachos PRO

Aplicación web en español para registrar órdenes, vehículos/placas y citas de despacho, indicar destinos, ordenar la cola de despachos y consultar el historial.

## Publicar gratis con GitHub Pages

1. Descarga y descomprime el archivo ZIP.
2. En GitHub, crea un repositorio nuevo (por ejemplo `control-despachos`).
3. Sube **el contenido** de esta carpeta al nivel principal del repositorio. Debe quedar `index.html` en la raíz, junto con `README.md` y `.nojekyll`.
4. En el repositorio, abre **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**.
6. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
7. Espera a que GitHub publique la página. La dirección aparecerá en esa misma sección de Pages.

## Importante sobre los datos

- La aplicación guarda los datos en el almacenamiento local del navegador (`localStorage`).
- Los datos no se sincronizan entre teléfonos, navegadores o usuarios diferentes.
- Si borras los datos del navegador o cambias de dispositivo, los registros locales pueden no estar disponibles. Usa las opciones de copia de seguridad de la aplicación cuando estén disponibles.
- GitHub Pages publica archivos estáticos; no proporciona por sí solo una base de datos compartida.

## Archivos

- `index.html`: aplicación completa (HTML, estilos y JavaScript integrados).
- `.nojekyll`: evita el procesamiento de Jekyll para este sitio.
- `README.md`: estas instrucciones.
