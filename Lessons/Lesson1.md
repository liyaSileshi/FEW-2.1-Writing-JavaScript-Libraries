# Introduction to JS Libraries 

In this class you will begin writing the code that will be a JavaScript Library. 

## Learning Objectives (5 min)

1. Describe a software library
  - How they are used 
  - Common use cases
1. Build a library of string functions/utilities
1. Use JavaScript String methods

## JavaScript Libraries

### Q: What are libraries? 

A library of code is like a library of books. Imagine each book as a block of code. Unlike a traditional library that contains books on every topic, software libraries contain code that is focused in a single area. 

Libraries of code like the public library makes code available to anyone who wants to use it. Unlike the public library your JavaScript library can be checked out as many times as there projects that might need to use it. 

Libraries are portable. Books can be cheked out from the public library. Any one of your software projects can "check out" code libraries.  

### Q: Why make a library? 

By puting code in a library you are making it portable and packaging it in a form that is easily shared. 

You're also toking DRY to the next level! Code in a library can be shared across multiple projects, and when change, updates, and bug fixes are made they can all be made in a single location. 

### Q: When to make a library? 

Anytime you find you are writing the same code in more than one project. When you have code that that you want to share with other people. 

You've already been using libraries of code in any of the projects that you have built using NPM. 

### What's NPM? 

Node Package Manager is the world's largest software registry. It's like a library of code where you check out code like books! 

### What will I make in this class? 

You will several Libraries. The libraries you write will be smaller and focus utility functions at first. Think of the code in each of the libraries written in this class as an interview question. 

Much of the code we write here has already been written. Normally we wouldn't want to reinvent the wheel but the goal of this class is learning how to write code and how to turn it into libraries. From that perspective recreating code that already exists is a great learning experience. 

### Let's look at  some existing libraries 

## Exploring Libraries

### Q: What kinds of libraries are people making in 2019? 

Here is a list of libraries that you may have used before. Pair up and take a look at the list at the link below and discuss what's there. 

https://tutorialzine.com/2019/04/10-interesting-javascript-and-css-libraries-for-april-2019

Discussion: What did you find on that list? 

### Q: What kinds of libraries have you used in past projects? 

Discuss with your pair... 

### Q: What about utility libraries?

Pair and look at the link below. It's a list of utility libraries. 

https://blog.bitsrc.io/11-javascript-utility-libraries-you-should-know-in-2018-3646fb31ade

Discussion: What do you see there? What are these libraries good for? 

### Q: What kind of code do you see? 

Take a look at a couple libraries below and look at the code. With your pair discuss the general features of the code. 

Just skim the repos and look at a couple files. Usually the code will be in `index.js` or in `src` folder. 

Look for these things in each of these thinsg as you explore the repos below. 

- How much code is there? 
- How is organized? 
- What language? 

- [has-values](https://github.com/jonschlinkert/has-values)
- [fill-range](https://github.com/jonschlinkert/fill-range/blob/master/index.js)
- [Lodash](https://github.com/lodash/lodash) is the most popular package on NPM. 

## Writing your first library

The goal of this first library is to make some String functions. These will be generic utilities that help you work with Strings. 

JavaScript provides many method to manipulate strings already but it deosn't do some of the things that we might want to do. It's your job to write functions that solve the problems below. 

- capitalize() - makes first character of a given string uppercase. 
  - Example: hello world -> Hello world
- allCaps() - makes all characters uppercase. (this is the same as .toUppercase())
  - Example: foo bar -> FOO BAR
- capitalizeWords() - makes the first character of each word uppercase. Imagine that each word is separated by a space. 
  - Example: do all the things -> Do All The Things
    - Advanced: capitalizeHeadline() - capitalizes all of the words except the words: the, in, a, an, and, but, for, at, by, from
      - Example: the mot foo in bar -> The Most Foo in Bar
- oddCaps() - Makes all odd characters uppercase and even characters lowercase. 
  - Example: hello world -> hElLo wOrLd
    - Advanced: Don't count spaces
      - Example: hello world -> hElLo WoRlD
  - evenCaps() - Make all even characters uppercase and the odd characters lowercase. 
    - Example: foo bar -> FoO BaR
      - Advanced: Don't count the spaces
        - Example: foo bar -> FoO bAr
- removeExtraSpaces() - Removes all spaces from the beginning and ending of a String along with any extra spaces in the middle. If more than one space appears in the middle of a string it is replaced by a single space. 
  - Example: "   Hello    world!   " -> "Hello world!"
- kabobCase() - Removes extra spaces and replaces spaces with the hyphen "-", and makes all characters lowercase. 
  - Example: "   Hello    world   " -> "hello-world"
- snakeCase() - Removes extra space and replaces spaces with an underscore "_", and makes all characters lowercase. 
  - Example: "  what the    heck   " -> "what_the_heck"


## Minute-by-Minute [OPTIONAL]

| **Elapsed** | **Time**  | **Activity**              |
| ----------- | --------- | ------------------------- |
| 0:00        | 0:05      | Objectives                |
| 0:05        | 0:15      | Overview                  |
| 0:20        | 0:45      | Exploring Libraries       |
| 1:05        | 0:10      | BREAK                     |
| 1:15        | 0:40      | Writing your first library|
| 1:55        | 0:40      | Writing your first library|
| TOTAL       | 2:00      |                           |