# Instructor Overview

This overview informs instructors on how to teach the RockIT Web Workshop in approximately 2-4 hours. The Workshop is broken into two main section: `Learn the Code` and `Project` as you'll read below.

## Key Concepts (Agenda)
To start, it's recommended that students download [SublimeText](http://www.sublimetext.com/3) and the code ahead of time. It's also recommended that the students use Chome or Firefox when doing the Workshop.

1. Setup
1. Learn the Code
 1. HTML Tags and whitepsace
 1. Attributes
 1. CSS include
 1. Tag Selectors
 1. Class Selectors
 1. Nesting HTML
1. Project
 1. Introduce the HTML 
 1. Design the Header

## Setup

Have all the students download the project and open the `index.html` and `final.html` in the browser. Then make sure all students have the `index.html` file open in SublimeText.

> Tip: Have the students drag the WebWorkshop folder into SublimeText so they can see all files/folders. Also note that since it's a brand new install of Sublime, they may need to turn on the Sidebar by going to `View > Sidebar`

# Learn the Code

The "Learn the Code" portion of the class is meant to teach the basics of how HTML and CSS work. Make a new HTML file and save it so you can do demonstrations in the browser. Some students might want to follow along and do the same steps as the instructor, but it's important to aknowledge that for most students simply watching and not trying to keep up with typing is perfectly acceptable. 

## HTML Tags and Whitespace

Start your HTML file by typing only plain-text. Show that this can be saved and rendered in the browser. Show that things like hard returns and duplicate spaces don't really matter (whitespace is ignored).

After showing plain-text, show how simple tags like `<p>` and `<h1>` can be used to enhance our document. Explain the "anatomy" of a tag and how opening/closing tags work. Using paragraph tags are nice because you can demonstrate how space is created between the content when rendered.

> Tip: It's important to not show the `<html>`, `<head>`, and `<body>` tags at this point. Just simply tags around content is enough.

## Attributes

Create an anchor tag with an `href` attribute. Show the students the "anatomy" of a tag again but with the attribute concept built in now. It might be helpful to show `<tag attribute=""></tag>` to convey the general syntax. Explain that attributes enhance tags and give them more abilities. An abstract concept that seems to work well is to create a person tag and describe that person with attributes:

```html
<person age="40" gender="male" name="Mike"></person>
```

Explain that this is conceptual and that we can't actually invent our own tags or attributes, but this example has shown to be useful in explaining what the purpose of an attribute is.

At this point, your demonstration might look something like:

```html
<h1>Our Title</h1>

<p>Our Paragraph</p>
<p>Our Paragraph</p>

<a href="http://www.google.com">Google</a>
```

## CSS Include

Now that we have a few tags, it's a good time to teach styles. If the class is longer, you can introduce inline-styles, then embedded styles (`<style>` tag). But if the class is shorter, it would be best to jump strait to `<link>` tags to include external styles (Since that's how the project is built).

> Tip: Again the `<link>` tag can be used without the `<head>` tag at this point

## Tag Selector

Start by doing a simple tag selector to stylize the headings, paragraphs, and anchors you've been building. Doing background and text colors will work best to illustrate how CSS works with styling. The students might notice that some tags get background colors that span the full width of the page and some like anchors only get background colors around their content. At this point you can introduce the basic concepts of inline vs block tags. It's important to stylize several paragraphs all to be `background-color: something` so the students can see that no matter how many tags we have, the CSS will apply to all that match.

## Class Selectors

Since we're at a point where we have all of our paragraphs stylized with one CSS block, it would be a good time to introduce the concept of classes and how to stylize a whole group of tags (as with all the paragraphs) and then to isolate certain ones with class names. 

> Tip: Since the students are already familiar with tag selectors, it would be important to the syntax: `tag.class-name` instead of just `.class-name` so the students feel like they are adding to their already existing knowledge of tag selectors

## Nesting in HTML

So far we should only have simple tags in our HTML without nesting. Nesting might be difficult to explain without seeing colors applied to tags so it makes more sense to explain nesting after we've applied some CSS. One idea could be to wrap our paragraph tags in a div tag and then stylized our div with a background color. 

It will be important to introduce terms like `parent`, `child`, `sibling`, and `container` at this point so the students can more easily converse with the instructors when the see the project.

# Project

With both the `index.html` and `final.html` files open in the browser, explain that the goal of the project is to add styles to get the first file to look like the second.

Its important to know that the `index.html` file includes `base.css` and `theme.css`. The base file sets up CSS structure and the students should ignore that file for now. The theme file is where the students will work on their CSS skills. Notice that this file already has all the selectors written for the students. It also has all the properties written in the comments section at the top of the CSS file. The goal is to have the students copy/paste the properties to the appropriate selector blocks.

## Introduce the HTML

It will be important to show the students the project's HTML at this point. Since the project makes use of proper `<html>`, `<head>`, and `<body>` tags. It might be useful to explain those in an isolated file at first.

Show the students that there are very semantic tag names with easy-to-understand classes and how it's relatively easy to tell which parts of the HTMl correspond to which parts of the design.

## Design the Header

To get the ball rolling, you'll want to design some of the project for them. You might want to do the header section and challenge the students to look at the final output (`final.html`), look at what we have so far with `index.html`, look at the HTML and CSS selectors and try to figure out what properties need to be applied. Once you get some working you can let the students finish it off while you help out any students with questions.




