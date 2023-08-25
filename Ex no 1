# java
//program 1
public class MinimumFinder {
    public static void main(String[] args) {
        // Define two numbers
        int num1 = 10;
        int num2 = 5;

        // Use the conditional operator to find the minimum
        int min = (num1 < num2) ? num1 : num2;

        // Display the minimum
        System.out.println("The minimum of " + num1 + " and " + num2 + " is: " + min);
    }
}

//program 2
import java.util.Scanner;

public class SalesRevenueCalculator {
    public static void main(String[] args) {
        // Create a scanner object to read user input
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the unit price
        System.out.print("Enter unit price: ");
        double unitPrice = scanner.nextDouble();

        // Prompt the user to enter the quantity
        System.out.print("Enter quantity: ");
        int quantity = scanner.nextInt();

        // Close the scanner
        scanner.close();

        // Calculate the revenue without any discount
        double revenue = unitPrice * quantity;

        // Calculate the discount rate
        double discountRate = 0.0;

        if (quantity >= 100 && quantity <= 120) {
            discountRate = 0.10; // 10% discount for quantities between 100 and 120
        } else if (quantity > 120) {
            discountRate = 0.15; // 15% discount for quantities greater than 120
        }

        // Calculate the discount amount
        double discountAmount = revenue * discountRate;

        // Calculate the final revenue after discount
        double finalRevenue = revenue - discountAmount;

        // Display the results
        System.out.println("The revenue from sale: " + finalRevenue);
        System.out.println("After discount: " + discountAmount + " (" + (discountRate * 100) + "%)");
    }
}

//program 3
import java.util.Scanner;

public class CountNumbersWithDigit5 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the value of n
        System.out.print("Enter a positive integer n: ");
        int n = scanner.nextInt();

        // Close the scanner
        scanner.close();

        int count = 0; // Initialize a counter for numbers with the digit 5

        for (int i = 1; i <= n; i++) {
            int number = i;
            
            // Check each digit of the number
            while (number > 0) {
                int digit = number % 10;
                if (digit == 5) {
                    count++;
                    break; // If 5 is found in the number, break out of the inner loop
                }
                number /= 10;
            }
        }

        System.out.println("The count of numbers from 1 to " + n + " with the digit 5 is: " + count);
    }
}

//program 4
public class StringConcatenation {
    public static void main(String[] args) {
        // Create an array of strings
        String[] strings = {"black" , "board", "!"};
        
        // Initialize an empty string to store the concatenated result
        String result = "";
        
        // Iterate through the array and concatenate the strings
        for (int i = 0; i < strings.length; i++) {
            result += strings[i];
        }
        
        // Print the concatenated string
        System.out.println(result);
    }
}

program 5
import java.util.Scanner;

public class PyramidPattern {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number of rows: ");
        int n = scanner.nextInt();
        
        for (int i = 1; i <= n; i++) {
            // Print spaces for alignment
            for (int j = 1; j <= n - i; j++) {
                System.out.print("  ");
            }
            
            // Print numbers in ascending order
            for (int k = 1; k <= i; k++) {
                System.out.print(k + " ");
            }
            
            System.out.println(); // Move to the next line
        }
        
        scanner.close();
    }
}
