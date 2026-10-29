# Semáforos de Vencimiento – prototipo de pruebas

Prototipo de una sola página (`index.html`) para registrar fechas de vencimiento por escaneo/búsqueda.

**Esta versión pública usa solo datos ficticios** (`datos_prueba_ficticios.xlsx`).
No suba aquí archivos de SIESA ni ningún dato real de la empresa.

Para probar: abrir la página, ingresar como Coordinador, cargar `datos_prueba_ficticios.xlsx`,
asignar referencias y luego ingresar como Operario (correo asignado) para escanear.
Los datos se guardan solo en el navegador de cada dispositivo.

## Datos compartidos (Supabase)
Esta versión guarda los datos en un proyecto de Supabase (tabla `documentos`) para que coordinador y operarios
vean lo mismo desde distintos dispositivos. La clave incluida es la **publishable** (pública por diseño).
Las reglas actuales son abiertas, solo válidas para datos ficticios; se cerrarán por rol cuando exista inicio de sesión real.
