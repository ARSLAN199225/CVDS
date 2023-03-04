# CVSD
public class FizzBuzz {
    public static void main(String[] args) {
        for (int i = 1; i <= 100; i++) {
            if (i % 3 == 0 || Integer.toString(i).contains("3")) {
                System.out.print("Fizz");
            }
            if (i % 5 == 0 || Integer.toString(i).contains("5")) {
                System.out.print("Buzz");
            }
            if (i % 3 != 0 && i % 5 != 0 && !Integer.toString(i).contains("3") && !Integer.toString(i).contains("5")) {
                System.out.print(i);
            }
            System.out.println();
        }
    }
}
