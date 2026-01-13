### Laboratorio 7: Excel: Análisis con tablas dinámicas

**Duración:** 22 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Copilot de Excel para crear tablas dinámicas con filtros y resumen mensual.


## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:

•  Crear tablas y gráficos dinámicos usando Copilot para Excel


## Prerrequisitos

### Conocimientos Requeridos
-  Conocimiento básico en el uso de hojas de calculo con Excel.

## Instrucciones Paso a Paso

En estos ejercicios se emplearán una serie de documentos base, que estarán disponibles en el One Drive de su maquina virtual de practicas.

Los documentos a disposición son los siguientes:

•  2DataCompras.xlsx

•  4DataComprasAmpliada.xlsx


### Ejercicio 1:  Creación de tablas y gráficos dinámicos con Copilot

**Objetivo:** Usar Copilot de Excel para crear tablas y gráficos dinámicos



**Instrucciones:**
1. Abrir **Excel**.
2. Abra el archivo **4DataComprasAmpliada.xlsx.**

3. Abra el panel de Copilot en modo **Capacidades de la aplicación.**

4. Aplique el siguiente prompt:

```

Genera una tabla dinámica con el conteo de ID Compra, segmentado por Región en filas y Canal en columnas.
```

5. Observe el resultado generado. El resultado podría ser similar al siguiente (imagen referencial):


![Imagen 68.](/images/Imagen68.png "Imagen 68")


6. Haga clic en **+ Agregar a la nueva hoja**

7. Obtendrá una tabla dinámica totalmente funcional (imagen referencial):

![Imagen 69.](/images/Imagen69.png "Imagen 69")

8. Pruebe aplicar filtros a los campos, o agregar campos en la zona de Columnas, Filas o Valores (imágenes referenciales):

![Imagen 70.](/images/Imagen70.png "Imagen 70")

![Imagen 71.](/images/Imagen71.png "Imagen 71")

9. Regrese a la hoja inicial. Ahora aplique el siguiente prompt:

```

Crea una tabla dinámica que calcule el ticket promedio (PrecioFinal) por TipoCliente.
```


10.   Observe el resultado generado

![Imagen 72.](/images/Imagen72.png "Imagen 72")

11.   Haga clic en + Agrega a una hoja nueva

12.   Ubiquese en la nueva hoja agregada. Abra el panel de Copilot haciendo clic en el botón de Copilot de la barra lateral.

![Imagen 73.](/images/Imagen73.png "Imagen 73")


13.   Aplique el siguiente prompt:

```
Crea un grafico dinamico circular que calcule el ticket promedio (PrecioFinal) por TipoCliente.
```

14.   Haga clic en Insertar en la hoja de cálculo (imagen referencial):

![Imagen 74.](/images/Imagen74.png "Imagen 74")

15.   Puede aplicar formatos a su gusto al grafico generado.

16.   Como ejercicio, puede aplicar algunos de los siguientes prompts sugeridos, para la creación de tablas dinámicas:

| Nº | Objetivo del Análisis | Prompt para Copilot en Excel | Insight / Vista que Aporta |
|----|----------------------|-----------------------------|----------------------------|
| 1 | Ventas por categoría y mes | Crea una tabla dinámica que muestre el total de Precio Final por Categoría y por mes de la Fecha Compra, ordenada de mayor a menor venta. Agrega un total general. | Identifica las categorías con mayor venta y su comportamiento estacional. |
| 2 | Ventas por región y canal | Genera una tabla dinámica con el Precio Final total por Región y Canal, mostrando subtotales por región. | Permite analizar qué canal funciona mejor según la región. |
| 3 | Captación de clientes nuevos | Crea una tabla dinámica que muestre la cantidad de clientes por Ciudad, filtrando solo Tipo de Cliente = Nuevo. | Detecta ciudades con mayor captación de nuevos clientes. |
| 4 | Consumo por género | Genera una tabla dinámica con el promedio del Precio Final por Género y Categoría. | Analiza patrones de consumo diferenciados por género. |
| 5 | Impacto de descuentos | Crea una tabla dinámica que muestre el Precio Final promedio y el descuento promedio por Categoría. | Evalúa si los descuentos influyen en el valor final de compra. |
| 6 | Preferencia de medios de pago | Genera una tabla dinámica con el conteo de compras por Medio de Pago y Región, ordenada por volumen. | Identifica métodos de pago preferidos por región. |
| 7 | Productos más vendidos | Crea una tabla dinámica con el total de ventas (Precio Final) por Producto, mostrando solo los 10 productos con mayor venta. | Permite identificar productos estrella y priorizar inventario. |
| 8 | Perfil etario por categoría | Genera una tabla dinámica que muestre la edad promedio de los clientes por Categoría de producto. | Ayuda a segmentar campañas por edad del cliente. |
| 9 | Evolución de ventas por tipo de cliente | Crea una tabla dinámica con el total de Precio Final por año de Fecha Compra y Tipo de Cliente. | Compara el comportamiento de clientes nuevos vs recurrentes en el tiempo. |
| 10 | Ticket promedio por canal | Genera una tabla dinámica que muestre el Precio Final promedio por Canal. | Permite evaluar qué canal genera mayor ticket promedio. |

17.   Guarde y cierre el libro al terminar.

18.   Abra el archivo **2DataCompras.xlsx**

19.   Seleccione la hoja **Compras2025Q4**. Aplique el siguiente prompt:

```
Compara las compras de las hojas Compras2025Q1 y Compras2025Q4 e indicame 5 insights
```

20.   Observe el resultado generado (imagen referencial)

![Imagen 75.](/images/Imagen75.png "Imagen 75")

21.   Si Copilot le genera una tabla de resumen final la puede agregar a una hoja nueva con el botón + Agregar a la nueva hoja, obteniendo un resultado similar al siguiente (imagen referencial): 

![Imagen 76.](/images/Imagen76.png "Imagen 76")


22.   Seleccione la hoja Compras2025. Aplique el siguiente prompt:

```
Crea una tabla y grafico dinamico que determine qué región genera el mayor ingreso por cliente promedio
```

23.   El resultado debe ser similar al siguiente (imagen referencial):

![Imagen 77.](/images/Imagen77.png "Imagen 77")

![Imagen 78.](/images/Imagen78.png "Imagen 78")


24.   Use los botones para insertar en una nueva hoja,ya sea para la tabla dinámica o para el gráfico dinámico, según sean sus necesidades de análisis o vista de datos. En el caso del gráfico lo podrá inserta en la hoja actual (imagen referencial):

![Imagen 79.](/images/Imagen79.png "Imagen 79")

25.   Retorne a la hoja Compras2025. Aplique el siguiente prompt:

```
Identifica las combinaciones más frecuentes de Categoría + Canal
```


Podrá observar un resultado similar al siguiente (imagen referencial):

![Imagen 80.](/images/Imagen80.png "Imagen 80")


26.   Observe los resultados. De ser valiosa la información obtenida puede pedir la creación del gráfico correspondiente usando el siguiente prompt:

```
Crea un grafico dinamico con los datos presentados
```

Podrá observar un resultado similar al siguiente (imagen referencial):


![Imagen 81.](/images/Imagen81.png "Imagen 81")

27.   Si desea inserte el gráfico en una hoja. Guarde y cierre el libro.
