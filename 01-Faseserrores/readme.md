# Fases de la traducción y errores

### Autor de la resolución:
``` 
Nombre: Genaro
Apellido: Garcia Arana
Legajo: 213.732-0
Usuario: Genarogarciaarana
```

```
Enunciado: Este trabajo tiene como objetivo identificar las fases del proceso de traducción o Build y los posibles errores asociados a cada fase.

1)B) Me di cuenta que al preprocesar hello2.c se genera hello2.i el cual expande los macros del "#include <stdio.h>" y que también elimina el comentario que estaba en el medio del codigo.

1)D) "Int printf" es una función de tipo entero que devuelve el número de caracteres impresos, o un valor negativo si ocurre un error. Luego se pasa como parámetro una variable "s" de tipo "const char *" la cual es un puntero a una cadena de caracteres constante, también se le agrega un "restrict", que es un calificador que le indica al compilador que s es el único puntero que accede a ese bloque de memoria mientras esté en uso en esa función. Por último se le agrega como parámetro una elipsis "..." lo cual significa que la función puede aceptar un número variable de argumentos.

1)E) El codigo entre hello3.c y hello3.i son muy similares ya que para el preprocesamiento no tiene que evaluar ningún "#define" o "#include", aún asi se abren 4 líneas de control antes del codigo que van a indicar de donde provienen las líneas del codigo.

2)C) El objetivo de este código ensamblador es imprimir en pantalla el número 42 usando la función printf de forma "La respuesta es %d\n".

5)B)
i) Si, devuelve un warning.
ii) Es la declaración previa de una función. Se puede generar escribiendolo manualmente en la parte superior del archivo especificando su nombre, tipo de retorno y los tipos de sus parámetros. También se pueden generar mediante archivos.
iii) Una declaración implícita de una función es cuando una función es llamada sin haber sido previamente declarada.
iv) La especificación es transmitir de forma exacta la información de lo que hace y significa la función mediante el correcto nombramiento de sus parámetros, tipos de datos y condicionamientos.
v) Las principales implementaciones del lenguaje C son GCC, Clang y MSVC, las cuales buscan ajustarse al estándar del lenguaje C y presentan diferencias entre sí en compatibilidad, rendimiento, herramientas diagnósticas y portabilidad.
vi) Una función "built-in" es una función proporcionada por el compilador, las cuales estan optimizadas para realizar tareas comunes de forma eficiente.
vii) Gcc actua de cierta manera ya que sigue de forma estricta el estándar del lenguaje de C y C++. Gcc no va en contra de la especificación ya que te da la libertad de nombrar a las funciónes, los parámetros y las variables de la forma que quieras.

6)C) En ambos casos nos debería tirar un error, ya que la función espera 2 argumentos, ni más ni menos.
D)IV) Habiendo definido la librería "studio.h" anteriormente, en el "hello9.c" puedo declarar prontf en la misma. Así despues, en "studio2.c" ya tengo definidas la librería y la función prontf para hacer uso de ellas en el codigo de forma correcta y sin que me devuelva ningún warning o error.

```
