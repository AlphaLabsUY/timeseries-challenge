# Challenge Time Series Forecasting:

![image](https://user-images.githubusercontent.com/57304126/162757374-eef49e19-1124-4cf1-bde3-53c6a060347e.png)

## Objetivo:
El siguiente ejercicio tiene como objetivo validar que el candidato cuenta con los conceptos básicos para el procesamiento y modelado de un problema de forecasting de series de tiempo.

Tendrás acceso a un dataset con el numero de productos vendidos por diferentes tiendas en un plazo de 5 años. A partir de estos datos, deberás realizar el forecast de las ventas a nivel de tiendas para 6 Meses, con frecuencia al menos mensual.

## Hitos:
Los hitos que debes desarrollar son:

1. Definir una metrica para evaluar el performance del modelo.
2. Explicitar estrategia de procesamiento y feature engineering: Diferencia, logarítmo, depuración de outliers, etc.
3. Entrena un modelo para las ventas con un enfoque clásico: SARIMA. En este punto, será suficiente seleccionar **una** sóla tienda.
4. Entrenar un modelo de redes neuronales multi-step (RNN/CNN/etc). Podrán seleccionarse una o más tiendas, según se entienda apropiado.
5. Generar una grafica con la prediccion vs los valores observados de cada uno de los modelos en el set de validación.

> :warning:   **NO** es necesario completar todos los Hitos, el candidato podrá seleccionar aquellos que crea relevante o estén más próximos a su nivel de conocimiento. En esta línea, los puntos que tendrán mayor relevancia son los 3 y 4.

## Requisitos:
- El código tiene que estar escrito en python (puede ser un script o un notebook).
- El código tiene que ser reproducible (lista dependencias usadas + código a ejecutar).
