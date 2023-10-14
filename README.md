# Trabajo Final de Master - octubre 2023
## Master Universitario en Modelización e Investigación Matemática, Estadística y Computación.

Análisis Semántico de Opiniones en Twitter sobre la Vacunación del COVID-19. Codigos generados
Utilizando como marco de datos los recopilados por el grupo Panacea Lab de la Universidad Estatal de Georgia, se seleccionaron y extrajeron un total de 11,787
tweets publicados durante el periodo comprendido entre el 1 de marzo 2020 al 15 de abril 2020 en la plataforma de redes sociales Twitter. El objetivo es identificar las opiniones de
los usuarios sobre el proceso de vacunación contra el COVID-19. Como metodología, este estudio sigue una combinación de técnicas y modelos de Procesamiento de Lenguaje
Natural y aprendizaje automático supervisado y no supervisado. Se aplica un modelo Word2Vec con las arquitecturas de Continuous Bag of Words y Muestreo Negativo para
representar las palabras en vectores de valores reales. Además, se emplea la Frecuencia de Términos-Frecuencia Inversa de Documentos y Análisis de Componentes Principales
para seleccionar un ranking de palabras clave y reducir la dimensionalidad de los datos. 
A continuación se aplica un análisis de clúster con el algoritmo k-medias. Los resultados permitieron identificar 8 etiquetas sobre las cuales giraron las opiniones de los usuarios
en este periodo, 4 de ellas pertenecientes al modelo de creencias en el ámbito de la salud. Finalmente, se usaron modelos de clasificación, como Random Forest y Máquinas de
Soporte Vectorial, para evaluar la capacidad de clasificación mediante distintas métricas.
