# A2.2-LDA-y-arboles-de-decision

Este proyecto busca analizar y predecir la esperanza de vida utilizando datos recopilados de 193 países entre los años 2000 y 2015, provenientes de la Organización Mundial de la Salud (OMS) y la Organización de las Naciones Unidas (ONU).

El conjunto de datos contiene 22 columnas y 2938 registros, con 20 variables predictoras divididas en cuatro categorías principales:

Inmunización: Cobertura de vacunas como la hepatitis B y el sarampión. Mortalidad: Tasas de mortalidad infantil, materna y de enfermedades específicas. Economía: Producto Interno Bruto (PIB) per cápita y gasto en salud. Factores sociales: Nivel de desarrollo del país y acceso a servicios básicos.

Dado que los datos contienen valores nulos y valores atípicos, se ha realizado un proceso de limpieza en el que se imputaron los valores faltantes utilizando la mediana con la función SimpleImputer, debido a la presencia de outliers que podrían sesgar la media. Además, se eliminaron países con datos insuficientes como Vanuatu, Tonga, Togo y Cabo Verde, asegurando así una base de datos más robusta para el análisis.

El objetivo principal del proyecto es clasificar la esperanza de vida en dos categorías:

Menor a 65 años
Mayor o igual a 65 años
Para ello, se aplicarán distintos modelos de clasificación, como Análisis Discriminante Lineal (LDA), regresión logística y árboles de decisión con poda, asegurando una correcta selección de características mediante técnicas estadísticas. Se evaluarán los modelos a través de métricas de desempeño en los datos de prueba y se compararán los resultados para determinar el modelo más preciso en la predicción de la esperanza de vida.

Con este estudio, se espera comprender mejor los determinantes clave de la longevidad y generar herramientas predictivas que puedan apoyar la toma de decisiones en salud pública y planificación económica.

Índice:

[Vista Previa](./A2.2_598303.html)

[Codigo.jpynb](./A2.2_598303.ipynb)

[Base de Datos](./Life_Expectancy_Dat_A2.2.xls)
