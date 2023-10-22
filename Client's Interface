import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int width = scan.nextInt();
        int height = scan.nextInt();
        Rectangle rectangle = new Rectangle(width, height);

        Shape adaptedRectangle = new RectangleAdapter(rectangle);

        System.out.println("Surface Area: " + adaptedRectangle.getArea());
        System.out.println("Perimeter: " + adaptedRectangle.getPerimeter());
    }
}
