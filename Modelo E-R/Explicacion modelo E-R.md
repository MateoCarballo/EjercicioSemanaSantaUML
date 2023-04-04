
En el punto 1-> " Los investigadores registrados podrán ser autores de artículos y/o puntuar aquellos artículos de los que no sean autores."

    Hasta donde sé y he buscado no he encontrado ningun simbolo que indique que una asociacion puede ser una u otra (puerta O) y una y otra (puerta &). La verdad que no se realicionar estos dos elementos de forma que cumplan estas condiciones.


En el punto 2-> "De cada artículo se almacenará su título, fecha de publicación y sus autores 
(un artículo tiene, normalmente, varios autores, y es importante almacenar 
la posición en la que estos aparecen: 1.er autor, 2º autor, etc.)."

    Aquí entiendo que autor es un campo multievaliuado, que se mas o menos lo que son, pero no se como tratarlo a la hora de implementar una base de datos asociada. En la parte de UML en la que me imagino como debería ser el código que funcione según las especificaciones que das lo resuelvo, creo mediante listas y hashmaps.

En el punto 3 -> "Cada artículo puede ser citado en otros artículos y un artículo puede citar otros muchos. Esa cita podrá considerarse positiva o negativa."

    Lo que intento es que quede claro que 'Cita' relaciona dos articulos entre sí. Porque cuando se crea una cita, se relacion un articulo que contiene la cita a otro articulo que es citado.

En el punto 4 -> "Además de las citas, cualquier investigador podrá puntuar un artículo con valoración positiva o negativa (solo con esos dos valores). Habrán de registrarse todas las valoraciones (qué investigador valoró, qué artículo con qué valoración) y en qué fecha se realizó."

    Esta parte no tengo ni idea de como resolverla mediante un modelo E-R. He intentado hacerlo en el diagrama de clases.

En el punto 5 -> "Los artículos podrán categorizarse en una o varias categorías, y tendrán una puntuación en cada una de ellas (el cálculo de esa puntuación no será relevante para este ejercicio)."

    ** Aqui no se me ocurre nada de nada de como representarlo ni en UML ni en un modelo E-R para uja base de datos ni Java la verdad. Entiendo que hara un atributo categoria en el modelo E-R que sera multievaluado. Aunque en UML y Java no se como representarlo, ya comenté anteriormente que se me ocurre un HashMap pero no sé que opinas. **
    En el punto dos especificas que informacion se guardará de cada articulo y esto es lo que mas me pierde porque al leerlo la primera impresion es que la/s categoria/s pertenecen a los articulos, es decir, son un atributo de estos. Quiero entender que será una nueva tabla que relacionara las categorias con los articulos pero no me queda nada claro.

En el punto 6 -> "A su vez, los investigadores también tendrán una puntuación en cada categoría a la que estén asignados(que podrá no ser ninguna o ser varias)" 

    **A partir de aqui ya no he sabido hacer más.**

La parte de las puntuaciones me pierde mucho porque si hago que una cosa sea cómoda, hago la otra incomodad de realizar.

