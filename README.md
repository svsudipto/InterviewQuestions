# Strativ Backend Assignment 

### Abstract
In this assignment, you need to fetch data from a source, format them, make them available by creating simple rest APIs. Your APIs should support HTTP clients. People should be able to use CURL, Postman or any other REST client to interact with your APIs. Commit your work according to each phase.


### Task

The weather right now is too hot to handle. Let's travel somewhere to cool off. 

We have the latitude and longitude of all the districts of Bangladesh here: 
```
https://raw.githubusercontent.com/svsudipto/bangladesh-geojson/master/bd-districts.json
```

Using the API from open-meteo.com, we can get the temperature forcasts of each districts for upto 7 days. 
```
https://open-meteo.com/en/docs
```

Now let's get to the interesting part. 

1. Let's make an API for the coolest 10 districts based on the average temperature at 2pm for the next 7 days. 

2. Now as we got the list, where do you want to travel? 

3. Let's say your friend want to travel as well and want your help. Let's create an API where you take your friend's location, their destination, and the date of travel. Compare the temperature of those two locations on that and at 2 PM and return a response deciding if they should travel there or not? 

### Deliverables

You should push your code to a public git repository like github, gitlab or bitbucket with clear instructions about how to run your program.

### Special instructions

* You must use .NET technologies to solve this problem.
* You are free to use any third party library if you want. Just make sure that you have added the dependency of those to your repository and you have given the instruction on the readme file regarding how to run your program including the libraries. The readme should contain any special instruction for installation and configuration of your application.
* Make sure your instructions are clear. You should include the specific version of the libraries, databases etc. Following your instructions, anyone should be able to set up your project in a new machine.
* Commit early and often. Don’t commit everything after finishing the assignment. By looking into your commit message we will try to get an idea how you approached the problem.
