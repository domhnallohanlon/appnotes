#CSS: Cascading Style Sheets

Cascading style sheets, or CSS, allow us to seperate the content of a document from it's appearance. For some incredible examples of this check out <a href="http://www.csszengarden.com/" target="_blank">CSS Zen Garden.</a> You should very quickly see that just by changing the CSS the appearance of a webpage can be dramatically changed. 

### Seperating Content from Presentation

The World Wide Web consortium (W3C) defines CSS as ...

> [T]he language for describing the presentation of Web pages, including       > colors, layout, and fonts. It allows one to adapt the presentation to        > different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language. The separation of HTML from CSS makes it easier to maintain sites, share     > style sheets across pages, and tailor pages to different environments. This  > is referred to as the separation of structure (or: content) from presentation

As we'll see shortly, this seperation of content and presentation is best acheived by keeping CSS and HTML in seperate documents, by to get started we'll try it out right in out HTML.

##Style tags

Since we're now writing in a new language, and since that language describes how the content of our documet should be displayed, we'll put a pair of `<style></style>` tags in the head of our document. Everything that is typed between these style tags is interpreted as CSS rather than HTML. The syntax is different but still relatively simple. You use a _selector_ to choose which element you want to style. Once this is done styles are applied in the form _property:value;_ Try some of the examples in the next section.

##HTML Elements

The easiest way to style something is by selecting it by its HTML element. For example, if we want to style all the level one headings to have red text rather than black text we write:

```css
    h1{
        color: red;
    }
```

There are a number of default colous in HTML (note the American spelling, color) but it's far more useful to use _hexadecimal_ which is described in greater detail in the [colours section](#!colours.md)

##Ids and Classes

The brute force approach of simply applying the same style to every element of the same type will eventually become less and less useful. It's much more helpful to make use of ids and classes. Any html element can have a `class` or `id` attribute applied to it. To signify that you are creating a css class begin with `.` and for an id begin with `#`. For example, `.myClass` and `#myId`.

##pseudo-selectors

One of the best examples of a pseudo selector is the `hover` state of an anchor tag. For example:

```css
    a{
    text-decoration: none;
    font-face: bold
    }

    a:hover{
        text-decoration: dashed;
        color: red
    }

```

## Example


<code data-gist-id="af6926978445086dec12"></code>

<a href="http://bl.ocks.org/domhnallohanlon/raw/af6926978445086dec12/" class="text-success pull-right" target="_blank">Preview Example</a>
<a href="https://gist.github.com/domhnallohanlon/af6926978445086dec12/download" class="text-success pull-right">Download Code</a><br>

