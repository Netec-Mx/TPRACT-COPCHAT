### Laboratorio 9: Microsoft 365 Copilot: Creación de Agente especializado

**Duración:** 30 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot Chat para crear un agente que use fuentes de datos personalizadas, contexto, indicaciones, asi como capacidades específicas.


## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:

•  Crear un agente personalizado usando Microsoft 365 Copilot.




## Prerrequisitos

### Conocimientos Requeridos
-Conocimiento básico en el uso de documentos de Office

## Instrucciones Paso a Paso

### Ejercicio 1:  Creación de un agente personalizado

**Objetivo:** Crear un agente personalizado usando Microsoft 365 Copilot.

**Instrucciones:**

1. Abra Microsoft 365 Chat (https://m365.cloud.microsoft/chat)

2. En el menu lateral selecione la opción New agent (imagen referencial):

![Imagen 120.](/images/Imagen120.png "Imagen 120")

3. Aparecerá la ventana para crear un agente, en una pestaña llamada Configure (imagen referencial):

![Imagen 121.](/images/Imagen121.png "Imagen 121")

4. Seleccione el template Prompt Coach

5. Complete los demás campos usando la siguiente información:
-  Name: Analista Financiero
-  Description : Agente creado para analizar información financiera, interpretar KPIs y generar conclusiones ejecutivas.
-  Instructions:

###Propósito: 
Actúa como un analista financiero profesional. Siempre responde con rigor técnico, claridad y estructura. Interpreta datos financieros, calcula KPIs, evalúa riesgos y elabora recomendaciones estratégicas basadas en lógica financiera.
  
###Metas:
Cuando el usuario proporcione cifras, valida consistencia antes de analizar. Si falta información clave, solicítala. No inventes datos ni realices proyecciones sin solicitud explícita.
Estructura tus respuestas de esta manera:
1. Contexto
2. Análisis (mostrar cálculos cuando aplique)
3. Interpretación financiera
4. Conclusión o recomendación
  
###Directivas generales: 
- Realiza preguntas clarificadoras o para continuar la conversación.
- Proporcione sugerencias y ejemplos para mejorar.
- Sea alentador y mantenga un tono profesional y comprensivo.
- Mantenga el contexto a lo largo de la conversación.
- Explique brevemente las capacidades si se le pregunta.
- Después de cada subtema, pregunte si se necesita más ayuda.

6. Deberia obtener algo similar a lo siguiente (imagen referencial):

![Imagen 122.](/images/Imagen122.png "Imagen 122")

7. En la sección Knowledge agregue los siguientes 4 sitios web, uno a uno:

https://www.wallstreetsurvivor.com/

https://corporatefinanceinstitute.com/

https://365financialanalyst.com/

https://www.fe.training/free-resources/?

8. Cuando finalice debe observar algo similar a lo siguiente (imagen referencial):

![Imagen 123.](/images/Imagen123.png "Imagen 123")

9. Activa las siguientes opciones en la sección Capabilities
- Create documents, charts, and code.
- Create images

![Imagen 124.](/images/Imagen124.png "Imagen 124")


10.   Ubiquese en la sección Suggested prompts. Debe observar algo similar a lo siguiente (imagen referencial):

![Imagen 125.](/images/Imagen125.png "Imagen 125")

11.   Reemplace esas entradas por las siguientes:
-  Financial Report Summary: Analiza este reporte financiero y dame un resumen ejecutivo.
-  KPI Interpretation: Interpreta estos KPIs y explica qué revelan del negocio.
-  Investment Comparison: Compara estas dos alternativas de inversión.
-  Ratio Analysis: Calcula ratios financieros con estos datos.
-  Forecasting: Genera una proyección financiera a 12 meses.
-  Risk Detection: Identifica los riesgos en este escenario.

12.   A la derecha podrá ver una vista previa de su asistente (imagen referencial):

![Imagen 126.](/images/Imagen126.png "Imagen 126")

13.   En la esquina superior derecha ubique el botón Create y dele clic.

14.   Espere unos momentos a que se cree el agente. Aparecerá finalmente una ventana con el botón Go to agent.

![Imagen 127.](/images/Imagen127.png "Imagen 127")

![Imagen 128.](/images/Imagen128.png "Imagen 128")

15.   Aparecerá la ventana de su agente personalizado Analista Financiero (imagen referencial):

![Imagen 129.](/images/Imagen129.png "Imagen 129")

16.   Aplique ahora el siguiente prompt:
```

Actúa como un analista financiero y analiza este escenario:
La empresa Alfa registró en los últimos 6 meses los siguientes ingresos mensuales: 

12000, 13500, 14800, 15200, 16000, 17100.

Sus costos operativos mensuales se mantuvieron estables en 9800.

Necesito que:
1. Calcules tendencia y crecimiento mensual.
2. Interpretes la evolución de la utilidad.
3. Evalúes la rentabilidad.
4. Identifiques riesgos financieros.
5. Des una conclusión ejecutiva y una recomendación clara.
Haz todo el análisis usando únicamente los datos proporcionados.
```


17.   Observe la respuesta que genera el agente (imagenes referenciales):

![Imagen 130.](/images/Imagen130.png "Imagen 130")

![Imagen 131.](/images/Imagen131.png "Imagen 131")


18.   Observe que el agente tiene todas las capacidades que ya conoce de Microsoft 365 Copilot, como preguntas para continuar la conversación, prompts de continuación, etc (imagen referencial):

![Imagen 132.](/images/Imagen132.png "Imagen 132")


19.   Si al agente se le hace una pregunta aparentemente Off-topic, en su respuesta puede orientar la conversación hacia temas financieros. Por ejemplo, aplique el siguiente prompt:

```

Indicame quien es Leo Messi
```


20.   Observe la respuesta (imagen referencial):

![Imagen 133.](/images/Imagen133.png "Imagen 133")

21.   Seleccione alguna de los prompts sugeridos y aplíquelo. Observe la respuesta (imagen referencial):

![Imagen 134.](/images/Imagen134.png "Imagen 134")


22.   El agente ahora estará disponible en el menú izquierdo, en la lista de agentes (imagen referencial):


![Imagen 135.](/images/Imagen135.png "Imagen 135")


23.   Si quiere hacer ajustes en el agente (cambiar el icono, instrucciones, conocimiento, capacidades o prompts sugeridos) puede abrir el Agent Store (opción All agents) y sobre las opciones del Agente Financiero seleccionar Edit.



![Imagen 136.](/images/Imagen136.png "Imagen 136")

24.   El agente también estará disponible desde los paneles de Copilot dentro de las aplicaciones de Microsoft 365. Por ejemplo, abra Excel.

25.   Abra el panel lateral de Copilot.

26.   Haga clic en el botón del extremo superior izquierdo. En la lista de agentes si aun no sale el que creó puede seleccionar la opción Todos los agentes. Aparecerá la lista de agentes, debe aparecer el que ha creado (imagen referencial):

![Imagen 137.](/images/Imagen137.png "Imagen 137")

![Imagen 138.](/images/Imagen138.png "Imagen 138")

![Imagen 139.](/images/Imagen139.png "Imagen 139")

27.   Listo. Ya tiene la experiencia embebida del agente creado dentro de una de sus aplicaciones de oficina favoritas.

![Imagen 140.](/images/Imagen140.png "Imagen 140")
