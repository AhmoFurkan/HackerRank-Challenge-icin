# HackerRank-Challenge-icin
girdiğiniz sayıyı 1'den 10'a kadar çarpar

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Sayı giriniz :");
        int number = inp.nextInt();
        int total = 1;

        for (int i = 1; i <= 10; i++) {

            total = number * i;
            System.out.println(number + " x " + i + " = " + total);

        }
      }
     }
![image](https://user-images.githubusercontent.com/107626332/182852182-651332ef-b625-495a-9ce2-169f37b031b0.png)
     
