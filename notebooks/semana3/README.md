Proyecto de Clasificación de la Calidad del Vino

Propósito del Proyecto

Este proyecto tiene como objetivo principal desarrollar modelos de clasificación que predigan la calidad del vino, clasificada en una escala de 0 a 10. El dataset utilizado contiene diferentes atributos fisicoquímicos de los vinos y su calidad, evaluada por expertos. El fin es identificar las mejores técnicas y modelos que ofrezcan un rendimiento óptimo en la predicción de la calidad del vino.

Técnicas y Modelos Utilizados

A lo largo del desarrollo de este proyecto, se implementaron y evaluaron diferentes modelos de clasificación, incluyendo:

Regresión Logística: Para evaluar su capacidad de manejo de problemas de clasificación binaria y multiclase en datos linealmente separables.

Random Forest: Modelo de ensamble basado en múltiples árboles de decisión para capturar relaciones complejas y reducir el sobreajuste.

K-Nearest Neighbors (KNN): Utilizado para comparar resultados, aunque sus limitaciones de escalabilidad y sensibilidad al ruido lo hicieron menos eficiente en comparación con los modelos anteriores.

Modelos Avanzados (XGBoost, LightGBM, CatBoost): Se sugieren como próximos pasos debido a su capacidad para manejar conjuntos de datos complejos y mejorar el rendimiento de la clasificación.

Se realizaron evaluaciones de rendimiento utilizando métricas como la precisión, F1-score, matriz de confusión, y curvas ROC, para comparar y elegir el mejor modelo.

Preprocesamiento de Datos

El preprocesamiento de los datos incluyó los siguientes pasos:

Limpieza de datos: Manejo de valores faltantes y datos atípicos.

Estandarización: Escalado de las características para asegurar que los modelos como KNN y SVM funcionaran de manera óptima.

Análisis exploratorio: Gráficos de distribución y correlación para identificar relaciones importantes entre las variables.

Cómo Ejecutar el Código

Clonar el repositorio:

git clone https://github.com/edgarRojasPy/Machine_Learning_DS02.git
cd nombre_proyecto

Instalar dependencias:
Asegúrate de tener Python 3.x instalado y ejecuta:

pip install -r requirements.txt

Ejecutar el código:
Puedes ejecutar el script principal desde la línea de comandos o un entorno de desarrollo como Jupyter Notebook.

python main.py

Explorar los resultados:
Los resultados y gráficos generados se guardarán en la carpeta output/ para su análisis.

Contacto

Para cualquier consulta o contribución al proyecto, puedes contactar a:

Email: efrojaspy@gmail.com

GitHub: tu_usuario