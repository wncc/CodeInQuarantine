# Week 1 | Python

## Introduction 
Python is one of the widely used programming languages in the world. Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built-in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms and can be freely distributed.


## Resources

 - ### [I am new to Python - How can I learn the basics of Python](https://www.wncc-iitb.org/wiki/index.php/Python_for_Beginners) 
   _This is ideal for people who have either almost never coded in their lives, or were intimidated by CS101. Starting from what variables are, we'll see how Python can be used to automate many repetitive tasks in everyday life._
- ### [I am an intermediate Python developer - How do I start using packages for real-life use cases](https://www.wncc-iitb.org/wiki/index.php/Intermediate_Python_Programming)
  _Once familiar with the basic concepts of Python, this tutorial will help you consolidate them & explore a wide variety of packages & modules for different use cases._
- ### [I am an advance Python developer - How do I learn advance concepts in Python](https://www.wncc-iitb.org/wiki/index.php/Advance_Python_Programming)
  _If you think you are quite comfortable with Python, this tutorial will help you to extend your knowlegde base by exploring some advance concepts like threading, socket programming, etc._


## Tasks

### 1. Weather Data

The first task is to report the average temperature and humidity of some cities over a week.

The following information is given to help you:

In a file named `input.txt`, you have a list of n cities. Create the file yourself, and list any nummber of cities you want the data for.
You can use this [Website](https://www.wunderground.com) to scrape the required information, i.e. *Temperature* and *Humidity* of the cities given in `input.txt`.  

Scraping is essentially pulling text from an HTML page, programmatically. One can extract the HTML code directly, and then parse it for certain strings. In this case, the HTML code would contain the weather of city in question. One can store it as a string, and use normal string methods to extract useful information from it.  The wiki link below contains a how-to guide to scraping, along with any additional information you may need for the task.


Alternatively, you could use an Application Program Interface (API). This would essentially mean that you get the job done for you. You send a normal HTTP request to an API, and it returns data corresponding to what you asked for. This [Website](https://openweathermap.org/api) provides an API for the task.

Check [this](http://wncc-iitb.org/wiki/index.php/Web_Scraping) out for an overview and resources for Web Scraping.


##### Sample Input (Contents of input.txt)
London                                                                                              
Paris                                                                                                                                                           
Berlin                                                                                              
Frankfurt

##### Sample Output (Could either be a new file or terminal)
London      13       80%                         
Paris       20        78%     
Berlin      17        83%                                                                                                              
Frankfurt   16        81%


### 2. Fetch My Rank

A Physics Professor has just uploaded a sheet with marks of the 1000 freshmen who did his course. All the students want to know their ranks so that they can predict their grade. It’s very tedious to search for a given roll number and calculate their rank. Let's automate this!

Your task is to create a script which keeps running and fetches the rank of a input roll number from the given `.csv` file. The valid range of roll numbers is from 1-1000. All are integers with no missing roll numbers. The script should keep running till the user types *`stop`*.
The script should do something like this - 
![](https://github.com/wncc/CodeInQuarantine/blob/master/script.png "script")

[Here](https://github.com/wncc/CodeInQuarantine/blob/master/marksheet.csv) is the `.csv` file containing the required data.
