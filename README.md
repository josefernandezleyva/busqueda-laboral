# Búsqueda laboral

App móvil (GitHub Pages) para gestionar vacantes, postulaciones y seguimientos de la búsqueda laboral de José Luis Fernández Leyva.

- **App:** https://josefernandezleyva.github.io/busqueda-laboral/
- **Datos:** hoja privada de Google Sheets `Busqueda_Laboral_JLFL`. El repositorio no contiene datos: la app los lee en el navegador después de iniciar sesión con Google (OAuth, alcance `spreadsheets`). Solo la cuenta dueña de la hoja puede verlos o editarlos.
- **Actualización:** una revisión semanal de Claude (Skill `busqueda-laboral`) lee las alertas de empleo en Gmail, evalúa cada vacante y la registra en la hoja.
- **Configuración:** `config.js` (`clientId` de OAuth y `sheetId`).

## Estructura
| Archivo | Uso |
|---|---|
| `index.html` | App completa (HTML, CSS y JS) |
| `config.js` | Client ID de Google y ID de la hoja |
| `manifest.webmanifest`, `icon*` | Instalación como app en el celular |
| `robots.txt` | Evita la indexación en buscadores |
