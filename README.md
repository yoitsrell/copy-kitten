# Copy Kitten

### Introduction

We'll be using CSS to get as close as we can to copying each of the three sections of the page, the button, header, and table.


### Guidelines

* We put them in order from easiest to hardest in our opinion, but Your Mileage May Vary. Do them in whatever order you please!
* Don't edit the html, nor the `style.css` file, which is just there to keep the components layed out with reasonable space between them.
* DO edit the three CSS files, `button.css`, `header.css`, and `table.css`. They're empty, but they are where you'll be doing your work!
* You may have noticed that the `index.html` file has FOUR separate CSS files. These are all being loaded in, and they're being kept separate so you can work in one and then the other, but all rules from any one CSS file apply to the ENTIRE page. That means you'll have to be a bit careful that they don't overlap; for example, your rules for the button shouldn't apply to the header! Here are some tools for that:
  * Each html section should have different enough html that you can target the `<a>` tags in each differently based on descendent rules, i.e., 'div p' or 'div > p'.
  * HOWEVER, if you wanted to add some IDs or classes to `index.html`, feel free!


### Stretch Goals

##### Button

* Add some styling to the button for when it's clicked using a [fill in the blank here] pseudoselector. Look up "inset shadow" for a neat effect!
* Capitalize only the first letter of each word in the button. With CSS!


##### Header

* Now that you've worked to make it look good horizontally, make the header vertical again. Be sure to move the "nav ribbon" (the grey part) as well. And you may have to remove the bullet points to make it pretty!


##### Table

* Add a background color to each cell when you hover over it. What part of the whole thing gets that color?
* Try adding some space between each `<a>` of a row. What does this do to the "clickable" space?