Fundamentos de programación
JAVA HOME
Variable de entorno que almacena la ruta donde está instalado el JDK (Java Development Kit) en un sistema. Se utiliza para que aplicaciones y herramientas de desarrollo puedan localizar y utilizar Java correctamente.

EJEMPLO:

public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}

JAVA INTRO
Java es un lenguaje de programación de propósito general, de alto nivel y orientado a objetos, desarrollado originalmente por James Gosling en Sun Microsystems y lanzado en 1995 

EJEMPLO:

public class Main {
  public static void main(String[] args) {
    String name = "John";
    System.out.println("Hello " + name);
  }
}

JAVA GET STARTED
Es el proceso inicial para comenzar a programar en Java. Consiste en instalar el JDK, configurar el entorno de desarrollo, escribir el primer programa, compilarlo y ejecutarlo para verificar que Java funciona correctamente

EJEMPLO:

public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}

JAVA SYNTAX
Es el conjunto de reglas y estructuras que definen cómo se debe escribir el código en Java. Incluye aspectos como la declaración de clases, métodos, variables

EJEMPLO:

public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}

JAVA STATEMENTS
Son las instrucciones que indican al programa qué acción debe realizar. Cada sentencia suele finalizar con un punto y coma

EJEMPLO:

System.out.println("Java is fun!");

JAVA SYNTAX CODE CHALLENGE
Su objetivo es ayudar a los estudiantes a comprender las reglas del lenguaje, mejorar la escritura de código y desarrollar habilidades para detectar y solucionar errores comunes

EJEMPLO:

public class Main {
  public static void main(String[] args) {
    // Write your code here
  }
}

JAVA OUTPUT
Es la forma en que un programa Java muestra información al usuario. Generalmente, la salida se presenta en la consola mediante instrucciones como System.out.println

EJEMPLO:

System.out.println("Hello World!");
System.out.println("I am learning Java.");
System.out.println("It is awesome!");

JAVA OUTPUT NUMBERS
Permite visualizar valores numéricos, realizar cálculos matemáticos y mostrar sus resultados al usuario sin necesidad de convertirlos a texto.

EJEMPLO:

System.out.println(3);
System.out.println(358);
System.out.println(50000);

JAVA COMMENTS
Son notas o explicaciones que se escriben dentro del código para facilitar su comprensión, los comentarios no son ejecutados por el programa y sirven para documentar

EJEMPLO:

System.out.println("Hello World"); // This is a comment

JAVA VARIABLES
Son espacios de memoria que se utilizan para almacenar datos que pueden cambiar durante la ejecución de un programa

EJEMPLO:

int myNum = 15;
System.out.println(myNum);

JAVA PRINT VARIABLES
Es la acción de mostrar en la consola el valor almacenado en una variable utilizando instrucciones como System.out.println() o System.out.print()

EJEMPLO:

String firstName = "John ";
String lastName = "Doe";
String fullName = firstName + lastName;
System.out.println(fullName);

JAVA DECLARE MULTIPLE VARIABLES
Es una característica de Java que permite declarar varias variables del mismo tipo de dato en una sola línea de código, haciendo que el programa sea más compacto y fácil de leer

EJEMPLO:

int x = 5;
int y = 6;
int z = 50;
System.out.println(x + y + z); // 61

JAVA IDENTIFIERS
Son los nombres que se utilizan para identificar variables, métodos, clases y otros elementos de un programa

EJEMPLO:

// Good
int minutesPerHour = 60;

// OK, but not so easy to understand what m actually is
int m = 60;

JAVA CONSTANTS
Son valores que no pueden modificarse después de ser asignados, en Java, las constantes se declaran utilizando la palabra clave final

EJEMPLO:

final int MINUTES_PER_HOUR = 60;
final int BIRTHYEAR = 1980;

JAVA VARIABLES
Son espacios de memoria que permiten almacenar datos que pueden cambiar durante la ejecución de un programa

EJEMPLO:

// Student data
String studentName = "John Doe";
int studentID = 15;
int studentAge = 23;
float studentFee = 75.25f;
char studentGrade = 'B';

// Print variables
System.out.println("Student name: " + studentName);
System.out.println("Student id: " + studentID);
System.out.println("Student age: " + studentAge);
System.out.println("Student fee: " + studentFee);
System.out.println("Student grade: " + studentGrade);

JAVA NUMBERS
Son tipos de datos utilizados para almacenar y manipular valores numéricos dentro de un programa, Java dispone de diferentes tipos de números, como int para números enteros y double para números decimales

EJEMPLO:

short myNum = 5000;
System.out.println(myNum);

JAVA BOLEAN
Son un tipo de dato que solo puede almacenar dos valores: true (verdadero) o false (falso),se utilizan principalmente para representar condiciones lógicas

EJEMPLO:

boolean isJavaFun = true;
boolean isFishTasty = false;
System.out.println(isJavaFun);     // Outputs true
System.out.println(isFishTasty);   // Outputs false
