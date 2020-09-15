# Read09

## HTML

### Forms

You can use forms in order to collect data from visitors who can input the data in its space. . One common example of forms is the search box in google chrome that the user inputs the search keywords there for google to get it. There is more than one type in which data is collected so form controls can be:

`adding text`

`making choices`

`submitting forms`

`uploading files`

**How forms work?**

The user enter data or selects data, and then it goes to a server. The server processes the information using the backend languages such as C# or Java and sometimes it also goes to a database. The server creates anew page to send it back to the browser according to the user and the information that he entered. A user might submit more than one piece of information at once so the server needs to know which piece is connected to which form, that’s why the information is sent to the server in pairs keys and values.

**How to create forms?**

`<form>` tags are the building block and then you can add methods and attributes. Each form will have an `action` attribute that has the link of the page in the server that is going to receive the submitted input.

The method attributes for the form can be `get` or `post`

Get is for the short forms and post is for the long ones.

We can also use the `id` attribute that will distinguish it from other forms.

The `<input>` tag is used to give more information about the form.

You can input text, passwords (that appear blocked out), textarea (that allows you to write comments or notes for more than one line), radio buttons (that allow you to choose one option from a list), checkbox (you can choose more than one option from a list), drop down list box (you choose from options), multiple select box, file input box (they upload a file).

Submit button: in an `<input>`, you add the type submit

## CSS

### Lists and Tables

Lists can have many styles, you can have radio buttons or circles or numbers using the selector `list-style-type`

You can also have images for the bullets by linking the image in the `ul` tag.

You also have the choice between having the bullets inside or outside of the list items.

Here are some properties that you can aplly to your table:

`list-style` property allows you to write all of the different values in any order to apply to the list.

`width` to set the width of the table.

 `padding` to set the space between the border of each table cell and its content.
 
 `text-transform` to convert the content of the table headers to uppercase letter-spacing.
 
 `font-size` to add additional styling to the content of the table headers.
 
`border-top`, `border-bottom` to set borders above and below the table headers.

 `text-align` to align the writing to the left of some table cells and to the right of the others.
 
 `background-color` to change the background color of the alternating table rows.
 
`:hover `to highlight a table row when a user's mouse goes over it.

### Forms

There are many stylings that you can apply to forms to make it catchy and fun to fill.

You can apply them to text inputs and text areas, submit buttons, labels on forms, to get the form controls to align nicely align it to the center, this will make the user interact more with the form.

## JavaScript

When you interact with the web, it creates the events which will trigger the code that will be executed as a response to the interaction. Any event that happens on the browser can trigger an event in JavaScript.

The binding method is when you want to specify which event that you want to happen and for which element.

The most commonly used events are W3C DOM events.
  
