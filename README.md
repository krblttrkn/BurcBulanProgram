# ÖDEV : 
## Burç Bulan Program
* Aynı örneği switch-case kullanmadan yapınız.
```
import java.util.Scanner;

public class BurcBulanProgram {
    public static void main(String[] args) {
        int month, day;
        String horoscope = "";
        boolean isError = false;
        Scanner input = new Scanner(System.in);

        System.out.print("Doğduğunuz Ay : ");
        month = input.nextInt();
        System.out.print("Doğduğunuz Gün : ");
        day = input.nextInt();

        if (month == 1) {
            if (day < 22) {
                horoscope = "Oğlak";
            } else if (day <= 31) {
                horoscope = "Kova";
            } else {
                isError = true;
            }
        } else if (month == 2) {
            if (day < 20) {
                horoscope = "Kova";
            } else if (day <= 28) {
                horoscope = "Balık";
            } else {
                isError = true;
            }
        } else if (month == 3) {
            if (day < 21) {
                horoscope = "Balık";
            } else if (day <= 31) {
                horoscope = "Koç";
            } else {
                isError = true;
            }
        } else if (month == 4) {
            if (day < 21) {
                horoscope = "Koç";
            } else if (day <= 31) {
                horoscope = "Boğa";
            } else {
                isError = true;
            }
        } else if (month == 5) {
            if (day < 22) {
                horoscope = "Boğa";
            } else if (day <= 31) {
                horoscope = "İkizler";
            } else {
                isError = true;
            }
        } else if (month == 6) {
            if (day < 23) {
                horoscope = "İkizler";
            } else if (day <= 31) {
                horoscope = "Yengeç";
            } else {
                isError = true;
            }
        } else if (month == 7) {
            if (day < 23) {
                horoscope = "Yengeç";
            } else if (day <= 31) {
                horoscope = "Aslan";
            } else {
                isError = true;
            }
        } else if (month == 8) {
            if (day < 23) {
                horoscope = "Aslan";
            } else if (day <= 31) {
                horoscope = "Başak";
            } else {
                isError = true;
            }
        } else if (month == 9) {
            if (day < 23) {
                horoscope = "Başak";
            } else if (day <= 31) {
                horoscope = "Terazi";
            } else {
                isError = true;
            }
        } else if (month == 10) {
            if (day < 23) {
                horoscope = "Terazi";
            } else if (day <= 31) {
                horoscope = "Akrep";
            } else {
                isError = true;
            }
        } else if (month == 11) {
            if (day < 22) {
                horoscope = "Akrep";
            } else if (day <= 31) {
                horoscope = "Yay";
            } else {
                isError = true;
            }
        } else if (month == 12) {
            if (day < 22) {
                horoscope = "Yay";
            } else if (day <= 31) {
                horoscope = "Oğlak";
            } else {
                isError = true;
            }
        } else {
            isError = true;
        }

        if (isError) {
            System.out.print("Hatalı İşlem Yaptınız, Tekrar Deneyiniz.");
        } else {
            System.out.print("Burcunuz : " + horoscope);
        }
    }
}
```
# Patika Profilim
<a href='https://academy.patika.dev/profile'><u>Profil Sayfam</u></a>