# Accessiblity of Hawaiian Government Websites

## Assignment 7: High Fidelity Prototype
Isaac Wen | DH 110 | Fall 2021

## Useful Links


## Overview
### Summary
This interactive high fidelity prototype is a redesign of the County of Hawai’i and specifically its Vehicle Registration & Licensing Department. 
The prototype aims to make information about applying for or renewing a Hawai’i permit/license easier to digest and streamline the appointment-booking process.

### Process
I used Figma to create this prototype and based the design on my lo-fi prototype and interface design from previous assignments. I created two hi-fi 
prototypes. After the first iteration, I conducted a couple of cognitive walkthroughs and usability tests to determine what needed to be fixed and made a 
revised, second hi-fi prototype accordingly.

### Purpose
The purpose of this interactive prototype is to test both the interface and functionality of the redesigned County of Hawai’i website. It evaluates whether or not it is easy for the user to complete tasks, use the proposed feature, and follow the intended interaction flow.


## Tasks
This interactive prototype supports 3 tasks:
1. Learning about the process of applying for an instruction permit
2. Booking an appointment for an instruction permit/written test
3. Access the help page for license renewal


## Wireflow w/ final interface design
For clarity and readability, I separated the flow by task:

### Task 1 Flow:
![Task 1 Flow](https://github.com/isaacwen01/DH110/blob/main/Assignments/A07/Task%201%20Flow.png)


### Task 2 Flow:
![Task 2 Flow](https://github.com/isaacwen01/DH110/blob/main/Assignments/A07/Task%202%20Flow.png)
*Note that the flow lines of the back arrows for the appointment-booking screens are intentionally left out in this prototype as clicking them would make the user lose their progress.*


### Task 3 Flow:
![Task 3 Flow](https://github.com/isaacwen01/DH110/blob/main/Assignments/A07/Task%203%20Flow.png)


## Full Wireflow:
Click the following link to access the [full wireflow](https://www.figma.com/file/FiP5xIDKEKWrtnXJAAugWU/DH-110-Project?node-id=213%3A15634)


## Prototype 1 (1st Iteration):
[Access Prototype 1](https://www.figma.com/file/FiP5xIDKEKWrtnXJAAugWU/DH-110-Project?node-id=129%3A960)

For this iteration of prototyping, I actually used screen designs that resembled more of my lo-fi prototype. Key traits of this design system include 
rectangular buttons, which aim to establish a more professional feel to the site. However, I quickly noticed some issues after conducting cognitive 
walkthroughs and usability tests.


## Cognitive Walkthrough & Usability Tests

## Cognitive Walkthrough:
[Access Data](https://docs.google.com/spreadsheets/d/15HXr6no3cgMHEjqRma5v7XQxy8vVqJVEQpGMI2l1gDA/edit?usp=sharing)

Overall, I think the cognitive walkthrough went smoothly. To my delight, my two testers were able to easily follow the intended interaction flow, easily completing the 3 proposed tasks. They appreciated the minimalist and straightforward interface design and thought most pages and buttons were clearly labeled. 

However, they did point out some areas of improvement:
On the “Permit & License Information” page, the tester indicated that she did not know what to click––the icon or the text. She assumed that the text would be clickable as well, not just the icon.
Proposed Revision: Adding a separate button and converting the icon into a decorative element
The tester struggled with returning to the home page and was confused by some of the back/previous buttons.
Proposed Revision: Making the “County of Hawai’i” icon a button that leads back to the home page

## Usability Tests:
In addition to the cognitive walkthroughs, I conducted more thorough usability tests to further pinpoint the most pressing issues with my first prototype.
[UT 1](https://drive.google.com/file/d/1Yd5SM7ljVbs4LsvQaUd9k8Y4E6J-q2FV/view?usp=sharing)
[UT 2](https://drive.google.com/file/d/14fCDqkEHyfmko2HS9EKUh2M1nBCFlGBB/view?usp=sharing)

Overall, the usability tests went very smoothly and the testers’ overall reactions post-test were positive. They appreciated the straightforward interaction flow and minimalistic design. Most, if not all, tasks took shorter than expected and both testers associated the website with the adjectives “professional”, “familiar”, “calm”, and “trustworthy”.

Nonetheless, the usability tests reaffirmed some of the problems that were noticed during the cognitive walkthrough. The overall lack of backflow and some minor button inconsistencies confused my testers. Aside from the aforementioned issues, there were some other issues that were brought up:
Text is slightly hard to read: since there’s a lot of reading to do, especially in the “Process” section, the small font size is a little hard to read.
Proposed Revision: Changing the font back to Europa, as Europa sized 16 is slightly larger and bolder than Futura sized 16. Adding more space between subheaders and body text will also help with readability.
Confusing Appointment-Booking Screen: the tester thought that they were asked twice about what type of appointment they wanted to make––once at the beginning (before selecting the date) and once when filling out their personal information. Technically, the second question asks the user what class vehicle (moped, motorcycle, passenger vehicle) they want to apply for, but the question was phrased ambiguously, leading to confusion.
Proposed Revision: Changing the field name to “Type of Vehicle” instead of “Type of Permit” to avoid ambiguity.


## Prototype 2 (Revision):

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FFiP5xIDKEKWrtnXJAAugWU%2FDH-110-Project%3Fnode-id%3D179%253A1110%26scaling%3Dscale-down%26page-id%3D179%253A1087%26starting-point-node-id%3D179%253A1110" allowfullscreen></iframe>


[Access Prototype 2](https://www.figma.com/file/FiP5xIDKEKWrtnXJAAugWU/DH-110-Project?node-id=196%3A12887)
*Again, the back arrows of the browser (not the prev buttons on the website itself) for the appointment-booking screens are not activated in this prototype. This is to prevent the user from losing progress on their appointment-booking form.*

This prototype introduced many revisions.

### General Changes:
1. Interface Design: I reverted my interface design to the final version I submitted for assignment 6, characterized by round buttons and the font Europa. The round buttons created a more “familiar” and “welcoming” feel for the site and the font matches the pre-existing brand assets better. I made minor edits here and there to create more variety for font sizes and colors. All changes are updated in Figma’s design system.
2. Smoother Transitions: To create a smoother interaction flow, I refined some of the transitions, including preserving the scroll position.

### Problem-Specific
1. Standardized Clickable Items/Buttons:
> Problem: On the “Permit & Licensing General Information page”, the user got confused about whether they should click the text or icon.
> Solution: I made the icons decorative by removing the colored padding that would otherwise mislead the user into thinking it is a button. I then added a separate button below the subheader that would prompt the user to click it.
2. Home Button:
> Problem: There is no easy way to return to the home screen.
> Solution: I linked the “County of Hawai’i” logo to the home screen, effectively making it a home button since the logo is on every single screen.
3. Added Spacing & Changed Font:
> Problem: Some of the chunks of texts were harder to read, especially on the “The Process” pages.
> Solution: I didn’t increase the font size as that would lead to excessive scrolling. Instead, I reverted back to using Europa as my main font as Europa sized 16 is larger and bolder than Futura sized 16. Referencing the gestalt principles, I added extra spacing between different sections to help the user group related categories of information more easily. Lastly, I changed the font color to black to increase contrast.
4. Rephrasing questions on the appointment-scheduling form:
> Problem: Users were asked the “type of permit” they were applying to twice. The second question is actually referring to the type of vehicle class they’re interested in applying for.
> Solution: I rephrased the question into “Type of Vehicle '' with a dropdown button so the user can clearly tell that the question is referring to vehicle class and not type of permit again. 
