# CucuReporter

## Description
This spring boot java application is primarily created to read the cucumber json report(s) and create the cucumber report in HTML format. It generates html reports with charts showing the results of cucumber runs. As it is a spring boot application, any user can view the report just by using a URL.
  
## Background
Cucumber is a test automation tool following the principles of Behavioural Driven Design and living documentation. Specifications are written in a concise human readable form and executed in continuous integration.

This project allows you to generate the report in html format and it gets published with the help of spring boot. In order for this to work you must generate a cucumber json report. The project converts the json report into an overview html linking to separate feature files with stats and results.
  
## Download and Install
Just download the java executable file from [here](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/cucureporter-1.0beta.jar).

## Usage
* Download the Jar file from the aforementioned section.
* Create the YAML file as shown [here](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/cucureporter.yml). Name of the yaml file *MUST* be cucureporter.yml and it must be present in the same folder where you have downloaded the jar file.
* Specify the name of the project in cucureporter.yml file in our case, we have specified "frostaxe".
* In the yaml file, create a list with the key "cucumber". In that you will have to specify path of Cucumber JSON file(s). It is shown in the example yaml file which is present in this GitHub repository.

## Command 
* In order to run the application, you will have to run the executable jar file with the below command.
    * java -jar cucureporter-1.0beta.jar

## View Cucumber Report
* In order to view report, Open the below URL in your web browser.
  * http://localhost:8080
  
## Glimpse of CucuReporter

* Stats Page ![CucuReporter Statistics Page](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/CucuReporter/StatsPage.PNG)

* For Dark Theme Lovers ![CucuReporter Dark Theme](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/CucuReporter/DarkTheme.PNG)

* Feel the power of Charts ![CucuReporter Charts](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/CucuReporter/Graph.PNG)
  Click on the Caption of the Grid to view charts

* View the Failures details ![CucuReporter Failures](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/CucuReporter/ViewFailures.PNG)
  To view the error messages. Click on the failed step. ![CucuReporter Failures](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/CucuReporter/Error.PNG)
  


## Author
* Abhishek Prajapati ( prajapatiabhishek1996@gmail.com )

###### Note: Suggestions are always welcome. If you feel anything needs to be added to make this application better. Please feel free to drop me an email @ prajapatiabhishek1996@gmail.com
