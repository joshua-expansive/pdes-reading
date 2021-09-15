---
Title: CSS Cascade, Specificity, Inheritance
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

# CSS Cascade, Specificity, Inheritance
```ad-note
title: Words to know
- cascade
- specificity
- inheritance
```

Cascade, specificity, and inheritance are fundamental concepts that control how CSS is applied to HTML, and importantly how the browser should behave when there are conflicting rules. Understanding these concepts will save you lots of frustration when you begin styling your websites. 

The **cascade** is closely related to **specificity**. They both control which rule applies when there is a conflict. A conflict happens when you have created two or more rules which could potentially apply to the same element. **Inheritance** means that some CSS properties, by default, inherit the values which are set on the current element's parent element. This often causes unexpected behavior in the browser and head-scratching on the part of web developers. 

## Cascade means that the order of CSS rules matter.
In the example below there are two rules that have identical selectors and the same specificity. Since the second rule is defined after the first one, the text will appear as red in the browser, not blue. Order matters. 

```css
h2 {
  color: blue;
}
h2 {
  color: red;
}

```

## Specificity is how the browser decides which rule to apply when different selectors target the same element.

```css
h2 {
  color: blue;
}

.secondary-header {
  color: red;
}

```

```html
<h2 class="secondary-header">Will I be red or blue?</h2> red!
<h2>Will I be red of blue?</h2> blue!

```

In this example, we are using both an element selector to target all h2 elements *and* a class selector. When both rules are valid, which one wins? Will the text be red or blue? The concept of specificity means that a class selector is *more specific* than the `h2` element selector. And fundamentally, this makes sense. The class selector overrides the *less specific* element selector. The first `h2` will be red, and the second will be blue. 

## Some child elements inherit CSS property values from parents elements.

```css
body {
  color: red;
  font-family: Inter, Helvetica, san-serif;
  width: 50%;
}
```

```html
<body>
  <p>This paragraph is a descendent of <body> and will inherit the color and font-family. But it will not inherit the width property.</p>
</body>
```


---
# Quiz
1. "Cascade" in Cascading Style Sheets refers to: 
	1. What happens when CSS rules conflict. 
	2. That the order of CSS rules matter. 
	3.  Cascading down from general to specific CSS rules
	4. CSS has an inherent hierarchy
	5. all of the above (correct)
2. A class selector being more specific than an element selector refers to: 
	1. Inheritance
	2. Specificity (correct)
	3. Responsive design
	4. Overriding the cascade