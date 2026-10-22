# MODELADO COMPUTACIONAL DE LA INTERACCIÓN METABÓLICA ENTRE MCF-7 Y FUSOBACTERIUM NUCLEATUM COMO MODELO DE MICROBIOTA INTRATUMORAL EN CÁNCER DE MAMA

En este trabajo, se desarrolló un modelo metabólico comunitario simulando un co-cultivo de tres subpoblaciones de MCF-7 (invasiva, reservorio y proliferativa) interaccionando con la bacteria Fusobacterium nucleatum*. Se utilizò el flujo de trabajo de [MICOM](https://micom-dev.github.io/micom/) para investigar còmo las interacciones metabólicas entre la microbiota intratumirak y la heterogeneidad celular de un tumor modelan las dinamicas metabólicas de la comunidad tumoral. 

# Contenido del repositorio
Todo lo necesario para ejecutar el modelo metabólico comuntario se encuentra en el folder de `MICOM`:
  - `Input_files` contiene todas los modelos metabólicos a escala genòmica (Genome-Scale Metabolic Models (GEMs)) para las tres reconstrucciones de MCF-7 y de *F. nucleatum* en archivo xml.
  - `Scripts` contiene el código de los modelos de la comunidad, de las reacciones de intercambio entre la comunidad y el medio, y del análisis de knock-out.
  - `Suplementarias` contiene las tablas suplementarios (flujos de reacciones de intercambnio y del medio, tiempo de duplicaciòn, entre otros.
  

# Atribución
Este trabajo forma parte de la tesis de Maestría de Gabriela Montserrat Torres Fernandez, perteneciente al Programa de Maestría y Doctorado en Ciencias Bioquìmicas de la Universidad Nacional Autónoma de México. Bajo la dirección del Dr. Osbaldo Resendis Antonio.

[Human Systems Biology Lab](https://resendislab.github.io/)
