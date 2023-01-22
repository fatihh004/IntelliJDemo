# IntelliJDemo
www.patika.dev
import java.util.Scanner;
public class taxi {
    public static void main(String[] args) {
    int km ;
    double perKm = 4.20 , baslangic = 20 ;

        Scanner input = new Scanner(System.in);
        System.out.println("Km Değerini Yazınız :) ");
        km = input.nextInt();
        baslangic += km * perKm ;
        baslangic = (baslangic < 30 ) ? 30 : baslangic ;

        System.out.println("Toplam Tutar  : " + baslangic);

    }
}
