
# Enunciado Propuesta ejercicio Semana Santa

Se quiere diseñar una aplicación de valoración de artículos académicos.

- Los investigadores registrados podrán ser autores de artículos y/o 
puntuar aquellos artículos de los que no sean autores.

- De cada artículo se almacenará su título, fecha de publicación y sus autores 
(un artículo tiene, normalmente, varios autores, y es importante almacenar 
la posición en la que estos aparecen: 1.er autor, 2º autor, etc.).

- Cada artículo puede ser citado en otros artículos 
y un artículo puede citar otros muchos. 
Esa cita podrá considerarse positiva o negativa.

- Además de las citas, cualquier investigador podrá puntuar un artículo con valoración positiva o negativa (solo con esos dos valores). Habrán de registrarse todas las valoraciones (qué investigador valoró, qué artículo con qué valoración) y en qué fecha se realizó.

- Los artículos podrán categorizarse en una o varias categorías, y tendrán una puntuación en cada una de ellas (el cálculo de esa puntuación no será relevante para este ejercicio).

- A su vez, los investigadores también tendrán una puntuación en cada categoría a la que estén asignados (que podrá no ser ninguna o ser varias).

- La puntuación de un artículo en una categoría se calculará sumando las valoraciones que tiene, ponderándolas por la puntuación de cada investigador en esa misma categoría (si un artículo es puntuado positivamente por 2 investigadores, uno con una puntuación 10 y otro con 20, el artículo pasará a tener una puntuación 30).

- La puntuación de un investigador en una categoría se calculará sumando las valoraciones de las publicaciones de las que es autor (si ha publicado 3 artículos, con puntuaciones 10, 20 y 30, el investigador pasará a tener una puntuación de 60).

## Ejercicio:

-Plantear uml (diagrama de clases), implementacion base de datos asociada (modelo E-R).

