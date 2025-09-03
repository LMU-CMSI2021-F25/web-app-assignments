**CMSI 2021** Web Application Development, Fall 2025

# Assignment 1: Standalone Vanilla Web App
We start our practicum with a standalone web app—one that does not need to communicate with other servers or services in order to do what it seeks to do. In addition, it’s a _vanilla_ web app—meaning that the web browser will be executing our code _exactly as written_, without any preprocessing, compilation, or additional frameworks. For this assignment, we’d like you to demonstrate:
* Knowledge of a fair amount of HTML and CSS
* Knowledge of basic event handling in browser-based JavaScript
* The ability to develop and host an app on [Code Sandbox](https://codesandbox.io)

## Background/Preparatory Reading
* Browse the HTML and CSS [HTML Dog tutorials](https://www.htmldog.com/guides/). (3 for HTML and 3 for CSS.) You can breeze through them quickly if they cover aspects of these technologies you already know. The goal here is for you to familiarize yourself with all the common uses of HTML and CSS, not to spend too much time. If you find something that interests you, by all means spend as much time as you need
* Since HTMLDog does not have tutorials on grid and flex, find an online tutorial for these, or study the guides on [CSS-Tricks](https://css-tricks.com)
* Briefly skim the Tutorials on the [MDN JavaScript page](https://developer.mozilla.org/en-US/docs/Web/JavaScript). Bounce around and take in the material you need; you do not have to complete all the tutorials for this assignment. Think of the MDN JavaScript documentation as something to be read through during the entire course, not just for this assignment (i.e., it can serve both as a _tutorial_ and a _reference_ source)
* Review Dr. Toal’s course notes for the introduction to web apps, HTML, CSS, JavaScript. Follow any links in the notes that interest you

## For Submission
Create a web app for computing [compound interest](https://en.wikipedia.org/wiki/Compound_interest). The core of the page will have a form with input fields for principal, interest rate, number of times compounded per year, and the total number of years. As these values change, you will update fields showing the amount of money you earned, and the total amount. The calculation must be functional, robust, and correct.

In addition to the app working correctly, the web app layout must demonstrate these characteristics:
* Responsiveness—the site must look good on mobile and web (narrow or wide screen)
* Site balance and aesthetics—Use colors and contrast properly! Line things up! We aren’t expected to be visual artists, but we can strive to present information in a way that is clear and usable. Optionally, get a designer friend of yours to critique your work

To attain the aforementioned qualities, the following are required—_all_ of them, or no credit will be awarded (as one goal of this assignment is to get you to actually use a large amount of HTML and CSS):

* A background image or gradient
* A non-standard font (show that you can import a font from Google Fonts or similar)
* A grid layout for the main content of the site, so that it has a header and footer
* A flex layout to make the form look gorgeous
* A nice title (perhaps an `h1` element, with matching CSS)
* A fun image or two
* A variety of input elements: don’t just use text! (sliders; `select`s for common values; etc.)
* At least one each of a margin, padding, and border
* At least one transition
* At least one transform
* At least one text shadow
* A footer with a link to the [Code Sandbox](https://codesandbox.io) repo where the live version of your app can be found

Build your site on [Code Sandbox](https://codesandbox.io). Test it well.

Some additional best-practice requirements:
* Your [Code Sandbox](https://codesandbox.io) repo must have a good name: named after the project, not something generic like “hw1”
* Your GitHub copy of the app (see below) must have a detailed _about.md_ Markdown file that not only explains the project (as real “about” documentation should) but also with a link to where the app is deployed
* Your code (all files) must be flawlessly formatted, and that means that you not only indent and space 100% consistently, but that you are also perfectly consistent with blank-line spacing where necessary (Prettier will help with most things if you format locally in your editor; your chosen environment may have an auto-format feature as well)
* HTML and accessibility validation—check your browser dev tools console for any warnings or errors!

## Operational Tips/Suggestions
* Depending on their respective latest versions, your chosen environment may or may not have an effective auto-format feature—to accommodate this, you can configure your code editor with Prettier and format your code there, then send the formatted code back to the environment. To help with this, this repository has a _.prettierrc_ file that has my (opinionated) formatting preferences
* Remember that there isn’t enough class time to cover absolutely everything that you might want to do! We hope that our class time so far has served to give you a good foundation for getting started, but definitely don’t let “this wasn’t mentioned in class” be a barrier when it comes to figuring things out

## AI Review
If you used any form of generative AI, please give a paragraph review on how you used it, how it help, or how it hurt. Submit this in a file call "AI_Review.md".
If you did not use any AI, please just submit the same file that says "No GenAI Used".

## How to Turn it In
* Commit the source code from [Code Sandbox](https://codesandbox.io) to this GitHub repository. Make sure to reflect the file structure of the original: the idea is for the GitHub version to run exactly as-is, if hosted by a web server
* Commit your _about.md_ file to this repository as well

## Specific Point Allocations
For this particular assignment, graded categories are as follows:

| Category | Points |
| -------- | -----: |
| Baseline functionality | 40 points total |
| • Ability to enter the necessary arguments:<br/>  - principal<br/>  - interest rate<br/>  - number of times compounded per year<br/>  - total number of years<br/>  - correct computation of compound interest | 25 points |
| • Effective display of result | 10 points |
| Baseline design/layout | 35 points total |
| • Responsiveness | 20 points |
| • Site balance and aesthetics | 15 points |
| Implementation specifications | 20 points |
| • Background image or gradient<br/>• Non-standard font<br/>• Grid layout for the main content<br/>• Flex layout for the form<br/>• Title<br/>• Fun image(s)<br/>• Input other than text<br/>• Margin<br/>• Padding<br/>• Border<br/>• Transition<br/>• Transform<br/>• Text shadow<br/>• Footer with link | |
| App description in _about.md_ | 5 points total |
| AI Review | 5 points |
| Hard-to-maintain or error-prone code | deduction only |
| Hard-to-read or inadequately-formatted code | deduction only |
| Version control | deduction only |
| Punctuality | deduction only |
| **Total** | **100** |

Note that websites with lingering code errors will negatively affect other criteria, because if we can’t run your code, we can’t evaluate related remaining items completely.
