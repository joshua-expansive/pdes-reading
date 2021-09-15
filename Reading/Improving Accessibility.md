# Improving Accessibility
In an ideal world, accessibility would be a priority from initial ideation to final product development. However, you’ll notice that this doesn’t always happen. Older products/services might not have been designed according to more modern accessibility standards, and newer products/services may have been designed by a team/company who viewed accessibility as a legal hurdle that ate up time, money, and resources. In your career, you’ll likely be asked to run an accessibility audit on an older, existing product created without accessibility in mind. You’ll also be asked to do the same for the designs you make to validate for your boss, stakeholders, or the client that the product is, indeed, accessible. (It’s also not a bad idea to do an accessibility audit of your company/client’s existing digital products regardless of if you are asked to or not.)

An accessibility audit aims to define which elements of the website or digital product/service are accessible and which elements need to be modified and improved. It allows designers to validate that every user will be able to accomplish their goals quickly and equally. A thorough accessibility audit includes:
-   Designer observations
-   The results of various accessibility tests
-   A rundown of how closely the product/service adheres to governing accessibility guidelines
At the end of the audit, you can highlight accessibility weaknesses and offer areas for improvement. 

Your audit should include the results of standardized accessibility tests you need to run on the product/service. These tests will give teams and stakeholders a set of qualitative and quantitative data to work off of in improving accessibility. Fortunately, you have a ton of tools at your disposal to quickly and accurately run accessibility tests. These tools automate the process, saving you a ton of manual time. 

