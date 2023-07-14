# SADP-Task---1
public class Calculator {
    public int add(int a, int b) {
        return a + b;
    }

    public int subtract(int a, int b) {
        return a - b;
    }

    public int multiply(int a, int b) {
        return a * b;
    }

    public static void main(String[] args) {
        Calculator calculator = new Calculator();
        int sum = calculator.add(5, 3);
        int difference = calculator.subtract(7, 2);
        int product = calculator.multiply(4, 6);

        System.out.println("Sum: " + sum);
        System.out.println("Difference: " + difference);
        System.out.println("Product: " + product);
    }
}
