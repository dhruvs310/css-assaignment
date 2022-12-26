# css-assaignment
Module:2
( css & css 3 )
name: Dhruv shrimali

1.What are the benefits of using CSS?
Ans.
• Easier to maintain and update
• Greater consistency in design
• More formatting options
• Lightweight code
• Faster download times
• Search engine optimization benefits
• Ease of presenting different styles to different viewers
• Greater accessibility

2. What are the disadvantages of CSS?
Ans. • CSS, CSS 1 up to CSS3, result in creating of confusion among web browsers.
• With CSS, what works with one browser might not always work with another. The web
developers need to test for compatibility, runningthe program across multiple browsers.
• There exists a scarcity of security.
• After making the changes we need to confirm the compatibility ifthey appear. The similar
change affects on all the browsers.
• The programming language world is complicated for non-developers and beginners. Different
levels of CSS i.e. CSS, CSS 2,CSS 3 are often quite confusing.
• Browser compatibility (some stylessheet are supported and some are not).
• There might be cross-browser issues while using CSS.
• There are multiple levels which creates confusion for non-developers and beginners.

3. What is the difference between CSS2 and CSS3?
Ans.
CSS: CSS stands for Cascading Style Sheet. Its main objective is to provide styling and
fashion to the web page. CSS provides color, layout, background, font, and border properties.
CSS features allow better content accessibility, enhanced flexibility, and control, as well as the
specification of the characteristics of presentation.

CSS3: CSS3 stands for Cascading Style Sheet level 3, which is the advanced version of
CSS. It is used for structuring, styling, and formatting web pages. Several new features have
been added to CSS3 and it is supported by all modern web browsers. The most important
feature of CSS3 is the splitting of CSS standards into separate modules that are simpler to learn
and use.

4. Name a few CSS style components
Ans.
1)Selecter:HTML element name, id name, class name.
2)Property:It's like an attribute such as background color,font-size,position,text-align,color,border
etc.
3)Values:which defines property or values allocate for properties.

5. What do you understand by CSS opacity ?
Ans. CSS Opacity Property The CSS opacity property makes elements see-through, or
transparent. The value of the opacity property ranges between 0 and 1.
• CSS Opacity Property The CSS opacity property makes elements see-through, or transparent.
The value of the opacity property ranges between 0 and 1. ...
• Creating a Transparent Image Suppose you are designing a website where you want an image
to appear transparent. You could accomplish this goal using the opacity CSS property. ...
• Trigger Opacity on Hover ...
• Transparent Boxes ...
• RGBA Color Transparency ...
• Trigger Opacity on Hover ...
• Transparent Boxes ...
• RGBA Color Transparency ...

6. How can the background color of an element be changed?
Ans. You can change the background color of an HTML
element using the background-color CSS property and giving it a value of a color.
p {
background-color: pink;
}
With this code, the paragraphs are given a pink background.
For example, this code will make all paragraph elements in
your HTML file have a pink background because

the background-color property has a value of pink.

7. How can image repetition of the backup controlled?
ans. The background-repeat property in CSS is used to repeat the background image both
horizontally and vertically. It also decides whether the background image will be repeated or not.
Syntax:

background-repeat: repeat|repeat-x|repeat-y|no-
repeat|initial|inherit;

Example 1: In the example, we will make use of the repeat-x to repeat the image in the
horizontal direction.
<!DOCTYPE html>
<html>
<head>
<title>background-repeat property</title>
<style>
body 
{margin-top: 40px;
background-image: url("https://media.geeksforgeeks.org/wp-content/uploads/geeks-25.png");
background-repeat: repeat-x;
background-size: 150px 100px;}
h1 {text-align: center}
</style>
</head>
<body>
<h1>GeeksforGeeks</h1>
</body>
</html>

8. What is the use of the background-position property?
Ans. The background-position property sets the starting position of a
background image.
<!DOCTYPE html>
<html>
<head>
<style>
body 
{background-image: url('i123.jpeg');
background-repeat: no-repeat;
background-attachment: fixed;
background-position: center;}
</style>
</head>
<body>
<h1>The background-position Property</h1>
<p>Here, the background image will be positioned in the center of the element (in this case, the
body element).</p>
</body>
</html>

