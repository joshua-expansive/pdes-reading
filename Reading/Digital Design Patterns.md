# Digital Design Patterns
---
## What
A design pattern, at its core, is a solution to a common everyday usability issue. When these solutions prove to be effective at solving for that usability issue, they become more widely adopted. As more products adopt this pattern to solve similar issues, the design pattern becomes more prevalent until it eventually becomes an industry standard, a best practice or common design pattern. 

---
## Why
There is a higher probability that the user will understand how this interaction should work rather than a navigation pattern that a user may be exposed to for the very first time. By using established and popular design patterns users expect and understand, products become more intuitive and an overall better user experience. That’s not to say new patterns can’t be learned and popularized to the point of being standard or widely adopted. It just requires explicit guidance and new learnings for the user. 

---
## How 
How does a designer come to decide which pattern to use over another that may solve the same design problem? Understanding the content and need is always a strong first step. Examining existing patterns is a smart secondary step. This allows time better suited for solving the custom challenges of your user and product versus trying to reinvent the wheel for each problem or content challenge. How are others solving for a similar problem? With those two foundational pieces in place, it is then easy to customize the pattern to make it most effective for the product or user need. 

---
## Where
Knowing where the pattern will live will also lend to which pattern to use or which new pattern to design for. Given the responsiveness of our digital experience, it may also be valuable to think device agnostically, meaning the pattern should work with whatever device or size that it needs to solve for. According to [PC Magazine](https://www.webdesignerdepot.com/2013/01/the-device-agnostic-approach-to-responsive-design/), device-agnostic simply means “not tied to a particular device. Same as machine-independent.” In other words, the site you build is not dependent on knowing what device it is being displayed on. This pushes the problem solver to not only focus on the implementation of the solution, which is generally focused on solutions for a particular device size, but instead on the solution best suited for the user’s need. [Sarita Harbour](https://www.webdesignerdepot.com/2013/01/the-device-agnostic-approach-to-responsive-design/) of Webdesigner Depot said it best when she stated:

>“Optimization should result from task and context analysis, so the user will receive the content they are most likely to require to perform the tasks given the device they use in the context of their environment.” — Sarita Harbour
___

## Patterns to Know
When thinking about popular design patterns, they typically will fall into one of three categories:** input and output, navigation, and content structure.** (Some fall into incentivization or behavior patterns but more on that later.) Though patterns may evolve over time due to changes and evolutions in technology, let’s take a look at some of the most current and common design patterns.

### Hamburger Menu
Though there is a plethora of [discussion](https://www.justinmind.com/blog/hamburger-menu/) and debate about the effectiveness and [when to use](https://www.nngroup.com/articles/hamburger-menus/) hamburger menus (it should be mostly for mobile), it will start off the patterns list. Screen space is a precious commodity on mobile, and the hamburger menu (or side drawer) is one of the most popular mobile navigation design patterns for helping you save it. The hamburger menu allows you to hide the navigation beyond the edge of the screen and reveal it only upon a user’s action. (Source: [Adobe](https://xd.adobe.com/ideas/principles/app-design/essential-patterns-mobile-navigation/)) Core functionality should still be surfaced to the user and not hidden within the hamburger menu.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/hamburger-menu.png)
######  [Google via UX Collective](https://uxdesign.cc/ux-of-the-hamburger-menu-890328a904f9)

### Springboard
A springboard or launchpad pattern is typically used in mobile operating systems and is organized into 3x3 or similar grids that provide users with options. This pattern is independent of the operating system meaning it can work on Android or iOS mobile devices. The most effective springboards are ones that are auto personalized by leaning on the user’s past behavior with the product and leaning on chunking to surface up the most relevant options versus all possible options in the springboard. (Source: [Mobile Design Pattern Gallery by Theresa Neil (O’Reilly Media)](https://www.oreilly.com/library/view/mobile-design-pattern/9781449336455/ch01.html) and [Evolution of a mobile menu by Bloomberg](https://www.bloomberg.com/ux/2020/04/08/evolution-of-a-mobile-menu/))

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/springboard.jpeg)
###### [Evolution of a mobile menu by Bloomberg](https://www.bloomberg.com/ux/2020/04/08/evolution-of-a-mobile-menu/)

### Sticky Menu
The fixed position menu, or sticky menu, is a web UI pattern whereby the header area (menu, website title and logo) remains visible as you scroll down, and the page’s content flows beneath it. Sticky headers have become a web UI pattern standard — Google + and Dropbox both have sticky menus. (Source: [UXPlanet](https://uxplanet.org/5-ui-patterns-navigation-that-makes-good-ux-sense-92a65df7485d)) It’s not uncommon for sticky navigation to show up on mobile as well but the common practice is for it to appear and disappear based on user’s behavior. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/sticky-menu.gif)
###### [UXPlanet](https://uxplanet.org/5-ui-patterns-navigation-that-makes-good-ux-sense-92a65df7485d)

### Mega or Fat Menus
A popular pattern used when there are a lot of top level categories to organize sub-pages. These diverge from the drop down menu in that it allows for a wide menu that shows users all available options instead of having them activate a drop down.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/mega-menu.jpeg)
###### Source: [Mockplus](https://www.mockplus.com/blog/post/website-navigation-examples-practices)

### Retractable Menus
Users need to access the navigation but they may need the screen space even more. Create a menu that can be put aside and easily retrieved again. (Source: [Welie](http://www.welie.com/patterns/showPattern.php?patternID=retractable-menu)) Similar to a hamburger menu, many times these retractable menus are supplemental content like a chat module or promotional items and less critical access content. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/retractable-menu.jpeg)
###### [Welie (Nike)](http://www.welie.com/patterns/showPattern.php?patternID=retractable-menu)

### Fat Footers
Users need a mechanism that will enable them to quickly access specific sections of a site or application bypassing the navigational structure.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/fat-footer.jpeg)
######  [UI-Patterns](http://ui-patterns.com/patterns/FatFooter)

### Breadcrumbs
Generally used as secondary navigation, breadcrumbs not only can be used to orient the user, they are labels that allow users to link to various sections of the site quickly. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/breadcrumbs.jpeg)
###### [UXPlanet](https://uxplanet.org/breadcrumbs-for-web-sites-what-when-and-how-9273dacf1960)

### Location Indicators
Similar to breadcrumbs, location indicators help users get oriented with their current location on the site or product. By differentiating the active menu item from the inactive items, users are usually able to identify where they are. This is best practice when designing for mobile, web, or responsively.  

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/location-indicators.jpeg)
###### [UXBooth](https://www.uxbooth.com/articles/the-rules-for-modern-navigation/)

### Dropdown Navigation Menu
One of the most common secondary navigation patterns is the drop down menu. This pattern allows designers to place important content for users to discover above the fold. It’s also a great organizational tool to not only clean up the user interface but also for users to find content more easily as it should be grouped with other similar menu items.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/dropdown-navigation.jpeg)
###### [Mockplus](https://www.mockplus.com/blog/post/website-navigation-examples-practices)

### Auto Save
The user wants to keep their data safe and saved while focusing on working without having to remember to do so. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/autosave.png)
###### [UI-Patterns](http://ui-patterns.com/patterns/autosave)

### Progressive Disclosure
Show users only features relevant for the task at hand, one per screen. If you break input demands into sections, you’ll reduce cognitive load (e.g., “Show More”).

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/progressive-disclosure.png)
###### [UXPlanet](https://uxplanet.org/design-patterns-progressive-disclosure-for-mobile-apps-f41001a293ba)

