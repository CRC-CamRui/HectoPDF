# Cuentas de cobro

App web para generar cuentas de cobro en PDF desde el celular.

- Los datos personales (nombre, cédula, cuenta bancaria) y la firma se guardan **solo en el navegador del celular** (localStorage). Este repositorio no contiene datos personales.
- Funciona sin internet después de abrirla una vez.
- El PDF se genera con jsPDF (incluido en `jspdf.umd.min.js`, licencia MIT).

Al publicar cambios, sube la versión en `sw.js` (`cuentas-v1` → `cuentas-v2`).
