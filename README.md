# Selenium UI Dropdowns, Edit Boxes, and Error Validation Assignment

## Overview
This project is an automation script written in Java using Selenium WebDriver. It automates interactions with a web form on [Rahul Shetty Academy's Angular Practice Site](https://rahulshettyacademy.com/angularpractice/), performing actions such as filling out text fields, selecting options from dropdowns, interacting with checkboxes and radio buttons, and submitting the form.

## Prerequisites
Before running the script, ensure you have the following installed:
- Java (JDK 8 or later)
- Maven (optional, if using Maven for dependency management)
- Chrome Browser
- ChromeDriver (managed automatically by WebDriverManager)

## Dependencies
This project uses the following dependencies:
- Selenium WebDriver
- WebDriverManager (for automatic driver management)

To add dependencies, include the following in your `pom.xml` if using Maven:
```xml
<dependencies>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.x.x</version>
    </dependency>
    <dependency>
        <groupId>io.github.bonigarcia</groupId>
        <artifactId>webdrivermanager</artifactId>
        <version>5.x.x</version>
    </dependency>
</dependencies>
```

## How to Run the Script
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repository
   ```
3. Compile and run the Java program:
   ```sh
   javac -cp .;path/to/selenium-java.jar Assignment_UI_Drop_downs.java
   java -cp .;path/to/selenium-java.jar Assignment_UI_Drop_downs
   ```
   Or if using Maven:
   ```sh
   mvn test
   ```

## Features Implemented
- Entering text in input fields
- Selecting options from a dropdown
- Checking/unchecking checkboxes
- Clicking radio buttons
- Submitting a form
- Validating success messages

## Expected Output
Upon successful execution, the script should:
- Fill in the form fields
- Select gender from the dropdown
- Mark a checkbox and radio button
- Submit the form
- Print a success message from the webpage

## Contributing
Feel free to fork this repository and contribute improvements. Create a pull request with detailed information on the changes made.

## License
This project is licensed under the MIT License.

## Author
Kundan Prasad

