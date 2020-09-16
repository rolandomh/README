
# 201 d66
# Read08.md
Reading notes and Repo updates from an aspiring WebDev.
![Type-copy](https://wtf.tw/ref/duckett.pdf)

### Reading08
### From the Duckett HTML book:
####HTML/CSS book, Ch. 15, “Layout” (again; repeat of Class 4 reading):

Links are created using the <a> element.The <a>  element uses the href  attribute to indicate the page you are linking to. If you are linking to a page within your own site, 
it's best to use relative links rather than qualiﬁed URLs. You can create links to open email programs with an email address in the "to" ﬁeld.You can use the 
id  attribute to target elements within a page that can be linked to.
'target' command IS pop-up.To link to a ﬁle in the sa me folder, just use the ﬁle name. (Nothing else is n eeded.)
For a child folder, use the name of the child folder, followed by a forward slash, then the ﬁle name. Use the name of the child folder, followed by a for ward slash, 
then the name of the grand child folder, followed by another for ward slash, then the ﬁle name.
Use .. /  to indicate the folder above the current one, then follow it with the ﬁle name. Repeat the .. /  to indicate that you want to go up two folders (rather than one),
then follow it with the ﬁle name.

This invol ves learning abo ut how desi gning for a s creen can be different to designing for other medium s (such as print). 
In this chapter we will: 
Explore different ways to position elements using normal  
●ﬂow, relative positioning , absolute position ing and ﬂoats .Discover how various devices have different screen sizes 
●and resolution, and how this affects the design process. clear andn the difference between ﬁxed width and liquid layouts,  
●and how they are created. Find out how designe rsuse grids to make theirp age  
●designs look more professiona l.
### Chapter 15: “Layout” (pp.358-404)
* Note: This layout chapter is BIG. Focus your attention on understanding the core concepts presented on pp.358-364 *

### From the Duckett JS book:
### Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements). 
//example code at html level: 
<!DOCTYPE html>
<html>
<head>
  <title>Basic Function</title>
<linkrel ="stylesheet" href="css/ c03.css" />
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></script>
</ body>
</ html> 
//example code at js level: 
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}

### Article: “6 Reasons for Pair Programming”
1. so you have extra eyes.
2. so you have extra hands.
3. so you have extra brains.
4. so theres a higher statistical chance you'll have some "sense" between the two assumed huemans. 
5. see reason 6.
6. see reason 1. (this is a loop and call back.HOLLAH!)
