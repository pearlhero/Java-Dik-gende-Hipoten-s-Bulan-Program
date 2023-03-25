# Java-Dik-gende-Hipoten-s-Bulan-Program
Java-Dik Üçgende Hipotenüs Bulan Program

import java.util.Scanner;
public class Baslangic {
    public static void main(String[] args) {
        int a, b;
        double c;

        Scanner girdi = new Scanner(System.in);
        System.out.println("1.Kenarı Giriniz : ");
        a = girdi.nextInt();
        System.out.println("2.Kenarı Giriniz : ");
        b = girdi.nextInt();

        c = Math.sqrt((a*a) + (b*b));
        System.out.println("Hipotenüs : " + c);

    }
}
