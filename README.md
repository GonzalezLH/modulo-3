# modulo-3



Ejercicio uno:
crea un programa que simule un inicio de sesion con dos cadenas de carateres (usuario y contraseña)
luego mostrar dos tipo de mensaje en pantalla:
bienvenido al sistema
y credencial incorrecta....


package educacionit.com;
import java.util.Scanner;
public class programa {

	public static void main (String[] args) {


Scanner datos =new Scanner (System.in);
String usuario = "alumno";
String contraseña= "bootcamp";
String us , con ;
System.out.println("ingresar usuario");
us=datos.nextLine();
System.out.println("ingresar contraseña");
con=datos.nextLine();

if(us== usuario && con==contraseña){
	System.out.println("bienvenido nuevamente");
}while(us!=usuario && con != contraseña) {
	System.out.println("datos incorrectos");
	System.out.println("pruebe nuevamente");
	break;
	
}
	}
}







ejercicio dos:
 que puede hacer una persona dicho pronostico
