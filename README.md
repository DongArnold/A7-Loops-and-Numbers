![Screenshot_20221126_195607_com android chrome](https://user-images.githubusercontent.com/112841655/204087795-1afb53d5-5161-4a43-9f69-80d5f5be315e.jpg)
# A7-Loops-and-Numbers

import java.util.Scanner;

class Main {
  public static void main(String[] args) {

    Double number, sum = 0.0;
    // create an object of Scanner
    Scanner input = new Scanner(System.in);

    for (int i = 1; i < 6; ++i) {
      System.out.print("Enter number " + i + " : ");
      // takes input from the user
      number = input.nextDouble();

      // if number is negative
      // continue statement is executed
      if (number <= 0.0) {
        continue;
      }

      sum += number;
    }
    System.out.println("Sum = " + sum);
    input.close();
  }
}
