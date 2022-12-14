# ChineseZodiac
```
import java.util.Scanner;

public class ChineseZodiac {
    public static void main(String[] args) {
        int year,a;

        Scanner i = new Scanner(System.in);

        System.out.print("Doğum yılınızı giriniz: ");
        year = i.nextInt();

        a = year % 12;

        if (a == 0) {
            System.out.print("Burcunuz MAYMUN");
        } else if (a == 1) {
            System.out.println("Burcunuz HOROZ");

        }else if (a == 2) {
            System.out.println("Burcunuz KÖPEK");

        }else if (a == 3) {
            System.out.println("Burcunuz DOMUZ");

        }else if (a == 4) {
            System.out.println("Burcunuz FARE");

        }else if (a == 5) {
            System.out.println("Burcunuz ÖKÜZ");

        }else if (a == 6) {
            System.out.println("Burcunuz KAPLAN");

        }else if (a == 7) {
            System.out.println("Burcunuz TAVŞAN");

        }else if (a == 8) {
            System.out.println("Burcunuz EJDERHA");

        }else if (a == 9) {
            System.out.println("Burcunuz YILAN");

        }else if (a == 10) {
            System.out.println("Burcunuz AT");

        }else if (a == 11) {
            System.out.println("Burcunuz KOYUN");

        }

    }
}
```
[Patika.dev](https://app.patika.dev/iremr)
