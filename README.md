# Code-Refactor

Homework 1 - refactoring code for an existing website! 
___



### Cool Code! 

```
    <div class="hero">
        <span role="img" aria-label="Business People"> </span>
            </div>
            <!-- adding aria-label as a workaround for an alt tag for background image -->
```
<p> The role of aria-label is that it will automatically be read by screen readers, so it will work as alt text for a background image like the class 

<p> While trying to find a way to add alt text to the background image of the site, I came across an option to add aria-label so it will be read by a screen reader, but while also not requiring a change to the .hero class.  Reference sited below. [Link to Sources](##Sources)


### Screenshot
---

<img src="https://user-images.githubusercontent.com/59800839/84452415-9eacda00-ac0a-11ea-83e8-fecccda143a8.png"  width="auto" height="300">

<p> Above you can see a screenshot of the orignal html for the unordered list displayed in the header of the site.  It was very long and had basic structural markup.  Below in the Code Snippet you can see the code I restructured to make it easier to read, more concise, and semantically descriptive.  I added header tags for semantic markup, moved all aspects of items on unordered list onto a single line for ease of reading and fewer lines of code. 

### Code Snippet
---
```
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li><a href="#search-engine-optimization">Search Engine Optimization</a></li>
                <li><a href="#online-reputation-management">Online Reputation Management</a></li>
                <li><a href="#social-media-marketing">Social Media Marketing</a></li>   
            </ul>
            <!--Put several aspects of the list on a single line from 3 different lines, see Readme.md for screenshot of original)-->
        </div>
    </header>
```
___


## Prerequisits

*Access to the Internet
*Web Browser
*Github Account
*Terminal (or gitbash)
*Local Disk Storage Capacity 
*VSCode, Sublime Text, or other IDE

## Installation

Navigate to Github

Execute the following commands in Terminal: 
1. ls 
    - view file directories on local machine
2. mkdir Code-Refactor
3. ls
    - view file directory was created
4. cd Code-Refactor
5. git clone https://github.com/hannahpsmith1/Code-Refactor.git 

### Installation GIF

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)


## Built With
[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

## Deployed Site

* [Live Site](https://hannahpsmith1.github.io/Code-Refactor/#search-engine-optimization)
---

## Author
**Hannah Smith**  
*[Portfolio](https://github.com/hannahpsmith1)
*[Github](https://github.com/hannahpsmith1/Code-Refactor)
*[LinkedIn](https://www.linkedin.com/in/hannah-patience-smith/)

---
## Licenses
*None


## Acknowledgements:

* Royce and Giovanni were kind enough to answer my questions in the homework breakout room Thursday Afternoon concerning metadata tags and file directories. 


## Sources:
1. [linking to parts of the same page](https://www.youtube.com/watch?v=bCt2FnyY7AE) This video helped me to link to a different part of the same webpage
2. Duckett, J. (2015). Html & Css: design and build websites. Indianapolis, IN: John Wiley & Sons, Inc.
3. [w3 schools](https://www.w3schools.com/) This site was my go to when poking around the internet to find things like semantic HTML
4. [google developer aria-label](https://developers.google.com/web/fundamentals/accessibility/semantics-aria/aria-labels-and-relationships)


