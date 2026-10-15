# Dashboard Cyber · versión interactiva

Descarga el ZIP, descomprímelo y abre **dashboard-cyber.html**. `index.html` es la demostración antigua: no es el archivo actualizado.

1. Pulsa **Cargar CSV** y elige el archivo acumulado completo con la estructura original.
2. Abre los segmentadores y marca una o varias casillas. Ejemplo: Android e iOS, cruzados con dos campañas. Dentro de un segmentador se combinan las opciones; entre segmentadores se cruzan.
3. Pulsa una barra, punto, arco o segmento para enfocarlo. Solo permanece lo elegido y se resalta la selección. Las columnas usan verde oscuro por defecto; un asterisco indica campañas con fechas faltantes y su explicación aparece debajo del gráfico. Para añadir otras opciones del mismo gráfico, márcalas en el segmentador correspondiente. Ctrl/Cmd + clic permite ajustar la selección existente.
4. Quita una opción con la × de su etiqueta. Usa **Restablecer** para volver a ver todo.

Las tarjetas incluyen su definición. El menú lateral resalta tanto la sección elegida como su área de contenido. Los gráficos muestran transiciones de relleno y trazado; se respeta la preferencia del sistema de reducir movimiento. No hay avisos temporales al filtrar.

La carga reemplaza la fuente de la sesión; no duplica las filas al volver a cargar el mismo archivo. Si falla la validación, se conservan los datos anteriores y se muestra el recuento procesado. Al reabrir el HTML, vuelve a seleccionar el CSV. No se incluyen datos comerciales en este repositorio.

El filtrado y los indicadores se calculan en un Worker local, con consultas agrupadas y caché de resultados. Los datos no se envían a servidores. La capacidad depende de la memoria y el equipo; no es ilimitada. No necesitas instalar nada.
