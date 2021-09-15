# Notification Design

A critical [design heuristic] (https://www.nngroup.com/articles/ten-usability-heuristics/) states that “_the system should always keep users informed about what is going on, through appropriate feedback within a reasonable time._ “ 
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/notification-mobile.png)
Visibility of system status and feedback is foundational for usability, and usability is the bedrock of great user experiences. Notification Design does this via peripheral messaging in a collection of design patterns. 
## Start notification design early
Considering notification design early in the product design process yields a better user experience. By carefully assessing the peripheral messaging that needs to be shown at the right moment, designers can increase a product’s efficiency and help users accomplish a goal. Understanding when and how to use notifications is essential to building consistency in-product messaging.
## Classify and categorize different types of notification
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/notification-categories.png)
###### [Miklos Phillips via UX Collective](https://uxdesign.cc/a-comprehensive-guide-to-notification-design-2fff67f08b7a)
The initial approach to notification design needs classification based on severity: high, medium, and low-attention. Interactions that may potentially be destructive need high-severity notifications, and non-destructive interactions need low-severity ones.

Another way to classify them will be to determine if they are alerts, warnings, confirmations, errors, success messages, or status indicators.

Here are some common types associated with the level of severity:
**High-attention**
-   Alerts (immediate attention required)
-   Errors (immediate action required)
-   Exceptions (system anomalies, something didn’t work)
-   Confirmations (potentially destructive actions that need user confirmation to proceed)

**Medium-attention**
-   Warnings (no immediate action required)
-   Acknowledgments (feedback on user actions)
-   Success messages

**Low-attention**
-   Informational messages (aka passive notifications, something is ready to view)
-   Badges (typically on icons, signifying something new since last interaction)
-   Status indicators (system feedback)
## Incorporate them into a design system
Styling each type of notification consistently makes it easier for users to process and learn the language. In addition, all UX copy on notifications must be clear, concise, helpful, and use a pre-defined tone of voice. (friendly, assertive, serious, etc.)
## Designing Great Notification UX
Notification design must assist (not block) users to perform tasks and determine this via testing early prototypes. During the test is when you note all interactions where notifications may provide value to enhance the UX. Consider the following in addition to the designed asset.
-   What triggers the notification?
-   What type of feedback communicated?
-   Where would the notification appear, and how?
-   What is the severity of this notification?
-   Is the notification persistent or non-persistent?
## Push notifications
For mobile apps, not only in-app notifications but push notifications (system-level, outside the app) also need to be meticulously designed and timed not to alienate users. Delay notifications of any kind (asking for access to a person’s location, sending push notifications, and so on) until people have had the chance to explore your product a bit. 

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/push-notifications.jpeg)
###### [Miklos Phillips via UX Collective](https://uxdesign.cc/a-comprehensive-guide-to-notification-design-2fff67f08b7a)
## Best Practices for Error Messages
-   Error messages should be concise and direct and explain the problem vs. be a generic “An error has occured.”
  ![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/error-messages.png)
-   Avoid negative language that implied that the user did something wrong.
-   Provide in-context constructive error messages so that people can fix the issue as they go along.  Use inline validation for input fields on forms. Live error checking and clear messages enhance the UX.
- Don’t rely on just color. Avoid indicating an error just by turning the field red. It doesn’t make it accessible to people with disabilities. It’s always best to include other visual cues that the colorblind can see.
-   Error messages should not disappear until people have fixed the problem.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/error-message-order.png)
###### [Toptal](https://www.toptal.com/designers/ux/notification-design)

___

# Quiz

1. The following is a consideration for Notification Design:
	- level of severity
	- where and how it appears
	- what triggers the notification
	- all of the above (correct)
2. Alerts are a high-severity instance that requires immediate action.
	 - True (correct)
	 - False 

3. It is best practice to solely use red to indicate errors in inline validation on a form.
	- True
	- False (correct)

4. Designers are not responsible for push notifications because they are system-level and outside the app.
	- True
	- False (correct)

___



