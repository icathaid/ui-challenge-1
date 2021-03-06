# Assignment Overview: UI Challenge 1


## Create a responsive webpage from a provided design comp

***Your boss comes up to you just before lunch: "OK, we just picked up this job, but I need it before 2:00 this afternoon. It doesn't need to be perfect... it needs to be as close to perfect as you can get it in that time."***

In lab today you will be building a single responsive webpage based off of the provided design comp assets. This assignment is a lot of HTML and CSS, but no JS or jQuery.

Your document must be designed in a ***mobile-first*** approach and must be responsive when the screen size changes. The details of the media query specifications are up to you, but your breakpoint must be at 800 pixels, because that is what our imaginary client wants.

This is an independent project, but your are free to collaborate with your classmates.

### Timebox : 2 - 3 Hours 

---
~ 1 hour
got the breakpoint set and the html structure (i think) set up and working on the mobile side, going to start coding out the rules for the desktop side.

There is a small gap between my e and f, and g and h elements that I can't seem to get rid of no matter where I set the margins.  Might have something to do with the borders.
    It only shows up on the mobile side.

It seems like there is a good way to structure the html/css to avoid repeated code for the mobile side that doesn't work on the desktop side (or vice versa).  Given the timebox, I'm just going to code everything out the long way for the desktop side.  I should have spent more time planning this out on paper but on a campus with enough processing power to put a satellite in orbit, I can't find a pencil anywhere.

~ 2 hours
got it working on the desktop side as long as the window is maximized.  Setting a width between 800 and 960 breaks everything.  It has something to do with the block-level elements and their containers because it starts putting things on new lines.

~ 2.5 hours
...found my pencil.



**GitHub Repository & Project Setup**

- Create a repository called ***ui-challenge-1*** for your work.
- Submit a link to this repository in the corresponding Canvas assignment when you are finished.
- Be sure to do your work in a non-master branch.


***PLAN YOUR WORK AND WORK YOUR PLAN***

---

**Assignment Overview**

The design comps can be found in the adjacent `comps` folder in this repo. These contain images of what you are striving to build in HTML and CSS, so be sure to open them up and keep them handy... ***but note that they are not for actual use on the page.*** You can also print out these comps and use them to mark up and sketch out page structure.

---

**Requirements**

- Use good HTML structure to scaffold this site, of course, using semantic elements where possible.
- Reminder: Container elements (a box outside of your content box that might contain multiple content boxes) are very useful in managing layout. You will need to think about the relationship between parent and child / descendant elements as well as the order in which you place them in the HTML. Be thoughtful about your CSS layout strategy.
- If you want, use SMACSS-style modularity to organize your CSS; there are no specific requirements. Feel free to try an alternate system for organizing your CSS.
- Style the page to reflect the comp images provided as closely as possible... the only text you should have in each box is the identifying letter, which should be centered horizontally and vertically.
- For the desktop view, the content should be inside of a channel that is 960 pixels wide and is centered on wider screen sizes.
- You will probably find it helpful to give each of the boxes a different background color.
- There are no right or wrong answers... just do your best.
