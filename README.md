import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double tutar, kdvOran = 0.18, kdvTutar, kdvliTutar ;

        Scanner input = new Scanner(System.in);
        System.out.print("ücret tutarını giriniz:");
        tutar = input.nextDouble();

        kdvTutar = tutar * kdvOran;
        kdvliTutar = tutar + kdvTutar;

        System.out.println("kdvsiz tutar: " + tutar);
        System.out.println("kdv oranı: " + kdvOran);
        System.out.println("kdv tutar: " + kdvTutar);
        System.out.println("kdvli tutarı: " + kdvliTutar);

    }
}
