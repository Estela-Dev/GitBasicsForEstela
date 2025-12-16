public class Day01Basics {

    public static void main(String[] args) {
        int amount = 100;
        boolean isValid = isValidAmount(amount);

        System.out.println("Amount: " + amount);
        System.out.println("Is valid: " + isValid);

        printTransactions();
    }

    public static boolean isValidAmount(int amount) {
        if (amount > 0) {
            return true;
        } else {
            return false;
        }
    }

    public static void printTransactions() {
        for (int i = 1; i <= 3; i++) {
            System.out.println("Transaction " + i);
        }
    }
}

day02: add conditional logic and loop examples
