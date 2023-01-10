
# Programación 1

## ------------Clase 1------------

## Tipos de Programacion que se puede realizar con el lenguaje C++

---

Existen dos tipos de programacion que se puede trabajar con el lenguaje C *Programacion Estructurada* y *Programacion orienta a objetos*, en ambos casos es necesario primero contar con un **workspace** en donde poder ***guradar y registrar*** el progreso que se esta realizando con el proyecto.  
  
![img1](https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/800px-ISO_C%2B%2B_Logo.svg.png)

## ---------Clase 2-----------

### Git Hub

---
El Git Hub es una herramienta utilizada para alojar proyectos de programacion en la nube, permite a los desarrolladores colaborar y realizar cambios en proyectos compartidos, a la vez que mantienen un seguimiento detallado de su progreso.
![img6](https://s36496.pcdn.co/wp-content/uploads/2019/01/7_Github_contenido.jpg)

## ---------Clase 3 y 4-----------

### Git

---
La herramienta **Git** es la que nos permite almacenar un proyecto de softwar y gestionar el workspace de nuestro ordenador, para que de esta manera sepamos que tenemos almacenado y que archivos han sido modificados, para ello se utilizan una serie de comandos que nos permiten gestionar el ***Git***.

+ git init
+ git status
+ git add .
+ git add "nombre del directorio"/"nombre del archivo"
+ echo "nombre del archivo" >> .gitignore
+ git commit -m "nombre de la version"
+ pwd
+ ls
+ git version
+ git config --global user.name "nombre"
+ git config --global user.email "correo electronico"  
+ git reverse "codigo unico del commit"
+ cat ."nombre del archivo"
+ git push
+ git pull
![git](https://www.welivesecurity.com/wp-content/uploads/2021/03/Atacantes-vulneraron-repositorio-Git-PHP-a%C3%B1adieron-backdoor-c%C3%B3digo-fuente.jpg)

### El Compilador  

---
Es aquel que se encarga de interpretar  el codigo escrito en ==codigo binario== para que este pueda ser ejecutado por el computador.  
Todos los archivos ejecutables terminan con la extension ***.exe***.  
Este tambien realiza un analisis sintactico y semantico.  
![gcc](data:image/png;base64,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)

## ----------Clase 5,7 y 8--------

### IDE

---
Es el entorno de trabajo en donde se encuentran las herramientas necesarias para la realizacion y el almacenamiento de un proyecto de software, este se compone de dos elementos escenciales los cuales son:

+ La herramienta visual estudio code
+ La herramienta Git

![ide](https://code.visualstudio.com/opengraphimg/opengraph-home.png)

## -----------Clase 6-----------

### Markdown

---
Es una herramienta utilizada para llevar a cabo anotaciones ne formato html, todos los archivos pertenecientes a la herramieta de markdown terminan con la extension ***.md***, esta herramienta tambien cuenta con una serie de comandos que se ejecuitan para desarrollar el texto:
|Comandos|Utilidad|
|------|------|
|#|Almohadilla utilizada para los titulos, van de 1 hasta 5|
|\** texto **|Utilizados para poner un texto en negritas|
|\* texto *|Utilizado para poner el texto en cursiva|
|\*** texto ***|Utilizado para poner el texto en negritas y cursivas|
|\~~ texto ~~|Utilizado para tachar el texto|
|\*,+ o -|Utilizados para representar viñetas en el texto|
|\---|Utilizados como separadores entre el titulo y el texto|
|\[] y [x]|Utilizados para realizar una lista de verificacion|
|\!\[Descripcion imagen](https://ejemplo.com/imagen.jpg)|Comando utilizado para insertar una imagen al texto que se esta realizando|
|\```|Comando utilizado para señalar la presencia del godigo|
![markdown](https://blogthinkbig.com/wp-content/uploads/sites/4/2020/09/Markdown-Logo-Example-Markdown-Preview-Enhanced.jpg?fit=1500%2C1000)

## -------------Clase 9---------

## Creacion del primer proyecto en C

---
Para iniciar con la creacion del primer proyecto al que se ha denominado "Hello World", primero se debe buscar "Create C project" en **Visual Studio Code** por medio de las teclas Shift + Ctrl + P

```C
#include <stdio.h>

int main()
{
    printf("Hello World!\n");
    printf("Hola mundo, mi primer proyecto en C!\n");
    return (0);
} 
```

La primera linea de codigo representa la existencia de liobrerias, las cuales almacenan varios comandos, estas librerias pueden ser mias o de terceros, en la segunda linea de codigo se encuentra el tipo de dato, el cual puede representa una ***funcion*** o un ***procedimiento***, finalmente en las lineas que se encuentran entre llaves se encuentran los comandos que se van a ejecutar en el programa, siendo uno de estos *printf()*, este comando se encarga de presentar el texto en la pantalla del computador.

### Declaracion de Variables

---
Las variables son aquellas que ofrecen un espacio en la ram para el almacenamiento de datos, ademas de que tambien ayudan en la ejecucion de procedimientos y funciones. Para ello se usan los tipos de dato, los cuales hacen referencia al tipo de informacion que se maneja, variando su rango dependiendo del dato utilizado como pueden ser: int, floot, double, char, etc. Manejar adecuadamente los tipos de dato es muy importante puesto que estos ayudan a organizar bien los recursos para consumir menos memoria y que el programa este mejor optimizado. Para declarar una variable se sigue la siguiente estructura:

```c

<tipo de dato><nombre de la variable>; 0=<valor;>
```

%--> llama a la variable declarada y trae lo guardado en la ram para imprimirlo.

## -----------Clase 10-----------

### Errores

Pueden ser:

+ Sintactico: palabras mal escritas que provocan que el codigo no funcione, haciendo especial referencia a las palabras reservadas como int, printf, scanf, for, etc.
+ Semantico: hace referencia a que el codigo tenga sentido, es decir que las palabras se encuentren en un orden correcto.
+ Logico: cuando no se trata de un error semantico ni sintactico y el programa se termina colgando se trata de un error logico, es decir que las instrucciones dadas al programa estan mal hechas.

### Algoritmo

---
Un algoritmo es un proceso a seguir para la solucion de un problema, el cual sera de gran ayuda en el ambito de la programacion puesto que se facilitara encontrar la solucion a problemas de manera eficaz.

## -------Clase 11,12 y 13-------

### Algoritmia

---
Es el proceso que se sigue en la programacion para la solucion de un problema, para ello se siguen cuatro pasos:

+ Pseudocodigo: se trata de escribir el procedimiento a seguir para resolver el problema en lenguaje verbal para luego transcribirlo a codigo.
+ Diagrama de Flujo: el diagrama de flujo se trata del uso de simbologia para representar el codigo con el fin de facilitar la comprension y encontrar mas facilmente una solucion a algun problema.
+ Codificacion: se trata de la transcripcion de la soclucion de un problema en lenguaje de programacion.
+ Trace: se trata de la prueba del codigo con el fin de verificar su funcionamiento adecuado y si la resolucion del problema fue la correcta.
![imgdf](data:image/png;base64,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)

## -----------Clase 14----------

### Estructura basica del lenguaje

---

```C
(1)#include <stdio.h>   
(2)                   
(3) int main(void)          
(4) {
(5)  printf("Hello World!\n");
(6)  } 
```

+ La linea (1) es en donde se encuentran las librerias, las cuales contienen procedimientos y funciones, todas terminan con la extension **.h**, un ejemplo de ello es: <stdio.h>. Esta linea es opcional.  
+ La linea (2) es en donde se colocan las variables globales y se declara procedimientos y funciones. Esta linea es opcional.  
+ La linea (3) es la mas importantey obligatoria dentro del codigo, puesto que sin esta no es posible ejecutar el programa, el compilador se encarga de correr todas las lineas que esten dentro del main().  
+ La linea (4) es donde se colocan las variables locales.
+ La linea (5) es en donde se coloca las instrucciones por medio de codigo al computador.
+ La linea (6) es en donde termina el codigo con **}**.

## ----------Clase 15-----------

### Operadores

---
Los operadores pueden ser aritmeticos, logicos o racionales, los cuales son utilizados principalmente para representar operaciones como la suma, resta, multiplicacion, division, mayor que, menor que, entre otros.
|Operadores Aritmeticos|Funcion|
|------|------|
|+|suma|
|-|resta|
|*|multiplicacion|
|/|division|
|%|cociente de la division|

|Operadores Racionales|Funcion|
|-------|------|
|<|menor|
|>|mayor|
|<=|menor o igual|
|>=|mayor o igual|
|==|igual|
|!=|diferente|

|Operadores Logicos|Funcion|
|-----|-----|
|&&|and, y, conjuncion|
|\|\||or, o, disyuncion|
|!|not, no , negacion|

## ---------Clase 16-----------

### Control de Flujo

---
Son comandos que permiten controlar la cantidad de datos que se transmiten, como:

+ if/else: sentencia que permite condicionar la presentacion de los datos en la pantalla.
+ for: bucle que permite realizar una accion un determinado numero de veces y está compuesto de tres expresiones: la de inicio, la de control y la de incremento, y de una sentencia.
+ while: Un bucle es un conjunto de sentencias que se ejecutan repetidamente hasta que se alcanza una condición de fin de bucle.
+ do-while: Su funcionamiento es análogo el del bucle while, salvo que la expresión de control se evalúa al final del bucle, esto nos garantiza que el bucle do-while se ejecuta al menos una vez.
![ifelse](https://procomsys.files.wordpress.com/2018/05/escon.png?w=640)

## -----------Clase 17-----------

### Arrays

---
Los arrays son variables estructuradas, donde cada elemento se almacena de forma
consecutiva en memoria.
Las cadenas de caracteres son declaradas en C como arrays de caracteres y permiten la
utilización de un cierto número de notaciones y de funciones especiales.
![array](https://cdn.programiz.com/sites/tutorial2program/files/c-arrays.jpg)

## --------Clase 18 y 19---------

### Array en dos dimensiones o matriz

---
Array en dos dimesiones o matriz: es interpretado como un array
(umidimensional) de dimensión "f" (número de filas), donde cada componente es un
array (unidimensional) de dimensión "c" (número de columnas). Un array de dos
dimensiones, contiene, pues, "f*c" componentes.
![matriz](https://codigosdeprogramacion.com/cursos/wp-content/uploads/2017/03/Imagen1.jpg)

## -----------Clase 20-----------

### Creacion de librerias

---
Las librerias son un recipilacion de archivos que poseen cierta funcionalidad que nos permiten llevar a cabo diferentes tareas sin necesidad de preocuparnos por o cómo se hacen sino simplemente entender cómo usarlas.  
Para llamar a las librerias despues de haber sido creadas se utiliza el siguiete formato:

```C
#include <..\lib\nombrelib.h>
```

Para crear una libreria simplemente se lo puede hacer con el comando de consola que nos permite crear nuevos archivos **touch lib/nombrelib.h**.

## ----------Clase 21------------

### Archivos

---
La fstreambiblioteca nos permite trabajar con archivos.

Para usar la fstream biblioteca, se debe incluir tanto el archivo estándar como < iostream > el de < fstream >encabezado:

```c++

#include<iostream>
#include<fstream>
```

## ----------Clase 22 y 23------------

### Editar Archivos

---
Para crear un archivo, se debe utilizar la clase ofstreamo fstreamy especificando el nombre del archivo.  

#### **Escribir Archico**  

Para escribir en el archivo, se debe utilizar el operador de inserción ( <<).

```c++
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream MiArchivo("nombrearchivo.txt");

   MiArchivo << "Hola mundo, edicion de archivos!";
 
  MiArchivo.close();
}
```

#### **Leer Archivo**

```c++
#include <iostream>
#include <fstream>
using namespace std;
string Text;

ifstream LeerAchivo("nombrearchivo.txt");

while (getline (LeerArchivo, Text)) {
    cout << Text;
}

LeerArchivo.close();
```
