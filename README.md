# uxBible
Best Practices to follow for having a great user experience in your software

### User Experience
How a person feels about interacting with my application
OR More appropriately put
The measure of friction between a user and their goal
(Cognitive, Emotional Physical)

### Desired Result
Happy Satisfied Productive

Measure cognitive friction whenever making UX changes

### Things that can adverse affect(increase) cognitive friction.
- How much visual noise does the screen have?
For example do you really need fancy headers, screen titles, logos, lots of visible meanus (Horizontal or vertical)

- Showing all fields by default. 
Users generally need very few fields to get the job done. Now they are wasting their energy to find where are their desired fields. 
They are doing a lot of scrolling.
Each time a user scrolls, the brain has to reprocess all the information and then try to find out what they want is there.

- Navigation helpers are generally mostly ignored.

- Save button not visible
Users had to scroll to find out where is the save button.
Now you know why Google Docs have auto save.


## BECOME a UX Hacker

### User Cantered thinking
### UX Professionals research
- Who the user is
- What the user needs (not wants)
- Create a design that delivers great user experience based on research
- Put the user at the center of every decision you make
- We are not the user
- Does the decision I make benefit the user or me ?

### Identify and confront biases
- 104+ cognitive biases, check out RSOAP, a visual study guide to Cognitive Biases
- Biases shape our thinking and decision making
- They can derail our efforts on UX
- It is very important ot identify and confront our own biases

### 7 Bad developer biases

- Bias Blind Spot
Not compensating for one's own cognitive bias. You can knock this over if you acknowledge that you have biases.

- Professional Bias
The tendency to look at things according to conventions of one's own profession. While putting your solutions use more terminology that general users understand rather than your own technical jargons.

- Semmelweis Reflex
The tendency to reject new evidence that contradicts an established paradigm. Have an open mind to new ideas and suggestions in order to get away from this reflex.

- Bandwagon effect
The tendency to do things because many other people do the same. Through forums or communities senior developers actually influence many people at once. Always ask why in order to get away from this bias.

- Confirmation Bias
The tendency to search for or interpret information in a way that confirms one's preconceptions. This comes when you have strong opinion about something and then you search for and filter information based on what you believe. It is ok to admit that we have our own opinions and ideas, but you should be open to evaluate other ideas.

- Status Quo Bias
The tendency for people to like things to stay relatively the same. Key to overcome this is to step out of your comfort zone and look to what is outside.

- Reactance
The urge to do opposite of what someone wants you to do. Because of a perception of losing control.



### Who are we?
- We are developers.
- We are problem solvers by nature.
- We solve technical puzzles.
- We see the world differently.
- We see only the tech and ignore the human part

### Changing our behavior
- Changing behavior can be hard but possible
- Coding for a new platform
- Human Brain
- Better decisions
- Avoid Common traps

### Common Mistakes
- Throwing Data on the screen (Doing what's easier for us and not what's best for user). User is interested in information and not pile of data you throw around.

- Exposing Technology jargons to the user (Not using regular english). Always use human friendly language and terminology that end user understands.

- Forcing user to think like database administrators. Talking about transactions, commits and other technical terms.

- Messy UI - Using excuse that I am not good at UI.

- Being inconsistent (Calling one button save and in another screen calling it submit), having varying margins, non aligned form fields.

- Coding for the Expert User (Avoid the hard work of making something easy to use by using expert user excuse)

- Coding for edge cases (Working to solve non existent problems)


### Top UX Myths


- **Myth (1) Counting clicks** -> User never should have to click more than x number of times in order to perform a task.

- Reality -> Users do not have a click counter in their mind. They will click as long as the cognitive friction is low & they are getting closer to their task accomplishment.

- Clicks matter in highly repeatable tasks. But they should be taken care by automation.

- **Myth (2) Whitespace is wasted space** -> User need to be shown as much data as possible. 

- Reality -> User just needs to be shown the information that he needs rather than being bombarded with all the info. Don't make stuff for your mythical power user. Whitespace helps lower cognitive friction, helps the brain process screen more quickly. It helps visual grouping.

- **Myth (3) Scrolling is evil** ->  

- Reality -> User tests show vertical scrolling is not a big deal. Even users that say they hate to scroll do it. But we very careful on horizontal scrolling. 

- **Myth (4) Small details don't matter**  -> If it is good enough and functionality is working as expected just ship it.

- Reality -> Small details can dramatically improve UX. One example is of BestBuy, they changed Register button to Continue button and their sales improved by $300 million in a year. That button is famously called $300 million button. Quality has a skin deep effect on brain.

