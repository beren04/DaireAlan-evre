package first;

import java.util.Scanner;

public class daire {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Daire yarıçapını giriniz:");
        float r = input.nextFloat();
        System.out.println("Daire dilimi açısını giriniz:");
        int a = input.nextInt();
        System.out.println("Dairenin çevresi:"+ (2*3.14*r));
        System.out.println("Dairenin alanı:"+((3.14*(r*r)*a/360)));

    }
}
