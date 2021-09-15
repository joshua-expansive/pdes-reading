---
Title: CSS Rules and Selectors
Category: Reading
Author: Joshua Robinson 
Phase: Portfolio
Time: 
Mastery: 
Updated: 07-20-2021
Concepts: 
---
Curriculum: #portfolio #reading 
Target skills: #software #web-design 

# CSS Rules and Selectors
```ad-note
title: Words to know
- ruleset
- selector
- property
- property value
- declaration
- ID selector
- class selector
```


CSS stands for Cascading Style Sheets and it's the code that styles the web. CSS can handle font styling, layout, images, animations, backgrounds, and borders to name just a few. CSS is not a programming language, but a style sheet language.

## CSS Rules
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/css.png)

In a CSS **ruleset** (or just rule), you will use a **selector** that declares which HTML element you intend to style. In this example above the HTML element is a `<p>` paragraph element. We'll talk about specificity and cascading styles more below, but for now just know that the selector is targeting *all* paragraph elements in our HTML. The **declaration** specifies which of the element properties you want to style, in this case we want the paragraph element **property** `color` to have the **property value** of `blue`. 

Rulesets are wrapped in curly braces (`{}`) and you must use a colon (`:`) to separate the property from its values. The semi-colon (`;`) separates each declaration from the next one. You can modify multiple properties and values in a single ruleset:
```css
p {
  color: blue;
  font-family: Inter, Helvetica, sans-serif;
  font-size: 1rem;
}
```

You can also select multiple elements and apply a single ruleset. Each element is separated by a comma. 
```css
p, li, h2 {
  color: blue;
  font-family: Inter, Helvetica, sans-serif;
  font-size: 1rem;
}
```

## Selectors
CSS gives you many different ways to target HTML elements. You've already seen element selectors like `<p>`. When you use an element selector it targets all HTML elements of that element type. To see all selector types available, visit the [Mozilla Selectors Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors). We're going to focus on three selector types, the ID selector, the Class selector, and the Attribute selector. 

**The ID selector can only be used for a single element, whereas class selectors can be used for multiple elements.** In other words, multiple elements cannot have the same id value on the same page.  Use the hash `#` in front of the ID name in the ruleset. In the example, the ID selector `#footer` will select the HTML element that has it applied. You can name ID and class selectors whatever you want, but there are [naming conventions](https://hackernoon.com/best-practice-in-css-organisation-and-naming-conventions-4d103ujy) you can follow that make it easier to organize your code. 

```css
#footer {
  width: 100%;
  height: 50px;
  background: purple;
}
```

Class selectors can target as many elements as you want. In [[Intro to HTML]] we showed you how a paragraph element can be given a class attribute. Use a period (`.`) to denote a class. 
```css
.student {
  color: excited-red;
}

/* 😁 No, excited-red is not a real color. */
```


![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/attribute.png)

Finally, the **attribute selector** looks for the presence of an attribute that you specify, or it can detect the presence of an attribute with a particular value. This makes attribute selectors quite powerful for targeting very specific elements. This will become increasingly important as you begin to understand how styles "cascade" in CSS. In the first example below, a link element `a` with an attribute of `title` is selected. In the second example, we are targeting only the link element with a specific `href`. 

```css
a[title] {
  color: black;
}

a[href="https://flatironschool.com"] {
  color: blue;
}

```

## Quiz
1. CSS rulesets must be wrapped in:
	1. parentheses
	2. curly braces (correct)
	3. brackets
	4. commas
2. T or F: There are only three selector types in CSS. (False, there are many)
3. T or F: If you wanted to style several different elements you should use an ID selector. (False, ID selectors can only be used on one element per page.)
4. Class selectors begin with a:
	1. hash
	2. cascade
	3. comma
	4. period (correct)

---