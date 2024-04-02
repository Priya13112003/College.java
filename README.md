# College.java
import java.util.Scanner;

public class ProductPurchase {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Get product details
        System.out.println("Enter product details:");
        System.out.print("Product ID: ");
        int productId = scanner.nextInt();
        scanner.nextLine(); // Consume newline
        System.out.print("Product Name: ");
        String productName = scanner.nextLine();
        System.out.print("Category: ");
        String category = scanner.nextLine();
        System.out.print("Unit Price: ");
        double unitPrice = scanner.nextDouble();
        System.out.print("Quantity: ");
        int quantity = scanner.nextInt();

        // Calculate total price
        double totalPrice = unitPrice * quantity;

        // Display purchase details
        System.out.println("Product ID: " + productId);
        System.out.println("Product Name: " + productName);
        System.out.println("Category: " + category);
        System.out.println("Unit Price: " + unitPrice);
        System.out.println("Quantity: " + quantity);
        System.out.println("Total Price: " + totalPrice);

        scanner.close();
    }
}
