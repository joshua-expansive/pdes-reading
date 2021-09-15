# Practical Recommendations For Designing With Icons

**Testing icons** in interfaces with real users is crucial. Other times, we can follow best practices to ensure clarity and recognition

#### Use labels for usability

Icons can save space by reducing text, but at the price of recognition. Text labels can dramatically increase the usability. Icons need to set clear expectations for users _before_ they click or tap on them so they aren't intimidated by them.

For example, the bottom tab bar icons might confuse first-time Android users. 

![[bottom-tab-bar.png]]
###### source: [Google]

On the other hand, labelled icons are much more likely to be used.
![[labeled-icons.png]]

###### source: [Google](https://www.thinkwithgoogle.com/articles/chapter-6-usability-and-comprehension.html)

#### Using icons alone

Labels help with clarity for users not familiar with the icons. However, experienced users might regard an interface with text labels everywhere to be cluttered. 

Consider using icons alone will suffice when at least two of the following three conditions are met:

-   space is very limited (i.e. too small for text alone)
-   the icons are standardized (e.g. they are universal)
-   the icons represent objects with strong physical analogs or visual attributes (e.g. a red rectangle to set the page’s background as red)
    
###### source: [Michel Zuschlag via UX Stack Exchange](http://ux.stackexchange.com/questions/1795/when-to-use-icons-vs-icons-with-text-vs-just-text-links)
	

#### BEWARE OF TOOLTIPS AND POPOVERS FOR ICONS

Some designers believe labels defeat the purpose of icons and clutter the interface. To avoid using labels, they use tooltips. However, tooltips are a poor substitute for text labels. The fact that text labels never need graphic tooltips is a pretty good clue that text is better than icons. Another major disadvantage is that tooltips fail to translate well to touchscreens.

Another common technique is to use tutorials or coach marks or popover hints. However, users might simply rush through the tutorial or forget everything they’ve learned when they next launch your app. Like tooltips, tutorials are no substitute for intuitive design; rather, the opposite. As [Matthew at CocoaLove](https://twitter.com/mb) says, “Your app’s tutorial screen is just a list of ways you’ve failed.”

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/8bca9e2b-54e8-419b-9e44-6dcdc5d9a0a8/swarm-app-preview-opt.jpg)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/b9c075da-994b-44dd-b523-1362dd14c3fa/swarm-app-large-opt.jpg)

