import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        double x = scanner.nextDouble();

        boolean isInsideSegment = isInsideSegment(x, 3, 8);
        System.out.println(isInsideSegment);
    }

    public static boolean isInsideSegment(double x, double start, double end) {
        return x >= start && x <= end;
    }
}
