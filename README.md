# ConversionCrusher

The ConversionCrusher program is a Java application that allows the user to perform different conversions and calculate a student's graduation honors title based on their GPA. The program uses a scanner to take user input and provides the following options:

- Convert cubic feet to U.S. bushels
- Convert miles to kilometers
- Determine a student's graduation honors title based on their GPA
- Exit the program
- The program includes three methods that handle the conversions and the GPA to graduation honors title calculation. These methods are:

1. cubicToBushel - This method takes a double parameter that represents cubic feet and returns the equivalent U.S. bushels value.
2. miles2Kilos - This method takes a double parameter that represents miles and returns the equivalent kilometers value.
3. gradHonors - This method takes a double parameter that represents a student's GPA and returns a string representing their graduation honors title based on the following GPA ranges:
- 4.0 and above -> "Summa cum laude"
- 3.8 to 3.9 -> "Magna cum laude"
- 3.5 to 3.7 -> "Cum laude"
- Below 3.5 -> "Invalid GPA"

The main method includes a while loop that keeps the program running until the user chooses to exit. The loop prompts the user to select one of the four options mentioned above, takes their input, and validates it using a switch statement. Once a valid input is received, the program calls the appropriate method to perform the conversion or calculation and displays the result to the user.

The program uses printf statements to format the output and provide precision up to two decimal places. It also includes input validation to ensure that the user provides appropriate values within the valid range for each option.

In summary, the ConversionCrusher program is a user-friendly tool for performing conversions and calculating graduation honors based on a student's GPA. It is written in Java, uses a scanner for input, and includes methods for performing conversions and calculating graduation honors.
