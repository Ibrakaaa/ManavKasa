# ManavKasa
### Java 101 - Manav Kasa Programı
(www.patika.dev)

import java.util.Scanner;

public class ManavHesap {
    public static void main(String[] args) {

        double elma=6.5,muz =24,üzüm= 14.5,domates= 8.5,karpuz=3.5,toplam;
        double ekilo,mkilo,dkilo,kkilo,ükilo;


        Scanner ürünler=new Scanner(System.in);

        System.out.print("Elma Kaç Kilo: ");
        ekilo = ürünler.nextDouble();
        System.out.print("Muz Kaç Kilo: ");
        mkilo = ürünler.nextDouble();
        System.out.print("Üzüm Kaç Kilo: ");
        ükilo = ürünler.nextDouble();
        System.out.print("Domates Kaç Kilo: ");
        dkilo = ürünler.nextDouble();
        System.out.print("Karpuz Kaç Kilo: ");
        kkilo = ürünler.nextDouble();

        toplam = elma*ekilo+muz*mkilo+üzüm*ükilo+domates*dkilo+karpuz*kkilo;
        System.out.println("Toplam Tutar :" +toplam+" TL");

        

    }
    }

