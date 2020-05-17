
# Week 7 | Advanced Frontend Development

## Introduction

Back in the day, web developers would implement front end logic by relying heavily on vanilla JS and jQuery. But, as front end applications became more and more complex, the tools rose to meet that complexity and Javascript Frameworks came into picture.
A JavaScript framework is a tool that you can leverage to develop advanced web applications.. At their most basic, JS frameworks are collections of JavaScript code libraries that provide developers with pre-written JS code to use for routine programming features and tasks—literally a framework to build websites or web applications around.
Think of building websites and web apps like building a house—when you set out to build a house, you could create all of your own building materials from scratch and start building without any schematics, but that approach would be incredibly time-consuming and doesn’t make a lot of sense. It’s more likely that you would purchase pre-manufactured building materials (wood, bricks, countertops, etc.) and then assemble them based on a blueprint to fit your specific needs.

Coding is very similar. When you set out to code a website, you could code every aspect of that site from scratch, but there are certain common website features that make more sense to apply from a template—if you need a wheel, for instance, it’s a lot more sensible to buy one than it is to reinvent it. And that’s where JavaScript frameworks come into play.

JS libraries like jQuery are used by plugging library code into the rest of your site’s code when needed while with a framework the process is more holistic—a framework doesn’t just offer an individual solution to a coding problem, it provides a structure (like a skeleton or a scaffolding…or a framework) that organizes the parts of your site where the framework is implemented.

[Here](https://blog.logrocket.com/history-of-frontend-frameworks/) is an interesting read if you would like to read about the history of frontend frameworks.

Native app development is the creation of software programs that run on specific devices and platforms. Unlike websites and web applications, native mobile apps don’t run in the browser. You need to download them from platform-specific app stores such as Apple’s App Store and Google Play. After installation, you can access each app by tapping its respective icon on the screen of your device.
Native app development requires different skills and technologies than mobile website development. You don’t have to worry about browser behavior and compatibility. You can use the native features of mobile OSs to deliver the user experience and implement the functionalities of your app. 


## Resources

- ### [ReactJS](https://www.wncc-iitb.org/wiki/index.php/ReactJs)
	*React is a front end tool to build both UI components and whole UIs – everything that concerns putting together visual elements, binding data to those elements, and specifying the logic governing it. Head to this link to more and learn how to build web apps with React*

## Tasks

### 1. React
#### Weather App
Display a 5-day weather forecast, where each day shows the high and low temperatures, and an image for sunny/rainy/cloudy/snowy. Use hard-coded data until you’ve got everything rendering correctly.
<br>
![](./weather.PNG)  

For added practice, here are a few ways you could expand on the app:
- Add the ability to click on a day, and see its hourly forecast.
- Add React Router to the project (npm install react-router) and follow the quick start guide here to add routes, such that "localhost:3000/" shows the 5-day forecast, and "localhost:3000/[name-of-day]" shows the hourly forecast for a particular day.
- Sign up for a free API key from [Open Weather Map](https://openweathermap.org/api), fetch a real 5-day forecast, and feed that data into your app.

