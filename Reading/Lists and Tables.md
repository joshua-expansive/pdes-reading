---
Title: Information Design–Tables
Category: Reading
Author: Joshua Robinson
Phase: 4
Time: 
Mastery: 
Updated: 07-06-2021
Concepts: 
---
 Curriculum: #studio-2 #reading 
 Target Skills: #information-design 

# Information Design–Lists and Tables
## Lists
Lists are used practically everywhere in software: movies, articles, bank statements, songs, emails, files, and on and on. The first question you must answer is: why does someone need this list? You should have research that indicates the need for displaying information and what people will want to do with it. 
1. **Why does someone need this list?** Are they browsing to buy items? Do they need an overview or the ability to deep dive into one item by clicking for more information? How much control do users need over the presentation of the list? Will they want to re-arrange or edit items in the list? Compare items? How much information should be displayed in the list view? 
2. **What are the non-visual characteristics of the list?** Make a list of the characteristics of the information you are working with. What is the length of the list? What order should the list default to: alphabetical, date, time? Will it require a grouping scheme? Are there categories the user will understand? What are the items like? Do they require images or dynamic content? What interactions are necessary for users to perform critical functions? The answers to questions like these will determine most of the design decisions you need to make, so make sure your answers are informed by user research and not guesses.

### Common Patterns
#### Split View
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/tables-overcast.png)

Overcast offers a split, or two-panel view, that allows users to browse podcast episodes on the left, and read deeper information and interact with the podcast controls on the right. Since Overcast is primarily used on mobile devices, the designers opted to stack the displayed attributes (title, date, length, description) vertically rather than horizontally.  

This is a common pattern for displaying information; most email clients offer options for split-view. Users can quickly see the overall structure of the list on one side, and then view an object's details on the other. This pattern reduces effort because it's easy to scan, interact with, and doesn't not ask the user to change context. 

**Tips**
- Make the selected item visually obvious. 
- Give users the ability to navigate the items via keyboard arrows. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/tables-reeder.png)
###### Reeder uses two list views to navigate two levels of hierarchy, the tags list and the article list, with the selected article in the right hand panel. As you resize the screen, Reeder changes to a drilldown view that is more appropriate for smaller views. 

It should be obvious that users might struggle with this pattern on smaller mobile devices. The physical display must be large enough to view two panels simultaneously. Apple News handles this by using a two-panel layout on iPad and Desktop, but then switches to a **one-window drilldown** on iPhone. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/tables-apple-news.jpg)

#### Drilldown
Just like the mobile view in Apple News, a one-window drilldown replaces the list view with the details or contents of the selected item. This pattern has the advantage of being able to quickly jump in and out of items by using a shallow hierarchy. Make sure the user can intuitively navigate back to the list view. If appropriate, include the ability to move to the previous or next item in the list view without having to go back to the main list. 

#### Inlay
A third option is to display item information in the context of the list itself via expanding and closing rows. This allows the user to stay in the list view and but also browse and compare items quickly. Readwise uses an inlay to allow users access to functionality to edit the selected item. Since you can expand as many rows as you want, Readwise includes a global expand/collapse control in the list bar to allow users to quickly reset to a collapsed state. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/tables-readwise.png)

- When an item is expanded, the other list items are pushed downward. 
- Use similar gestures for expand and collapse. 
- Keep controls near the top of the list item so users do not have to move the mouse to collapse it.

## Tables
Data tables show sets of data across rows and columns in a grid-like format. It's an easy to way to organize information, and it supports comparative analysis on categorical objects. Data tables often have interactive components and tools to query or manipulate the data. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/notion.png)
###### Notion

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/airtable.jpg)
###### Airtable

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/data-table.jpg)
1. Header row with attribute titles. Clicking a title sorts the rows by that attribute. Notice the dash (–) in the header checkbox indicates an intermediate state since some rows are selected and some are not. 
2. Selected rows with check boxes. The background highlight is another selected-state indicator. 
3. Control row. The ability to delete only appears when a row is selected. 
4. Search field.
5. Contextual menu allows for editing individual rows. 
6. Pagination control bar. 

