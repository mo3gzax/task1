public class GravityCalculator {
    public static void main(String[] arguments) {
        //Example
        double gravity = -9.81; // Earth's gravity in m/s^2
        double initialVelocity = 0.0;
        double fallingTime = 10.0;
        double initialPosition = 0.0;
        double finalPosition = 0.0;
        System.out.println("The object's position after " + fallingTime + " seconds is " + finalPosition + " m.");

        //TheTask
        double a = -9.81;
        double vi = 0.0;
        double t = 10.0;
        double xi = 0.0;
        double x = (0.5 * a * Math.pow(t,2)) + vi * t + xi;
        System.out.println("The object's position after falling for " + t + " seconds is " + x + " m.");
    }
}
