# In the beginning was the net

A loosely organised collection of computers where you could email someone, but where the idea of a website - like twitter.com - was still far removed. By the end of this chapter you should know enough `HTML` to build a very basic user interface. 

[TOC]


### Scientists were on the web before it was cool. #Hipsters

The developers of the worlds first system of formatting information for linking documents together on the Internet. Their development - Hypertext Markup Language - gave birth to the world wide web. 

## HTML 

> Innovation is serendipity, so you don't know what people will make.
> ~Sir Tim Berners-Lee

Hypertext Markup Language (HTML) is a system for "marking up" a document. What does this mean? Well, it gives the data a context that a browser can understand. The concept of a HTML tag is not too far removed from the idea of using quotation marks in a piece of text. If you want to signify that someone has said something you surround it in quotation marks, such as "To be or not to be?". These symbols have special meaning for human readers as they imply that those specific words have been spoken out loud. Similarly, HTML uses a system of tags to confer meaning to information. It is from those tags the browser understands what it should do with that information. 

## Markup Tags

The majority of tags that you will encounter are like quotation marks in that there are opening tags and closing varieties. A HTML tag is any word that is surrounded by brackets like so: `<tagName>`. A closing tag differs slightly in that the tag name is preceeded by a forward slash like this: `</tagName>`. Here's a quick example to try which creates a very simple page with the words "Hello World" in big letters.

<code data-gist-id="b362490ab6fb7d332aeb"></code>
    
<a href="http://bl.ocks.org/domhnallohanlon/raw/ba92975e504d2cebd3c9/" class="text-success pull-right" target="_blank" role="button">Preview Example</a><br>
<a href="https://gist.github.com/domhnallohanlon/ba92975e504d2cebd3c9/download" class="text-success pull-right">Download Code</a><br>


<!-- The page above should look like the image below.
![example1](img/ex01.png "Hello World")
 -->

Let's take a look at this example in a bit more detail. The first and last line are for the opening and closing `<html>` tags. This tells the web browser that all the code it is about to read should be formatted as HTML code. 
Next there are two sections that every page should have. The `<head>` and the `<body>`. 

The __head__ section contains information about the page, such as what information should appear in the title bar (specified inside the`<title>` tags) as well as how the pages should be styled, how it should be rendered on different screensizes and what information will be displayed by Search Engines. We will address all of these topics in a later section. The `<head>` section begins on line 2 and end on line 4 in our example above.

The __body__ section contains the information that should be displayed on the page itself. In our example above the `<body>` begins on line 5 and ends on line 7. In this case we have only displayed the message "Hello World" on our page. You will notice that is it surrounded by `<h1>` tags. 


## Headings

In HTML 'h' is shorthand for 'heading' so `<h1>` is the biggest heading. Here are a few more example - you should try them out for your self.

HTML Tag    | Output
:----------:|:----------:
`<h1>heading 1</h1>`   |  <h1> heading 1</h1>
`<h2>heading 2</h2>`   |  <h2> heading 2</h2>
`<h3>heading 3</h3>`   |  <h3> heading 3</h3>
`<h4>heading 4</h4>`   |  <h4> heading 4</h4>
`<h5>heading 5</h5>`   |  <h5> heading 5</h5>
`<h6>heading 6</h6>`   |  <h6> heading 6</h6>

## Text

## Lists

<code data-gist-id="be335a12f1e908fd74c4"></code>

<a href="http://bl.ocks.org/domhnallohanlon/raw/09bdd8a562a8f311a14b/" class="text-success pull-right" target="_blank">Preview Example</a> <br>

<a href="https://gist.github.com/domhnallohanlon/be335a12f1e908fd74c4/download" class="text-success pull-right">Download Code</a><br>
## Images

The image tag, `<img/>` is our first example of a self-closing tag, which means that there is no closing image tag. This makes sense since you typically wouldn't want to display text as an image, rather you would like to tell the web browser what image file it should display. 

### Attributes
The image tag is a good opportunity to introduce the concept of _attributes_. To display any image on screen we have to tell the image tag exactly which image file we want it to display. Files can be stored locally or on a remote server but in either case you have to specify the _source_ of the image. This is done by including a `src` attribute:
`<img src=""/>` 

Please note the _value_ you give the `src` arrtibute must be the exact path to the file. The full location is written between the opening and closing quotation marks. If we want to display an image called phone.png, which is in the same directory as our HTML file then we'd type:
`<img src="phone.png">`

It is also considered best practice to include an `alt` tag. This attribute specifies the alternative text that should be displayed in the event that the image can not be displayed. You should try to make your alt text as descriptive as possible as it is also the information that is read by screen readers for people who have visual impairments. Using the phone example.

`<img src="phone.png" alt="A picture of a smartphone">`

In the sample code below you will notice that I have used a `height` attribute, which allows us to specify how tall the image should be. Similarly there is also a `width` tag, which tells the browser how wide the image should be on the screen. It is not generally considered best practice to resize images in this manner, but I have done it for the sake of introducing a few more attributes and because it makes the <a href="http://bl.ocks.org/domhnallohanlon/raw/9f9eeae17a26e2a3ba61/" target="_blank">preview </a> look better.

### Sample Code

The code snippet below uses a local image and two remote images to demonstrate how images can be include in an HTML document.

<!-- gist with html only, no .png file -->
<code data-gist-id="dd0b15e0e80894044620"></code>

<a href="http://bl.ocks.org/domhnallohanlon/raw/9f9eeae17a26e2a3ba61/" class="text-success pull-right" target="_blank">Preview Example</a>
<a href="https://gist.github.com/9f9eeae17a26e2a3ba61/domhnallohanlon/download" class="text-success pull-right">Download Code</a><br>

### Attributes
src, alt

## Links

href, target, rel?

## Sections

div and span

classes and ids?

## Summary