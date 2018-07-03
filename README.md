# create-a-simple-web-app
Set up a simple web app to start a random search for your users

## Random Research Topic Generator

Use the template in this repository to set up the Random Research Topic Generator. It consists of three small files- html, css and js. Go ahead and look at the code:

* the html is simple- a basic set of divs
* the css is a bit more complicated- getting the thing to look like a gameboy took some tricky manouvering
* the js is the key to this app. Look at the code closely and read all of the comments. 

## Build Your Own Project

Now take a moment to think about a version of this app that you can create from this template. There are two main pieces to this: 
* a random topic generator, which randomly grabs two terms from a list
* a dynamic hyperlink, which starts a search in the HSU library's catalog for articles based on the randomly selected terms

What will you create from this? A silly name generator? A search in Google Books or Amazon.com? How will you make these changes? 

Changing the basic header and text in the html file should be fairly simple- replace the ```<title>``` and ```<h1>``` elements, etc. Changing the CSS will be a bit more tricky, but not terribly so. Start out by changing the background color. Next, try some other things, such as:

* changing the font
* make the gameboy larger (and the nested divs inside it)
* create an entirely new 'screen' for it- scrap the gameboy design and create something that's your own!

Now move on to tweaking the JS file. The first thing you'll want to do is to find a new search URL. If you want to use ebay, for example, go ahead and conduct a search in ebay and look at the URL for the search results page. Find where your search terms appear, and split the URL as it is on line 23. 

The next thing you'll want to do with the JS is to create a new list of terms- this one is pretty easy to code. Just replace the terms already in the 'terms' array (line 4) and you're good to go! But what if you want to create two lists (maybe one is for nouns and the other for adjectives)? How will you write code to pick from that second list randomly? Hint: look at lines 6&7 and 11&12.
