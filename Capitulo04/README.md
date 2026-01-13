### Laboratorio 4: Excel : Generación automática de datos

**Duración:** 22 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot en Excel para crear data sintética, tomando ejemplos de clientes, productos y compras.

## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
•  Generar data sintética usando Copilot para Excel, con datos de ejemplo de clientes, productos y compras.


## Prerrequisitos

### Conocimientos Requeridos
Conocimiento básico de Microsoft Excel para manejo de hoja de cálculo

## Instrucciones Paso a Paso

### Ejercicio 1:  Generar data sintética de Compras en Excel

**Objetivo:** Usar Copilot para Excel, para generar datos de ejemplo con IA generativa para Compras.

**Instrucciones:**
1. Abrir **Excel**.
2. Crea un nuevo libro. Guardelo con el nombre **2DataCompras.xlsx.** Guardelo en su OneDrive de preferencia.

3. Abra el panel de Copilot. Aplique el siguiente prompt:
```
Genera una tabla masiva con 2,000 compras de clientes. Columnas: ID Compra, ID Cliente, Género, Edad, Producto, Categoría, Fecha Compra, Medio de Pago, Descuento, Precio Final, Ciudad, Región, Tipo de Cliente, Canal. Los datos deben corresponder a diferentes meses del 2025.
```
![Imagen 38.](/images/Imagen38.png "Imagen 38")

4. Observe la respuesta generada. Copilot informará que ha generado un archivo CSV con los datos y mostrará el enlace de descarga respectivo (si no lo hace pedirlo explícitamente mediante otro prompt). Imagen referencial:

5. Descargue el archivo CSV generado y ubíquelo en una ruta accesible para usted.

6. En el ribbon Datos, haga clic en De texto / CSV y seleccione el archivo descargado:

![Imagen 39.](/images/Imagen39.png "Imagen 39")

7. En la ventana que aparece verifique que el **Origen de archivo** es **65001: Unicode (UTF-8)** y el **Delimitador** es **Coma**. Revise la vista previa y si todo está conforme despliegue las opciones del botón **Cargar**, seleccione **Cargar en**…, en la ventana **Importar datos** que aparece seleccione **Hoja de cálculo existente** y finalmente clic en **Aceptar** (imágenes referenciales)

![Imagen 40.](/images/Imagen40.png "Imagen 40")

![Imagen 41.](/images/Imagen41.png "Imagen 41")

![Imagen 42.](/images/Imagen42.png "Imagen 42")

8. Observe los datos importados. Cambie el nombre de la hoja a **Compras2025.**

9. Retorne al panel lateral de Copilot. Cambie a Capacidades de la aplicación

![Imagen 43.](/images/Imagen43.png "Imagen 43")

10.   Aplique el siguiente prompt:
```
Lleva a otra tabla las compras del canal Online
```
**Importante:** adapte el nombre del canal acorde a los datos que tiene en su hoja Compras2025.

11.   Observe el resultado. Excel realiza un análisis empleando Python normalmente. Si tiene una sección **“Mostrar análisis”** la puede expandir para revisar las sentencias utilizadas. Debajo debe ver una muestra del resultado (imagen referencial):

![Imagen 44.](/images/Imagen44.png "Imagen 44")

12.   Debajo de la tabla de datos, debería tener un botón + Inserta en una hoja nueva, hagale clic.

![Imagen 45.](/images/Imagen45.png "Imagen 45")

13.   Debe observar una hoja nueva con datos de compras solamente del canal Online (imagen referencial):

![Imagen 46.](/images/Imagen46.png "Imagen 46")

14.   Cambie el nombre de la nueva hoja a **ComprasOnline**

15.   Cree una hoja nueva, aplique el nombre **Compras2025Q1**

16.   Retorne a la hoja **Compras2025**. Copie solo la primera fila de la tabla (la que tiene los encabezados) y péguela como fila 1 de la hoja nueva **Compras2025Q1**, debería obtener un resultado 

