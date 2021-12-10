# Topicos selectos en TIC
 ***Grupo 4***

 **Ricardo Fernandez**,
 **Brami Prudencio** y
 **Pablo Rivas**
 
# Mantenimiento Predictivo Basado en Datos de Equipamiento de Microsoft Azure 

## Resumen
 
El objetivo es construir un modelo de ML para predecir cuando habrá un fallo en los equipos, apoyandose en datos de telemetria y reportes de fallos, errores y mantenimientos. Pero para predecir los posibles fallos, uno debe saber que falla, cuando tiempo resiste, que valores son los influyentes y más. Por tanto, para analizar el comportamiento tanto de los equipos como del modelo generado y comprender la situación, se requiere conocer el proposito de las distintas variables y la relacion que tienen.

## Preguntas

Es necesario realizar preguntas para conocer la situación y aprender como resolver el problema en cuestión. 

* ¿Qué modelo de equipamiento son los mas propensos a fallar?

* ¿Cuáles son las causas mas comunes que provocan los fallos y con que piezas se tienden a reemplazar?

* ¿Existe relación entre las fechas de los fallos con algun evento en especifico? Por ejemplo un apagon masivo, en cuyo caso, ¿Qué información podría proveer?

* ¿Tendrá relación la cantidad de años en servicio y el promedio de fallos en dicho tiempo? Sera posible que a medida que más envejezca, más propenso sea a tener errores o seguira igual.

* ¿Qué relacion existe entre las variables de telemetria? Siendo este análisis el más importante, ¿Podemos encontrar las relaciones pertinentes entre las fallas y las variables de telemetria que corresponden? ¿Cómo podríamos identificar las irregularidades para predecir que va a fallar a futuro?

(Posiblemente las preguntas siguientes se modifiquen o aumenten)

## Datasets 

Los datasets que se emplearan provienen de la página recomendada Kaggle:

> [PdM_telemetry](https://azuremlsampleexperiments.blob.core.windows.net/datasets/PdM_telemetry.csv)

> [PdM_errors](https://azuremlsampleexperiments.blob.core.windows.net/datasets/PdM_errors.csv)

> [PdM_maint](https://azuremlsampleexperiments.blob.core.windows.net/datasets/PdM_maint.csv)

> [PdM_failures](https://azuremlsampleexperiments.blob.core.windows.net/datasets/PdM_failures.csv)

> [PdM_machines](https://azuremlsampleexperiments.blob.core.windows.net/datasets/PdM_machines.csv)
