---
Title: The Box Model
Category: Reading
Author: Joshua Robinson
Phase: 2
Time: 
Mastery: 
Updated: 06-15-2021
Concepts: 
---
# The Box Model
The exact method of layout, object spacing, and adhering design elements to a grid is different depending on what tool and technology you are using. Figma and Sketch both use layout grids with features to work with padding and margin. Xcode, Apple's proprietary software development kit (SDK) uses Auto Layout with constraints to adjust sizes and positions. On the web, spacing is determined by the CSS Grid layout system or Flexbox. No matter how programs implement spacing, they all use the same underlying concepts. 

The CSS box model is a great place to start learning about spacing methods because it's the closest conceptual model to how design software does layout. 

## The standard box model
![|800](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/standard-box-model.png)
There are 4 parts of a CSS box. 
- Content box: This is where content like text is displayed. It's size is controlled by the `width` and `height` properties. 
- Padding box: The `padding` surrounds the content as white space. 
- Border box: The `border` wraps around the padding box and the content box. 
- Margin box: The `margin` wraps all the other boxes and is used to control additional whitespace between other elements. 

```ad-note
This model is the standard CSS box model. Notice that the total width and height measures the content box, but does not include the padding and margin. CSS has a user-controlled alternative model that does include the border and padding space called the `border-box`. 

```

---
# Quiz
1. T or F: On the web, layout is typically controlled by CSS Grid and Flexbox. (T)
2. T or F: The box model is only useful when working in Figma or Sketch. (F)
3. T or F: In the box model, padding and margin are the same thing. (F)