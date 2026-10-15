# Farmacias Peruanas · Inteligencia comercial

Descarga el ZIP, descomprímelo y abre **dashboard-cyber.html**. `index.html` es una demostración anterior; no es el archivo actualizado.

Pulsa **Cargar CSV** y elige el archivo acumulado completo con la estructura original. Los datos se procesan en tu navegador y no se publican en GitHub.

## Vistas

- **Resumen:** cuatro indicadores con definiciones y lecturas para decidir.
- **Rendimiento:** columnas de venta por día, línea de ticket y anillo de pedidos, distribuidos horizontalmente.
- **Portafolio:** mix de productos y resultados por canal o corporación.
- **Detalle:** tabla de campañas con encabezado fijo y desplazamiento interno.

Los once filtros están visibles arriba y se conservan al cambiar de vista: año, campaña, corporación, canal, familia, categoría, subcategoría, local, estado y fechas desde/hasta. Marca varias casillas en un segmentador para combinar opciones. Pulsa una barra, punto, arco o segmento para enfocarlo; quita su etiqueta o usa **Restablecer** para ampliar la selección. Los gráficos conservan sus colores al seleccionar. Un borde o un trazo más grueso identifica lo elegido. La paleta utiliza rojo de marca y grises sobre fondos claros.

**Definiciones** explica los indicadores con ejemplos sencillos: por ejemplo, 90% significa 90 de cada 100 pedidos. Está disponible incluso antes de cargar un CSV. El Resumen muestra preguntas claras, un dato y qué conviene revisar; no afirma causas que el archivo no permite demostrar. La tabla de Detalle tiene un marco visible, separación de columnas y filas alternadas. En escritorio, las vistas se ajustan al alto disponible. En pantallas pequeñas, la distribución se adapta para conservar la legibilidad.

La carga reemplaza la fuente durante la sesión; no anexa ni duplica filas. Si falla la validación, conserva los datos anteriores. Al reabrir el HTML debes seleccionar de nuevo el CSV. No se incluyen datos comerciales en esta descarga.

Los cálculos se realizan en un Worker local, con caché y consultas agrupadas. Las transiciones respetan la preferencia de reducir movimiento. La capacidad depende de la memoria y del equipo. No necesitas instalar nada.

Todos los valores monetarios se presentan en **soles (S/)**. Las tarjetas explican las ventas entregadas, cuántos pedidos se entregaron, el valor de las cancelaciones y rechazos, y la venta promedio por pedido entregado. Las definiciones usan ejemplos en soles y evitan expresiones como «suma de importes».