### Lazy Registration
Don’t force users to sign up before trying out the product. Instead, utilize lazy registration which allows users to explore the product as long as they would like while the product can probe and collect information needed to register along the way. This makes the decision to sign up much easier for users when they realize most or all of the information required is already saved. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/lazy-registration.jpeg)
###### [Maxim Stepanov of UX Collective](https://uxdesign.cc/30-steps-in-the-registration-process-for-stopping-users-from-cursing-you-369a6c18400))

### Guided Tours or Wizards
A particular introduction to new users or a guided step by step walkthrough of tasks to be completed by the user. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/guided-tour.png)
###### [UI-Patterns](http://ui-patterns.com/patterns/Guided-tour/examples/18279)

### Icons
When creating icons for the product, there should be a distinction between icons that are links and icons that are used for information purposes. According to [Nielsen Norman Group](https://www.nngroup.com/), “users are roughly 37% faster at finding items within a list on a web page when visual indicators vary both in color and icon compared to text alone.”

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/icons.gif)
######  [UXBooth](https://www.uxbooth.com/articles/the-rules-for-modern-navigation/)

### Cards 
Limiting information to fit into small containers to prevent clutter and to focus the user. Also referred to as chunking, the bite-sized content boxes are usually limited to include text, an image and sometimes a CTA button that upon clicking expands to reveal more information.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/card.png)
######  [Google Material Design](https://material.io/components/cards)

