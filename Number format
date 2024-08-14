import java.text.NumberFormat;
import java.util.Locale;
class Employee {
    private int employee_id;
    private String employee_name;
    private double employee_salary;
    public Employee(int employee_id, String employee_name, double employee_salary) {
        this.employee_id = employee_id;
        this.employee_name = employee_name;
        this.employee_salary = employee_salary;
    }
    public int getEmployeeId() {
        return employee_id;
    }
    public void setEmployeeId(int employee_id) {
        this.employee_id = employee_id;
    }
    public String getEmployeeName() {
        return employee_name;
    }
    public void setEmployeeName(String employee_name) {
        this.employee_name = employee_name;
    }
    public String getFormattedSalary() {
        NumberFormat currencyFormat = NumberFormat.getCurrencyInstance(Locale.US);
        return currencyFormat.format(employee_salary);
    }
    public static void main(String[] args) {
        Employee emp = new Employee(101, "Alice Johnson", 75000.00);
        System.out.println("Employee ID: " + emp.getEmployeeId());
        System.out.println("Employee Name: " + emp.getEmployeeName());
        System.out.println("Employee Salary: " + emp.getFormattedSalary());
        emp.setEmployeeId(102);
        emp.setEmployeeName("Bob Smith");
        System.out.println("\nUpdated Employee Details:");
        System.out.println("Employee ID: " + emp.getEmployeeId());
        System.out.println("Employee Name: " + emp.getEmployeeName());
        System.out.println("Employee Salary: " + emp.getFormattedSalary());
    }
}
