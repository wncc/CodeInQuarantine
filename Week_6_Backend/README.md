# Week 6 | Backend Development

## Introduction

Last week we introduced you to basics of front end development. However the websites that you created did not have any state. Once you closed the site all information about what you did on the site was lost. Ideally you would like your application to interact with some server so that this information is stored. For instance in your personal website you would like it if a visitor can post a comment which gets stored permanently. This is where the backend comes in. The backend refers to the code running on the server of your website. This code thus allows you to modify resources on the server. For example this backend code could take the comment that you posted via an HTTP request and store it in a database. The next time your site is visited the backend would fetch data from the database and provide it to you through the HTML front end that we talked about last week. Your backend could also do computational heavy tasks which cannot be done in your computer alone. WolframAlpha is one example that uses this very innovatively in their backend. Google uses their backend to run crawlers on the internet that bring you your search results.

It is however very difficult to write backend code without using external frameworks. You will have to manually listen for requests and then serve data while maintaining a connection. Fortunately there are some great frameworks out there that make this process very simple. Let us go through a very powerful framework called Django which allows you to write large scale applications using Python.

## Resources

- ### [Introduction to Django](https://www.wncc-iitb.org/wiki/index.php/Django)
	*Get introduced to Django through this article*

- ### [Basic Django Tutorial](https://www.wncc-iitb.org/wiki/index.php/The_Django_Logic)
	*Create a very simple backend using Django through this tutorial*

- ### [Introduction to Databases](https://www.wncc-iitb.org/wiki/index.php/Database_Management_System)

	*Learn more about databases that you will use to add storage and other features to your backend application*

- ### [Introduction to APIs in Django](https://www.wncc-iitb.org/wiki/index.php/Django_REST_Framework)
	*Provide extensibility to your applications by allowing other users to extend your applications using their own code*

- ### [Introduction to NodeJS](https://www.wncc-iitb.org/wiki/index.php/Node.js)
	*There are other backend frameworks as well. This time we introduce you to NodeJS which allows you to run javascript on the backend also. This means that both your front end and backend can be in one single language, Javascript*
## Tasks

### 1. Your Own Blog

All of us have at one point in time wanted to create a blog where we share our thoughts. Most people use Wordpress or Blogger for this. Your task, if you choose to accept it, is to create your own blogging system using Django.

- The blog must have posts, comments and a login system
- The login system will allow users to login and create new posts.
- There should be an admin interace through which an admin can approve/reject posts so that malicious posts are kept out.
- Add features like adding images to the blog and make the design more beautiful using frameworks like Bootstrap that we introduced you to last week.

### 2. Your Own Chat App

Now we ask of you to make your own whatsapp! Your task is to create a simple chat application using Django.

- The application does not have to be real time. You can simply make the front end make a request (this is called a GET or POST request) periodically to the server and get the messages.
- Once you are done with this you can try researching on Sockets. Sockets allow communication to happen in real time over the internet by using what is called the WebSockets technology. There are numerous modules available for Django that make this simple for you to use. One such module is called SocketIO. You will have to google and read various tutorials to make this work.
- Now you must implement an API for your application. Once you have done this try integrating your chat app to a python script that will send messages periodically.
- If you want you can also do this task using NodeJS to learn a different way of doing things.

### 3. Your Own Instagram

This time you will create a simple photo sharing application using Django.

- This application will allow users to login and upload pictures.
- Implement a common dashboard for every user where their pictures will be seen
- Add commenting features and tagging features.
- If you have done the Machine Learning Code in Quarantine, you could experiment with running your machine learning models on the backend. As your backend is in python and your ML code was also in python you can intergate them. Add a zone in your application for adding cat images. Create a classifier using Keras/TensorFlow that will detect cats in images and link this with your application. This may get a bit difficult to implement so make sure to search online for various implementations.

That's it for this week. We hope to have you onboard next week for some advanced front end development.
