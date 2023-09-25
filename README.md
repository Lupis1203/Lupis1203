import java.util.Scanner;

/**
 *
 * @author sala1e4
 */
public class calculadora {
    public static void main(String[] args) {
        
    
   Scanner entrada=new Scanner (System.in);
   
 //Se crean las variables de entorno en función del programa.
   int op,a,b,r;
   
  /*
   Se desea realizar un código que pueda resolver operaciones matemáticas de una 
   manera muy rápida y eficaz en el mismo momento en que se requiere, haciendo uso
   de la herramienta NetBeans.
   */ 
 

//Se crea un menú en donde el usuario selecciona la opción que desea realizar.

   System.out.println("Seleccione la opción que desea realizar");
   System.out.println("[1]. Suma");
   System.out.println("[2]. Resta");
   System.out.println("[3]. Multiplicacion ");
   System.out.println("[4]. División");
//La opción elegida se guarda dentro de una variable conocida como "op" para
//realizar la siguiente función del código.
   op=entrada.nextInt();
   
   
    //Se crea una condición para validar las opciones. 
    
     if(op==1)
     {
     
    //Entrada de datos para la ejecución del caso 1.
         
         System.out.println("Ingrese el primer valor");
         a=entrada.nextInt();
         System.out.println("Ingrese el segundo valor");
         b=entrada.nextInt();
    //Operación a realizar para obtener el resultado.
         r=a+b;
    //Imprime el resultado de la operacion en pantalla.
         System.out.println("El resultado es: "+r);
     }
     
   //Entrada de datos para la ejecución del caso 2.  
     else if(op==2)
     {
         System.out.println("Ingrese el primer valor");
         a=entrada.nextInt();
         System.out.println("Ingrese el segundo valor");
         b=entrada.nextInt();
    //Operación a realizar para obtener el resultado.
         r=a-b;
         System.out.println("El resultado es: "+r);
     }
     else if(op==3)
     {
         System.out.println("Ingrese el primer valor");
         a=entrada.nextInt();
         System.out.println("Ingrese el segundo valor");
         b=entrada.nextInt();
    //Operación a realizar para obtener el resultado.
         r=a*b;
         System.out.println("El resultado es: "+r);
     }
     else if(op==4)
     {
         System.out.println("Ingrese el primer valor");
         a=entrada.nextInt();
         System.out.println("Ingrese el segundo valor");
         b=entrada.nextInt();
    //Operación a realizar para obtener el resultado.
         r=a/b;
     //Imprime el resultado de la operacion en pantalla.
         System.out.println("El resultado es: "+r);
     }
     
    
  }
}
