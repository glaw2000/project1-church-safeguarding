

# Church Safeguarding
Welcome to the README for a standalone webpage on Safeguarding information for a local church parish. This page has been built using HTML and CSS. This is my first project built for the Code Institute's Full Stack Software Development course.

My page can be viewed here on github:


## User Experience - User Stories

- As a member of the parish I want to know what the churchs safeguarding policy is so that I understand how the church protects its parish. 
- As a member of the parish I want to know how to get safeguarding advice so that I can report a concern. 
- As a member of the parish I want to know who to contact so that I can get safeguarding support.
- As an organisation we want to incorporate and refer to the Church of England (CoE) safeguarding guidance so that we are in alignment with the CoE safeguarding.
- As an organisation we want to incorporate and refer to Diocese of Blackburn safeguarding guidance so that we are in alignment with the Diocese of Blackburn safeguarding.
- As an organisation we want to provide clear easy to access safeguarding information so that anyone can find out about how the church safeguards its people.
- As an organisation we want to provide contact information so that parishioners can raise concerns where necessary.
- As an organisation we want to provide contact information so that parishioners can get safeguarding support where needed.
- As an organisation we want to provide a complaints procedure  so that parishioners can log complaints about church safeguarding if necessary.
- As an organisation we want to ensure all church leaders are trained in safeguarding so that they can adhere to church safeguarding.
- As a church leader ( choir master/ sunday school teacher etc ) I want to know how to learn/train about safeguarding so that I adhere to the churchs safeguarding
guidelines
- As a church leader ( choir master/ sunday school teacher etc ) I want to know how to keep my safeguarding training up to date so that I adhere to the churchs safeguarding
guidelines


------
## Development Plane Considerations
### Strategy
The aim of the page is to build a single static webpage using html and css to provide safeguarding information to anyone involved in the church. 

### Scope
The page will
1. provide information for all about what safeguarding is
2. provide information for all about how the church safeguards its parish
3. provide information for all on how to raise a concern
4. provide information for all on how to get advice and support
5. have an option so that users can get in touch 

### Structural
The page should:

1. have a logo
2. have a nav bar
3. have recognisable icons for social media links
4. have a clear header and footer section
5. have a simple but attractive layout of the body that is not too busy but gives the user all the information they need or a way of getting to it. 
6. be repsonsive to different screen sizes 
7. have an intuitive layout that all can navigate with ease
8. have the most important information at the top of the page


### Skeleton
1. A header and footer will sandwich the content 
2. Using the principle of 3s for design layout the content will be split up into 3 horizontal sections to contain the main topics of information of About Safeguarding, How to repoond and Further Information.
3. The layout will be balanced by placing images alternatively left to right within the three sections.
4. Familiar icons for social media links will be used  

Wireframe for mobile, created using balsamiq

### Surface
1. Colours will be used to tie together the header, content and footer
2. A minimum colour pallette will be used to provide an easy to view accessible site

---
## Design
 Using Coolers I picked my colour theme but starting with the burgandy in the colour picker as this is the existing colour used on the church logo.
 I used a contrast checker on a practice repo where I set the colours up to ensure they passed for accessibilty. 

 Typography
 I went with a standard sans serif I'd seen used in previous code institute projects to start with and if time allows I will look into different options from google fonts.

Used free imagery fron pexels and existing church logo.

Page features will include a basic get in touch form, clickable links to further information and icons for social media links.

## Roadmap and future features
Ideas for releases in the future:
Add a hero image to fill width of screen below the Emergency message - church candle imagery.
Improve typography
Include a option for complaints
Format the tables better
Format the text around the images to have a better use of white space when viewed on large screens.
Use hover over links rather than traditional underlined hyperlinks.
Reduce height of footer by making the contact form a pop up rather than a static form.
Add more information to the footer. 

## **Technologies & Programs Used** 
- HTML5
- CSS3

