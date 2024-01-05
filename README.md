import java.util.Scanner;

public class Practice {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String[] strArray = new String[3];
        int[] xArray = new int[3];

        System.out.println("================================");

        for (int i = 0; i < 3; i++) {
            strArray[i] = sc.next();
            xArray[i] = sc.nextInt();
        }

        for (int i = 0; i < 3; i++) {
            System.out.printf("%-15s%03d%n", strArray[i], xArray[i]);
        }

        System.out.println("================================");
    }
}
