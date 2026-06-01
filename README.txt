Sistema de Rifas sin Flask
==========================

Este proyecto no requiere internet ni instalacion de paquetes con pip.
Usa solo librerias internas de Python y una base SQLite llamada rifa.db.

Uso:
1. Ejecutar run.bat
2. Abrir http://127.0.0.1:5000
3. Crear una o varias campañas desde el menu Campañas.
4. Cargar boletas desde Venta de boletas.
5. Imprimir desde el navegador en impresora termica.
6. Realizar sorteo desde el menu Sorteo.

Funcionalidades:
- Multiples campañas o rifas.
- Logo por campaña.
- Costo por boleta por campaña.
- Datos del cliente: nombre, apellido, direccion y telefono.
- Cantidad de boletas por venta.
- Numeracion automatica por campaña.
- Guardado de clientes, ventas, boletas y sorteos en rifa.db.
- Impresion en formato termico de 80 mm desde navegador.

Impresion termica:
En Chrome o Edge seleccionar la impresora termica, margen ninguno, escala 100%, sin encabezado ni pie.
