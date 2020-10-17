
![Image description](https://i1.faceprep.in/ProGrad/prograd-logo.png)

# ProGrad Lab | REACT - Think with React

## Learning Goals

In this exercise, the goal is to apply as many as possible of the concepts you've just learned:

- when and how to setup react in your application,
- ways of using react.

## Getting started

1. Fork this repo
2. Clone this repo

Whenever you create a first significant change, you should make your first commit.

3. Follow these [guidelines to add, commit and push changes](https://github.com/FACEPrep-ProGrad/general-guidelines-labs-project-builders.git).

In the end of this document, you will find guidelines on how to submit the exercise.

### Introduction

In this exercise, you will try to setup the react application. As you can see react is a javascript library to create super cool reusable UI. Our goal is to understand the ways in which you can include react to your application.

We will divide our work into four parts:

- part I - Include react library in your html file
- part II - Use JSX and babel compiler
- part III - By using npm/yarn 
- part IV - By using typescript

So let's get started!

## Part I - Include react library in your html file

It might seem like a joke, but this is our goal in this iteration:

The very first step is deciding **how to add react to the html page**. Do you remember how to include javascript in your html? As you can see, React is not a framework, It's a very simple and powerful javascript library to create reusable UI components. Since it is a javascript library, we can add it in the same way like javascript. To include the react library please include the following code in your index.html file.

```index.html
    <!-- Load the React Library  -->
    <!-- React and React DOM -->
    <script src="https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>
```

Our recommendation is to try to keep it as simple as possible. Try to identify the ways to setup react library.

#### REACT 1 | `LET'S START UP`

Your task in this iteration is just to finish the react setup. To do this, let's use the same html file what we created and create a div with an id called react container.
You have included the react libraries to your javascript file. But we have to include our react element to your index.html. To do this create a file called app.js and include it in your html file.

```index.html
<body>
    <!-- Create a div to setup a react container -->
   <div id="react-container"></div>
 
    <!-- Load the React Library  -->
    <!-- React and React DOM -->
    <script src="https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>
   
   <!-- Include the react element -->
    <script src="./app.js"></script>
</body>

```

You're ready to move to the next iteration. :raised_hands:

#### REACT 2 | CHECK N CHECK

Your task in this iteration is to check whether you have successfully setup react in your application. To do it inside the app.js, get the div tag like how you get the element using it's id.

```
const container = document.getElementById('react-container');
```
Now the most important step, How to make a difference between Javascript and React. You might have learnt about ReactDOM in your code along session. ReactDOM is the place where you render the output. Now how to render using ReactDOM. Kindly look into the code snippet given below.

```
ReactDOM.render("Hello! Welcome to React",container);
```
If you do the above, you need to get an output similar to this.
![Image description](https://i1.faceprep.in/ProGrad/l1-output.png)

## Submission

If you didn't add, commit and push the changes you made, this is the last call. :smile:

please share your github links with your Mentors. Your Mentor's will check up your work and provide feedback. 

## Summary

In this exercise, you've learnt various ways of setting up react in your system. If you managed to do it, good job! :trophy:

This concludes the React setup. We are proud of you!

Happy Coding ProGrad ❤️!

