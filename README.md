# InceKalinSesliHarfler

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

      char harf ='E';
      switch (harf) {
          case 'A':
          case 'I':
          case 'O':
          case 'U':
              System.out.println("Kalın sesli harftir");
              break;
          default:
              System.out.println("İnce sesli harftir");

      }
    }
}
