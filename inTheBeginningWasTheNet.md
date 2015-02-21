## In the beginning was the net

A loosely organised collection of computers where you could email someone, but where the idea of a website - like twitter.com - was still far removed. 

### Scientists were on the web before it was cool. #Hipsters

The developers of the worlds first system of formatting information for linking documents together on the Internet. Their development - Hypertext Markup Language - gave birth to the world wide web. 

## HTML 

> Innovation is serendipity, so you don't know what people will make.
> ~Sir Tim Berners-Lee

Hypertext Markup Language (HTML) is a system for "marking up" a document. What does this mean? Well, it gives the data a context that a browser can understand. The concept of a HTML tag is not too far removed from the idea of using quotation marks in a piece of text. If you want to signify that someone has said something you surround it in quotation marks, such as "To be or not to be?". These symbols have special meaning for human readers as they imply that those specific words have been spoken out loud. Similarly, HTML uses a system of tags to confer meaning to information. It is from those tags the browser understands what it should do with that information. 

### Tags

The majority of tags that you will encounter are like quotation marks in that there are opening tags and closing varieties. A HTML tag is any word that is surrounded by brackets like so: `<tagName>`. A closing tag differs slightly in that the tag name is preceeded by a forward slash like this: `</tagName>`. Here's a quick example to try which creates a very simple page with the words "Hello World" in big letters.

```html
<html>
    <head>
        <title>My first HTML page</title>
    </head>
    <body>
        <h1>Hello World</h1>
    </body>
</html>
``` 

The page above should look like the image below.
![example1](img/ex01.png "Hello World")

Let's take a look at this example in a bit more detail. The first and last line are for the opening and closing `<html>` tags. This tells the web browser that all the code it is about to read should be formatted as HTML code. 
Next there are two sections that every page should have. The `<head>` and the `<body>`. 

The __head__ section contains information about the page, such as what information should appear in the title bar (specified inside the`<title>` tags) as well as how the pages should be styled, how it should be rendered on different screensizes and what information will be displayed by Search Engines. We will address all of these topics in a later section. The `<head>` section begins on line 2 and end on line 4 in our example above.

The __body__ section contains the information that should be displayed on the page itself. In our example above the `<body>` begins on line 5 and ends on line 7. In this case we have only displayed the message "Hello World" on our page. You will notice that is it surrounded by `<h1>` tags. In HTML 'h' is shorthand for 'heading' so `<h1>` is the biggest heading. Here are a few more example - you should try them out for your self.

HTML Tag    | Output
`<h1>heading 1</h1>`   |  <h1> heading 1</h1>
`<h2>heading 2</h2>`   |  <h2> heading 2</h2>
`<h3>heading 3</h3>`   |  <h3> heading 3</h3>
`<h4>heading 4</h4>`   |  <h4> heading 4</h4>
`<h5>heading 5</h5>`   |  <h5> heading 5</h5>
`<h6>heading 6</h6>`   |  <h6> heading 6</h6>
