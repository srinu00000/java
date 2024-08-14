class Bank {
    public double getRateOfInterest() {
        return 0.0; // Default rate if not overridden
    }
}
class SBI extends Bank {
    @Override
    public double getRateOfInterest() {
        return 8.0;
    }
}
class ICICI extends Bank {
    @Override
    public double getRateOfInterest() {
        return 7.0; 
    }
}    
class AXIS extends Bank {
    @Override
    public double getRateOfInterest() {
        return 9.0; // Rate of interest for AXIS
    }
}
public class BankDemo {
    public static void main(String[] args) {
        Bank sbi = new SBI();
        Bank icici = new ICICI();
        Bank axis = new AXIS();
        System.out.println("SBI Rate of Interest: " + sbi.getRateOfInterest() + "%");
        System.out.println("ICICI Rate of Interest: " + icici.getRateOfInterest() + "%");
        System.out.println("AXIS Rate of Interest: " + axis.getRateOfInterest() + "%");
    }
}
