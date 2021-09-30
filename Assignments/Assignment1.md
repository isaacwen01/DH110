# Accessiblity of Hawaiian Government Websites

## Assignment 1: Heuristic Evaluation

Isaac Wen | DH 110 | Fall 2021

### About the project:
This project aims to examine the accessibility and efficiency of Hawaiian government websites. Our government plays an important role in society, 
from taking actions on social issues to protecting our boundaries. Of course, our government also manages the way we go about our daily lives, 
including setting regulations on transportation and healthcare. Hawaii, for instance, has around 516,544 registered automobiles––all of these drivers
have had to interact with the DMV at one point. Healthcare, on the other hand, is even more of a necessity and for Hawaii's 1.4 million population, 
access to the right health resources and information is beyond crucial. For this reason, I specifically wanted to analyze the website for Vehicle 
Registration & Licensing and Hawaii State Department of Health to examine ways we could expedite the licensing process and make health-related 
news/resources more accessible for everyone.

### Jakob Nielson's [10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/) Explained
| Number | Heuristic | Description |
|---|---|---|
| 1 | Visibility of System Status | The system informs the user about what is going on. It indicates the status of the task and gives appropriate feedback. |
| 2 | Match Between System and the Real World | The system is intuitive and designed based on ideas and concepts familiar or logical to the user. |
| 3 | User Control and Freedom | The system allows the user to have control and use the site freely, including the ability to undo and redo. |
| 4 | Consistency and Standards | The system follows conventions in its design and makes sure its components are designed consistently across the platform. |
| 5 | Error Prevention | The system prevents error-prone conditions and offers safety-nets such as reminders or a confirmation notice. |
| 6 | Recognition Rather Than Recall | The system gives options to choose from or suggestions to reference. |
| 7 | Flexibility and Efficiency of Use | The system is designed flexibly so that there are multiple ways for the user to perform a task. |
| 8 | Aesthetic and Minimalist Design | The system contains only relevant information and its design components present the information in an uncluttered, useful way. |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | The system informs the user of errors and provides suggestions to resolve the issue. |
| 10 | Help and Documentation | The system has additional resources to help users complete their tasks. |

### [Severity Ratings](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) for Usability Problems by Nielsen Norman Group
Ratings are displayed in parentheses after each usability issue.
| Rating | Description |
|---|---|
| 1 | Cosmetic problem only: need not be fixed unless extra time is available on project |
| 2 | Minor usability problem: fixing this should be given low priority |
| 3 | Major usability problem: important to fix, so should be given high priority |



## Website 1: [Vehicle Registration & Licensing](https://www.hawaiicounty.gov/departments/finance/vehicle-registration-licensing)

<img width="1440" alt="HawaiiDMVWebsite" src="https://user-images.githubusercontent.com/82692970/135472147-505d26cb-1db6-456b-8cf1-d6cf32ad37f0.png">

### About
This website belongs to the County of Hawaii and offers tax services, employment information, tax maps, permits, etc. However, I’ll mainly be examining the Vehicle Registration and Licensing Division. The webpage covers information about VRL Office Appointments, Road Test Appointments, COVID-19 FAQs, and many other forms and documents that are crucial for vehicle registration and licensing.

### Initial Overall Evaluation
Overall, I’d say the website is very informative and detailed. It’s updated to include protocols for COVID-19. It colors important phrases, dates of updates, and useful links in red. On the page for VRL Office Appointments or Road Test Appointments, the procedures and requirements for making appointments are extremely detailed and thorough. However, the overall lack of buttons and visuals makes the information-dense web pages hard to read through. Furthermore, each page lacks an intentional layout––the text is structured into paragraph format without many breaks. This layout is uneasy on the eye and discourages the user from reading each page thoroughly.

