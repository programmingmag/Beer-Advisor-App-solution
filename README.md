# Beer-Advisor-App-solution

Download Here: [Beer Advisor App solution](https://jarviscodinghub.com/assignment/lab-exercise-2-beer-advisor-app-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Introduction
The goal of this lab is to know how to create an app which the user can interact with. You will create a Beer Adviser app. In the app, users can select the types of beer they enjoy, click a button and get back a list of tasty beers to try out.
Activities
1. Let’s begin by creating the new app (the steps are similar to those we used in Lab1):

2. Update the layout file. Create the interface of your app. When you click on the Finish button, Android Studio creates a new project containing an activity called FindBeerActivity.java and a layout called activity_find_beer.xml. Let’s start by changing the layout file. To do this, go to the app/src/main/res/layout folder, and open the file activity_find_beer.xml. Just like before, the wizard has created a default layout for us with a “Hello world!” element on the page like lab1:
Change the layout file by using design or text to the following look( a spinner, a button, and a textview). Below figure gives you some ideas about the functionality your app need to implement. The spinner shows different types of beer, the user makes a selection from spinner, then click the button, then the BeerExpert java class to provide you with a selection of suitable beers.

how to implement the interface? Give you several hints:
a. Change the strings.xml file for new string variables:

b. add a string-array resource to your app. Open up strings.xml and add the array like this:

b. get the spinner to reference a string_array.

3. Make the button to call a method

Button on click method

4. Activity code.
You might notice that if you test run your app, the textview only shows the selected item of the spinner. You need to add a java class named BeerExpert class to your project. The custom class BeerExpert will provide the names of beer in each category.

5. Custom java class.

6. We need to enhance the onClickFindBeer() method to call the BeerExpert class for beer recommendations.



