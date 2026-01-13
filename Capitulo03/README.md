### Laboratorio 3: Excel: Trabajo con Workbooks

**Duración:** 22 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Copilot para Excel para aplicar formato condicional, varios otros formatos, columnas calculadas y pedir asistencia con fórmulas.

## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:

•  Aplicar formatos diversos a una hoja de calculo usando Copilot.

•  Aplicar formato condicional a una hoja de calculo usando Copilot.

•  Crear columnas calculadas usando Copilot para Excel.
•  Pedir asistencia con fórmulas usando Copilot para Excel.
 

## Prerrequisitos

### Conocimientos Requeridos
- Conocimiento básico de Microsoft Excel en creación, formato y fórmulas para una hoja de cálculo.

## Instrucciones Paso a Paso

### Ejercicio 1:  Aplicar diferentes formatos en una hoja de calculo
**Objetivo:**  Usar Copilot para Excel, para aplicar diferentes formatos a una hoja de calculo.

**Instrucciones:**
1. Abrir **Excel**.
2. Abra Copilot usando el botón del Ribbon, aparecerá la barra lateral de Copilot

![Imagen 17.](/images/Imagen17.png "Imagen 17")

3. Ingrese el siguiente prompt
```
Crea una tabla de datos de planilla de 10 trabajadores

```

4. Observa el resultado creado. Debajo de la respuesta aparece una botonera, haz clic en el botón Copiar respuesta (imagen referencial):

![Imagen 18.](/images/Imagen18.png "Imagen 18")

5. Selecciona la celda A1 de la hoja y pega la respuesta, puedes usar CTRL+V por ejemplo. Debes obtener un resultado similar al siguiente (imagen referencial):

![Imagen 19.](/images/Imagen19.png "Imagen 19")

6. Guarde el libro con el nombre PlanillaDemo.xlsx en la ruta que desees para tus archivos de practica.

7. Elimine los comentarios que aparecen debajo de la tabla de datos.

8. Aplique el siguiente prompt

```
 Aplica a la tabla un estilo profesional, filas alternadas y filtros activados en los encabezados
```
9. Copilot devolverá una respuesta y un enlace a un Excel en el que ha aplicado el formato solicitado. Descargue el archivo y observe los formatos aplicados (imagen referencial):

![Imagen 20.](/images/Imagen20.png "Imagen 20")

10.   Si se desea que los formatos se apliquen directamente a la hoja de calculo abierta se debe cambiar al modo Capacidades de la aplicación, que se encuentra en la lista desplegable de opciones del botón Copilot (imagen referencial):

![Imagen 21.](/images/Imagen21.png "Imagen 21")

11.   Active el autoguardado haciendo clic en Activar Autoguardado. Seleccione alguna ubicación de OneDrive y espere unos momentos

![Imagen 22.](/images/Imagen22.png "Imagen 22")

12.   Cuando aparezcan las opciones de Copilot, aplique este prompt:
Aplica formato financiero a las columnas de montos, usando moneda en soles, separador de miles y dos decimales

13.   Copilot analizará los datos y luego mostrará un mensaje de resumen similar al siguiente (imagen referencial):

![Imagen 23.](/images/Imagen23.png "Imagen 23")

14.   Haga clic en Aplica. Despues de unos momentos aparecerá este mensaje

![Imagen 24.](/images/Imagen24.png "Imagen 24")

Asimismo, debe observar los cambios aplicados en la hoja de calculo (imagen referencial):

![Imagen 25.](/images/Imagen25.png "Imagen 25")

15.   Ahora aplique el siguiente prompt:
```
Aplica un formato ejecutivo a esta hoja: encabezados en negrita, fondo gris claro, bordes suaves y ajusta automáticamente el ancho de las columnas.
```

16.   Copilot informará sobre los cambios que va a realizar

![Imagen 26.](/images/Imagen26.png "Imagen 26")

17.   Haz clic en **Aplica**. Observe los cambios aplicados.

18.   En el panel de Copilot tiene la opción de deshacer los cambios. Haga clic en **Deshaz**.

![Imagen 27.](/images/Imagen27.png "Imagen 27")

Los cambios se deben haber revertido.

19.   Aplique ahora el siguiente prompt:

```
Crea una formula que calcule el sueldo neto
```

20.   Copilot debe mostrar una propuesta de columna con la formula correspondiente (imagen referencial):

![Imagen 28.](/images/Imagen28.png "Imagen 28")

21.   Haga clic en + Inserta una columna , ubicado en la parte inferior de la respuesta

![Imagen 29.](/images/Imagen29.png "Imagen 29")

La columna se debe haber agregado luego de la ultima columna de la tabla (imagen referencial):

![Imagen 30.](/images/Imagen30.png "Imagen 30")

22.   Ahora aplique el siguiente prompt
```
Agrega una columna BonoAniversario que tenga el valor 500 para aquellos trabajadores que tengan mas de 3 años de antigüedad
```
23.   Revisa la sugerencia indicada por Copilot y haz clic en + Inserta una columna
El resultado obtenido seria similar al siguiente (imagen referencial):

![Imagen 31.](/images/Imagen31.png "Imagen 31")

La fórmula de la celda debería ser similar a la siguiente:
**=SI((HOY()-$E2)/365>3;500;0)**

24.   Aplique ahora el siguiente prompt:
```
Aplica barra de datos para la columna bonificación
```

25.   Revise la sugerencia indicada. Haga clic en Aplica. Observe el resultado (imagen referencial):

![Imagen 32.](/images/Imagen32.png "Imagen 32")

26.   Ubiquese en la celda A13 y agregue los siguientes datos:

| Celda | Dato |
|-------|------|
| A13 | Búsqueda de trabajador |
| A14 | Nombre: |
| A15 | Cargo: |
| A16 | Fecha Ingreso: |
| A17 | Sueldo Base: |

27.   En la celda B14 escriba uno de los nombres de la tabla (el que desee)

28.   En la celda B15 (contigua a "Cargo:") poner la formula 
**=BUSCARV(FALSO;Tabla1[[#Todo];[Nombre]:[BonoAniversario]];"2";B14)**

29.   Observe que aparece el mensaje **#íVALOR!** en la celda B15

30.   Aplique el siguiente prompt:

```
 Por qué esta formula da error =BUSCARV(FALSO;Tabla1[[#Todo];[Nombre]:[BonoAniversario]];"2";B14)

```

31.   Copilot enviará una respuesta indicando los motivos del error, algo similar a lo siguiente (imagen referencial):

![Imagen 33.](/images/Imagen33.png "Imagen 33")

32.   Posicionese sobre la formula corregida indicada por Copilot y haga clic en el botón Copiar

![Imagen 34](/images/Imagen34.png "Imagen 34")

33.   Ubiquese en la celda B15 nuevamente y reemplace su valor con el que acaba de copiar. Esta vez debería aparecer como resultado el cargo que corresponde al nombre de la persona indicada en la celda B14 (imagen referencial):

![Imagen 35.](/images/Imagen35.png "Imagen 35")

34.   Escriba ahora el siguiente prompt:
```
Aplica la misma formula de la celda B15 para buscar la Fecha Ingreso en B16 y el Sueldo Base en B17
```

35.   Revise lo indicado por Copilot, copie las formulas de B16 y B17 y aplíquela en las celdas correspondientes. Revise el resultado.
Nota: es probable que necesite aplicar formato de fecha a la celda B16

![Imagen 36.](/images/Imagen36.png "Imagen 36")

El resultado final debería ser similar al siguiente (imagen referencial):

![Imagen 37.](/images/Imagen37.png "Imagen 37")