#### 1. Visibility of System Status
* **Good**: The website highlights the sidebar item of the page the user is currently on. When booking a VRL Office Appointment, there are tabs in the center of the page to indicate which of the 3 stages––Choose Appointment, Your Info, and Confirmation––the user is in.
*  **Bad**: When scheduling a Road Test appointment, there is no clear indication as to which stage of the process the user is in. This makes it difficult for the user to gauge how much longer the scheduling process will take. (2)
> *Recommendation: Add a status bar to help the user recognize how far into the appointment-making process they are. The status bar could be split into four sections: “Schedule an Appointment,” “Your Info,” “Confirmation,” and “Make payment”.*

#### 2. Match Between System and the Real World
* **Good**: The sidebar items under the DMV website are organized in a logical manner. More complex items like “Driver Licensing––General Information” are broken down into subitems.
*  **Bad**: Some subitems can be a little intimidating and confusing for people who are unfamiliar with driving jargon, including people who are first-time drivers looking to apply for a permit or license. Terms like “Limited Purpose Instruction Permit” or even “Provisional Drivers License” may confuse users. (2)
> *Recommendation: Rename and group sidebar items to more general terms such as “Types of Permits & License” so that the users feel more comfortable navigating the website. After clicking into the renamed menu item, terms that may seem unfamiliar to first-time drivers should be explained and then added as dropdown menu items.*

#### 3. User Control and Freedom
* **Good**: The user can freely navigate through the site by clicking the backward or forward button in their web browser. If they use the search bar, their query will be saved as well.
*  **Bad**: When making a road test appointment, once the user fills out their info and clicks “continue the payment,” there is no way to return back to the first screen without losing all progress. This is rather inconvenient because people may want to double-check that they inputted the right permit number, re-confirm the date of the appointment, etc. (2)
> *Recommendation: Redesign the form so that the user’s answers are saved/still accessible when moving back and forth between the different stages of the appointment-making process. It would also be useful to have a confirmation screen either before or as a split-screen during the payment review. This makes it easier for the user to check if they input the correct information without losing any progress.*


#### 4. Consistency and Standards
* **Good**: Hyperlinks are made distinct from the rest of the text through coloring and underline. Important phrases are bolded in color.
* **Bad**: People usually look for buttons to make appointments, or some other type of distinction so they can recognize the call to action. To make an appointment, the user has to scroll through the page to find a link titled “appointment” among the many other hyperlinks underlined/colored in red. This does not match industry conventions. (3)
> *Recommendation: Create a separate button for making appointments.*
*  **Bad**: The forms for making appointments for the VRL office and Road Test look drastically different [see Visibility of System Status for direct comparison]. (2)
> *Recommendation: Redesign the form for booking a road test to emulate the style of the page for making VRL office appointments.*  

#### 5. Error Prevention
* **Good**: On content only, the website thoroughly details the process for making VRL and Road Test appointments. Also, when making a Road test appointment, the system does not allow the user to move on unless they confirm an open time slot.
* **Bad**: When inputting the Permit Number and Behind the Wheel Certificate Number, the system does not check if the number of digits and formatting meet the permit/certificate numbering conventions of Hawaii. Similarly, there is also nothing that checks whether the inputted email address is real. (3)
> *Recommendation: Offer an example for formatting the permit/certificate number as well as some secondary checking system that catches inputs that are not of a valid format.*  

#### 6. Recognition Rather Than Recall
* **Good**: When the user scrolls down from the landing page and clicks on the magnifying glass icon, there are helpful filters like “jobs” and “vehicle registration”. 
* **Bad**: When using the search function, no suggestions show up under the search bar. This makes it difficult for the user who may not remember the exact name of the type of permit they’re trying to apply for or appointment they’re trying to make. Furthermore, there is also a serious inconsistency where the filters only show up when you click the magnifying glass icon (after scrolling down) and not when you click into the search bar. (2)
> *Recommendation: Show suggestions and results as the user is typing to help the user recognize terms that they want to search but perhaps do not know the exact name of.*  

