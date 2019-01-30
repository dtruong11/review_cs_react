## What does CSS stand for?

<details>
  <summary>Answer here</summary>
  Cascading Style Sheets 
</details>

## Give some examples of self closing tags

<details>
  <summary>Answer here</summary>
  The answer are these tags. 
  hr 
  input 
  br - break line 
</details>

## What is used to wrap HTML content?

<details>
  <summary>Answer here</summary>
    tags
</details>

## What is the correct HTML for referring to an external style sheet?

<details>
  <summary>Answer here</summary>
    The answer is 
    <link rel="stylesheet" type="text/css" href="mystyle.css">
</details>

## Which HTML attribute is used to define inline styles?

<details>
  <summary>Answer here</summary>
    style
</details>

## Which is the correct CSS syntax?

<details>
  <summary>Answer here</summary>
    body {color: black;}
</details>

## How do you insert a comment in a CSS file?

<details>
    <summary>Answer here</summary>
    /* this is a comment */
</details>

## Which property is used to change the background color?

<details>
    <summary>Answer here</summary>
    background-color
</details>

## Which CSS property is used to change the text color of an element?

<details>
    <summary>Answer here</summary>
    color
</details>

## Which CSS property controls the text size?

<details>
    <summary>Answer here</summary>
    font-size
</details>

## What is the correct CSS syntax for making all the <p> elements bold?

<details>
    <summary>Answer here</summary>
   p {font-weight:bold;}
</details>

## How do you display hyperlinks without an underline?

<details>
    <summary>Answer here</summary>
   a {text-decoration:none;}
</details>

## How do you make each word in a text start with a capital letter?

<details>
    <summary>Answer here</summary>
  text-transform:capitalize
</details>

## Which property is used to change the font of an element?

<details>
    <summary>Answer here</summary>
    font-family 
</details>

## Where inspect the CSS for a page within your browser?


<details>
    <summary>Answer here</summary>
    Styles (in spec element)
</details>


## When using the padding property; are you allowed to use negative values?

<details>
    <summary>Answer here</summary>
    not allowed
</details>

## How do you make a list that lists its items with squares?

<details>
    <summary>Answer here</summary>
    list-style-type: square;
</details>

## How do you select all p elements inside a div element?

<details>
    <summary>Answer here</summary>
    div p
</details>

## How do you display a border like this:
```
The top border = 10 pixels
The bottom border = 5 pixels
The left border = 20 pixels
The right border = 1pixel?
```
<details>
    <summary>Answer here</summary>
    border-width:10px 1px 5px 20px
</details>


## Which tag generaly hosts all of the web page content?

<details>
    <summary>Answer here</summary>
    body
</details>



## Which tag contains a page's title and links to stylesheets?

<details>
    <summary>Answer here</summary>
    The head tag
</details>

## What is the default position property?

<details>
    <summary>Answer here</summary>
    The position property specifies the type of positioning method used for an element (static, relative, absolute, fixed, or sticky).

    The default value is static. 
</details>

## How many ways can you integrate a CSS stylesheet into an HTML page?

<details>
  <summary>Answer here</summary>
  Three:
  <ul>
    <li>Inline: Style attribute can be used to have CSS applied HTML elements</li>
    <li>Embedded: The Head element can have a Style element within which the code can be placed</li>
    <li>Linked/Imported: CSS can be placed in an external file and linked via link element.</li>
  </ul>
</details>
<br>


## What does this CSS selector point to?

```css
div .card.active #something p.important {
    font-size: 10pt;
}
```

<details>
  <summary>Answer here</summary>
  A p tag with a class of "important" within an element with a id of "something" within an element with classes "card" and "active", within a div.
</details>
<br>

## What does the z-index attribute do?

<details>
  <summary>Answer here</summary>
  Helps specify an overlapping element.
</details>
<br>

## What is semantic HTML?

<details>
  Semantic HTML is a coding style. It is the use of HTML markup to reinforce the semantics or meaning of the content.
  eg: <strong>, <em> intsead of <b>(bold) or <i>(italics)
</details>
<br>

## How to create a nested webpage in HTML?
```iframe
<iframe src="URL"></iframe>
```
<details>
  The HTML iframe tag is used to display a nested webpage. In other words, it represents a webpage within a webpage. The HTML <iframe> tag defines an inline frame. For example:

</details>
<br>

## Is a <!DOCTYPE html> tag is a HTML tag?

<details>
<summary>Answer here</summary>
No, It is used to instruct the web browser about the HTML page.
</details>
<br>

## How to create form in html?
```
<form>
  First name:<br>
  <input type="text" name="firstname"><br>
  Last name:<br>
  <input type="text" name="lastname">
  <input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
  <input type="checkbox" name="vehicle2" value="Car"> I have a car 
  <input type="password" name="psw">
  <input type="submit" value="Submit">
</form>
```
<details>
  <summary>Answer here</summary>
  ```<input type="submit">``` defines a button for submitting form data to a form-handler
</details>


## How to select direct child?
```
body > p {
   color: #000000; 
}
```
<details>
  <summary>Answer here</summary>
  This rule will render all the paragraphs in black if they are direct child of <body> element. Other paragraphs put inside other elements like <div> or <td> would not have any effect of this rule.
</details>

## How to style based on attribute?
```
input[type = "text"] {
   color: #000000; 
}
```

<details>
  <summary>Answer here</summary>
  The advantage to this method is that the <input type = "submit" /> element is unaffected, and the color applied only to the desired text fields.
</details>

## How to select all paragraph elements with a lang attribute?

<details>
  <summary>Answer here</summary>
  p[lang] : Selects all paragraph elements with a lang attribute.
</details>


## How to select all paragraph elements whose lang attribute contains the word "fr"?

<details>
  <summary>Answer here</summary>
  p[lang~="fr"] - Selects all paragraph elements whose lang attribute contains the word "fr".
</details>

## What is the purpose of em measurement unit?

<details>
  <summary>Answer here</summary>
  em − A relative measurement for the height of a font in em spaces. Because an em unit is equivalent to the size of a given font, if you assign a font to 12pt, each "em" unit would be 12pt; thus, 2em would be 24pt.
</details>

## Which property is used to control the repetition of an image in the background?

<details>
  <summary>Answer here</summary>
  The background-repeat property is used to control the repetition of an image in the background.
</details>

## How to make text italic or oblique?

<details>
  <summary>Answer here</summary>
  The font-style property is used to make a font italic or oblique.
</details>

## What are variables used for?

```
$primary-font-stack: 'Helvetica', sans-serif;
$primary-color: #fccd48;

body {
    color: $primary-color;
    font-family: $primary-font-stack;
}
```
<details>
  <summary>Answer here</summary>
Variables are super useful for things like colors, fonts, font sizes, and certain dimensions, as you can be sure you’re always using the same ones, not 4 different versions of roughly the same color.
</details>

## What are functions/mixin?
```
@mixin border-radius($radius) {
    -webkit-border-radius: $radius;
       -moz-border-radius: $radius;
        -ms-border-radius: $radius;
            border-radius: $radius;
}

.box {
    @include border-radius(10px);
}
```
<details>
  <summary>Answer here</summary>
  Mixins are a very handy way of adding a number of styles, based on a particular input parameter. For example, you might always want to add fallback styles when adding border-radius, but you don’t necessarily know what value you might want.
</details>