### Lists
Lists are a continuous group of text or images. They are composed of items containing primary and supplemental actions, which are represented by icons and text. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/list.png)
###### Source: [Google Material Design](https://material.io/components/lists)

### Quick View or Hovers
Quick View can give the ecommerce shopper an easy way of accessing a screen-sized image gallery of products without losing their place in the product list. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/quickview.jpeg)
###### [Baymard](https://baymard.com/blog/ecommerce-quick-views)

### Popovers
A popover is a view that appears above other content onscreen when you click a control or view. Typically, a popover includes an arrow pointing to the location from which it emerged. Popovers also support vibrancy. Use a popover to expose a small amount of information or functionality. Don’t use a popover as an alert. Source: [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/macos/windows-and-views/popovers/)

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/popover.png)
###### [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/macos/windows-and-views/popovers/)

### Infinite Scroll
Infinite scrolling is a technique that allows users to scroll through a massive chunk of content with no finishing-line in sight. This technique simply keeps refreshing a page when you scroll down it. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/infinite-scroll.gif)
###### [UXPlanet](https://uxplanet.org/ux-infinite-scrolling-vs-pagination-1030d29376f1)

### Drag and Drop
The user needs to perform operations on one or more objects by moving them from one place to another.Use when you want to let users to perform more complex tasks through direct manipulation – through a What-you-see-is-what-you-get (WYSIWYG) approach. Source: [UI-Patterns](http://ui-patterns.com/patterns/drag-and-drop)

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/drag-n-drop.gif)
###### [Prototypr](https://blog.prototypr.io/building-a-responsive-drag-and-drop-ui-5761fd5281d5)https://miro.medium.com/max/581/1\*6l7qupx0SmHHvVXkHqGi4Q.gif

### Good Defaults
The user needs to enter data into the system, where some input values are most likely to match default values. Use when the user has to choose among many options, where some are most likely to match the default values chosen by other users.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/good-default.png)
###### [UI-Patterns](http://ui-patterns.com/patterns/GoodDefaults)

### Tables
Data tables display information in a grid-like format of rows and columns. They organize information in a way that’s easy to scan so that users can look for patterns and develop insights from data. Information should be organized in a meaningful way, such as hierarchy or alphabetization. Data tables should allow user interaction so that a data display is customizable and interactive. Data tables should be easy to use, with a logical structure that makes content easy to understand. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/tables.png)
###### [Google Material Design](https://material.io/components/data-tables)

### Text Fields and Labels
Text fields allow users to enter text into a UI. They typically appear in forms and dialogs. When text input isn't accepted, an error message can display instructions on how to fix it. Error messages are displayed below the input line, replacing helper text until fixed. Label text is used to inform users as to what information is requested for a text field. Every text field should have a label. Label text should be aligned with the input line, and always visible. It can be placed in the middle of a text field, or rest near the top of the container.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/text-fields.png)
###### [Google Material Design](https://material.io/components/text-fields#usage)

### Tab Menu
Unlike the springboard and list menu, the tab menu is not OS neutral on mobile devices. When considering a tab interaction, designers should be conscious of the appropriate location and orientation of their tabs to best meet their users expectations.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/tab-menu.png)
######  [Google Material Design](https://material.io/components/tabs)

