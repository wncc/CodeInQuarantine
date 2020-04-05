# Week 1 | Python

## Introduction 
Python is one of the widely used programming languages in the world. Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built-in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms and can be freely distributed.


## Resources

### [Automate the Boring Stuff with Python](http://automatetheboringstuff.com/) 
This is ideal for people who want to see some cool applications of Python to do repetitive tasks. It consists of mini projects after every chapter to help you understand the concepts better.

### [Learn Python Programming](https://www.programiz.com/python-programming)
This is a pretty long tutorial and consists of almost every major concept you can think of. Also, it comes with an in-site Python interpreter so you can check your code there itself.


## Tasks

### 1. Weather Data
Your task is to report the average temperature and humidity of each of those cities over a week.

The following information is given to help you:

In a file named input.txt, you have a list of n cities.
You can use this [Website](https://www.wunderground.com) to scrape the required information.

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


 