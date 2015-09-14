#Welcome to JavaScript !!

##Outline for Monday 9/14
- Introductions
- What is JavaScript, and why should I learn it?
- Setting up our environment (GitHub, terminal/command line, Atom, Chrome console)
- Pulling down our first repository
- Basic JS syntax

##Introductions
```javascript
var firstName = 'Caleb';
var wantToLearn = 'what you want to achieve with JS';

var aboutMe = function() {
  return 'My name is ' + firstName + ', and I want to learn ' + wantToLearn + '!';
};
```

##What is JavaScript?
JavaScript is often referred to as the 'language of the web', because it appears in almost every page you view today. JavaScript functions within the end-user's browser, allowing for more dynamic content and operations than HTML and CSS alone.

- Example html, html + css, html + css +js



##Environment setup
- Command line intro
- Version control, introduce GitHub
- Create GitHub account
- Install Git in terminal
- Chrome, introduce console

##Command line
- Open terminal
- Create class directory

##Version control
`Version Control` is system system that records changes to a file or set of files over time so that you can recall specific versions later.
  - Reversion to previous states
  - Team Coordination
  - Due Diligence (open source credit)
<br>
<br>
![Repo Flow](/images/repoFlow.png)
<br>
<br>
[More on Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
<br>[Git Version Control Basics](http://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

##Setting up Git
- Create your [GitHub](https://github.com) account !!
- Setting up Git:
<br>
<br>
https://help.github.com/articles/set-up-git/#platform-mac
<br>
<br>
[Windows users download and guide](https://git-for-windows.github.io/)
<br>

- Generate your SSH key:  https://help.github.com/articles/generating-ssh-keys/

##Repositories
- Create your first repository (repo): [Documentation](https://help.github.com/articles/create-a-repo/)
<br>
Basic Git Commands
```
$ git add .
$ git commit -m 'My first GitHub commit'
$ git push
```
[More Git Commands](https://confluence.atlassian.com/stash/basic-git-commands-278071958.html)
- Add and commit your changes to your ReadMe.
- Push your changes to GitHub !


##Syntax
Data Types, Variables, Operators
```javascript
var number = 9;
var float = 3.2;
NaN   //not a number, ie 0/0
var string = "truck";
var longerString = "That\'s my dog!"
var boolean = true; //or false. Boolean values distinguish between possibilities
undefined   //no meaningful value
null    //no meaningful value
```
Basic operators
```javascript

console.log(7 - 3);
// 4
console.log(3 + 6);
// 9
console.log(5 * 2);
// 10
console.log(3/2);
// 1.5
console.log(0.2 + 0.4);
// ????????


var person = 'David';
var greetPerson = 'Hello ' + person + '!'
console.log(greetPerson);
// Hello David!
```

When an operator is applied to the “wrong” type of value, JavaScript will quietly convert that value to the type it wants, using a set of rules that often aren’t what you want or expect. This is called `type coercion`

```javascript
console.log(8 * null)
//  0
console.log("5" - 1)
//  4
console.log("5" + 1)
//  51
console.log("five" * 2)
//  NaN
console.log(false == 0)
//  true

```
##document.write() vs console.log()
```javascript
document.write('Hello World');
// appends string to body element of page
console.log('Hello World');
// displays string in console
```
##prompt() and alert()
```javascript
prompt('What is your name?');
// opens modal for user to type in
var name = prompt('What is your name?');
// sets name variable equal to the typed response
alert('This is a test!');
// opens modal with message 'This is a test!'
```
##Push your work to GitHub
- Add, commit, push
