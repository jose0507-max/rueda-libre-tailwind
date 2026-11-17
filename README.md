# Rueda Libre

Sitio estático para conocer la flota, consultar tarifas y solicitar el alquiler de bicicletas en Medellín.

## Desarrollo

1. Instala Node.js 20 o superior.
2. Ejecuta `npm install`.
3. Ejecuta `npm run dev` para recompilar Tailwind CSS al guardar cambios.
4. Abre `index.html` con Live Server o cualquier servidor estático local.

`src/input.css` importa Tailwind y contiene los estilos básicos del sitio. Las páginas usan clases comunes de Tailwind para el diseño. Tailwind genera `css/tailwind.css`, que se incluye en las páginas y se mantiene versionado para que el sitio también funcione en hosting estático.

El formulario valida los datos en el navegador y abre la aplicación de correo para enviar la solicitud. No requiere ni incluye un backend.
