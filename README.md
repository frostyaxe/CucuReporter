# CucuReporter

## Description
This spring boot java application is primarily created to read the cucumber json report(s) and create the cucumber report in HTML format. It generates html reports with charts showing the results of cucumber runs. As it is a spring boot application, any user can view the report just by using a URL.
  
## Background
Cucumber is a test automation tool following the principles of Behavioural Driven Design and living documentation. Specifications are written in a concise human readable form and executed in continuous integration.

This project allows you to generate the report in html format and it gets published with the help of spring boot. In order for this to work you must generate a cucumber json report. The project converts the json report into an overview html linking to separate feature files with stats and results.
  
## Download and Install
Just download the java executable file from [here](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/cucureporter-1.0.jar).

## Usage
* Download the Jar file from the aforementioned section.
* Create the YAML file as shown [here](https://github.com/frostyaxe/CucuReporter/blob/CucuReporter/1.0beta/cucureporter.yml). Name of the yaml file *MUST* be cucureporter.yml.
* Specify the name of the project in cucureporter.yml file in our case, we have specified "frostaxe".
* In the yaml file, create a list with the key "cucumber". In that you will have to specify path of Cucumber JSON file(s). It is shown in the example yaml file which is present in this GitHub repository.

## Author
* Abhishek Prajapati ( prajapatiabhishek1996@gmail.com )

