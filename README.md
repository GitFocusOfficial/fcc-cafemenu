# Learn Basic CSS by Building a Cafe Menu

CSS tells the browser how to display your webpage. You can use CSS to set the color, font, size, and other aspects of HTML elements.

In this course, you'll learn CSS by designing a menu page for a cafe webpage.

** Step 1

In this project, you will learn the basics of CSS (Cascading Style Sheets) by building a cafe menu. CSS is the language used to style an HTML document. It describes how HTML elements should be displayed on the screen.

As you learned in the last few steps of the Cat Photo App, there is a basic structure needed to start building your web page. Every HTML document should have a DOCTYPE declaration and html element. The DOCTYPE tells the browser which version of HTML the document is in. And the html element represents the root element which contains all other elements.

Example Code

``<!DOCTYPE html>
<html lang="en">
<!--all other elements go here-->
</html>``

Add the ``<!DOCTYPE html>`` tag, and an html element with a lang attribute of en.

Step 2

Add a head element within the html element, so you can add a title element. The title element's text should be Cafe Menu.

Step 3

The title is one of several elements that provide extra information not visible on the web page, but it is useful for search engines or how the page gets displayed.

Inside the head element, nest a meta element with an attribute named charset set to the value utf-8 to tell the browser how to encode characters for the page.

Step 4

To prepare to create some actual content, add a body element below the head element.

Step 5

It's time to add some menu content. Add a main element within the existing body element. It will eventually contain pricing information about coffee and desserts offered by the cafe.

Step 6

The name of the cafe is CAMPER CAFE. Add an h1 element within your main element. Give it the name of the cafe in capitalized letters to make it stand out.

Step 7

To let visitors know the cafe was founded in 2020, add a p element below the h1 element with the text Est. 2020.

Step 8

There will be two sections on the menu, one for coffees and one for desserts. Add a section element within the main element so you have a place to put all the coffees available.

Step 9

Create an h2 element in the section element and give it the text Coffee.

Step 10

Up until now, you have been limited regarding the presentation and appearance of the content you create. To start taking control, add a style element within the head element.

Step 11

You can add style to an element by specifying it in the style element and setting a property for it like this:

Example Code

element {
 property: value;
}

Center the content of the h1 element by setting its text-align property to the value center.

Step 12

In the previous step, you used a type selector to style the h1 element. Center the content of the h2 and the p elements by adding a new type selector for each one to the existing style element.

Step 13

You now have three type selectors with the exact same styling. You can add the same group of styles to many elements by creating a list of selectors. Each selector is separated with commas like this:

Example Code

selector1, selector2 {
  property: value;
}

Delete the three existing type selectors and replace them with one selector list that centers the text for the h1, h2, and p elements.

Step 14

You have styled three elements by writing CSS inside the style tags. This works, but since there will be many more styles, it's best to put all the styles in a separate file and link to it.

We have created a separate styles.css file for you and switched the editor view to that file. You can change between files with the tabs at the top of the editor.

Start by rewriting the styles you have created into the styles.css file. Make sure to exclude the opening and closing style tags.