### Typography for Tables
- Left-align text.
- Right-align numbers to help users make comparisons when scanning down columns.
	- Use consistent precision, the same number of decimal places.
	- If numbers don't use the same decimal places or format, align to the decimal place to aid in scanning. 
- Match heading alignment with the data below.
- Use a monospace font or, even better, tabular lining numerals.
- Fit columns to the data, they don't all need equal space.
- [[Gestalt Principles]] of Proximity and Similarity. Try using alignment, spacing, and grouping to organize the data instead of additional visual elements like borders (called "rules") or zebra stripes. Tables should not look like nets, or an excel sheet. If you use borders, they should be light in order to create a distinction, not a barricade. 

### Design Patterns for Data Tables
```ad-note
The following examples were created by product designer [Andrew Coyle](https://andrewcoyle.com).  
```

#### Fixed Header
![|800](https://miro.medium.com/max/1400/1*kXEEaxvKP_9xRT0HuqScTQ.gif)

#### Horizontal Scroll
![|800](https://miro.medium.com/max/1400/1*Mp9kJSIlLyn5qjX-vD56iA.gif)

#### Resizable Columns
![800](https://miro.medium.com/max/1400/1*3Mjvd1N9OlQC-aMWXEVtBQ.gif)

#### Row Style, Zebra Stripes, Line Divisions, Free Form
![|800](https://miro.medium.com/max/1400/1*yDwqntdUINCNJJTV7BXKzQ.gif)

#### Display Density
![|800](https://miro.medium.com/max/1400/1*68Gj3oI6z0ssNSqX3sSQbw.gif)

#### Visual Table Summary
![|800](https://miro.medium.com/max/1400/1*xhD2-Xa-jn1ve-jT0PLKTw.jpeg)

#### Pagination
![|800](https://miro.medium.com/max/1400/1*yLNoP3bNRc37jHn28Mqucg.jpeg)

#### Hover Actions
![|800](https://miro.medium.com/max/1400/1*dCPE8gp5tbaVouGODN5bRQ.gif)

#### Inline Editing
![|800](https://miro.medium.com/max/1400/1*Sy9hS1AMycj5Uzo4VvckmQ.gif)

#### Expandable Rows
![|800](https://miro.medium.com/max/1400/1*0E1UPRzvK4gaV8sZEwOxLQ.gif)

#### Quick View
![|800](https://miro.medium.com/max/1400/1*Tt2x8SRugOlJQNsMdidF_g.gif)

#### Modal
![|800](https://miro.medium.com/max/1400/1*NSGIPqQ5nnFhunR8Osiunw.gif)

#### Row to Details
![800](https://miro.medium.com/max/1400/1*HAkPMgQhO-0kFgh-ITT5qA.gif)

#### Sortable Columns
![|800](https://miro.medium.com/max/1400/1*ViE5_uxbbU6LEfnV8GrQtA.jpeg)

#### Basic Filtering
![|800](https://miro.medium.com/max/1400/1*TJJAdrX7xwlhuyLBmD37pg.jpeg)

#### Filter Columns
![|800](https://miro.medium.com/max/1400/1*TKej8krSFjNDHoN43tOTkg.gif)

#### Searchable Columns
![|800](https://miro.medium.com/max/1400/1*jnENY_7hvq7iYlXayoQV3w.jpeg)

#### Add Columns
![|800](https://miro.medium.com/max/1400/1*mFs9KK1VADJbN4hAtjLX1w.jpeg)

#### Customizable Columns
![|800](https://miro.medium.com/max/1400/1*0NZs7HZtRrB_TukLjxInIQ.jpeg)

---
# Quiz
1. An important first step to designing a list or table view is: 
	1. Selecting a color theme. 
	2. Research that indicates the need to display information. (correct)
	3. Deciding on the titles of the columns. 
	4. None of the above. 
2. When an item is expanded, the rest of the view is pushed down is an example of: 
	1. An inlay (correct)
	2. A split view
	3. A drilldown 
	4. A bad design pattern