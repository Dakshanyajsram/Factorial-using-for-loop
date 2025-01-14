class Factorial {
    public static void main(String[] args) {
        int num = 4;
        long factorial = 1;

        for (int i = 1; i <= num; i++) {
            factorial *= i;
        }

        // Printing the final factorial
        System.out.printf("Factorial of %d = %d%n", num, factorial);
    }
}

OUTPUT:
factorial of %d = %d1
factorial of %d = %d2
factorial of %d = %d6
factorial of %d = %d24
 
