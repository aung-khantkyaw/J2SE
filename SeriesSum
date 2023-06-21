import java.util.Scanner;

public class SeriesSum {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the value of n: ");

        int n = scanner.nextInt();

        

        double sum = 0.0;

        StringBuilder series = new StringBuilder();

        

        for (int i = 1; i <= n; i++) {

            double term = 1.0 / i;

            

            if (i % 2 == 0) {

                term = -term; // negate the term for even i

            }

            

            sum += term;

            

            if (i > 1) {

                series.append(term > 0 ? " + " : " - ");

            }

            series.append("1/" + i);

        }

        

        System.out.println("Series: " + series);

        System.out.println("Sum: " + sum);

    }

}

