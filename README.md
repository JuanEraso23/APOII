# APOII

Curso de Algoritmos y Programacion II.

## Descripción
Registro de Actividades. 

### Programas

Eclipse 
### ![ALT](https://2.bp.blogspot.com/-PqNShh8OyR0/WbnhQF1M_xI/AAAAAAAAM0Q/ZD4RsPm6hjkYrIGh61sTcY2HKxRJGsTuwCLcBGAs/s1600/eclipse-800x188.png)

### Instalación

1. Ingresa a la página oficial de Eclipse.

```
[anchor](https://www.eclipse.org/)
```

2. Presiona la opción "Download".

![ALT]()

3. Presiona la opción "Download x86_64".

![ALT]()

4. Presiona la opción "Download".

![ALT]()

## Archivos

### Ejercicio 01
Calcula la distancia de un cuerpo según la velocidad y el tiempo dadas

_Sin Ingreso Por Teclado_

```
package ej01

public class Ej01 {
      public static void main (String [] args) {
      int d=0;
      int v=4
      int t=8;
      
      d=(v*t)
      System.out.print("Distancia: "+d);
      }
}
```

_Scanner_

```
package ej01
import java.util.Scanner;
public class Ej01 {
      public static void main (String [] args) {
      Scanner sc=new Scanner(System.in);
      System.out.print("Ingrese la Velocidad");
      int v=sc.nextInt();
      System.out.print("Ingrese el Tiempo (Seg)");
      int t=sc.nextInt();
      
      int d=(v*t)
      System.out.print("Distancia: "+d);
      }
}
```

_JOptionPane_

```
package ej01
import javax.swing.JOptionPane;
public class Ej01 {
      public static void main (String [] args) {
      int v=Integer.parseInt(JOptionPane.showInputDialog(null, "Ingrese la Velocidad"));
      int t=Integer.parseInt(JOptionPane.showInputDialog(null, "Ingrese el Tiempo (Seg)"));
      
      int d=(v*t)
      JOptionPane.showMessageDialog(null, "Distancia: "+d)
      }
}
```

### Y pruebas de estilo de codificación.

Explique qué prueban estas pruebas y por qué.

```
Give an example
```

## Despliegue (Deployment)

Agregue notas adicionales sobre cómo implementar esto en un sistema en vivo


## Construido con

Dropwizard : el marco web utilizado
Maven - Gestión de dependencias
ROMA : se utiliza para generar canales RSS

## Versionado

Usamos Git para el control de versiones. Para conocer las versiones disponibles, consulte las etiquetas en este repositorio .

## Autores

* **Juan Coronado**
* **Jaider Narvaéz**
* **Juan Eraso**


## Licencia

Este proyecto tiene la licencia MIT; consulte el archivo LICENSE.md para obtener más detalles.

## Expresiones de gratitud (Acknowledgments)

* Un consejo para cualquiera cuyo código se haya utilizado
* Inspiración
* etc
