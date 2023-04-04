"Clase Artículo:

    -Añadiría a mayores un id único con el que poder identificar de forma inequívoca.

    -Mi idea para tener ponderados a los autores en función de la importancia a la hora de crear el artículo es hacerlo con un hashmap. En el que tendría un entero y un autor. Este primer entero nos dirá el peso que tiene en la creación del artículo y desde el objeto de clase Investigador accederíamos a los demás atributos que contiene.

    -En el método 'addAutor()', paso un autor que ya existe (no lo instancio en el método), y consulto el valor del hashmap usando '.size()'. Ese tamaño será el integer que le daré y el objeto de la clase Investigador será el segundo parámetro. El primer elemento será quien nos diga la importancia del autor, así que es muy importante que se añadan autores en orden.

    -Para guardar las citas dentro del artículo lo haría con un ArrayList que contenga enteros. Estos enteros serían los ids de los artículos a los que menciona.

    -Tengo dudas en si debería crear dos ArrayList, uno para artículos citados positivos y otro para negativos o si debería crear una clase cita que tenga:
    · Quien cita (int idArticulo).
    · A quien cita (int idArticulo).
    · Valoración (boolean true = valoración positiva).

Cita:

    -Desde mi punto de vista, las citas a artículos no pueden existir si no existen artículos. Como tampoco deberían existir valoraciones a artículos sin existir quien los valore. Por este motivo, las valoraciones deben ser creadas por un Investigador y pasadas como parámetro a un método que existe dentro del artículo. A este método 'addValoracion(Valoracion)' le pasamos un objeto de la clase Valoración que contiene el id del investigador que valora y el tipo de valoración.

    -Duda sobre si los artículos deben ser creados por los investigadores. Por ahora, vamos a suponer que es así.

    -Una de las dudas más importantes que tengo es que mi cabeza quiere organizar el diagrama de modo que los artículos son creados por los autores, pero deberían poder existir si se elimina al autor del artículo y ahí me pierdo. También me cuesta saber cómo relacionar 'Investigador', 'Artículo', 'Valoración' y 'Cita'. Porque el 'Investigador' crea 'Artículo' y crea 'Valoración' y el 'Artículo' crea la 'Cita' a otros artículos.

MAYORES DUDAS:

· No sé cómo plantearlo, algunas cosas me encajan mejor al intentar el modelo entidad-relación, otras con código Java y otras con el UML.
· Las cardinalidades no tengo muy claro cuando usar ceros y unos.
· Las claves multievaluadas, entiendo que son los autores en los artículos y las categorías de los artículos."