# DriveAppTest
Test Code for Job interview


Application Name: Driver's History App
Date:Nov /2019

Technical Details:
Java Version: 1.7.0_80;
IDE: NetBeans
Author: ?

# Approach
1)The Drivers Story App is a desktop application developed in Java Swing, it was created to track the driver history of a driver.

2)This app includes a User Interface where the final user must input the required values in each field, to finally press the button "New Driver" and display the information in a table, including the calculation of the speed.

3)The user can sort the output by most miles driven to least by clicking the top of the column Speed.

4)Basically my approach was creating a user friendly app that allows to capture the information in a short time and get the results in one click, then the user can sort the output  and understand the data in the best convenient way for his personal purposes.


# Set Up
Please be sure that your java version  1.7.0_80 is installed.

Run the programm and enjoy the magic of the functionality and the user interface.

Test the app according the Test Case  "" you can check here. I wanted to be sure that a human understand how to use the app and that be functional to be used in real life.

# Execution 

1) Through an IDE
Clone this project from GIT and downloade as ZIP.
Unzip and pen the folder in your IDE.
Run the program and use it through the User Interface.

# Problem Statement

The code will process an input file. You can either choose to accept the input via stdin (e.g. if you're using Ruby cat input.txt | ruby yourcode.rb), or as a file name given on the command line (e.g. ruby yourcode.rb input.txt). You can use any programming language that you want. Please choose a language that allows you to best demonstrate your programming ability.

Each line in the input file will start with a command. There are two possible commands.

The first command is Driver, which will register a new Driver in the app. Example:

Driver Dan

The second command is Trip, which will record a trip attributed to a driver. The line will be space delimited with the following fields: the command (Trip), driver name, start time, stop time, miles driven. Times will be given in the format of hours:minutes. We'll use a 24-hour clock and will assume that drivers never drive past midnight (the start time will always be before the end time). Example:

Trip Dan 07:15 07:45 17.3

Discard any trips that average a speed of less than 5 mph or greater than 100 mph.

Generate a report containing each driver with total miles driven and average speed. Sort the output by most miles driven to least. Round miles and miles per hour to the nearest integer.

Example input:

Driver Dan

Driver Lauren

Driver Kumi

Trip Dan 07:15 07:45 17.3

Trip Dan 06:12 06:32 21.8

Trip Lauren 12:01 13:16 42.0

Expected output:

Lauren: 42 miles @ 34 mph

Dan: 39 miles @ 47 mph

Kumi: 0 miles
