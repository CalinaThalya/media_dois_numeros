java
import java.util.Scanner;

public class MediaDeDoisNumeros {
   public static void main(String[] args) {
      int num1, num2;
      double media;

      Scanner sc = new Scanner(System.in);

      System.out.println("Digite o primeiro número inteiro: ");
      num1 = sc.nextInt();

      System.out.println("Digite o segundo número inteiro: ");
      num2 = sc.nextInt();

      media = (num1 + num2) / 2.0;

      System.out.println("A média é " + media);

      sc.close();
   }
}
