### Laboratorio 6: Excel : Creación de gráficos dinámicos

**Duración:** 22 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Copilot para Excel para crear diferentes tipos de gráficos a partir de cuadro de datos.

## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
•  Crear gráficos de diferentes tipos a partir de tablas de datos




## Prerrequisitos

### Conocimientos Requeridos
-  Conocimiento básico de Microsoft Excel para manejo de hojas de cálculo.

## Instrucciones Paso a Paso

En estos ejercicios se emplearán una serie de documentos base, que estarán disponibles en el One Drive de su maquina virtual de practicas.
Los documentos a disposición son los siguientes:
•  4DataComprasAmpliada.xlsx
•  5SubscripcionesSemanales.xlsx


### Ejercicio 1:  Crear gráficos de diferentes tipos con Copilot

**Objetivo:** Usar Copilot para crear un resumen y accionables luego de una reunion
Instrucciones:

**Instrucciones:**
1. Abrir **Excel**.
2. Abra el archivo **5SubscripcionesSemanales.xlsx.**

3. Abra el panel de Copilot en modo **Capacidades de la aplicación.**

4. Aplique el siguiente prompt:
```
Crea un grafico "Subscripciones por semana Plan Basico" que muestre la tendencia de crecimiento semanal, usa la columna Semana como eje X y la columna Plan Basico como eje Y
```

5. Observe el resultado que entrega Copilot

![Imagen 63.](/images/Imagen63.png "Imagen 63")

6. Haga clic en **+ Agregar a la nueva hoja**

7. Guarde nuevamente el libro

8. Abra el archivo **4DataComprasAmpliada.xlsx.**

9. Aplique el siguiente prompt:
```
Genera un gráfico de barras que compare el total de ventas por Categoría
```

10.   Observe el resultado obtenido por Copilot. Haga clic en + Agregar a la nueva hoja.

11.   Se debe obtener un resultado similar al siguiente:

![Imagen 64.](/images/Imagen64.png "Imagen 64")

12.   Retorne a la primera hoja. Ahora aplique el siguiente prompt:

```
Crea un gráfico circular que muestre la participación porcentual del Precio Final por Canal.
```
13.   Observe el resultado obtenido por Copilot. Haga clic en + Agregar a la nueva hoja.

14.   Se agregará la hoja con un gráfico con datos

![Imagen 65.](/images/Imagen65.png "Imagen 65")

15.   Puede usar la tabla para quitar algunos valores, lo cual será reflejado en el gráfico

![Imagen 66.](/images/Imagen66.png "Imagen 66")

![Imagen 67.](/images/Imagen67.png "Imagen 67")

16.   Use los siguientes prompts para obtener gráficos con insights adicionales:

| Nº | Objetivo del gráfico | Prompt para Copilot de Excel | Insight que aporta |
|----|----------------------|-----------------------------|-------------------|
| 1 | Ventas por categoría | ``` Crea un gráfico de columnas que muestre el total de Precio Final agrupado por Categoría. Ordena de mayor a menor y agrega etiquetas de datos.``` | Identifica qué categorías generan más ingresos y cuáles requieren impulso. |
| 2 | Ventas por región | ``` Genera un gráfico de barras con el total de Precio Final por Región. Usa colores distintos por región. ``` | Compara desempeño regional para priorizar campañas, stock o expansión. |
| 3 | Evolución de ventas | ``` Crea un gráfico de líneas con la evolución mensual del Precio Final usando la columna Fecha Compra.``` | Detecta tendencias, estacionalidad, picos y caídas de ventas. |
| 4 | Ventas por tipo de cliente |``` Genera un gráfico de columnas comparando el total de Precio Final entre Tipo de Cliente.``` | Mide el aporte de clientes nuevos vs recurrentes y orienta fidelización. |
| 5 | Top productos |``` Crea un gráfico de barras con los 5 productos con mayor suma de Precio Final. Ordena de mayor a menor.``` | Revela productos “estrella” para decisiones de inventario y promociones. |
| 6 | Impacto del descuento |``` Genera un gráfico de dispersión que relacione Descuento con Precio Final.``` | Evalúa si descuentos altos realmente se traducen en mayor valor de venta. |
| 7 | Ventas por género | ```Crea un gráfico de columnas que muestre el total de Precio Final agrupado por Género. ```| Segmenta preferencias de compra y ayuda a afinar mensajes de marketing. |
| 8 | Medios de pago | ```Crea un gráfico de barras que muestre el número de compras por Medio de Pago. ``` | Identifica el método dominante y oportunidades para optimizar comisiones y experiencia de usuario. |
| 9 | Ventas por ciudad y región | ``` Crea un gráfico de columnas apiladas que muestre el total de Precio Final por Ciudad, segmentado por Región.``` | Ubica ciudades clave y diferencias regionales para estrategias locales. |
