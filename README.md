package JavaExceptions;

public class ExceptionDivision {
    public static void main(String[] args) {
        int a = 9;
        int b = 0;
        try {
            int result = a / b;
        } catch (Exception e) {
            System.out.println("Division by zero is not possible, try again");
        }
        System.out.println("==++==++==++==++");
    }
}
