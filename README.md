# Atividade-1
Lista 1 Exercicio 1

import java.util.Scanner;

public class EX_1{
    public static void main(String[]args){
        Scanner in = new Scanner(System.in);
        int Sub,numero=0;

        System.out.print("Digite um valor:");
        numero = in.nextInt();

        Sub = numero - 1;

        System.out.println("O antecessor do numero é="+Sub);
    }
}
