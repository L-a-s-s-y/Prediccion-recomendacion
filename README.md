# Predicción de la rentabilidad y sistema de recomendación de películas.

En este trabajo se ha partido de un [dataset de kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) con información sobre unas 50 000 películas. Hecho junto a [Raúl Rodríguez Fernández](https://github.com/RaulRF02).

El trabajo se ha dividido en dos partes
- En la primera parte se ha tratado de **predecir el *revenue*** de una película en base a las columnas que se han condierado relevantes, esto acompañado de el consecuente estudio de los resultados. Posteriormente se experimentó con la fiabilidad de la predicción de este campo utilizando sólamente variables como director, géneros, keywords y sinopsis mediante análisis de texto.
- En la segunda parte se han implementado tres sistemas de recomendación mediante estrategias híbridas (filtrado colaborativo y basados en contenido) utilizando distintas estrategias y utilidades disponibles ([surprise](https://surpriselib.com/), red neuronal y [lightfm](https://making.lyst.com/lightfm/docs/home.html)). Dos de estos sistemas de recomendación tratan de predecir el rating que dará el usuario y un tercero recomienda en función del ranking de las recomendaciones de los demás usuarios.

#### Para más información consultar la documentación.

**Nota**: Se ha separado en dos notebooks por conflictos entre dependencias de ciertos módulos.