![Imagen 47.](/images/Imagen47.png "Imagen 47")

17.   Retorne a la hoja **Compras2025**. Ahora aplique el siguiente prompt:
```
Lleva a otra tabla las compras del primer trimestre del 2025
```

18.   Observe la respuesta ofrecida por Copilot. Debe sugerir el uso de la función **FILTRAR**. Copie la formula sugerida (imagen referencial):

![Imagen 48.](/images/Imagen48.png "Imagen 48")

19.   Cambie a la hoja **Compras2025Q1**. Ubiquese en la celda A2. Pegue la formula copiada con la función FILTRAR y pulse ENTER.

20.   Observe el resultado. Deben aparecer un conjunto de ítems de compras.

21.   Aplique el siguiente prompt:

```
Aplica formato de fecha a la columna Fecha Compra
```
22.   Haga clic en **Aplica**.

23.   Deberia observar solamente las compras realizadas en el primer trimestre de 2025 (imagen referencial):

![Imagen 49.](/images/Imagen49.png "Imagen 49")

24.   Ejercicio: aplicando los pasos previos, cree una hoja nueva Compras2025Q4 que muestre solamente las compras de los meses de Octubre, Noviembre y Diciembre de 2025

25.   Asegurese que el libro este correctamente grabado. Debe tener finalmente 4 hojas: Compras2025, Compras2025Q1, Compras2025Q4 y ComprasOnline

### Ejercicio 2:  Generar data sintética diversa en Excel
**Objetivo:** Usar Copilot para Excel, para generar datos de ejemplo con IA generativa de diversos tipos.

**Instrucciones:**
1. Abrir **Excel**.

2. Crea un nuevo libro. Guardelo con el nombre 3DataSintetica.xlsx. Guardelo en su OneDrive de preferencia.

3. A continuación, se presenta una lista de prompts para generar datos sintéticos.
Use por lo menos 2 de estos prompts para generar la data correspondiente. Ubique los datos en una hoja con un nombre acorde.

| ID | Escenario | Prompt para Copilot de Excel |
|----|-----------|------------------------------|
| 1 | Compras – básico | Genera una tabla de datos sintéticos de compras con 500 registros, incluyendo: Fecha de compra, Cliente, Producto, Categoría, Cantidad y Monto total. Usa fechas de los últimos 12 meses. |
| 2 | Productos | Crea una tabla de productos sintéticos con ID de producto, nombre, categoría, precio unitario y estado del producto (Activo/Inactivo). Genera al menos 50 productos. |
| 3 | Clientes | Genera una tabla de clientes sintéticos con ID de cliente, tipo de cliente (Nuevo/Recurrente), región, segmento y fecha de registro. |
| 4 | Compras + clientes | Genera una tabla de compras sintéticas que relacione clientes y productos, permitiendo analizar compras por cliente, frecuencia de compra y monto acumulado. |
| 5 | KPIs financieros | Crea datos sintéticos de compras que permitan calcular KPIs como ventas totales, ticket promedio, unidades vendidas y ventas por categoría. |
| 6 | Análisis temporal | Genera datos sintéticos de compras distribuidos por mes durante un año, con variaciones estacionales claras para poder analizar tendencias y comparativos mensuales. |
| 7 | Segmentación de clientes | Crea datos sintéticos de clientes y compras que permitan segmentar clientes por valor de compra (alto, medio, bajo). |
| 8 | Análisis de productos | Genera datos sintéticos de productos y ventas que permitan identificar top 10 productos, productos de baja rotación y contribución por categoría. |
| 9 | Nivel intermedio–avanzado | Crea un conjunto de datos sintéticos de compras, clientes y productos en hojas separadas, relacionadas por identificadores, para análisis tipo modelo estrella. |
| 10 | Escenario ejecutivo | Genera datos sintéticos de compras realistas que permitan a un ejecutivo analizar KPIs como crecimiento mensual, clientes activos, churn estimado y productos más rentables. |
