# HTML
Html has elements that are there to structure the page and these are called structural markup like the `<p>` tag and the `<h1>` tag.

And elements that has to do with indicating the meaning of an element and they are called **semantic markup** like `<strong>` tag and `<em>` tag.

### Headings

Headings are placed in the website according to their importance so `H1` is the most important tag in the page and `h6` is the least important tag.

Some more examples of markup elements are `<i>` for italics, `<sup>`, `<abbr>`, and `<sub>`.

We also have the tags `</br>` and `</hr>` that are used to structure the spacing in the webpage. 

There are two elements to make quotations: `<blockquote>` and `<q>`.
One is used to indent the quoted paragraph and the other is used to put quotation marks around the quoted word or phrase.

`<cite>`:  It makes the sources in italics. We can also have <dfn> tag for definitions which does nothing :smile:

We also have the `<address>` element to write the contact information and it is displayed as italics by some browsers.

If you ever want to make the editing of the webpage visible to the viewer, you can use the `<ins>` and `<del>` elements which would indicate the deleted text and underline the inserted text. And if you want to indicate that something is no longer available or accurate, you can use the `<s>` element.

# CSS
CSS is the what we include in our codes to design our website. It helps with creating the layout to your page. It can also change colors everything associated with styling the page. CSS codes work with HTML element so they have a certain way to interact with each other so that we get the result of the styled website with the content needed. You can select a certain part of the HTML codes to apply the CSS to. 

CSS could be inside the HTML elements (inline) or in the head in the same sheet (internal) or it can be done externally and then we link it to the HTML sheet (external), which is the recommended way. One of the major features in CSS is the color to the texts and the background. It is very important to color the website so you should not underestimate it. You can add the colors using three methods: color name, hex codes, and RGB values.

In order to apply CSS styles to the page layout, you need to have a selector: which elements you need to apply to. And also the Declarations that has the property you want and the value.
`h1, h2, h3 
{ font-family: Arial; 
color: yellow;}`

The previous CSS style will be applied to `h1`, `h2`, and `h3` this part of the CSS is called selector.

Font-family and color are called **properties** because they define what you want to do with the elements selected. Arial and yellow are called **values**.

For the CSS selectors, you can select the elements by writing the tag name or many other ways as follows:

Universal Selector: applies to all the elements on the page `*{}`
Type Selector: applies to all the elements that have this type `h1{}`
Class Selector:  applies to all the elements that have the same class in the html file 
`.note {}` Targets any element whose class attribute has a value of note 
`p.note {}` Targets only 
elements whose class attribute has a value of note
ID Selector: applies to the one element with this id `#name of the id {}`
Child Selector: applies to any direct child of a certain element `li>a {}`
Descendant Selector: applies to any child of any element even when it’s not direct `p a {}`
Adjacent Sibling Selector: applies to the element next to another element of another type `h1+p {}`
General Sibling Selector: applies to the elements at the same level of another element even when they’re not adjacent. `h1~p {}`


If it happens that you wrote more than one CSS rule for the first element the last one to be written will be applied or the most specific one or if any rule has the note `!important` next to it, it will be applied even if there are other rule somewhere else.

If you want the child to inherit some properties from the parent, you can use the value `inherit` when specifying CSS to the element.

# JavaScript
JavaScript files contain statements which are the lines in the document no matter what it does and they usually end with a semicolon.

You can write comments in your script which you can refer to when you read if later or if anyone wants to visit your script and you can also put certain statements inside the comment section if you don’t want it to be executed.

There are certain statements in the script that are called variables. In order to declare a variable, you need to write the keyword var then the name of the variable and then the value you want to give it
`Var x= 10`

You can assign different data types to a variable: numbers, strings, or Boolean

There are certain rules to make your variables clear, you should start it with a letter or `$`, the names are case sensitive, and many other rules.

Using an array, you can store more than one value into one variable. If you want to use a certain index in this array you write the number of this index but you should start counting from zero.

## Expressions
Expression assign a value or more than one value to a variable so it could be:
X=3
Or
X= 3-1

In the second scenario, the operation is done and 2 will be given to x as a value.

## Operators
Comparison operators compare two things using in the script and it gives you a result using Boolean: true or false. Example: x=4, y=7
X<y
True
Other example of comparison operators are: >, ==, etc.
Logical operators compare the results of two or more comparison operators and it also give the result as true or false. Example:
X<y && y>x
True

Other example of logical operators:
(&& and) (|| or)

## If statement 
You can make the execution of a block of code depend on a condition so if the result of the condition is true, the code will be executed. If you need to also execute another block of code if the result of the condition is false, you can write the code after the else part.

## Commit Messages
When you make any changes in your file, and then you want to hit commit, you will be asked to leave a message indicating why you made this change and usually these messages are not taken seriously. However, the importance of these messages should not be underestimated when you want to have an organized flow of work or if you want other people to follow with your writing of the code. The commit messages are considered vital when you work in a group and you need other members to be on the same page without any misunderstanding. 