#### 7. Flexibility and Efficiency of Use
* **Bad**: The search filters are rather broad and aren’t super useful for users who are more familiar with the DMV or know exactly what information they need from the site. (1)
> *Recommendation: Incorporate more specific search filters or provide search suggestions that directly take the user to the desired page without hitting the search icon/enter key.*  

#### 8. Aesthetic and Minimalist Design
* **Good**: The site has buttons that allow the user to customize the font size of each page they visit. This is great accessible design, especially for users who have impaired vision.
* **Bad**: The website lacks a clear layout. Each page is understandably information-dense, but the website does nothing to break up the long paragraphs of text, making the entire page resemble some sort of essay. (3)
> *Recommendation: Create more distinct separations between sections of the page to help with readability. Each page can also feature multiple layouts. For instance, a section could have text on the left side and a visual on the right side. Certain sections like the “Safety Requirements” could be translated into an infographic to reduce the user’s cognitive load. Longer paragraphs can also be rewritten into bullet format for easier reading.* 
* **Bad**: The lack of buttons makes each page’s call to action unclear, especially because there are multiple hyperlinks. A user trying to book an appointment has to sift through all the links underlined in red before locating the correct one. (3)
> *Recommendation: Add buttons in place of the most important links to indicate a clearer CTA as well as introduce some sort of hierarchy to the page.*  

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* **Good**: When booking an appointment, the system notifies the user when an invalid phone number or email is entered. 
* **Bad**: When choosing a date for a Road Test Appointment, the user is not notified when the next available date and time is. If most dates are already booked at a certain location, the user will have to toggle through each date to see which times are available. This is incredibly inconvenient and time-consuming for the user. (2)
> *Recommendation: Implement an option or button that will take the user to the next available date/time if all of the listed dates on the current calendar page are booked.*  

#### 10. Help and Documentation
* **Bad**: There is no FAQ section for the entire site nor a FAQ section specific to the DMV. If the user searches FAQ, only pdf files with hyperspecific topics like “FAQ-InnovationGrants-FY21-22” show up, which would not be helpful to the average user trying to make an appointment at the DMV. (3)
> *Recommendation: Introduce two FAQ sections––one for the entire website attached in the footer and one specific to the Vehicle Registration & Licensing Division, accessible through the sidebar.*  



## Website 2: [Hawaii State Department of Health](https://health.hawaii.gov/)

### About
The Hawaii State Department of Health website covers the latest health-related news and guides users to important health resources relating to aging & disability programs, environmental health, mental illness, and more. Furthermore, the website is also linked to Hawaii’s COVID-19 portal and offers additional services like ordering birth and marriage certificates, marriage licenses, and health records.

### Initial Overall Evaluation
Overall, the website is clean and straightforward. The navigation bar is appropriately categorized into logical bins. From the submenu length to the layout of news articles, the website is uncluttered despite the vast amount of information it hosts. However, there are pretty noticeable consistency issues when you click the various links. Each form looks drastically different and consists of varying visual components that may potentially confuse a user completing multiple tasks. There are also some issues with interactivity, specifically with the hover effect, that makes the website less intuitive to use.

#### 1. Visibility of System Status
*  **Bad**: The navigation bar does not indicate which page the user is currently viewing. There is no visual signal to display where the page belongs, which may confuse the user when they are navigating back and forth between pages. (2)
> *Recommendation: Add a visual signal, such as a colored underline or a colored background for the navigation bar item the current page belongs to.*
*  **Bad**: When filling out forms such as the “Marriage/Civil Union License Application,” there is no progress bar to indicate how far into the application the user is. (1)
> *Recommendation: Add a progress bar that fills up as the user moves along the application.*

#### 2. Match Between System and the Real World
* **Good**: The website employs user-friendly vocabulary to name the components of the navigation bar and buttons.
*  **Bad**: Normally, if a navigation bar has an item with a submenu, directly clicking the item will lead the user to the first page on the submenu. However, clicking the navigation bar items that have submenus like “About DOH” and “News” does not do anything. (2)
> *Recommendation: Link the items on the navigation bar to the first page of the submenu for easier access.*