9. Which property controls the image scroll in the
background?
Ans. The background-attachment property in CSS is used to specify the kind of attachment of
the background image with respect to its container. It can be set to scroll or make it remain fixed.
It can be applied to all HTML elements.
Syntax:background-attachment: scroll|fixed|local|initial|inherit;
Example 1: The following example demonstrates the “scroll” value for the background-
attachment property of CSS. The background-
attachment image also gets scrolled.
<!DOCTYPE html>
<html>
<head>
<style>
#example {background-image:
url("https://www.bing.com/images/search?
view=detailV2&ccid=ZouubBhD&id=606C665C7CC9592975E788EA97C6F6B9C1624D97&thid=O
416943_link-icon-free-download-chain-link-icon-
png.png&exph=940&expw=900&q=small+link+img&simid=607988969449792824&FORM=IRPRS
background-position: center;
background-repeat: no-repeat;
background-attachment: scroll;}
</style>
</head>
<body style="text-align:center">
<h1 style="color:green">GeeksforGeeks</h1>
<h2> background-attachment: scroll;</h2><br><br>
<div id="example">
<p>Prepare for the Recruitment drive of product
based companies like Microsoft, Amazon,
Adobe etc with a free online placement
preparation course. The course focuses on
various MCQ's & Coding question likely to
be asked in the interviews & make your
upcoming placement season efficient and
successful.</p>
<br>
<p>This course is especially designed for the
Java apprentices who want to hone their
skills in Java for Coding Interviews and
Competitive Programming. No matter if you
are a school student or college student,
if you have the zeal of programming, this
is the right time to start.
</p>
<br><br><br>
<p>Prepare for the Recruitment drive of product
based companies like Microsoft, Amazon,
Adobe etc with a free online placement
preparation course. The course focuses on
various MCQ's & Coding question likely to
be asked in the interviews & make your
upcoming placement season efficient and
successful</p>
<br><br><br>
<p>This course is especially designed for the Java apprentices who want to hone their skills in
Java for Coding Interviews and Competitive Programming. No matter if you are a school student
or college student, if you have the zeal of programming, this is the right time to start.
</p> <br>
<br>
<br>
<p>Prepare for the Recruitment drive of product
based companies like Microsoft, Amazon,
Adobe etc with a free online placement
preparation course. The course focuses on
various MCQ's & Coding question likely to
be asked in the interviews & make your upcoming placement season efficient and successful
</p>
</div>
</body>
</html>

10.Why should background and color be used as separate
properties?
Ans. The reasons for this are as follows: - It increases the legibility of the style sheets. The
background property is a complex property in CSS. If it is combined with color, the complexity
will further increase.

11.How to center block elements using CSS1?
Ans. To horizontally center a block element (like <div>), use margin: auto;
Setting the width of the element will prevent it from stretching out to the edges of its container.
The element will then take up the specified width, and the remaining space will be split equally
between the two margins:
<!DOCTYPE html>
<html>
<head>
<style>
.center {
margin: auto;
width: 60%;
border: 3px solid #73AD21;
padding: 10px;}
</style>
</head>
<body>
<h2>Center Align Elements</h2>
<p>To horizontally center a block element (like div), use margin: auto;</p>
<div class="center">
<p>Hello World!</p>
</div>
</body>
</html>

12.How to maintain the CSS specifications?
Ans. There are four categories which define the specificity level of a selector:
• Inline styles - Example: <h1 style="color: pink;">
• IDs - Example: #navbar
• Classes, pseudo-classes, attribute selectors - Example: .test, :hover, [href]
• Elements and pseudo-elements - Example: h1, :before

13.What are the ways to integrate CSS as a web page?
Ans. 1. First Way is <style> Tag (Embedding Styles):
this may be useful if you have only one HTML Page and you don’t want to create a separate
Stylesheet .
<html>
<head>
<style>
p
{color: green;
font-style: italic;}
</style>
</head>
<body>
<p>This is just an Example</p>
</body>
</html>
2. Second way is <link> Tag (Linking an External CSS File): This is the most
common way of including an External Stylesheet. In this method you can keep all of your CSS
rules in a single file saved with an Extension .css . This will be useful if you have number of
HTML Pages. If you need to alter a style across all of your web pages you just have to edit
only this CSS file, this will affect the pages wherever you included the CSS file with the tag
below.
[code] <link href=”style.css” rel=”stylesheet” type=”text/css” />

3. Third Way (Inline CSS):
Wrinting Inline CSS style is not recommended. But if you want to test quickly some
styles in your webpage you can do this.
Just include a parameter “style” in any HTML Tag.
[code]
<p style=”font-size: 12px; font-weight: bold”>This is inline style example</p>
4. Fourth Way (importing CSS inside a CSS file):
Sometimes you may need to include one more External CSS file in all of your Web Pages. This
will be difficult if you have 50 or 100 HTML Pages. But you can do this easily by attaching within
the present CSS file using the import rule.
[code]
@import “second.css”;
So the above @import will import all css rules into the present CSS file.

14. What is embedded style sheets?
Ans. Embedded Style Sheets is a style sheet where designers can embed information of the
style sheet in an HTML document by makinguse of the <style> element. This embedding of style
sheet info within <style> .... </style> tags are done within head section of HTML.

15.What are the external style sheets?
Ans. External Style Sheet
• External Style Sheet is basically a CSS file containing list of declaration blocks.
• This (.css) file is linked to various web pages to apply similar styles.
• To link HTML and CSS files together we use link tags.
<link href="filename.css" type="text/css" rel="stylesheet" />

16.What are the advantages and disadvantages of using
external style sheets?
Ans. Advantages And Disadvantages of External Style Sheets
• The style of a few documents can be controlled from the site by utilizing them.
• Multiple HTML elements can have numerous documents, where classes can be made.
• To assemble styles in complex circumstances, selector and grouping strategies are utilized.

17.What is the meaning of the CSS selector?
Ans. A CSS selector is the part of a CSS style call that identifies what part of the web page
should be styled. The selector contains one or more properties that define how the selected
HTML.

18.What are the media types allowed by CSS?
Ans. CSS defines the following media groups:
• continuous or paged .
• visual, audio, speech, or tactile .
• grid (for character grid devices), or bitmap .
• interactive (for devices that allow user interaction), or static (for those that
do not).
• all (includes all media types)

19.what is the rule set?
Ans. A rule set is a collection of one or more rules that you can associate with a realm
authorization, factor assignment, command rule, or secure application role. The rule set
evaluates to true or false based on the evaluation of each rule it contains and the evaluation type
