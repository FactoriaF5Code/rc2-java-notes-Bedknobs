## **Cómo crear un proyecto de Java**
Con Visual Studio Code:

1. Abrir Visual Studio Code.
1. Pulsar *F1* y escribir *java:*
1. Hacer click en la opción de *Java: Create Java Project...*
1. Elegir una herramienta si quisiera usarse.
1. Elegir donde se quiere guardar el proyecto.

## **Clase Main**
Es la clase donde se va a ejecutar el código que cree. Ejemplo de una clase main: 

```

    package proyecto;

    public class Proyecto {

        public static void main(String[] args){

        }

    }
```

## **Cómo imprimir mensajes en la consola**
Para imprimir mensajes en la consola se usa *System.out.println()*, poniendo dentro de los paréntesis el mensaje. 


```
    public static void main(String[], args){

        System.out.println("mensaje");

    }
```

## **Tipos de Datos**
Los tipos de datos definen qué puede ser almacenado dentro de una variable y los límites de lo que allí se almacena. Algunos de los más usados son: 

- **Entero**, *int* → Ej: 0, 1, 35, 120, 44, etc
- **Entero largo**, *long* → Ej: 624197054097101680185
- **Decimales**, *double* → Ej: 1.2, 5.8, 35.64, etc
- **Booleanos**, *Boolean* → true o false
- **Caracteres**, *char* → 'a', 'b', 'c', 'i', etc
- **Cadena de Caracteres/Texto**, *String* → Ej: "Hola Mundo" 
## **Cómo declarar una variable**
La declaración de las variables cuenta de dos partes fundamentales:

1. Tipo de Dato → Ej: int
1. Nombre de la variable → Ej: numero
