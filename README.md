- Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
Scanner console = new Scanner(System.in);

    int lado = 10;
    System.out.println("Digite o valor da lateral do quadrado: " + lado);

    int valor = (lado * lado * 2);
    System.out.println("O dobro da area do quadrado eh de: " + valor  );
  
