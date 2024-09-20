# COP-1220-6-Module-1-Programming-Exercise
This is a GitHub repository link for Programming Exercise of Module 1.

// This program is used to convert inches to centimeters (1 inch = 2.54 cm))
using System;
// Class declaration
class Program
{
  // This is the main method
  static void Main()
  {
    // Declare variables
    Console.WriteLine("Enter the length in inches: ");
    // Convert the input to a double
    double inches = Convert.ToDouble(Console.ReadLine());
    // Declare a variable to store the result
    double centimeters = inches * 2.54;
    // Display the result
    Console.WriteLine("The lenght in centimeters is: " + centimeters);
  }
  
}
