Clase Articulo:

    - Atributos que se especifican en el enunciado fáciles de interpretar y llevar a UML (fecha de publicacion y titulo).

    - Añadiria a mayores un id unico con el que poder identificar de forma inequivoca.

    - Mi idea para tener ponderados a los autores en funcion de la importancia a la hora de crear el articulo es hacerlo con un hashmap.
    En el que tendre un entero y un autor. Este primer entero nos dira el peso que tiene en la creacion del articulo y desde el objeto de clase Investigador accederiamos a los demas atributos que contiene.


    -En el metodo 'addAutor()', paso un autor que ya existe(no lo instancio en el metodo), y consulto el valor del hashmap usando '.size()' ese tamaño sera el integer que le daré y el objeto de la clase Investigador será el segundo parametro. El primer elemento será quien nos diga la importancia del autor asi que es muy importante que se añadan autores en orden.

    -Para guardar las citas dentro del articulo lo haría con un arrayList que contenga enteros.Estos enteros serian los ids de los articulos a los que menciona.

    Tengo dudas en si deberia crear dos arrayList uno para articulos citados positivos y otro para negativos o si deberia crear una clase cita que tenga:
        · Quien cita.(int idArticulo).
        · A quien cita(int idArticulo).
        · Valoracion (boolean true = valoracion positiva).    


    - Desde mi punto de vista las citas a articulos no pueden existir si no existen articulos. Como tampoco deberian existir valoraciones a articulos sin existir quien los valore. Por este motivo las valoraciones deben ser creadas por un Investigador y pasadas como parametro a un metodo que existe dentro del articulo. A este metodo 'addValoracion(Valoracion)' le pasamos un objeto de la clase Valoracion que contiene el id del investigador que valora y el tipo de valoracion.

    - Duda sobre si los articulos deben ser creados por los investigadores. Por ahora vamos a suponer que es así.

Una de las dudas mas importantes que tengo es que mi cabeza quiere organizar el diagrama de modo que los articulos son creados por los autores pero deberian poder existir si se elimina al autor del artiulo y ahí me pierdo. Tambien me cuesta saber como relacionar 'Investigador', 'Articulo', 'Valoracion' y 'Cita'. Porque el 'Investigador' crea 'Articulo' y crea 'Valoracion' y el 'Articulo' crea la 'Cita' a otros articulos .