The Swarm app uses popover hint to educate users. (Image: [Mobile Patterns](http://images.mobile-patterns.com/1400178879546-2014-05-15%2014.29.24.png)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/b9c075da-994b-44dd-b523-1362dd14c3fa/swarm-app-large-opt.jpg))

#### ICONS AND BUTTON LABELS

Icons accompanied by labels make information easier to find and scan, as long as they’re placed **in the right spot**. Place icons according to the natural reading order. As [argued by UX Movement](http://uxmovement.com/buttons/where-to-place-icons-next-to-button-labels/), there are two important factors in an icon’s location:

-   In order for icons to serve as a visual scanning aid, users need to see them _before_ they see the accompanying label. Place icons to the left of their labels so that users see them first.
-   Align the icon with the label’s heading, instead of centering it with the heading and body. Seeing the icon first will help users to scan the page more easily.
    

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/699d0819-0061-4523-ac48-fcfb97f539bd/icons-order-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/699d0819-0061-4523-ac48-fcfb97f539bd/icons-order-preview-opt.png)

(Image: [UX Movement](http://uxmovement.com/buttons/where-to-place-icons-next-to-button-labels/)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/699d0819-0061-4523-ac48-fcfb97f539bd/icons-order-preview-opt.png))

#### ICONS IN DATA TABLES

Let’s imagine that you have a table with numbers in rows, and you need icons as supporting elements to indicate whether a value is good, mediocre or bad. What is the proper placement for icons next to numbers — to the right or left? As [Don Nickel explains](http://ux.stackexchange.com/questions/42988/placing-icons-next-to-numbers-to-the-right-or-left), icons to the left of a number usually indicate the **intent** of the data, whereas icons to the right usually indicate the **quality** of the data. As with icons with button labels, the placement of icons should follow the natural reading order. There are two possibilities for icon placement:

  
-   **Status** icons would appear at the end of the line. As seen in the example below, the user will see the subject first, then the value associated with the subject and, finally, the status of the value.
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/adad63ec-0562-405d-aa8b-b45cff630f21/status-icons-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/adad63ec-0562-405d-aa8b-b45cff630f21/status-icons-preview-opt.png)
    
    (Image: [Stack Exchange](http://ux.stackexchange.com/questions/42988/placing-icons-next-to-numbers-to-the-right-or-left))
    
-   If the icons themselves are the **subject**, then they would appear at the start of the line, and everything else would follow thereafter.
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/f1aeeae9-628e-4bfc-9c07-b274382adf44/subject-icons-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/f1aeeae9-628e-4bfc-9c07-b274382adf44/subject-icons-preview-opt.png)
    
    (Image: [Stack Exchange](http://ux.stackexchange.com/questions/42988/placing-icons-next-to-numbers-to-the-right-or-left))
    

#### ICONS FOR ACCORDION MENU

The accordion menu is a UI pattern that collapses long lists into manageable groups. It is useful for navigation menus and particularly for search filters.

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/38d29be9-f079-49ff-b207-8952e23d1416/accordion-menu.gif)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/1e2b4993-240c-4f52-9dac-f3d768751a09/accordion-menu-large.gif)

(Image: [Viget](https://www.viget.com/articles/testing-accordion-menu-designs-iconography)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/1e2b4993-240c-4f52-9dac-f3d768751a09/accordion-menu-large.gif))

Beyond the decision of whether to use an accordion menu, designers often wrestle with the specifics of designing one. The most common questions are:

-   What icon should I use? In terms of usability, is an icon really necessary at all?
-   Should the icon go on the left or right of the menu item?

Lance Gutin [conducted an experiment](https://www.viget.com/articles/testing-accordion-menu-designs-iconography) with different type of icons (chevrons, plus and minus signs, and triangles) and locations (to the left and right). With three icon choices in two locations and a control group with no icon at all, he identified seven total designs to investigate.

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/d5aae244-825d-47d8-96c0-157cf1aa4741/heatmap-summary-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/86cebfe7-a013-4e49-90be-42ed3ec783f8/heatmap-summary-large-opt.png)

Heat map summary of click locations per test (Image: [Viget](https://www.viget.com/articles/testing-accordion-menu-designs-iconography)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/86cebfe7-a013-4e49-90be-42ed3ec783f8/heatmap-summary-large-opt.png))

Analyzing the results, he mentioned two important findings:

-   The most convincing data involved icon location. Presented with an icon to the right of the menu item, many users preferred to click the icon rather than the text label. It’s quite possible that some users believed the icon and the label functioned differently; the icon’s small size and distance from the label increased the recorded task times, resulting in slower task times for accordions with icons to the right.
-   In terms of icon choice, the accordion menu with a plus placed on the left measured the fastest, with 90% of participants predicting that the menu would change. However, most of the task times did not differ statistically, and none of them differed practically.

Please notice that the study doesn’t mean that we all should use the icon with a “plus” icon placed on the left in accordion menus. However, if we put the icon on the right side, it’s safer to make sure that this icon is of a big enough size (at least 44×44px), so it’s easy to hit with a finger or a mouse.

#### BE CAREFUL WITH HAMBURGER ICON

Three horizontal lines (i.e. the “hamburger” icon) has become a convention for the main menu button, especially on mobile websites:

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/1113b568-05da-4022-8fc4-3763aa3f52f4/google-material-design-site-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/a3a03978-f798-4a94-b002-350df2471c4a/google-material-design-site-large-opt.png)

Google's Material Design website ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/a3a03978-f798-4a94-b002-350df2471c4a/google-material-design-site-large-opt.png))

However, take into account two important factors when deciding whether to use a hamburger icon:

  
-   A/B testing based on [Jon Rundle's article](https://www.smashingmagazine.com/2013/09/responsive-navigation-on-complex-websites/) shows a correlation between correct identification of the hamburger icon's function and the age of users. This icon isn't familiar to elderly users. Hence, from a usability perspective, ask who the majority of your users are.
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/9fac0684-f5ff-4243-a925-3690cc223cee/hamburger-icon-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/9fac0684-f5ff-4243-a925-3690cc223cee/hamburger-icon-preview-opt.png)
    
    (Image: [Edgar Anzaldúa](http://ux.stackexchange.com/users/13689/edgarator)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/9fac0684-f5ff-4243-a925-3690cc223cee/hamburger-icon-preview-opt.png))
    
-   Research from the [Nielsen Norman Group](https://www.nngroup.com/articles/magnifying-glass-icon/) found that the hamburger icon still requires labels for clarity. Other [research by James Foster](http://sitesforprofit.com/mobile-menu-abtest) clearly shows that the hamburger icon is not as clear as the simple word "Menu." Thus, using the word "Menu" (and making it look like a button) could be more helpful to visitors.
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/5d75590a-f13c-4260-928a-0b16c3e17ab9/menu-preview-opt.jpg)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/63589560-3588-420f-873f-744989752139/menu-large-opt.jpg)
    
    Original (baseline); variation 1 ("Menu" + border); variation 2 ("Menu" + hamburger icon + border); variation 3 ("Menu" without border). (Image: [Sites for Profit](http://sitesforprofit.com/mobile-menu-abtest)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/63589560-3588-420f-873f-744989752139/menu-large-opt.jpg))
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/73a13031-726a-4bdc-baeb-c82aed46cec5/menu-variations-preview-opt.jpg)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/a91de0d4-fb0d-4e07-b6a6-1b4ed1293713/menu-variations-large-opt.jpg)
    
    (Image: [Sites for Profit](http://sitesforprofit.com/mobile-menu-abtest)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/a91de0d4-fb0d-4e07-b6a6-1b4ed1293713/menu-variations-large-opt.jpg))
    

#### DESIGNING ICONS FOR MAXIMUM AFFORDANCE

When designing user interface elements, consider the principles of usability (consistency, affordance, etc.). Affordance, an important concept, essentially means that elements such as icons should be intuitive:

  
-   **Keep icons simple and schematic.**  
    In most cases, icons aren't the place to be creative. If you design a new icon, minimize visual detail and avoid a highly realistic image by focusing on the basic characteristics of the object. [Fewer graphic details](https://www.nngroup.com/articles/magnifying-glass-icon/) aid recognition.
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/75c5086c-e737-41f3-bace-1c198b2efaed/two-options-for-the-same-icon-preview-opt.jpg)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/53f6f807-e744-493f-a403-4ff16e9e9c99/two-options-for-the-same-icon-large-opt.jpg)
    
    If you have two options for an icon, choose the simpler one. ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/53f6f807-e744-493f-a403-4ff16e9e9c99/two-options-for-the-same-icon-large-opt.jpg))
    
-   **Choose familiar icons.**  
    A user's understanding of an icon is based on previous experience. If you decide to include icons in your interface, research first. Familiarize yourself with icons used by your competitors and with icons commonly used on the platforms you're targeting (i.e. system icons), because those will be most recognizable to your users.
-   **Don't port platform-specific icons.**  
    As you build your app for Android or iOS, [don't carry over themed UI](https://developer.android.com/design/patterns/pure-android.html) elements from other platforms. Platforms typically provide sets of icons for common functionality, such as sharing, creating a document and deleting. When you migrate your app to another platform, swap out the old platform-specific icons with the target platform's counterparts.
    
    [![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/0ef63e4c-61ef-42fc-9b9c-4748e428f4b1/icons-for-common-functionality-preview-opt.jpg)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/0ef63e4c-61ef-42fc-9b9c-4748e428f4b1/icons-for-common-functionality-preview-opt.jpg)
    
    Icons for common functionality in Android (top) and iOS (bottom)
    

#### MAKE ICONS GOOD TOUCH TARGETS FOR MOBILE APPS

People interact with touch-based interfaces using their fingers. UI controls have to be big enough to capture fingertip actions without frustrating users with unintended actions and tiny targets. The image below shows that the width of the average adult finger is about 11 millimeters (mm) wide, while a baby’s is 8 mm; some basketball players have fingers wider than 19 mm!

[![A diagram showing the finger width of people in different ages and from Baby to Basketball player](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/f12a800e-4c4b-4b5d-80ba-1c23059bbd95/touch-width.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/f12a800e-4c4b-4b5d-80ba-1c23059bbd95/touch-width.png)

People often blame themselves for having "fat fingers." But even baby fingers are wider than most touch targets. (Image: [Microsoft](https://developer.microsoft.com/en-us/windows/design)) ([View large version](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/f7aa0da6-9d0c-4887-b3ac-68d3e41ca6f2/touchtarget-opt.png))

The recommended target size for touchscreen objects is 7 to 10 mm. Below are Apple and Google’ recommendations for their platforms (see “[iOS Human Interface Guidelines](https://developer.apple.com/ios/human-interface-guidelines/)” and [Material Design](https://material.google.com/)):

-   Apple recommends a minimum target size of 44 × 44 pixels. Because physical pixel size varies by screen density, Apple’s pixel specifications apply best to the iPhone’s 320 × 480-pixel 3.5-inch display.
-   Google recommends that touch targets be at least 48 × 48 density-independent pixels (DP). A touch target of 48 × 48 DP results in a physical size of about 9 mm, regardless of screen size. In most cases, icons should be separated by 8 DP or more of space to ensure balanced information-density and usability.
    

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/a7c1b410-c5d5-4d6e-9daa-bb7b86870cc4/user-input-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/a7c1b410-c5d5-4d6e-9daa-bb7b86870cc4/user-input-preview-opt.png)

Touch targets include the area that responds to user input. (Image: [Material Design](https://material.google.com/))

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/9ae66432-1101-403c-a975-220b5d14c934/touch-area-preview-opt.png)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/9ae66432-1101-403c-a975-220b5d14c934/touch-area-preview-opt.png)

For this touch area, the icon is 24 DP, and the touch target is 48 DP. The values apply to Android apps. (Image: [Material Design](https://material.google.com/))

But not only is target size important; sufficient space between touch targets matters, too. The main reason to maintain a minimum distance between touch targets is to prevent users from touching the wrong icon and invoking the wrong action. This becomes extremely important when icons such as “Save” and “Cancel” are right next to each other. At least [2 mm of padding](http://www.lukew.com/ff/entry.asp?1085) between targets is extremely important in such cases.

[![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/83b47a46-fa69-4708-9ed3-6283ebcf9049/target-size-preview-opt.jpg)](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/83b47a46-fa69-4708-9ed3-6283ebcf9049/target-size-preview-opt.jpg)

#### TEST YOUR ICONS

Icons need to be handled with care. **Always test them for usability**. Watch how a real first-time user interacts with your UI, which will help you to determine whether the icons are clear enough:

-   **Test the icons for recognizability.**  
    Ask people what they think the icons represent. They shouldn’t have to wonder what they do, because they won’t bother trying to find out.
-   **Test the icons for memorability.**  
    Icons that are hard to remember are usually inefficient. Bring back a set of test users and ask whether they remember an icon’s meaning after having been told a couple weeks earlier.
    

### Conclusion

Iconography lies at the heart of UI design. It can make or break the usability of an interface. Every icon should serve a purpose. It should help the user do what they need to do without requiring additional effort. When designed correctly, icons guide users intuitively through a workflow, without relying much on copy. Don’t make your users think. Make clarity in the app a priority!

#### RECOMMENDED READING

-   “[On Icons](https://ia.net/know-how/on-icons),” iA
-   “[Myth #13: Icons Enhance Usability](http://uxmyths.com/post/715009009/myth-icons-enhance-usability),” Zoltán Gócza, UX Myths

> This article is part of the UX design series sponsored by Adobe. The newly introduced [Experience Design app](http://adobe.ly/2dHuTKc) is made for a fast and fluid UX design process, as it lets you sketch out ideas, create interactive prototypes, test and share them all in one place.  
>   
> You can check out more inspiring projects created with Adobe XD on [Behance](http://adobe.ly/1U9LS0E), and also visit the Adobe XD blog to stay updated and informed. Adobe XD is being updated with new features frequently, and since it's in public Beta, you can [download and test it for free](http://adobe.ly/2dHvV8T).

![Smashing Editorial](https://www.smashingmagazine.com/images/logo/logo--red.png) (ms, yk, al, il)

Explore more on

-   [UX Design](https://www.smashingmagazine.com/category/ux-design)
-   [Icons](https://www.smashingmagazine.com/category/icons)
-   [Experience Design](https://www.smashingmagazine.com/category/experience-design)
-   [Sponsored Content](https://www.smashingmagazine.com/category/sponsored-content)

[![Smashing Newsletter](https://www.smashingmagazine.com/images/smashing-cat/cat-in-a-chair--tall.svg)](https://www.smashingmagazine.com/the-smashing-newsletter/)

#### [Smashing Newsletter](https://www.smashingmagazine.com/the-smashing-newsletter/)

Tips on front-end & UX, delivered weekly in your inbox. Just the things you can actually use.

[![Front-End & UX Workshops, Online](https://www.smashingmagazine.com/images/smashing-cat/cat-explorer.svg)](https://www.smashingconf.com/online-workshops/)

#### [Front-End & UX Workshops, Online](https://www.smashingconf.com/online-workshops/)

With practical takeaways, live sessions, video recordings and a friendly Q&A.

[![TypeScript in 50 Lessons](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_400/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/c2f2c6d6-4e85-449a-99f5-58bd053bc846/typescript-shop-cover-opt.png)](https://www.smashingmagazine.com/printed-books/)

#### [TypeScript in 50 Lessons](https://www.smashingmagazine.com/printed-books/)

Everything TypeScript, with code walkthroughs and examples. And other printed books.

## — Comments 11

![Himanshu Sukhwani](https://smashingmagazine.com/images/userpics/avatarSM-8.png)

Himanshu Sukhwani wrote — october 21, 2016 6:43

Great article! Key takeaway for me was the difference between chevron and plus icon in the sidebar menu. Makes me look at my app design in a new light. Thanks!

Reply

![Yantram Studio](https://smashingmagazine.com/images/userpics/avatarSM-5.png)

Yantram Studio wrote — october 27, 2016 10:06

This Post I Read It It's Very Impressive Article And Information Too.

Reply

Load all 11 comments ↓

#### LEAVE A COMMENT

Comments are moderated. They will be published only if they add to the discussion in a constructive way. If you disagree, please be polite. We all want to learn from each other here. We use _GitHub Flavored Markdown_ for comments. Call out code within a sentence with single backticks (`` `command` ``). For a distinct block, use triple backticks (` ```code block``` `). Typo? Please [let us know](https://www.smashingmagazine.com/contact/).

Your message

Your (real) name

Your Twitter (e.g. 'smashingmag')

Post Comment

#### BROWSE ALL SMASHING MAGAZINE TOPICS

-   [Accessibility](https://www.smashingmagazine.com/category/accessibility)
-   [Android](https://www.smashingmagazine.com/category/android)
-   [Animation](https://www.smashingmagazine.com/category/animation)
-   [Apps](https://www.smashingmagazine.com/category/apps)
-   [CSS](https://www.smashingmagazine.com/category/css)
-   [Design](https://www.smashingmagazine.com/category/design)
-   [Design Patterns](https://www.smashingmagazine.com/category/design-patterns)
-   [Design Systems](https://www.smashingmagazine.com/category/design-systems)
-   [E-Commerce](https://www.smashingmagazine.com/category/e-commerce)
-   [Freebies](https://www.smashingmagazine.com/category/freebies)
-   [Graphics](https://www.smashingmagazine.com/category/graphics)
-   [HTML](https://www.smashingmagazine.com/category/html)
-   [Illustrator](https://www.smashingmagazine.com/category/illustrator)
-   [Inspiration](https://www.smashingmagazine.com/category/inspiration)
-   [iOS](https://www.smashingmagazine.com/category/ios)
-   [JavaScript](https://www.smashingmagazine.com/category/javascript)
-   [Mobile](https://www.smashingmagazine.com/category/mobile)
-   [Pattern Libraries](https://www.smashingmagazine.com/category/pattern-libraries)
-   [Performance](https://www.smashingmagazine.com/category/performance)
-   [Photoshop](https://www.smashingmagazine.com/category/photoshop)
-   [Plugins](https://www.smashingmagazine.com/category/plugins)
-   [React](https://www.smashingmagazine.com/category/react)
-   [Responsive Design](https://www.smashingmagazine.com/category/responsive-design)
-   [Service Workers](https://www.smashingmagazine.com/category/service-workers)
-   [Sketch](https://www.smashingmagazine.com/category/sketch)
-   [Typography](https://www.smashingmagazine.com/category/typography)
-   [UI](https://www.smashingmagazine.com/category/ui)
-   [Usability](https://www.smashingmagazine.com/category/usability)
-   [User Experience](https://www.smashingmagazine.com/category/user-experience)
-   [Wallpapers](https://www.smashingmagazine.com/category/wallpapers)
-   [Web Design](https://www.smashingmagazine.com/category/web-design)
-   [WordPress](https://www.smashingmagazine.com/category/wordpress)
-   [Workflow](https://www.smashingmagazine.com/category/workflow)

With a commitment to quality content for the design community.

Founded by Vitaly Friedman and Sven Lennartz. 2006–2021.

Smashing is proudly running on [Netlify](https://www.netlify.com/?utm_source=link&utm_medium=parter&utm_campaign=sm-footer).

Fonts by [Latinotype](http://latinotype.com/).

-   ✎ [Write for us](https://www.smashingmagazine.com/write-for-us/)
-   [Contact us](https://www.smashingmagazine.com/contact/)
-   [About us (Impressum)](https://www.smashingmagazine.com/about/)
-   [Privacy policy](https://www.smashingmagazine.com/privacy-policy)
-   [Membership login](https://www.smashingmagazine.com/auth/)
-   [Delivery times](https://www.smashingmagazine.com/delivery-times/)
-   [Advertise](mailto:advertising@smashingmagazine.com?subject=Let%E2%80%99s%20talk%20about%20advertising)