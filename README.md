# ortalama-hesap

import java.util.Scanner;

public class Test {
    public static void main(String[] args) {
        int mat, fizik, kimya, turkce, tarih, muzik;

        Scanner scanner = new Scanner(System.in);

        System.out.println("Matematik Notunuz : ");
        mat = scanner.nextInt();

        System.out.println("Fizik Notunuz : ");
        fizik = scanner.nextInt();

        System.out.println("Kimya Notunuz : ");
        kimya = scanner.nextInt();

        System.out.println("Turkce Notunuz : ");
        turkce = scanner.nextInt();

        System.out.println("Tarih Notunuz : ");
        tarih = scanner.nextInt();

        System.out.println("Muzik Notunuz : ");
        muzik = scanner.nextInt();

        int toplam = (mat + fizik + kimya + tarih + muzik+ turkce);

        double sonuc = toplam / 6.0;
        System.out.println("ortalamanız : " + sonuc);

        String durum = sonuc>=60? "Sınıfı Geçti":"Sınıfta Kaldı";
        System.out.println(durum);

    }
}
