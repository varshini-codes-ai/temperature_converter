import java.util.Scanner;

public class TemperatureConverter {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        while (true) {
            System.out.println("\n===== TEMPERATURE CONVERTER =====");
            System.out.println("1. Celsius to Fahrenheit");
            System.out.println("2. Fahrenheit to Celsius");
            System.out.println("3. Celsius to Kelvin");
            System.out.println("4. Kelvin to Celsius");
            System.out.println("5. Fahrenheit to Kelvin");
            System.out.println("6. Kelvin to Fahrenheit");
            System.out.println("7. Exit");

            System.out.print("Enter your choice: ");
            int choice = sc.nextInt();

            double temp, result;

            switch (choice) {
                case 1:
                    System.out.print("Enter temperature in Celsius: ");
                    temp = sc.nextDouble();
                    result = (temp * 9 / 5) + 32;
                    System.out.println("Temperature in Fahrenheit: " + result);
                    break;

                case 2:
                    System.out.print("Enter temperature in Fahrenheit: ");
                    temp = sc.nextDouble();
                    result = (temp - 32) * 5 / 9;
                    System.out.println("Temperature in Celsius: " + result);
                    break;

                case 3:
                    System.out.print("Enter temperature in Celsius: ");
                    temp = sc.nextDouble();
                    result = temp + 273.15;
                    System.out.println("Temperature in Kelvin: " + result);
                    break;

                case 4:
                    System.out.print("Enter temperature in Kelvin: ");
                    temp = sc.nextDouble();
                    result = temp - 273.15;
                    System.out.println("Temperature in Celsius: " + result);
                    break;

                case 5:
                    System.out.print("Enter temperature in Fahrenheit: ");
                    temp = sc.nextDouble();
                    result = (temp - 32) * 5 / 9 + 273.15;
                    System.out.println("Temperature in Kelvin: " + result);
                    break;

                case 6:
                    System.out.print("Enter temperature in Kelvin: ");
                    temp = sc.nextDouble();
                    result = (temp - 273.15) * 9 / 5 + 32;
                    System.out.println("Temperature in Fahrenheit: " + result);
                    break;

                case 7:
                    System.out.println("Thank you for using Temperature Converter!");
                    sc.close();
                    System.exit(0);

                default:
                    System.out.println("Invalid Choice! Please try again.");
            }
        }
    }
}
