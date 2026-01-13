### Laboratorio 5: Excel : Análisis de datos

**Duración:** 22 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Copilot para Excel para solicitud de KPIs, y realizar consultas variadas de análisis desde nivel básico hasta avanzado.

## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
•  Solicitar KPIs y consultas de análisis de datos usando Copilot para Excel




## Prerrequisitos

### Conocimientos Requeridos
-  Conocimiento básico de Microsoft Excel para manejo de hojas de cálculo.

## Instrucciones Paso a Paso

En estos ejercicios se emplearán una serie de documentos base, que estarán disponibles en el One Drive de su maquina virtual de practicas.
Los documentos a disposición son los siguientes:
•  4DataComprasAmpliada.xlsx
•  5SubscripcionesSemanales.xlsx


### Ejercicio 1:  Análisis de datos

**Objetivo:** Usar Copilot para Excel, para realizar consultas variadas de análisis desde nivel básico hasta avanzado.

**Instrucciones:**
1. Abrir **Excel**.
2. Abra el libro 4DataComprasAmpliada.xlsx.

3. Abra el panel de Copilot. Aplique el siguiente prompt para un análisis simple:
```
Dame un resumen general de los datos del archivo, indicando cuántas filas hay y qué representa cada columna
```

4. Observa la respuesta devuelta por Copilot, debe ser similar a lo siguiente (imagen referencial):

![Imagen 50.](/images/Imagen50.png "Imagen 50")

5. Aplica ahora el siguiente prompt:
```
Indica cuántas compras se realizaron por cada Ciudad.
```
6. Observa el resultado entregado por Copilot, debe ser similar al siguiente (imagen referencial):

![Imagen 51.](/images/Imagen51.png "Imagen 51")

7. Si desea puede insertar los datos de la tabla en una hoja nueva usando el botón + Agregar a la nueva hoja

![Imagen 52.](/images/Imagen52.png "Imagen 52")

8. Puedes ahora aplicar los siguientes prompts y ver su resultado:
```
Muestra el total de compras por Canal (Online vs Tienda Física)
```
```
Cuántas compras corresponden a cada Categoría.
```

Si deseas puedes agregar la tabla resultante en una hoja nueva

9. Para un análisis de nivel intermedio, aplica ahora el siguiente prompt:
```
Agrupa las compras por Rango de Edad (18-25, 26-35, 36-50, 51+), y calcula el total de ventas para cada grupo
```

10.   Observa el resultado entregado por Copilot. Si desea se puede agregar a una hoja nueva (imagen referencial):

![Imagen 53.](/images/Imagen53.png "Imagen 53")


11.   También se dispone de sugerencias adicionales de Copilot para obtener insights mas precisos, puede utilizar el que desee (imagen referencial):

![Imagen 54.](/images/Imagen54.png "Imagen 54")


12.   Aplica ahora el siguiente prompt:
```
Muestra el ticket promedio por Región.
```
(imagen referencial del resultado)

![Imagen 55.](/images/Imagen55.png "Imagen 55")


13.   Puedes ahora aplicar los siguientes prompts y ver su resultado:

``` 
Identifica el método de pago más utilizado y la cantidad de veces que aparece.

Muestra el total de ventas por mes usando la columna FechaCompra.

Calcula la correlación entre Edad y PrecioFinal para ver si la edad influye en el gasto promedio.
```

Genera una tabla comparando hombres vs mujeres en número de compras y ticket promedio.

14.   Para un análisis de nivel avanzado, aplica el siguiente prompt:
```
Identifica patrones de compra por TipoCliente: ¿qué categorías prefieren los clientes Nuevos, Recurrentes y VIP?
```
**Importante:** cambia los nombres de los tipos de cliente acorde a los datos que tenga.

15.   Observa el resultado obtenido (imagen referencial):

![Imagen 56.](/images/Imagen56.png "Imagen 56")

16.   Puedes ahora aplicar los siguientes prompts y ver su resultado:

```


Analiza si existe estacionalidad en las compras, mostrando los meses con más y menos ventas.

```

```
Realiza un análisis de segmentación RFM simple usando: Recency (FechaCompra), Frequency (ID Compra por cliente) y Monetary (PrecioFinal promedio).

```

```
Calcula el lifetime value estimado de los clientes recurrentes basándote en su gasto promedio y frecuencia de compra.

```
### Ejercicio 2:  Solicitud de KPIs

**Objetivo:** Usar Copilot para Excel, para solicitar de KPIs para una hoja de calculo.

**Instrucciones:**
1. Abrir **Excel**.
2. Abra el libro **5SubscripcionesSemanales.xlsx.**

3. Abra el panel de Copilot en el modo Capacidades de la aplicacion

4. Aplique el siguiente prompt:
Sugiere 3 indicadores KPI utiles, por cada uno indicame el nombre, que mide y por qué sería útil

5. Observe el resultado que muestra Copilot, puede ser algo similar a lo siguiente (imagen referencial):

![Imagen 57.](/images/Imagen57.png "Imagen 57")

 
En la zona inferior de la respuesta dispone de botones para agregar la respuesta a una hoja nueva o copiarla

![Imagen 58.](/images/Imagen58.png "Imagen 58")

6. Ahora aplique el siguiente prompt:

```

Cual seria la formula del KPI Tasa de crecimiento semanal de suscriptores

```


7. Observe la respuesta de Copilot (imagen referencial):

![Imagen 59.](/images/Imagen59.png "Imagen 59")

8. Haga clic en el botón ubicado en la parte inferior de la respuesta + Inserta una columna

![Imagen 60.](/images/Imagen60.png "Imagen 60")

9. Se debe poder apreciar la columna agregada a la tabla de datos (imagen referencial):

![Imagen 61.](/images/Imagen61.png "Imagen 61")

10.   Escriba el siguiente prompt:
```
Que significa #N/D ?
```
11.   Observa la explicación devuelta por Copilot, se entiende que #N/D no es un error:

![Imagen 62.](/images/Imagen62.png "Imagen 62")

12.   Repita los pasos previos si desea agregar los otros KPIs recomendados por Copilot.
