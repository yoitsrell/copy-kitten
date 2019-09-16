# Copy Kitten

### Introduction

We'll be using CSS to get as close as we can to copying each of the three sections of the page, the button, header, and table.


### Setup

* Fork and clone this repo.
* Run Live Server so you can see what's going on.
* Code away.


### Guidelines

* Each component you'll be copying has at least one image showing you what it's _supposed_ to look like. The header and button also have an image showing you what happens when you hover over it. These are your reference images, so keep them close by. You may want to open them in a browser, though you can also view them in VS Code directly.
* We put them in order from easiest to hardest in our opinion, but Your Mileage May Vary. Do them in whatever order you please!
* Don't edit the html, nor the `style.css` file, which is just there to keep the components layed out with reasonable space between them.
* DO edit the three CSS files, `button.css`, `header.css`, and `table.css`. They're empty, but they are where you'll be doing your work!
* You may have noticed that the `index.html` file has FOUR separate CSS files. These are all being loaded in, and they're being kept separate so you can work in one and then the other, but all rules from any one CSS file apply to the ENTIRE page. That means you'll have to be a bit careful that they don't overlap; for example, your rules for the button shouldn't apply to the header! Here are some tools for that:
  * Each html section should have different enough html that you can target the `<a>` tags in each differently based on descendent rules, i.e., 'div p' or 'div > p'.
  * HOWEVER, if you wanted to add some IDs or classes to `index.html`, feel free!
* Don't forget to `add`, `commit`, and `push`! There must be AT LEAST 3 commits for this project, since we're talking about copying three different components. However, the more, the merrier; work on one ASPECT of a component at a time--for example, the spacing between the items in the header--and then make that a commit. Thinking in `git` is a skill, and the more you work at it, the better you'll get.


### Stretch Goals

##### Button

* Add some styling to the button for when it's clicked using a [fill in the blank here] pseudoselector. Look up "inset shadow" for a neat effect!
* Capitalize only the first letter of each word in the button. With CSS!


##### Header

* Now that you've worked to make it look good horizontally, make the header vertical again. Be sure to move the "nav ribbon" (the grey part) as well. And you may have to remove the bullet points to make it pretty!


##### Table

* Add a background color to each cell when you hover over it. What part of the whole thing gets that color?
* Try adding some space between each `<a>` of a row. What does this do to the "clickable" space?