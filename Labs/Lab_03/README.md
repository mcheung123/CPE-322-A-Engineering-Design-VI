# Lab 3 - Python

## Instructions

- Go to the [repository](https://github.com/kevinwlu/iot) 
- Go to Lesson 3
- Install required Python packages such as jdcal, astral, and geopy

## Install
I installed using the Python launcher because I was having issues
![0](install.png)

## $ cd ~/iot
changes directories to iot
![0](0.png)

## $ cd *3
Changes directories to the first directory in iot that has a 3 in it. In this case this is the directory "lesson3"
![0](1.png)

## $ python3 julian.py
runs a python script called julian.py. It gives the calendar date, Julian date, and modified Julian date.
![0](2.png)

## $ python3 date_example.py
runs a python script called date_example.py. It gets the current date, formats it in a couple different ways, and calculates the number of days since the first day of classes and until the last day of classes.
![0](3.png)

## $ python3 datetime_example.py
runs a python script called datetime_example.py. It displays time in a couple different ways using the datetime and time modules.
![0](4.png)

## python3 time_example.py
runs a python script called time_example.py. It continuously prints the current local time every 10 seconds until interrupted. 
![0](5.png)

## $ python3 sun.py "New York"
runs a python script called sun.py. It takes in a city, then gives data regarding the sun such as sunrise, sunset, dawn, dusk, and noon.
![0](6.png)

## $ python3 moon.py
runs a python script called moon.py. It prints out the phases of the moon for the next 30 days starting with the current day.
![0](7.png)

## $ python3 coordinates.py "Samuel C. Williams Library"
runs a python script called coordinates.py. It takes in an address or landmark, uses the geopy library to find its geographical coordinates, and prints the full address along with its latitude and longitude.
![0](8.png)

## $ python3 address.py "40.74480675, -74.02532861159351"
runs a python script called address.py. It takes in geographical coordinates, uses the geopy library to find the corresponding address, and prints the full address along with its latitude and longitude.
![0](9.png)

## $ python3 cpu.py
runs a python script called cpu.py. It displays the number of physical and logical CPU cores and prints CPU utilization percentages for each core every second for 10 seconds.
![0](10.png)

## $ python3 battery.py
runs a python script called battery.py. It prints current battery statistics (percentage, seconds left, and whether or not computer is plugged in).
![0](11.png)

## $ python3 documentstats.py document.txt
runs a python script called documentstats.py. It reads a text file (in this case document.txt), counts the occurrences of wordsmexcluding common stop words, and prints the total word count along with the top ten most frequent words.
![0](12.png)

## Summary
By completing this lab, I learned how to run Python commands through the terminal and gained familiarity with basic functions from the jdcal, astral, and geopy packages. I wasn't previously aware of these libraries, so it was great to gain exposure to something new.