Tools that automate the accessibility evaluation process are software programs or online services that help designers determine if digital content meets accessibility standards. The World Wide Web Consortium (W3C) has compiled a [comprehensive list](https://www.w3.org/WAI/ER/tools/) of these tools, which you can filter through to find the ones most relevant to the particular product or service you are evaluating. There is no golden number of tests you should run before you consider your audit complete. Aim to run as many as are relevant until you have a wide range of global and feature-specific data that you can use to advocate for improvements to the product/service’s accessibility. 
## Conducting an Audit
To conduct an [accessibility audit](https://www.w3.org/WAI/test-evaluate/preliminary/), commit to challenging all assumptions around who will and won’t use the product/service. You might have an idea of who the intended audience is, but you never truly know all of the people that might use your product/service to complete a daily, monthly, yearly or one-time task or goal.

As you navigate through the product/service, the goal is to find opportunities to improve the design’s accessibility to better support various disabilities and user limitations. When designing to reach [Level AA conformance](https://www.w3.org/TR/WCAG20/), one of the more popular levels of compliance, be sure to speak to the following:  
### User Tasks and Navigation
- **Pattern libraries:**  Use pattern libraries to define a coherent and consistent system for users. After you establish your baseline hierarchy and pattern usage, avoid deviating from them, so your audience’s navigation is not hindered. Switching design patterns around on your users drives down usability and causes user dropoff.
- **Forms:** Everyone (especially those with cognitive disabilities) benefits from a logical, clear, and intuitive form. Accessible forms refer to ensuring they are allowed for people who use screen readers or keyboards to navigate easily through tasks. Start with making sure the form can be completed by someone who only uses the keyboard to navigate. Provide clear guidance and information within the form, and be sure to associate form labels with controls 
- **Time-based tasks:** Some people require more time than others to complete specific tasks. A person with a motor function disability or poor vision will likely need a few extra seconds or minutes to understand and finish a digital task (like a form) than someone with perfect vision and fast typing skills. If security concerns necessitate a time limit for users, the first step in promoting accessibility is to make sure users are warned about that time limit well in advance. You can also allow users to turn off, adjust or extend the time limit before encountering it. 
- **CAPTCHA:** [CAPTCHA](https://www.wikiwand.com/en/CAPTCHA) is a way companies verify if a user is a human versus a robot. You’ve probably encountered this before when you’ve been asked to fill out a digital form or log in to an interface. It asks users to complete a task believed to be relatively simple for humans but difficult for robots. However, some of these “simple” tasks are not so easy for those with disabilities and other impairments. It’s best to have a CAPTCHA that combines vision-based, audio-based, and biometrics-based tasks to make it more accessible to users who cannot complete tasks based on only one type. 
- **Open-tab links:** If there’s a link that a user can open from your interface or website, make sure it doesn’t open in a new window or tab. Links that open in new windows or tabs aren’t accessible to users navigating via a screen-reader and users with cognitive impairments. 
- **Keyboard-compatible tasks:** Some users navigate the web solely via keyboard, rather than with a mouse or trackpad (due to disability, impairment, convenience, or just personal preference). Ensure all the content, navigation commands, and tasks can be found or reached using a keyboard. This often means that a user uses the tab button to navigate around the platform, so creating a logical tab order is critical to making sure the site is accessible. Additionally, adding a “skip to content” header before the page header also helps keyboard users navigate the content without the need to tab through half of the page. Ultimately, the goal is for users to engage with the right content with the fewest amount of keystrokes. 
### Interaction Design Elements
- **Interactions:** Be mindful of how often you use interactions on the platform. Users should understand the design of the platform and the tasks that need to be completed without relying solely on the interactions. Since users can complete tasks without interactions, things like hover states may only distract users -- especially those with visual impairments or cognitive disabilities. 
- **Animations:** Animations are great for bringing designs to life, but your designs shouldn’t rely on them to communicate pertinent information to users. Another thing to keep in mind is: Animated designs that flash will make your platform inaccessible (and potentially super harmful) to users with epilepsy or other seizure-causing impairments. Be sure that your animated designs don’t flash more than 3 times per second, regardless of size and contrast. 
- **Pointer gestures:** The more complicated the pointer gestures, the less accessible the platform. Much like device motion, leave the option open for users to deactivate these features when necessary. Additionally, provide single-pointer alternatives: Those who cannot pinch, drag, and gesture still need to access your platform and perform essential tasks. 
- **Touch targets:** Touch targets or anything on a phone or tablet that the user needs to touch to perform a task needs to be at least 9mm high by 9mm wide, regardless of the device. Be sure to include inactive space in between touchpoints to de-risk the user clicking on something by mistake.
- **Alternative device motion:** Build in features that allow the user to deactivate/activate motions to suit their specific needs better. Not everyone will be able to gesture swipe for Tinder or tilt their phones for Google Maps. While these are excellent features that have become colloquialized and ingrained in popular culture, they’re not accessible to every user. Build products with the understanding that motion-based features should be able to be disabled when needed. 
### Visual Design Elements
- **Data visualizations:** If data visualizations (graphs, infographics, charts, etc.) are not carefully thought about from an accessibility standpoint, it will be harder for some users to understand the information they are supposed to take away from those visualizations. You want everyone to be able to interpret your visualizations in a way that gives them the info you want to convey, so make sure you’re careful about using color-agnostic coding, clear text, alternative text, white space, distinctive labeling and takeaway titles to give users multiple ways of identifying the “point” of your visuals. 
- **Audio and video:** Provide transcripts and captions for audio or video elements to make them accessible to hearing-impaired users. Use audio and video only as necessary and make sure that there is no pertinent information in audio or video attachments. 
- **Typography:** Typography should be legible with line spacing minimally 1.5 times the font size in a paragraph and two times the font size following a paragraph section. The typeface in use should have tracking 0.12 times and kerning at least 0.16 times the font size. All large-scale text (header and subheaders) should have a contrast ratio of at least 3:1.
- **Color:** color should have contrast at least [4.5:1](https://webaim.org/resources/contrastchecker/) against its background. Icons need to be 3:1 against adjacent colors.
### Content Elements
- **Menus:** You probably know from your own experience browsing the web that there are several [different types of navigation menus](https://www.gate39media.com/ui-design-spotlight-7-types-of-navigation-menus/). Ensure that no matter what type of menu (drop-down, fly-out, etc.) your interface includes, users will be able to navigate through them without needing to hover or click their mouse. All menus should be clearly labeled, as simple as possible, and be screen reader/keyboard-friendly.
- **Links:** Links shouldn’t be labeled with language that only provides general direction like “click here” or “learn more.” Instead, provide context and language that will set clear expectations of where that link will guide them.
- **Call-to-actions (CTA):** When it comes to designing call-to-action (particularly those that involve buttons and text), don’t just use color, shape, size, and proximity to convey CTAs to users. It’s easy to fall back on color to build CTAs and to drive user understanding, but keep in mind that those understandings will be totally lost on users who are color impaired. Instead, focus on promoting user understanding by using precise language to define your call-to-action.
- **Headers:** Promote clarity by using understandable language in your headers. This may sound pretty straightforward, but headlines can quickly turn into click-bait or marketing fodder that is unrelated to the supporting content. Keep headlines simple and relevant to the content underneath them. 
- **Content orientation:** Think about how your designs can stack content to both portrait and landscape viewpoints. If a design was being mounted to a fixed device, how would it look?
- **Content location:** To reduce cognitive overload, there should be more than one way to find information within a platform. This will allow users to get to information faster with less platform friction.

---
# Quiz

1. Older digital products are not meant to be designed for accessibility, and should be assessed differently
	- True
	- False (correct)

2. You should run an accessibility audit on an existing product you're working on whether you are asked or not.
	- True (correct)
	- False 

3. Some of the places where accessibility best practices can be practiced are
	- pattern libraries
	- interactions and gestures
	- Menus and headers
	- Typography and Color
	- all of the above


___
