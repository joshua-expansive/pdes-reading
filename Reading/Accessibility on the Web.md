# Accessibility on the Web
## Web Content Accessibility Guidelines (WCAG)
The World Wide Web Consortium (W3C) maintains a set of internationally recognized [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/) that provides developers, designers and all interested parties with accessibility standards that are broken up into three levels of conformance: A, being the most low; AA, being moderate and most used; and AAA being the most strict. These guidelines can feel intimidating due to it’s granularity, even to seasoned users. Therefore a good place to start foundational understanding is with the W3C’s [four principles of accessibility](https://www.w3.org/WAI/WCAG21/Understanding/intro#understanding-the-four-principles-of-accessibility):
-   **Perceivable:** Information and user interface components must be presentable to users in ways they can perceive; sight, hearing, and/or touch. 
-   **Operable:** User interface components and navigation must be operable.
-   **Understandable:** Information and the operation of the user interface must be understandable.
-   **Robust:** content must be robust enough to be interpreted reliably by a wide variety of user agents, including assistive technologies.

While we don’t recommend approaching the global practice of designing for accessibility with a “checklist mentality,” referring to accessibility guidelines, requirements and checklists can help designers understand accessible design best practices and double-check that existing designs are accessible. In your career, you might find that your particular company or team has their standards for accessibility or that they follow the [WCAG guidelines checklist](https://webaim.org/standards/wcag/checklist) (as many companies do). Figuring out the level of accessibility compliance the product/service already has with the guidelines of choice will help you highlight strengths and identify areas for improvement. When using the WCAG guidelines, the standard compliance for the web is Level AA conformance. Not all platforms will be able to reach Level AAA  -- the highest level of accessibility -- conformance.
## Testing with Assistive Technologies 
[Assistive technologies](https://www.atia.org/at-resources/what-is-at/) are used by people with disabilities or other limitations to navigate daily challenges. From a user experience perspective, assistive technologies include special-purpose computers, special switches, keyboards, pointing devices, and screen readers. 

As a designer, keep in mind that these technologies may require you to make design modifications to increase the accessibility of your digital product or service. A great way to test for accessibility is to navigate your content using some of the standard assistive technologies you can expect some of your users to have. Here are some of the technologies and settings we recommend testing with: 
-   Keyboard Navigation:
-   Can you tab through the page without getting lost?
-   Do all focusable elements have focus states?
-   Do you have a skip navigation link?
-   When you encounter form controls, do the arrow keys work as expected?
-   Can you operate tabs, accordions, quick search results, etc, with just your keyboard?
-   Screen Readers:
	-   [VoiceOver](https://help.apple.com/voiceover/info/guide/10.13/) (macOS)
	-   [Narrator](https://support.microsoft.com/en-us/help/22798/windows-10-narrator-get-started) (Windows) 
	-   [NVDA](https://www.nvaccess.org/) (Windows) 
	-   [Chrome Vox](http://www.chromevox.com/) (Chrome & ChromeOS)
-   High contrast mode on your screen
	- Text and images of text have a contrast ratio of at least 4.5:1.
-   Low brightness settings on your screen
-   200% zoom
---

# Quiz
1. T or F: The WCAG's principle of 'Robust' means content should work with assistive web technologies like screen readers. (T) 
2. T or F: Navigating a website with just the keyboard is not part of the WCAG conformance. (F)
3. To conform with WCAG, text and images of text must have a contrast ratio of at least:
	1. 3:1
	2. 4.5:1 (correct)
	3. 7:1
	4. 3.5:1

 