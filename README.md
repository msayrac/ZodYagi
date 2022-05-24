# ZodYagi
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int birthYear, remainder;


        Scanner input = new Scanner(System.in);

        System.out.println("Please enter birthyear : ");

        birthYear = input.nextInt();

        remainder = birthYear % 12;

        switch (remainder) {

            case 0:
                System.out.println("Çin Zodyagı burcunuz : At");
                break;
            case 1:
                System.out.println("Çin Zodyagı burcunuz : Horoz");
                break;
            case 2:
                System.out.println("Çin Zodyagı burcunuz : Köpek");
                break;
            case 3:
                System.out.println("Çin Zodyagı burcunuz : Domuz");
                break;
            case 4:
                System.out.println("Çin Zodyagı burcunuz : Fare");
                break;
            case 5:
                System.out.println("Çin Zodyagı burcunuz : Öküz");
                break;
            case 6:
                System.out.println("Çin Zodyagı burcunuz : Kaplan");
                break;
            case 7:
                System.out.println("Çin Zodyagı burcunuz : Tavşan");
                break;
            case 8:
                System.out.println("Çin Zodyagı burcunuz :  Ejderha");
                break;
            case 9:
                System.out.println("Çin Zodyagı burcunuz :  Yılan");
                break;
            case 10:
                System.out.println("Çin Zodyagı burcunuz : At");
                break;
            case 11:
                System.out.println("Çin Zodyagı burcunuz :  Koyun");
                break;
        }
    }
}