### Clear Primary Actions
Leaning on visual design to have calls-to-actions that stand out and set priorities. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/clear-primary-aciton.png)
###### [UX Collective by Tess Gadd](https://uxdesign.cc/ui-cheat-sheets-buttons-7329ed9d6112)

### Search (Persistent and Expandable)
Search allows users to quickly locate content across an app. Basic search enables users to input a query into a search text field to view related results. Search query input methods can be extended to include historical suggestions, auto-completion of queries, and voice input. Use persistent search when search is the primary focus of your app. The search text field is presented inside of a search bar, ready to receive focus. Use expandable search when search is not the primary focus of your app. Expandable search displays a search icon in the toolbar, instead of an open search text box.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/search.png)
######  [Google Material Design](https://material.io/design/navigation/search.html#persistent-search)

### Auto Complete
A technique focused on speed and eliminating ambiguity, that allows users to only type what’s necessary to quickly provide results and even surface up options.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/autocomplete.jpg)
###### [Google](https://blog.google/products/search/how-google-autocomplete-works-search/)

### Social Media Integration
Be it with sign up, leveraging existing popular accounts of users makes the user experience easier and boost engagement. Help users connect and join the group. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/social-media-integration.png)
###### [Hootsuite](https://blog.hootsuite.com/social-media-integration-for-your-website/)
  
### Progress Indicators or Steps Left
Showing a simple progress bar or indicator of steps needed to complete an action orients and motivates users to complete the task. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/progress-indicators.jpeg)
###### [StackExchange](https://ux.stackexchange.com/questions/124959/step-left-design-pattern-for-large-number-of-steps-on-mobile)

### Notifications
When users have new activity or need to take action, notifications go a long way of informing users something needs to be done. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/notifications.png)
###### [Miklos Philips of UX Collective](https://uxdesign.cc/a-comprehensive-guide-to-notification-design-2fff67f08b7a)

---
## Primary Navigation Patterns
Arguably the most important element when designing digital products is the navigation. How does the user get to where they need to go? When designing for smaller screens and mobile devices, designers will not be able to rely on a traditional top navigation bar which is seen on a majority of commercial websites. Below is a breakdown of four types of primary navigation on mobile devices.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/primary-navigation.jpeg)
###### Source: [TIS India](https://www.tisindia.com/blog/12-amazing-mobile-ui-design-patterns-unleashed-industry-popular-apps/)

### Card Navigation
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/trello.png)
###### [Justinmind](https://www.justinmind.com/blog/cards-ui-design/)

### Accordions 
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/accordian.png)
###### [[Jaed Mosharraf via Dribble](https://dribbble.com/jaedmosharraf)

### List Menu (similar to hamburger menu)
Similar to the functionality in a springboard, items in a list menu direct users to a specific page in the product. It is also OS neutral. Lists, however, are a better choice for navigation if there are a lot of menu items. Because those lists can be large, it is also common to allow users functionality like searching or filtering. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/list-idea.jpeg)
###### [TIS India](https://www.tisindia.com/blog/12-amazing-mobile-ui-design-patterns-unleashed-industry-popular-apps/)

---

# Quiz

1. Which one the following is NOT true?
	- By using established and popular design patterns users expect and understand, products become more intuitive and an overall better user experience.
	- A design pattern, at its core, is a solution to a common everyday usability issue.
	- It is important know to know where the design pattern will live when deciding which to use
	- New patterns can never be learned and popularized to the point of being standard or widely adopted. (correct)

2. Which design pattern shows users only features relevant for the task at hand, one per screen to reduce cognitive load?
	- location indicators
	- infinite scroll
	- progressive disclosure (correct)
	- clear primary actions

3. The design pattern of cards is used for ____.
	- storing contact information for the user
	- limiting information to fit into small containers to prevent clutter and to focus the user (correct)
	- payments in ecommerce checkout flows
	- progressive disclosure

4. Which of the following is a technique focused on speed and eliminating ambiguity, that allows users to only type what’s necessary to quickly provide results?
	- quick view
	- infinite scroll
	- auto complete (correct)
	- guided tours or wizards

5. Which of the following is NOT a navigation pattern?
	- Breadcrumbs
	- Drop down
	- Location Indicators
	- Quick View or Hovers (correct)


___
