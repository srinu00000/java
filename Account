class Account {
    private String acc_no;
    private String name;
    private double amount;
    public Account(String acc_no, String name, double initialAmount) {
        this.acc_no = acc_no;
        this.name = name;
        this.amount = initialAmount;
    }
    public void deposit(double depositAmount) {
        if (depositAmount > 0) {
            amount += depositAmount;
            System.out.println("Deposited: $" + depositAmount);
        } else {
            System.out.println("Deposit amount must be positive.");
        }
    }
    public void withdraw(double withdrawAmount) {
        if (withdrawAmount > 0) {
            if (withdrawAmount <= amount) {
                amount -= withdrawAmount;
                System.out.println("Withdrew: $" + withdrawAmount);
            } else {
                System.out.println("Insufficient funds.");
            }
        } else {
            System.out.println("Withdrawal amount must be positive.");
        }
    }
    public void displayAccountInfo() {
        System.out.println("Account Number: " + acc_no);
        System.out.println("Account Holder: " + name);
        System.out.println("Balance: $" + amount);
    }
}

public class BankingSystemDemo {
    public static void main(String[] args) {
        Account acc = new Account("123456", "John Doe", 500.0);
        acc.displayAccountInfo();
        acc.deposit(150.0);
        acc.withdraw(100.0);
        acc.displayAccountInfo();                  
        acc.withdraw(600.0);
        acc.displayAccountInfo();
    }
}
