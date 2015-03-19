<head>
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
</head>

# A Picture Paints a Thousand Words
By this stage you should be comfortable with including images and CSS files in your pages. In this post you'll learn how to include icon fonts so that you can have thousands of images at your fingertips
<!--more-->

## How to include Font Awesome
Font Awesome is a great example of a free, online, icon font. It's really well documented too so you should be able to answer any questions you have on the site itself. For more information on setting up Font Awesome head over to their [getting started page.](http://fortawesome.github.io/Font-Awesome/get-started/) 
As of January 2015 the most recent version was 4.2.0. To include the font in your site you can include the CSS file in the `<head>` section of you page.

    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">  



## Examples
Then to put an icon on your page you use an `<i>` tag with a `class = "fa"` followed by the icon name, so for example to include this code icon 
<i class="fa fa-code"></i> simply use the following snippet:

    <i class="fa fa-code"></i>

Your icons can easily be resized by using the `fa-2x, fa-3x, fa-4x,` or `fa-5x` suffixes. Take the following for example:
    
    
    
    
    

HTML                              | OUTPUT
:-----------                      |:------------:
`<i class = "fa fa-coffee"></i>`      |<i class = "fa fa-coffee"></i>
`<i class = "fa fa-coffee fa-2x"></i>`|<i class = "fa fa-coffee fa-2x"></i>
`<i class = "fa fa-coffee fa-3x"></i>`|<i class = "fa fa-coffee fa-3x"></i>
`<i class = "fa fa-coffee fa-4x"></i>`|<i class = "fa fa-coffee fa-4x"></i>

## Other Icon Fonts
If you want to use another icons font the steps are usually the same - i.e. include the CSS and any JavaScript dependencies and the use the specific syntax for inserting the icon of your choice.
To find more icons for your projects check out [glyphsearch](http://glyphsearch.com) where you can quickly and easily search the following icon sets:
- Font Awesome
- Glyphicons
- Icomoon
- Ionicons
- Octicons
- Foundation