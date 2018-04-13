import javax.swing.*;

/**
 * Created by aluno on 12/04/2018.
 */
public class aula09 {
    /*public static void latir (int numVezes){
        System.out.println("Meu cachorro "+ "Vai latir! ");
        System.out.println("Meu cachorro "+"Latiu! ");

        for (int i =1; i <= numVezes; i++){
            System.out.println("au!");
        }
    }*/
    /*public static void envia(){
        recebe (12, 34);
    }
    public static void recebe(int x, int y){
        int z = x+y;

        System.out.println(z);
    }*/


    public static void main(String [] args){
        //latir(3);
        //envia();
        Integer [] A = new Integer[2];
        Integer [] B = new Integer[2];
        Integer [] C = new Integer[2];

        for (int i = 0; i < A.length; i++){
            A [i] = Integer.parseInt(JOptionPane.showInputDialog(null,"Digite os elementos de A: "));
            B [i] = Integer.parseInt(JOptionPane.showInputDialog(null,"Digite os elementos de B:"));
            C [i] = Integer.parseInt(JOptionPane.showInputDialog(null,"Digite os elementos de C: "));

            if (A [i] % 2 == 0){

            }else(){

            }
        }

    }

}
