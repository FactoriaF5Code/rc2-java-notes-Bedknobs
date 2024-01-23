## **Cómo crear un proyecto de Java**

Con Visual Studio Code:

1. Abrir Visual Studio Code.
1. Pulsar _F1_ y escribir _java:_
1. Hacer click en la opción de _Java: Create Java Project..._
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
## **Comentarios**
Para escribir comentarios de una sola línea hay que poner antes de este dos '//'.
```
    // Esto es un comentario.
```
Para escribir comentarios de varias líneas hay que poner '/*' y '*/' antes y después del comentario respectivamente.
```
    /*
    Esto es un comentario multilínea.
    */
```


## **Cómo imprimir mensajes en la consola**

Para imprimir mensajes en la consola se usa _System.out.println()_, poniendo dentro de los paréntesis el mensaje.

```
    public static void main(String[], args){

        System.out.println("mensaje");

    }
```

## **Tipos de Datos**

Los tipos de datos definen qué puede ser almacenado dentro de una variable y los límites de lo que allí se almacena. Algunos de los más usados son:

- **Entero**, _int_ → Ej: 0, 1, 35, 120, 44, etc
- **Entero largo**, _long_ → Ej: 624197054097101680185
- **Decimales**, _double_ → Ej: 1.2, 5.8, 35.64, etc
- **Booleanos**, _Boolean_ → true o false
- **Caracteres**, _char_ → 'a', 'b', 'c', 'i', etc
- **Cadena de Caracteres/Texto**, _String_ → Ej: "Hola Mundo"

## **Cómo declarar una variable**

La declaración de las variables cuenta de dos partes fundamentales:

1. Tipo de Dato → Ej: int
1. Nombre de la variable → Ej: numero
1. Poner al final el ";".

## **Declarando y asignando valor a variables**

```
    public static void main(String[], args){

        int edad = 2;
        String nombre = "Kai";
        char inicial = 'K';
        double temperatura = 35.1;
        boolean siONo = true;
        long pelos = 157489126;

    }
```

Para el tipo **String** se utilizan siempre comillas dobles (" ") mientras que para el tipo **char** se utilizan siempre comillas simples(' ').

## **Operadores en Java**

Existen tres tipos de operadores en Java:

1. Aritméticos (+, -, \*, /).
1. Relacionales (==, <, >, <=, >=, !=).
1. Condicionales (&&, ||, !).

Se utilizan de la misma manera que en JavaScript:

```
    public static void main(String[],args){

        int num1, num2, resultado;

        num1 = 5;
        num2 = 3;

        resultado = num1 + num2;

    }
```
## **Funciones**
Igual que en JavaScript:
```
    imprimirSaludo(String name){
        System.ou.prinln("Buenas tardes " + name);
    }
```

## **Condicional Simple If | Else**

Igual que en JavaScript:

```
    public static void main(String[],args){

        int num1 = 5;
        int num2 = 3;

        if (num1 > num2) {
            System.out.prinln("El número 1 es mayor");
        }
        else {
            System.out.println("El número 2 es mayor");
        }

    }
```
## **Condicional Anidado If | Else If | Else**

En vez de poner _else if_ como JavaScript, en Java se escribe el _if_ dentro del _else_, como si fuera otra condicional dentro de esta. Ejemplo:

```
    if (num1 > num2) {
        System.out.prinln("El número 1 es mayor");
    }
    else {
        if (num1 == num2) {
            System.out.println("Los dos números son iguales");
        }
        else {
            System-out.println("El número 2 es mayor");
        }
    }
```

No se puede poner un igual (=) solo en las condicionales, porque se reserva para asignación. En las condicionales es obligatorio poner mínimo dos iguales (==).

## **Condicional Switch**

Igual que en JavaScript:

```
    int dia = 5;
    String nombreDia;

    switch (dia) {
        case 1: nombreDia = "Lunes";
        break;
        case 2: nombreDia = "Martes";
        break;
        case 3: nombreDia = "Miércoles";
        break;
        case 4: nombreDia = "Jueves";
        break;
        case 5: nombreDia = "Viernes";
        break;
        case 6: nombreDia = "Sábado";
        break;
        case 7: nombreDia = "Domingo";
        break;
        default nombreDia = "Número de día inválido";
        break;
    }
```
## **Operador Ternario**
El operador ternario es una herramienta para tomar decisiones simples en una sola línea de código. Estructura:
```
    variable = condición ? valor_si_verdadero : valor_si_falso;
```
