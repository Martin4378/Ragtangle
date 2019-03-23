# Ragtangle

import java.util.Scanner;

public class Ragtangle {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        double x1 = Double.parseDouble(scanner.nextLine());

        double y1 = Double.parseDouble(scanner.nextLine());

        double x2 = Double.parseDouble(scanner.nextLine());

        double y2 = Double.parseDouble(scanner.nextLine());

        double lenght = Math.abs(x1 - x2);

        double hight = Math.abs(y1 - y2);

        double face = lenght * hight;

        double parameter = 2 * (lenght + hight);

        System.out.println(face);
        System.out.println(parameter);
    }
}
