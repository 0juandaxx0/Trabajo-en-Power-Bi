# Trabajo-en-Power-Bi
README
Juan David Echeverria García
Pasos de ETL en Power Bi
Septiembre 2025
Se busco un DataFrame o base de datos en la pagina del gobierno “Datos Abiertos” y desde la sección de cultura se encontró la base de datos que evidencia las matriculas a diferentes cursos y materias sobre cultura y arte, contando con 3012 filas y 7 columnas, se guardo como un archivo .csv para su manejo en Power Bi Desktop.

1.	Para abrir y poder empezar a trabajar la base de datos, en la parte de inicio en la opción de Obtener datos elegimos la opción de Texto o CSV el cual es el formato que vamos a trabajar
 
	Buscamos nuestro DataFrame.
 
	Una vez abierta, Power Bi nos mostrara los datos a cargar.
 

2.	Limpieza y transformaciones
	Para ver nuestros datos y poder editarlos, abrimos el editor de Power Bi en transformar datos.
 
	En la parte de vista seleccionamos las casillas de Vista previa de datos, al seleccionarlo nos mostrara información de los datos con porcentajes y diagramas de barras, con esto podremos saber cuántos datos son válidos, cuantos hay que arreglar o transformar y los diferentes tipos de cada columna.
 
	El primer paso es convertir la primera fila del archivo como un encabezado, en este caso Power automáticamente configura y detecta la primera columna como el encabezado asi que no es necesario.
 
	El primer dato o columna de datos que debemos cambiar es el año, como podemos ver este está en tipo texto, y si tal vez quisiéramos hacer un análisis entre años calculando edades entre otras, este tipo de dato no nos servirá por lo que debe cambiarse al menos a un tipo entero, primero quitaremos la coma que indica los miles. Con click derecho en el encabezado buscamos reemplazar valores.
 
	Aquí pondremos el símbolo “,” en el valor que desea buscar y el valor por el que vamos a reemplazar se deja vacío.
 
	Ahora podremos convertirlo en tipo entero sin problemas, lo pondremos entero ya que los datos que nos da la base de datos es poca, deberíamos tener mes dia y año para poderlos convertir a un tipo fecha y trabajar mejor con ellos, aun asi podremos trabajar con ellos asi.
 
	Haremos lo mismo que el paso anterior ahora con la columna de la edad, no la queremos en tipo texto si no es entero.
 
	Por ultimo revise cada columna con la opción de vista que me muestra el perfil de columna con unas barras para ver los datos que aparecen en el DataFrame.
 
	Puedo notar que en el encabezado de zona residencial hay una pequeña parte que no esta definida, quisiera hacerla mas simple y que en lugar de decir “sin definir” diga algo como “ninguna”, para esto reemplazare los valores.
 
	Aquí debo escribir la palabra o frase que voy a cambiar exactamente como aparece en la base de datos, y luego la palabra que quiero utilizar.
 
 
	Como finalmente ninguna otra requiere un arreglo o modificación podemos guardar los cambios, desde la barra de herramientas en inicio de doy cerrar y aplicar.
 
3.	Gráficas y visualización de datos
	Con un grafico de pastel o circular podemos var el porcentaje y la cantidad de personas de cada genero que se inscribe a estos programas.
 
	Por último con un diagrama de barras podemos ver cual es el promedio de edad de las personas dependiendo el curso al que se inscriban, esta opción de puede ver en la opción del eje y 
 
 

