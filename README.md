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
Calcula la distancia de un cuerpo según la velocidad y el tiempo.

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

### Ejercicio 02
Calcula el promedio del estud.

_Sin Ingreso Por Teclado_

```
package ej02

public class Ej02 {
      public static void main (String [] args) {
      
      float n1=5;
      float n2=2;
      float n3=9;
      
      prom=((n1+n2+n3)/3)
      System.out.print("Promedio: "+prom);
      }
}
```

_Scanner_ 

```
package ej02
import java.util.Scanner;
public class Ej02 {
      public static void main (String [] args) {
      Scanner sc=new Scanner(System.in);
      System.out.print("Ingrese las Calificaciones del Estud.");
      float n1=sc.nextFloat();
      float n2=sc.nextFloat();
      float n3=sc.nextFloat();
      
      prom=((n1+n2+n3)/3)
      System.out.print("Promedio: "+prom);
      }
}
```

### Ejercicio 03
Calcula el puntaje de un equipo según los resultados de sus partidos. 

**Nota:** Los partidos ganados equivalen a 3 puntos, los partidos empatados equivalen a 1 punto y Los partidos perdidos equivalen a 0 puntos.

_Sin Ingreso Por Teclado_  

```
package ej04

public class Ej04 {
      public static void main (String [] args) {
      int puntaje=0;
      int pg=5;
      int pp=3;
      int pe=2;
      
      puntaje=(pg*3)+(pp*0)+(pe*1);
      System.out.print("Puntaje: "+puntaje);
      }
}
```

### Ejercicio 04
Se debe identificar el día de la semana según el número . 

_Scanner_

```
package ej04
import java.util.Scanner;
public class Ej04 {
      public static void main (String [] args) {
      Scanner sc=new Scanner(System.in);
      float num=sc.nextFloat();

      if (num==1){
      System.out.print("Lunes");
      }
      else if (num==2){
      System.out.print("Martes");
      }
      else if (num==3){
      System.out.print("Miercoles");
      }
      else if (num==4){
      System.out.print("Jueves");
      }
      else if (num==5){
      System.out.print("Viernes");
      }
      else if (num==6){
      System.out.print("Sabado");
      }
      else if (num==7){
      System.out.print("Domingo");
      }
      else {
      System.out.print("No coincide con algún día");
      }

}
```

### Ejercicio 05
Convierta un valor dado en pesos colombianos a dolares. 

_Scanner_  

```
package ej05
import java.util.Scanner;
public class Ej05 {
      public static void main (String [] args) {
      Scanner sc=new Scanner(System.in);
      System.out.print("Conversor de Monto");
      System.out.print("Monto (Pesos Colombianos):");
      double valor=sc.nextDouble();
      
      dolar=((valor)/19.5)
      System.out.print("Monto (Dolares): "+dolar);
      }
}
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
