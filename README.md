# ejercicio10
actividad
package ejercicio.pkg10;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercicio10 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        int pesokg;
        int gr =1000;
        int resulgr;
        float lb;
        lb=(float) 2.2;
        float resullb;
        int tn =1000;
        float resultn;
        
        System.out.print("Ingrese el peso en KG\n");
        pesokg = entrada.nextInt();
        
        System.out.print("----Valor del peso en KG a Gramos----\n");
        resulgr = pesokg*gr;
        System.out.println("El valor en GR es de:\n"+resulgr+"Gr\n");
        
        System.out.print("---El valor del peso en KG a Libra---\n");
        resullb = pesokg*lb;
        System.out.printf("El valor en LB es de:\n"+resullb+"Lb\n");
        
        System.out.print("---El valor de peso en KG a Toneladas---\n");
        resultn = pesokg/tn;
        System.out.printf("El valor del peso en TN es de:\n"+resultn+"Toneladas");
// TODO code application logic here
    }
    
}
