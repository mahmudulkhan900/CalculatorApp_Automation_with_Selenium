# CalculatorApp_Automation_with_Selenium

## Project Summary

Automate any series for the calculator app. Pass the series as a parameter to your test method.

For example:

100/10*5-10+60

or

50+10-20*2+10/2

pseudocode for your test function can look like this:

public void doSeries()

{

calcuateSeries("100/10*5-10+60");

}

## Tools and Technologies
 - Web automation tool: Selenium
 - App automation framework: Appium
 - GUI inspector: Appium Inspector
 - IDEs: Intellij IDEA, Android Studio
 - Reporting framework: Allure

## Way to run the project
  - Clone this project
  - Run the following command into the terminal: gradle clean test
  - For generating Allure report, use these commands: allure generate allure-results --clean -output and then allure serve allure-results

## PreRequisite
- Install Android Studio
- Install Appium
- Configure ANDROID_HOME, JAVA_HOME and GRADLE_HOME
  
