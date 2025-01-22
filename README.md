# First-n-numbers
import java.util.Scanner;

public class FirstNNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
// Input from the user
System.out.print("Enter the value of n: ");
int n = scanner.nextInt();
System.out.println("The first " + n + " numbers are:");
for (int i = 1; i <= n; i++) {
    System.out.print(i + " ");
        }
        scanner.close();
    }
}

output-

Enter the value of n: 10
The first 10 numbers are:
1 2 3 4 5 6 7 8 9 10
