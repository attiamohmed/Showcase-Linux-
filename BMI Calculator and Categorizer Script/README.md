# BMI Calculator Script for Linux

This Bash script calculates the Body Mass Index (BMI) based on user-provided weight and height values. It categorizes the BMI into different categories such as Underweight, Normal Weight, Overweight, and Obesity and displays the result to the user.

## Description

The Body Mass Index (BMI) is a simple measure of a person's weight in relation to their height. It is commonly used to categorize individuals into different weight categories. This script allows Linux users to input their weight (in kilograms) and height (in meters) and calculates their BMI. It then determines the BMI category based on predefined ranges.

## Algorithm

Here's an overview of how the script works:

1. Clears the screen.
2. Prompts the user to enter their weight and height.
   - Enter your height in m:
   - Enter your weight in kg:
3. Calculates the BMI using the formula: BMI = weight / (height * height).
4. Determines the BMI category using if-elif-else statements based on the following ranges:
   - BMI < 18.5: Underweight
   - 18.5 <= BMI < 25: Normal Weight
   - 25 <= BMI < 30: Overweight
   - BMI >= 30: Obesity
5. Displays the calculated BMI and the corresponding category.

## Usage

To use this script on your Linux system, follow these steps:

1. Clone this repository to your local machine or download the script file.
2. Make sure you have `bc` (Basic Calculator) installed on your Linux system. Most Linux distributions come with `bc` pre-installed, but if it's not available, you can install it using your package manager. For example, on Ubuntu or Debian-based systems:
   ```bash
   sudo apt-get install bc
3. Open a terminal and navigate to the directory where the script is located.
4. Make the script executable with the following command:
   chmod +x bmi_calculator.sh
5. Run the script using the following command:
   ./bmi_calculator.sh
6. Follow the prompts to enter your height and weight.
7. The script will calculate your BMI and display it along with the category.

## Contributing

Contributions are welcome! If you have any suggestions or improvements for this script, feel free to open an issue or create a pull request.

## Author
Mohamed Attia.
   
