``` java
//A variavel "int i" já nao faz sentido colocar já que sempre vai ser 0 na posição inicial.
package javaapplication2;
import java.util.Scanner;
/**
 *
 * @author marce
 */
public class SistemasOp {
    public static void main (String [] args){        
        Scanner input = new Scanner(System.in);
        System.out.println("Digite o processo");
        String processoinput = input.next(); // processo recebido       
        System.out.println("Digite o quantum");
        int quantum  = input.nextInt();     
        int containput = 0; //contador do processo recebido
        
for (int i = quantum;i>0;i--){

    /*if(i==1){
        
    }else{*/
    if(processoinput.isEmpty()){
        System.out.println("Deseja iniciar um novo processo?");
        
    }else{
           
if (processoinput.charAt(0) == 'A' || processoinput.charAt(0) == 'C') { // Posição zero. 
       processoinput = processoinput.replaceFirst("A","");
    if (processoinput.charAt(0) == 'C'){
            String C = input.next();
        }
}else{
}if (processoinput.charAt(0) == 'B'){
        processoinput = processoinput.replaceFirst("B","A");

}else{
	if (processoinput.charAt(0) == 'D'){
	processoinput = processoinput.replaceFirst("D","C");
	String digite1 = input.next();
        

}
}
        System.out.println(processoinput);
    }
    
    }
}
}


``` 
