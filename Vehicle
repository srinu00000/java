class Vehicle {
    private int speed;
    public Vehicle() {
        this.speed = 0;
    }
    public int getSpeed() {
        return speed;
    }
    public void speedUp() {
        speed += 5;
    }
}
class Car extends Vehicle {
    @Override
    public void speedUp() {
        int currentSpeed = getSpeed();
        setSpeed(currentSpeed + 20);
    }
    private void setSpeed(int speed) {
    }
}
class Bicycle extends Vehicle {
    @Override
    public void speedUp() {
        int currentSpeed = getSpeed();
        setSpeed(currentSpeed + 10);
    }
    private void setSpeed(int speed) {        
    }
}

public class VehicleDemo {
    public static void main(String[] args) {
        Vehicle car = new Car();
        Vehicle bicycle = new Bicycle();
        car.speedUp();
        bicycle.speedUp();
        System.out.println("Car Speed: " + car.getSpeed());
        System.out.println("Bicycle Speed: " + bicycle.getSpeed());
        car.speedUp();
        bicycle.speedUp();
        System.out.println("Car Speed after speeding up again: " + car.getSpeed());
        System.out.println("Bicycle Speed after speeding up again: " + bicycle.getSpeed());
    }
}