- balsamiq - used to produce wireframes and background vector artwork 
- GitHub - used to save and store all files for this website  
- Git - used for version control
- Google Fonts - fonts were imported from here 
- pexels - images were downloaded from here  
- Convertio - to convert PNG files to WEBP files
- Favicon.io - for compressing logo into a favicon  
- - Google Dev Tools - to debug and for testing responsiveness 
- Google Lighthouse - for auditing the website
- W3C Validator - for validating the HTML and CSS code 
- stackoverflow - questions eg left-aligning-tables-with-css
- general google queries
- wave - evaluate accessibility


## Installation


### **How to deploy**  

GitHub was used to deploy the website. These were the steps taken to achieve this:  

1. Login to GitHub account.
2. Navigate to the project repository, put name here
3. Click the Settings button near the top of the page.
4. In the left-hand menu, find and click on the Pages button.
5. In the Source section, choose 'main' from the drop-down, and select branch menu.
6. Select 'root' from the drop-down folder menu.
7. Click 'Save' and after a few moments the project will have been made live and a link is visible at the top of the page.

<br>

### **How to run this project locally**  

To clone this project from GitHub:  

1. Visit the put link title here in sq brckets followed by url in round
2. Click on the <b>Code</b> dropdown menu located beside the green <b>GitPod</b> button. 
3. Choosing your preferred cloning option of <b>HTTPS, SSH</b> or <b>GitHub CLI</b>, click on the clipboard icon to copy the displayed URL. 
4. Open the terminal in your code editor and change the working directory to the location that you wish to use for the cloned directory.
5. Type 'git clone' into the terminal, paste your copied link, and press enter.

<br>  

### **To fork the repository on GitHub** 
  
To make a copy of this GitHub repository that allows you to view the content and make changes without affecting the original repository, please take the following steps:
  
1. Login to <b>GitHub</b> and find repo name and url
2. Locate the <b>Fork</b> button on the top, right hand side of the page.
3. Click on the <b>Fork</b> button to create a copy of the repository in your GitHub account.

## Testing


Tested using chrome browser. Future work would be to test with Edge and Firefox. 
 
Did not have apple safari to test with.

Tested all internal links on page worked and menu navigation items. Pass.
Tested social media icons took user to right page. Pass.
Tested layout was responsive using devtools. Pass.
Tested form gave user expected repsonse when completed with expected input. Pass.
Tested form gave message to user and did not submit if they had missed entering input into a required field or put the email address in the wrong format. Pass.
Tested performance using devtools Lighthouse tool. Pass.
Tested accessibility using WAVE. Pass.


Bugs Feature status fix details here:
Table overflow was a bug initially until it was fixed using table-layout fixed value and setting width to 100%.
Main 3 content divs were overflowing on some views. Fixed by removing the width setting.
Added feature to return user to the top from the bottom of each section.
Changed alt of compass in hand image to satisfy WAVE tool.
Removed unordered lists from within paragraph tags to satify W3C validator.
Modified a table from 4 columns to 3 to satisfy validator.
Removed multiple erroneous /tr tags. 
Removed button code from top anchor tag.


Devtools - responsiveness
See docs for accessibility evaluation report (WAVE)
See docs for performanace check (lighthouse report)

### Validation
W3C html validator results
W3C css validator results

## Credits
### **Content References**
Used Amy's Irish Wildlife Matchup repo ReadMe as a bit of template and copied some of the relevant content.
Used content on church safeguarding from the following sites:
- 
- https://www.churchofengland.org/safeguarding
- https://www.blackburn.anglican.org/safeguarding
- https://ubwby.org/safeguarding/
- https://www.lancashire.gov.uk/health-and-social-care/
- https://www.ncvo.org.uk/help-and-guidance/safeguarding/getting-started-with-safeguarding/what-is-safeguarding/#/further-resources-to-get-you-started
-  https://thirtyoneeight.org/


---