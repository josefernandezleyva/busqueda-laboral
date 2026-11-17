# Tablero

Aplicación web estática (GitHub Pages) para consultar y actualizar un tablero personal guardado en una hoja privada de Google Sheets.

- No contiene datos: todo se lee en el navegador después de iniciar sesión con Google (OAuth, alcance `spreadsheets`).
- Solo la cuenta dueña de la hoja puede ver o editar la información.
- Configuración en `config.js` (`clientId` de OAuth y `sheetId`).
