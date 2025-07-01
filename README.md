import java.util.Scanner;

public class RectangleCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt user for length
        System.out.print("Enter the length of the rectangle: ");
        double length = scanner.nextDouble();

        // Prompt user for width
        System.out.print("Enter the width of the rectangle: ");
        double width = scanner.nextDouble();

        // Calculate area and perimeter
        double area = length * width;
        double perimeter = 2 * (length + width);

        // Display results
        System.out.println("Area of the rectangle: " + area);
        System.out.println("Perimeter of the rectangle: " + perimeter);

        scanner.close();
    }
}
