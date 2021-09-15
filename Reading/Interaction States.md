# Interaction States
Successful interaction states inform the status of an element in the interface, communicate action taken, and suggest the ability (or inability) to interact with the component. Treating these interaction states consistently makes them recognizable patterns and reduces cognitive load.
## Don’t decorate or add noise
Avoid elaborate transitions that create visual noise or intense color changes. Distracting animation can create disturbance and make an interface unpleasant to use.
## Consider input devices
Keep in mind that interactions are different depending on which input device used. Devices users may use include:
-   Mouse
-   Touch screen
-   Keyboard
-   Voice
-   Game controller
-   Refreshable braille display
## Use signifiers
Signifiers provide cues as to what the interface will do if the user interacts with it. It creates a more intuitive interface that’s easier to use. The types of signifiers include:
1. **Explicit**, where content directs merchants to do the intended action, such as “Sort” or “Save.”
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/save-as.png)
###### [Collab Space](https://collabspace.zendesk.com/hc/en-us/articles/115001191753-How-to-Save-a-Search)

2. **Hidden or Ghost buttons**, where the clue isn’t revealed until the user interacts with it, such as hovering or using tab navigation to see if a button is clickable.
3. **Negative**, where the action appears inactive or disabled (like the button is grayed out and doesn’t respond to hover) because it isn’t available for the merchant to use.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/button-states.png)
###### [Abhimanyu Rana via Collect UI](https://collectui.com/designers/planetabhi/button)
## Behavior
1. Use **feedback indicators** like the progress bar component or the spinner component to let them know that the interface received their request. If appropriate, you can also provide added information about what or how long it will take to complete.

![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/progress-indicator.png)
###### [UX Planet](https://uxplanet.org/a-guide-to-creating-accurate-progress-indicators-in-adobe-xd-72a43b46889d)

2.  For **non-disruptive feedback** on the outcome of an action, use the toast component.
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/toast-component.png)
######  [UX Planet](https://uxplanet.org/toast-notification-or-dialog-box-ae32ad53106d)
For an **unsuccessful completion** that requires the merchant to take action, provide information about what prevented the action from completing successfully and what the merchant can do to fix the problem. For example, use the validation error state of the text field component.
![](https://prodesigncurriculum.s3.us-east-2.amazonaws.com/validation-text.png)
######  [Stack Overflow](https://stackoverflow.com/questions/58033726/how-show-basic-validation-messages-in-the-text-field)
___

# Quiz
1. Treating interaction states consistently makes them recognizable patterns and reduces cognitive load.
	- True (correct)
	- False 

2. Signifiers are important to
	- provide cues as to what the interface will do if the user interacts with it
	- create a more intuitive interface that’s easier to use
	- suggest the ability (or inability) to interact with the component
	- all of the above (correct)

3. If you don't disrupt the user behavior with attention-seeking noise, there be no impact on their actions.
	- True
	- False(correct)

4. Feedback indicators add anxiety to the user and increases cognitive load
	- True
	- False (correct)

___