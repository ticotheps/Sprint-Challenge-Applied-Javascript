# Sprint-Challenge Applied Javascript - Lambda Times


This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored the DOM and the concept of components. During this Sprint, you studied the DOM, DOM Events, and Components. In your challenge this week, you will demonstrate proficiency by creating an online Lambda newspaper called "Lambda Times."

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in Applied JavaScript.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You are going to create a Lambda Newspaper. Your job is going to be to add functionality to the tabs below the 'Lambda Times' logo. These tabs will act as filters for our articles, and when clicked on, should filter out all articles except those with that tag.

![Working Sprint Challenge Gif](./Sprint-Challenge.gif 'Example of working project')

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. What is the DOM?

    The technical definition of the “DOM” (Document Object Model) is 'an object representation of the HTML elements of a web page.’ However, it is important to remember that the DOM is only a REPRESENTATION of the HTML elements; it is NOT the actual HTML elements themselves. Another way to look at the DOM is viewing it like an API (Application Programming Interface), or like a bridge between the HTML content and the WEB BROWSER. It provides an interface with which two entities, of differing ways of communication, can understand one another. The best analogy, for the DOM, that I have constructed in my own mind is comparing it to the concept of how a writer uses their writing (i.e. - books, essays, articles, etc.) as a way to communicate their thoughts/ideas to a reader. So, the DOM in this analogy would be the books/essays/articles, which, are NOT the ACTUAL thoughts/ideas from inside the writer’s mind (only a visual REPRESENTATION of those thoughts/ideas), just like the DOM is NOT the actual HTML elements themselves (but also only a REPRESENTATION of them).

2. What is an event?

    An ‘event’ is any instance in which a user interacts with a website. When the web browser recognizes that event, it is represented in the DOM as an object. For example, when a user visits a website and clicks on a navigation link (with an event listener on it), that click will trigger the browser into recognizing that a ‘click event’ has occurred and thens store it as an object in the DOM.

3. What is an event listener?

    An ‘event listener’ is the combination of selecting a specific user interaction [with a website] to detect and then firing a specified callback function once that user interaction is detected. For instance, an event listener could be set to listen for any clicks on only the navigation links of a web page with the class ‘.nav-link’, which would then fire a callback function, printing “A navigation link was clicked!” to the console.

4. Why would we convert a NodeList into an Array?

    A NodeList, along with an HTMLCollection, is an ‘array-like’ object. This means that it has ‘array-like’ properties, BUT it is not an array, which means that it does not have access to ALL of the built-in methods that normal arrays have. NodeLists, unlike HTMLCollections, do come pre-built with the capability to utilize the ‘.forEach( )’ method. However, if we use the ‘Array.from( )’ method, we can convert a NodeList into an ACTUAL array, which would give us FULL access to all of the built-in methods for normal arrays (i.e. - ‘.push( )’ method).

5. What is a component?

    Components are what allow developers to reuse code throughout a website. A ‘component’ is modular and can be made up of several parts, which could include: HTML, CSS, and JavaScript. Components improve efficiency and allow developers to write ‘DRY’ code.

### Git Set up

* [ ] Fork the project into your GitHub user account
* [ ] Clone the forked project into a directory on your machine
* [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
* [ ] You are now ready to build this project with your preferred IDE

## Minimum Viable Product

Your finished project must include all of the following requirements:

* [ ] Look through the HTML code paying particular attention to the Tabs component and the Cards components. You will notice they share a data attribute. We will be using this data attribute to determine which cards should show when each tab is selected.

* [ ] Following the instructions in the `Tabs.js` file, complete the `TabLink`, and `TabCard` class components. It will look and feel very similar to the last project we worked on, but with a twist. Now, instead of one `Item` to display, we will need to display a collection of `Cards`. Think about ways to iterate over an array and manipulate each item.  **Note: You will need to un-comment the code after the lines of instructions.  The code is commented out so you can work error-free**

* [ ] Once you get your `Tab` component working properly add a couple more articles yourself and check out how it works.

## Stretch Problems

Your stretch challenge is to write the functionality of a `Carousel` component. You have the HTML and CSS already in place, simply un-comment the HTML in the `index.html` file. This is an advanced challenge, so you are not expected to be able to complete it. If you begin and don't finish, you should still submit with what you have. You may reference the `Tabs.js` file for assistance.

* [ ] Complete the carousel functionality in `Carousel.js`

* [ ] If you complete the Carousel, add functionality so that the carousel slides when the buttons are pressed instead of just appearing.

* [ ] Create an 'infinite loop' carousel. In which as long as you click on an arrow, the array of images will loop over itself.

* [ ] If you have finished the above, play around with the styling on all the components, and understand how each is built.