#### 3. User Control and Freedom
* **Good**: The user can freely navigate through the site by clicking the backward or forward button in their web browser. 
*  **Bad**: When filling out the Marriage License Application, there is no “previous” button that allows the user to go back and edit information. There are only the “save and continue” button and “cancel” button, with the latter completely erasing all filled-out cells on previous pages. (2)
> *Recommendation: Change the two buttons to “Previous” on the left and “Next” on the right. Introduce a system of auto-saving to expedite the lengthy application progress and streamline the user journey.*

#### 4. Consistency and Standards
* **Good**: The news articles are formatted in accordance to  feels very familiar to the user.
* **Bad**:  Not all pages of the site display the path the user took to that specific page. For example, the “Office of the Director” page includes “Home » Office of the Director” at the top of the page, but not the “Strategic Plan” page. (1)
> *Recommendation: Make sure all pages include pathnames so the user can traverse pages effortlessly, even without the forward and backward buttons of their web browser.*

#### 5. Error Prevention
* **Good**: On the Marriage License Application, there are clear instructions regarding formatting the free response questions and dropdown selections.
* **Bad**: On the WIC application form, there are no visual indications that inform the user of required fields that might prevent them from moving on if left unfilled. This lack of signaling may be annoying for the user, especially if they are trying to fill out the application quickly. However, because the user does not know which fields are mandatory to fill out, they would have to fill out all fields or selectively answer questions they believe are mandatory, but risk being stopped by the system (if a mandatory field is left unfilled). (2)
> *Recommendation: Place a red asterisk next to the required fields so the user can immediately recognize which questions are the most important.*  

#### 6. Recognition Rather Than Recall
* **Good**:The navigation bar items and the various submenus are effective in aiding users to recognize specific health topics they are interested in.
* **Bad**: The search bar does not have any search filters or dropdown suggestions, increasing the user’s cognitive load when they do not have a specific topic in mind. (2)
> *Recommendation: Introduce search filters on the search results page that can help the user sort results based on categories. Have suggestions drop down from the search bar as the user types.*

#### 7. Flexibility and Efficiency of Use
* **Bad**: If the user already knows what program, resource, or topic they want to search, there is no shortcut to reach their desired destination. For instance, if they wanted to learn more about Medical Reserve Corps, they would have to click Health Topics > Emergency Preparedness & Response > Medical Reserve Corps. (1)
> *Recommendation: Have more submenus for each item on the navigation bar so more prepared users can easily jump to the page they want to read. Alternatively, the search bar feature can also match the user’s input while they are typing to the closest page; by clicking the suggestion provided by the search function, the user would be able to directly enter their desired page.*  

#### 8. Aesthetic and Minimalist Design
* **Good**: Overall, the website is clean and easy to read. Hyperlinks are underlined in blue and there is enough spacing between longer reads to prevent the user from feeling overwhelmed. 
* **Bad**: For news articles, the layout of the text is rather dry––everything is either in bullet or paragraph format with not much variation. (1)
> *Recommendation: Add a cover photo for each article as well as other images to aid with comprehension.* 
* **Bad**: There are a lot of links and pages nested within each other, especially on the Health Topics page. It may be easy for the user to lose track of where on the page they are or which specific link they are looking for.
> *Recommendation: Add appropriate icons to help the user recognize each of the main categories more easily.*  

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* **Bad**: Bad: 404 Error page simply tells the user that the original page might have been taken down and does not offer anything else to help the user. (1)
> *Recommendation: Add an option on the 404 Error page to report the err to customer service or provide possible general solutions to the problem.*  

#### 10. Help and Documentation
* **Bad**: There is no FAQ section for the entire site. If the user searches “help” using the search bar, only articles mentioning the word “help” and mental health resources show up. (3)
> *Recommendation: Include a FAQ section and/or a help icon in the footer for easy access.* 

