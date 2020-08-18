![link-lab11](https://github.com/rolandomh/reading-notes/blob/master/READ11.md)
# 201 d66
# Read11.md
Reading notes and Repo updates from an aspiring WebDev.
![Type-copy](https://wtf.tw/ref/duckett.pdf)


### Reading11
### From the Duckett HTML book:
### Chapter 16: “Images” (pp.406-427)
Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.
*Examples of code at html/css level respectively for styling linkage:*
#### HTML
< img src= "images/magnolia-large.jpg"
 class= "large" alt="Magnolia" / >
< img src= "images/magnolia-medium.jpg"
 class= "medium" alt="Magnolia" / >
< img src= "images/magnolia-small.jpg"
 class= "small" alt="Magnolia" / >
 
 #### CSS
 img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}
img.small {
width: 100px;
height: 100px;}

#### CSS 
p {
background-image: url("images/pattern.gif");}

*or*
 
 body {
background-image: url("images/pattern.gif");}

You can specify the dimensions of images using CSS. This is very helpful when you use the same sized images on several pages of your site.
X Images can be aligned both horizontally and vertically using CSS.
X You can use a background image behind the box created by any element on a page.
X Background images can appear just once or be repeated across the background of the box.
X You can create image rollover effects by moving the background position of an image.
X To reduce the number of images your browser has to load, you can create image sprites.


### Chapter 19: “Practical Information” (476-492)

The Basics: Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results
when people look for the topics that your website covers. At the heart of SEO is the idea of
working out which terms people are likely to enter into a search engine to find your site and then using these terms in the right
places on your site to increase the chances that search engines will show a link to your site in their results. In order to determine who comes
first in the search results, search engines do not only look at what appears on your site. They also consider how many sites link
to you (and how relevant those links are). For this reason, SEO is often split into two areas: on-page techniques and off-page techniques.
 On-Page Techniques: On-page techniques are the methods you can use on your web pages to improve their rating in search engines. The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including
these in the text and HTML code for your site in order to help the search engines know that your site covers these topics. Search engines rely very heavily on the text that is in your pages so it is important that the terms people are going to search for are in text. There are seven
essential places where you want your keywords to appear. Ensuring that any images have appropriate text in the value of their alt attribute also helps
search engines understand the content of images.
 Off-Page Techniques Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your
site by looking at the number of other sites that link to yours. They are particularly interested in sites whose content is related to yours. For example, if you were running a website that sold fish bait, then a link from a hairdresser is not likely to be considered as relevant as one
from an angling community. Search engines also look at the words between the opening < a > tag and closing < /a > tag
in the link. If the text in the link contains keywords (rather than just click here or your website address) it may be considered
more relevant. The words that appear in links to your site should also appear in the text of the page that the site links to.
1: Page Title The page title appears at the top of the browser window or on the tab of a browser. It is specified in the <title> element which lives
inside the <head> element. 
 2: URL / Web Address The name of the file is part of the URL. Where possible, use keywords in the file name.
3: Headings If the keywords are in a heading <hn> element then a search engine will know that this page is all about that subject and give it
greater weight than other text.
4: Text Where possible, it helps to repeat the keywords in the main body of the text at least 2-3 times. Do not, however, over-use
these terms, because the text must be easy for a human to read.
5: Link Text
Use keywords in the text that create links between pages (rather than using generic expressions such as "click here").
6: Image Alt Text
Search engines rely on you providing accurate descriptions of images in the alt text. This will also help your images show up in the results of image-based searches.
7: Page Descriptions The description also lives inside the < head > element and is specified using a < meta > tag. It should be a sentence that
describes the content of the page. (These are not shown in the browser window but they may be displayed in the result.
  1: Brainstorm
List down the words that someone might type into Google to find your site. Be sure to include the various topics, products or services your site is
about. It often helps to ask other people what words they would use to find your site because people less familiar with a topic might use different terms than you. (In particular, they are less likely to use industry-specific jargon.) Your list may include some keyword phrases (not just
individual words) if you have topics which are described by more than one word
  2: Organize
Group the keywords into separate lists for the different sections or categories of your website. For example, if your website was a pet shop you might have different categories for different animals (such as dogs, cats and rabbits). On a large site you may break this up further into sub-categories (for example, separate groups for different pet food brands).
  3: Research
There are several tools that let you enter your keywords and then they will suggest additional keywords you might like to
consider, such as: adwords .google .co .uk/ select/KeywordToolExternal (When using this tool, select the "exact match" option rather than "broad match.")
### ![helplink1](www.wordtracker.com)
### ![helplink2](www.keyworddiscovery.com)
Once these tools have suggested additional keywords, add the relevant options to your lists. (Keyword tools will most likely suggest some terms that are irrelevant so do omit any that do not seem appropriate).
4.Compare
5.Refine
6.Map

### Article: “6 Reasons for Pair Programming”
1. so you have extra eyes.
2. so you have extra hands.
3. so you have extra brains.
4. so theres a higher statistical chance you'll have some "sense" between the two assumed huemans. 
5. see reason 6.
6. see reason 1. (this is a loop and call back.HOLLAH!)
