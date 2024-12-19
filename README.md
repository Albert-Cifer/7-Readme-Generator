# README Generator

## Description
The README Generator is a command-line application that will help you to generate a README file. It allows the project creators to use more of their time to work on their current project. 

This application generates a README.md file from the user's input, by using the [Inquirer package](https://www.npmjs.com/package/inquirer/v/8.2.4).

## Installation
For this application, you will require [Node.js](https://nodejs.org/) and also the package manager [npm](https://www.npmjs.com/).  
First, you'll need to open the terminal in the root directory of the application and then, run the next command:

```bash
npm i
```
This command will install the [Inquirer](https://www.npmjs.com/package/inquirer/v/8.2.4) package needed for the application to run.

## Usage
To run this application, first, you will need to open the terminal of the application in the root directory again, after installing the previous packages and run the following command:

```bash
node index.js
```
If the application works as intended, you'll be prompted for the project title.

```bash
$ node index.js
? What is the project title?
```
You'll need to answer this question, and then, all the questions that follow, it is very intuitive.

After answering all the questions, a README.md file will be created and stored in the result folder of the root directory.  

> [!WARNING]
> Be careful! Running the application again will overwrite you current README.md file!

## Demo
[Video](https://youtu.be/wMnU7WhVIkU)
  