
# 201 d66
# Read09.md
Reading notes and Repo updates from an aspiring WebDev.
![JonDuckett PDF](https://wtf.tw/ref/duckett.pdf)

### Reading09
### From the Duckett HTML book:
### Chapter 7: “Forms” (p.144-175)
Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.
HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.
Whether you are adding a simple search box to your website or you need to create more complicated insurance applications,
HTML forms give you a set of elements to collect data from your users. You will see forms when registering as a member of a website, when shopping
online, and when signing up for newsletters or mailing lists. 
There are several types of inputs to look for: 
*Text input (single-line)*
Used for a single line of text such as email addresses and names.
*Text area (multi-line)*
For longer areas of text, such as messages and comments.
*Password input*
Like a single line text box but it masks the characters entered.
*Checkboxes*
When a user can select and unselect one or more options.
*Radio buttons*
For use when a user must select one of a number of options.
*Drop-down boxes*
When a user must pick one of a number of options from a list.
*Image buttons*
Similar to submit buttons butthey allow you to use an image.
*Submit buttons*
To submit data from your form to another web page.
*File upload*
Allows users to upload files (e.g. images) to a website.
***Form*** controls live inside a <form> element. This element should always carry the action attribute and will usually have a
method and id attribute too. action Every <form> element requires an action attribute. Its value is the URL for the page on the
server that will receive the information in the form when it is submitted. method Forms can be sent using one of
two methods: get or post. With the get method, the values from the form are added to the end of the URL specified in the action attribute. 
  The get method is ideal for:
● short forms (such as search boxes)
  With the post method the values are sent in what are known as HTTP headers. As a rule of thumb you should use the post method if your form:
● allows users to upload a file
● is very long
● contains sensitive data (e.g. passwords)
● adds information to, or deletes infomation from, a database If the method attribute is not used, the form data will be sent using the get method.

#### id
We look at the id attribute on page 183, but the value is used to identify the form distinctly from other elements on the page (and
is often used by scripts — such as those that check you have entered information into fields that require values).

#### this section is very dense, my notes are not complete; I suggest reading through this with assistance before 201.

### Chapter 14: “Lists, Tables & Forms” (pp.330-357)
In this section you'll find information of how to:
● Specify the type of bullet point or numbering on lists
● Add borders and backgrounds to table cells
● Control the appearance of form controls
This example demonstrates the CSS properties commonly used with text inputs, most of which you have already met. font-size sets the size of the
text entered by the user. color sets the text color, and background-color sets the background color of the input. border adds a border around
the edge of the input box, and border-radius can be used to create rounded corners (for browsers that support this property).
The :focus pseudo-class is used to change the background color of the text input when it is being used, and the :hover psuedo-class applies the same
styles when the user hovers over them. background-image adds a background image to the box. Because there is a different image for each input, we are
using an attribute selector looking for the value of the id attribute on each input.

### From the Duckett JS book:
### Chapter 6: “Events” (pp.243-292)

### Article: “6 Reasons for Pair Programming”
1. so you have extra eyes.
2. so you have extra hands.
3. so you have extra brains.
4. so theres a higher statistical chance you'll have some "sense" between the two assumed huemans. 
5. see reason 6.
6. see reason 1. (this is a loop and call back.HOLLAH!)