- **Myth (5) More Choices**  -> Users may want to do this/that. Power users want everything.

- Reality -> More choices present more roadblocks to the users. Choices increase cognitive friction. It slows user down and make UI harder to learn. Users will often say yes to more choices. But as developer you have to be intelligent in stop offering those and give them one 
really good way to do something.

- **Myth (6) Users make good choices** -> Users know what they need. They'll select right option.

- Reality -> Most decision making is subconscious. Multiple choices paralyze thought process. Then all guess work starts. Low cognitive friction can help influence good choices.

- **Myth (7) Users know what they want** -> Customer is king. They drive features and requirements.

- Reality -> Want != NEED. Users will often request more than what their brains can handle. People are horrible at estimate feature values. Customers need not be treated as Kings but Children.  Find out user's goal in order to idenify their ultimate need.

- **Myth (8) Usability is greater than Beauty** -> Users just care if it's usable. They don't care what it looks like.

- Reality -> Users judge initial quality of an app by it's appearance. Users may abandon them before discovering the good stuff. Good
visual design lowers emotional friction which improves overall UX. Perception is reality in this case.

- **Myth (9) Let's do it like  Apple, Microsoft, Google, etc** 

- Reality -> Amazon's menu system may not be appropriate for your timesheet application. Don't blindly follow someone else and think loudly 
about your application.  But it makes sense to match others if you are integrating into their platform.  It is important to use UX
and UI conventions of Apple, Google and Microsoft for Mobile apps. You should read and follow their guidelines.

- **Myth (10) UX is a project step** -> The code is done. Let's "UX" the UI and ship it.

- Reality -> Improving the user experience is a continual and iterative process. The earlier you start in development process, the better the results are.  Try incremental improvement of user experience.

## Hacking the User's Experience

We would be targeting incremental user experience improvement here. The goal is to lower cognitive friction.

1. **SHAPES HACK** - Let's make our UIs easy for the brain to de construct, by using shapes. 
 - The brain loves easy to see shapes.
 - Central vision is a high brain CPU resource.
 - Peripheral vision is a low brain CPU resource.
 - If user has to visually scan our UI to understand it, the cognitive friction would be high.  ![alt text](https://github.com/anilpank/uxBible/blob/master/img/badshapes.PNG "UI needing lot of visual scanning")


 - If user's brain can break our UI down to big shapes, the cognitive friction would be LOW. ![alt text](https://github.com/anilpank/uxBible/blob/master/img/GoodShape.PNG "UI using big Shapes")
 

2. **WHITESPACE HACK** - Let's allow our user brains some respite by using whitespace. Whitespace is the place where brain gets some rest from scanning.

 - A crowded UI requires your user's brain to use central vision which makes cognitive friction very high.
 - Using whitespace allows your user's brain to use peripheral vision which helps make cognitive friction very low.
 - It helps user focus on important information.
 
3. **GROUPING HACK** - Let's make our UIs easier to understand by grouping elements more effectively. User's brain loves anything structured.
 - User's brain loves groups.
 - Grouping, whitespace and shapes hack all work together.
 - Crowded groups that are too close together require central vision of user's brain and make cognitive friction very high.
 - Repeating groups without enough visual separation makes cognitive friction high.
 - Whitespace within and between groups allows user brain to user peripheral vision which helps make cognitive friction low.

4. **ALIGNMENT HACK** -> Non aligned UI elements are slient UX killers.
 - Misalignment can make cognitive friction very high.
 - The brain detects even small misalignments.
 - There are multiple alignment options available. Choose one and be consistent across all your pages.
 - Align with reading direction (left aligned with English, right aligned with Hebrew, etc).
 - You can create alignment scopes by whitespacing and grouping. 
 - Use center center trick in case of central alignment. For example for a central aligned button, button text should be in center of button.
 
 
5. **Attention Hack** -> Make our UI attract user's attention.
 - Change blindness issues are very common. Users are so focussed through their central vision, they don't notice that something in UI has changed.
 - When applying a change, do something to gain user's attention, like making text in bold, having borders around the changed area and so on.
 - But if the user needs to focus on a specific goal, then you should eliminate any distraction on peripheral vision.
 - Movement in peripheral vision is very powerful but it has to be used wisely.
 - If the user focus is needed, movement in peripheral vision will distract, so keep the UI calm.
 - If user's attention is needed, then use peripheral movement to get attention.
 - Signal important changes using subtle animations.
 - Turn off animated ads and live data streams to keep user focus.
 
 
 