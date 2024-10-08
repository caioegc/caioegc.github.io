package treino;

import java.util.Scanner;

public class Treino {

    public static void main(String[] args) {

        Scanner tec = new Scanner(System.in);
        int numero;
        int fatorial = 1;

        System.out.println("Escreva um numero para saber sua fatorial");
        numero = tec.nextInt();
        if (numero == 0 || numero == 1) {

            System.out.println(" Fatorial = " + fatorial);
        } else {

            int count = numero;
            while (count >= 1) {
                fatorial = fatorial * count;

                count--;

            }

            System.out.println(" Fatorial = " + fatorial);
        }

    }
}
