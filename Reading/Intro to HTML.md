---
Title: Intro to HTML
Category: Reading
Author: Joshua Robinson
Phase: 4
Time: 
Mastery: 
Updated: 07-19-2021
Concepts: 
---
Curriculum: #studio-2 #reading 
Target Skills: #software #web-design 

# Intro to HTML
Watch this fantastic introduction video from Webflow on how HTML and CSS provide the structure and styling of the modern-day web. 

<div style="display: block; position: relative; width: 100%; height: 0px; --aspect-ratio:9/16; padding-bottom: calc(var(--aspect-ratio) * 100%);"><iframe src="https://www.youtube.com/embed/w-kBRUXsuSQ" allow="fullscreen" style="position: absolute; top: 0px; left: 0px; height: 100%; width: 100%;"></iframe></div>

```ad-note
title: Words to know
- Element
- Tag
- Attribute
- Identifier/Value
- Heading
- Unordered list
- Ordered list
- List item
```




## Elements and Attributes

HTML stands for Hypertext Markup Language. It's the code that structures all webpages and content. HTML is made up of **elements** that contain data, text, images, or sometimes nothing. An element usually has an opening **tag** and a closing tag. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/html.png)

**Attributes** change the behavior of an element. An attribute is made of an identifier name followed by it's value. In the example below the attribute name is `class` and `student` is the attribute value. In this case, the attribute gives the element a non-unique identifier that allows us to target the element in CSS and style it however we want. Anything then given the value of `student` will take on the style information we define in CSS. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/attribute.png)

Some elements do not contain content and these are called empty elements. The `<img>` element contains no closing tags and no content. The `src` attribute contains a value that is the path to where the image is actually stored. The `alt` attribute is used to specify a text description for accessibility purposes. Alt text should always be descriptive so that readers have enough information to understand the content of the image. 

````html
<img src="images/student-picture.png" alt="The student profile headshot">
````

## Headings, Paragraphs, and Lists
HTML includes six heading levels, h1 through h6. Heading elements should be semantic, meaning they indicate level of importance in the text hierarchy, not the style of the text. Styling of the heading elements should be done through CSS. 

```html
<h1>My main title</h1>
<h2>My top level heading</h2>
<h3>My subheading</h3>
<h4>My sub-subheading</h4>
```

Use the paragraph element `<p>` to contain paragraphs of text. 

Lists contain two elements: an ordered `<ol>` or unordered list `<ul>` element and the list item `<li>` element nested inside. Nesting elements means putting an element inside another one. 
- **Unordered lists** should be used when the order of items does not matter, like a grocery list. 
- **Ordered lists** typically use numbers that specify an order like a set of instructions.
```html
<ol class="story">
	<li>Character</li>
	<li>Setting</li>
	<li>Plot</li>
</ol>
```

## Links
Links are what makes the web the web! You can make any text a link by wrapping it in the `<a>` element and giving an attribute of `href` (hypertext reference) with the web address you want it to look too. This is what it looks like: 

```html
<a href="https://flatironschool.com">This text goes to the school website</a>
```

## Nesting
Nesting means exactly what it sounds like. HTML elements can be nested inside one another creating parent, child, and sibling relationships. Nesting becomes very important when you are trying to apply CSS styles due to the concept of inheritance. Child elements inherit certain CSS property values that are set on the parent element. In the following example, the `span` element is nested inside the `p` element. 
```html
<body>
  <p>This paragraph will inherit certain CSS values that are set on the parent body element</p>
</body>
```

---
# Quiz
1. Which html would you use to link to another page in HTML? 
	1. the 'href' attribute
	2. the <p> element
	3. the <body> element
	4. the <a> element and the 'href' attribute (correct)
2. T or F: HTML elements cannot be nested inside one another. (F)
3. What changes the behavior of an element? 
	1. Nesting the elements
	2. attributes (correct)
	3. selectors
	4. child elements
	4. T or F: The <img> element does not require a closing tag (</img>) (T)