# MILESTONE PROJECT - 1 
  
Personal Portfolio Alexandre Gregorio,

A comprehensive portfolio website for a job seeker based in Dublin. This portfolio features an on-line CV with a profile greetings, personal information, about me section, 
who I am section, contact details, network links, download cv link, hamburger button, and a contact form page. This portfolio aim is to lead potential recruiters to make contact
after the portfolio presentation. 


## UX 

#### This portfolio aims are: 

* Demonstrate the candidate's enthusiasm for learning to develop new professional skills;
* Obtain a position as an Entry-Level Web Developer;
* Build a long-term career for growth and to keep up with great enthusiasm.


#### The ideal recruiters for this candidate are: 

* Flexible for contracting an entry-level candidate;
* Available to provide training and mentoring sections;
* Focused on candidate work experience in other sectors.


#### This portfolio introduces a candidate that could be a good fit for the companies as: 

* The candidate has the experience to lead with internal and external customers would be a good match for an entry-level candidate;
* A mature student would demonstrate a willingness to compromise in a new career;
* Flexibility to adapt to new tasks and develop new skills.


#### Stakeholders stories:

* As a recruiter, I want to learn about the candidate, so I can feel if I would contact him for the available position.
* As a recruiter, I want to see how the candidate manages the development tools.
* As a recruiter, I want to check the candidate's work experience. 
* As a recruiter, I would like to see if the candidate would start as an entry-level in a new career.
* As a recruiter, I want to verify the candidate networking links to see if the candidate has already been involved in any other projects. 
* As a visitor, I want to easily navigate throughout the website.


#### Wireframes

The layout placement and how they interact with one another goes through many stages, from conception to mockups to finalized UI is based on a responsive view.

The pages are developed and designed on their content at the structural level having commonly used layouts content and functionality which takes into account user needs and user 
journeys.

I have thought early in the project, in the development process to establish the basic structure of a page before visual design and content is added.

##### Desktop wireframes: 
* <a href="assets/Wireframes/HomeDesktopView.png" target="_blank">Home</a>
* <a href="assets/Wireframes/ResumeDesktopView.png" target="_blank">Resume</a>
* <a href="assets/Wireframes/ContactDesktopView.png" target="_blank">Contact</a>

#### Mobile wireframes
* <a href="assets/Wireframes/HomeMobileView.png" target="_blank">Home</a>
* <a href="assets/Wireframes/ResumeMobileView.png" target="_blank">Resume</a>
* <a href="assets/Wireframes/ContactMobileView.png" target="_blank">Contact</a>


## FEATURES

The page features are responsive navigation with a hamburger button with a translateX() function which is used to move the elements in a two-dimensional space along the x-axis. 
It moves the position of the element on the horizontal plane by the amount provided by "t".

Every single page has its footer with social media icons linking to the candidate network, e-mail contact, and a printable version of CV.

Apart from the contact form page, there is an image applied to the background features with background-blend-mode applied as multiply.

An image profile with a zoom animation is applied to all pages, the purpose is to grab attention and give a positive response to the user.

### HOME 

The home page consists of a profile picture, greetings, and a dedicated section to describe "Who I am".
A hamburger button is applied on the top-right of the page, and it is programmed to collapse the navigation buttons. 
Inside the footer section, there is a link with a printable version of my CV and my contact details.

The method applied to develop this page is described as per below: <br>

#### Header
- Section wrapped with a profile image and greetings;
- Zoom animation applied on a scale from 0.9 to 1.0 to call the user's attention;
- Hamburger button developed with a transform translateX (0) animation and collapsing the navigation buttons. Once the user clicks on the hamburger button, the navigation shows up, and the options are available to be clicked. <br>

#### Resume 
- Screen developed to split its size into two different layouts;
- Personal details takes 1/3 of the desktop view, while "about me" takes 2/3 of the desktop view. 
- Screens are responsive, when the page is opened on a small screen, the layout will float to the left, and text is aligned to the center page. The paragraphs are developed to display its context underneath each other as a column.

#### About Me
- Dedicated section to demonstrate to potencial recruiters about the candidate personality, what he/she has done, and what are their expections;
- A picture, and a resume text with "Who I am" context were wrapped in the same section.

#### Footer 
- An anchor link to access a printable version of the CV is available in pdf;
- The target_ blank attribute is applied to keep the user on the main screen;
- Anchor links are applied to the professional network;
- Font awesome button is applied and it is hovering in red color.


### RESUME

The resume page consists of my work history and my skills as a developer student at Code Institute. 
Although my work history is from my background experiences, my front end and back end skills are copied from my resume project lecture at Code Institute.

The method applied to develop this page is described as per below: <br>

#### About Me
- Screen developed to split its size into two different layouts;
- Work history takes 1/3 of the desktop view, while "my skills" takes 2/3 of the desktop view. 
- Screens are responsive, when the page is opened on a small screen, the layout will float to the left, and text is aligned to the center page. The paragraphs are developed to display its context underneath each other as a column.


### CONTACT

The contact page consists of a form for potential recruiters to be in touch to send assessment tests, projects, and any other text inputs.

The method applied to develop this page is described as per below: <br>

#### Form
- Name, e-mail, and project description inputs;
- Required attribute;
- Placeholder fields;
- Submission button; 
- Boostrap effects.


### DOWNLOAD CV

Located on the footer section, the anchor link gives an option for recruiters to download the CV in pdf version. 

To keep the user on the main page, a "target_blank" attribute is applied to open the download page in a new tab.

### Existing Features

1.  Greetings logo - applied on every single page and the purpose is to give a positive emotion to recruiters and all visitors.
2.  Hamburger navigation bar - allows the users to navigate throughout the portfolio, as it has a fixed position overflowing on every single page.
3.  Personal info - allows recruiters and any other is interest to have a phone call or quick access to the candidate's e-mail for future contact.
4.  About me - introduce the way how the candidate works giving the first impression from the candidate to recruiters.
5.  Who I am - allows to recruiters have a brief life history of the candidate giving to the recruiters an idea about the candidate's personality.
6.  Footer network icons - applied on every single page, allows all visitors to access the network platforms that the candidate is part of.
7.  TransleX() function - applied on every single page and bring animation to visitors interact with the portfolio navigation.
8.  Work history - introduction to the work experience from the candidate allows the recruiters to know the candidate's work history.
9.  My skills - candidate's skills as a web developer, allows the recruiters to identify if the candidate has the required skills that the company is looking for.
10. Printable CV version - for those recruiters who are looking for a traditional CV, it allows the recruiters if a click having the pdf CV version for printing.
11. Contact form - allows potential visitors to ask questions, send projects in mind or assessments for recruitment process.
12. Download CV - applied on the navigation bar, allows quick access to download the CV in pdf version.

### Features Left to Implement

1. Projects:    as a new coding student, the candidate hasn't got the opportunity to develop projects to show to potential recruiters. A projection section in the portfolio 
                should be created in the portfolio
2. Blogs:   acting as a contributor in **Technology Blogs** should create a new network connection for the candidate. A blog section with the candidate posting to share his 
            knowledge should be created in the portfolio


## TECHNOLOGIES USED

- **HTML** 
    - The project uses **HTML** as a programming language.

- **CSS** 
    - The project uses **CSS** as a programming language.

- <a href="https://www.javascript.com/" target="_blank">JavaScript</a>
    - The project uses **JavaScript** to create interactive effects.

- <a href="https://github.com/" target="_blank">GitHub</a>
    - The project uses **GitHub** to host this website and review code.

- <a href="https://www.gitpod.io/" target="_blank">GitPod</a>
    - The project uses **GitPod** as a development environment (IDE).

- <a href="https://getbootstrap.com/" target="_blank">Bootstrap</a>
    - The project uses **Bootstrap** to design and customize responsive mobile website.

- <a href="https://fontawesome.com/" target="_blank">FontAwesome</a>
    - The project uses **FontAwesome** to get icons and social logos to the website.

- <a href="https://balsamiq.com/wireframes/" target="_blank">Balsamiq</a>
    - The project uses **Balsamiq** as a wireframing tool.

- <a href="https://fonts.google.com/" target="_blank">GoogleFonts</a>
    - The project uses **GoogleFonts** to style the website fonts.


## TESTING

* <a href="https://jigsaw.w3.org/css-validator/" target="_blank">CSS Validation Service</a>
* <a href="https://validator.w3.org/nu/" target="_blank">HTML Checker</a>
* <a href="https://www.createmockup.com/generate/?laptop=on&tablet=on&mobile=on&desktop=on&width=1024&preset=preset1&urlScreenshot=https%3A%2F%2Falexandregrego1.github.io%2FFinalVersion20-10-20%2F" target="_blank">Mockup</a>

### UX testing visitors stories 

The path through the website: Home > Resume > Contact > Download CV

Those pages point to the next call with an action button. Visitors can have different navigations throughout the menu navigation. 

1. As a visitor to the website, I want to easily navigate throughout the website portfolio. 
	i. A fixed navigation bar navigation overflowing the screen is applied. 
	ii. The visitors can easily access the navigation from whatever part of the portfolio they are in.

2. As a recruiter, I want to decide quickly if the candidate is a good fit for the job position offered.
	i. On the resume page, there are two sections about "work history" and "my skills". 
	ii. A resume is displayed to let the recruiter know about the work experience and education of the candidate. 

3. As a recruiter, I want to know more about the candidate's profile.
	i. On the home page, a "who I am" section is applied.
	ii. A text with a brief autobiography about the candidate's experiences is available for recruiters to analyze the profile of the candidate. 
    iii. A casual picture is applied to this section to bring positive emotion to the recruiter.

4. As a recruiter, I want to know about the candidate's last jobs.
	i. On the footer, social network media is applied. 
	ii. The social network provides the past jobs of the candidate.
	iii. Once the recruiter clicks on the network media, a new tab is opened linking the network media clicked. 
	iv. Target_blank function is applied to keep the recruiter on the main page.

5. As a recruiter, I want to make sure that the candidate is available to start a new career from entry-level.
	i. On the home page, an about me section is applied.
	ii. The candidate explains "why the company" should hire him.

6. An interested recruiter wants to contact the candidate for an interview process.
	i. Personal information, e-mail link, and a contact form are applied.
	ii. All pages have a footer with e-mail contact displayed.	
	iii. On the home page, personal information is applied. The recruiter can easily find the e-mail or mobile number of the candidate.
	iv. A contact page with a form is applied to the recruiter or other users send a project in mind or a text for contact. 

7. As a recruiter, I want to see the development projects that the candidate is involved in.
	i. On the footer page, network media is applied. 
	ii. Once the recruiter clicks on the network media, a new tab is opened linking the network media clicked keeping the recruiter on the main page.


### Testing website functionality 

#### Home:

	1. Navigation button:
	
		i. Browse the web project on google chrome.
		ii. Use the google develop tool clicking with the right button of the mouse and click on the inspection option. 
		iii. Change the screen size from desktop to tablet to verify if the sections are responsive reducing the screen size. During the test, the screen sizes were not fitting in its sizes. Adjusts on media screen sizes were
		     made to fit the pages as its screen sizes.
		iv. Click on the hamburger button bar to verify if the navigation options are opening. During the test, the "X" button to collapse the navigation had a border around it causing an ugly designer. So, a CSS outline property was applied to hidden the border.
		v. Click on the home page to verify if the pages are linked to each order and if the navigation is responding to the command.
		vi. Close the navigation button clicking on the "X" to verify if the translateX function is working. 
		vii. Scroll down the page to check if the bar button is fixed and overflowing the background. During the test, the hamburger button was fixed on the top of the page even if the scroll down was applied. The fixed position
		     was applied to stick the bar navigation even if the page was scrolling down. 

	2. Profile image: 

		i. Refresh the home page screen
		ii. Verify if the zoom is working, the scale is properly sized, and if the time of the zoom animation is not too much.
		iii. Increase the shadow of the image profile and verify if the image is overflowing the subtitle.
		iv. Confirm if the width of the subtitle background is wider than the profile image. During the test, the background of the subtitle text wasn't wider than the image profile. So, the width calc applied is: 100% + 1.5em.
		v. On responsive view the image profile, greetings, and the subtitle text are center positioning. 
	
	3.  About me section: 

		i. Section slipped between 1/3 and 2/3 size screen classified in a container box.
		ii. During the test, the background color was too dark that was covering the image. So, a background blend mode was applied to keep the background image showing up.
		iii. On responsive view, the section is split into two parts. The personal information is coming up on the top with its text-align to center, and the about me section is underneath the personal information. 

	4. Who I am section:

		i. Test if the text is justified align. During the test, was observed that the text aligns to the left the layout on the right was not align as if it was a book layout.
		ii. Confirm if the subtitle background is wider than the picture.

	5. Footer
		i. Check if the hover property is applied. Once hovering the mouse pointer, a red color should come up hovering the font awesome button. 
		ii. Click on the download button. Check if a new tab is open. During the test, once the download button was clicked, the new tab was opening overflowing the current home page. A target_ blank attribute was applied.
		iii. Verify if the hovering property is applied to the download button. The font awesome button should become red. 
		iv. Confirm if the network links are linked to the candidate profile. Click on the font awesome button and verify if a new tab will come up if the network clicked (remain the user on the main page).
		v. Check if the hover property is applied. Once hovering the mouse pointer, a red color should come up hovering the font awesome button.  

#### Resume:

	1. Navigation button:
	
		i. Browse the web project on google chrome.
		ii. Use the google develop tool clicking with the right button of the mouse and click on the inspection option. 
		iii. Change the screen size from desktop to tablet to verify if the sections are responsive reducing the screen size. During the test, the screen sizes were not fitting in its sizes. Adjusts on media screen sizes were
		     made to fit the pages as its screen sizes.
		iv. Click on the hamburger button bar to verify if the navigation options are opening. During the test, the "X" button to collapse the navigation had a border around it causing an ugly designer. So, a CSS outline property was applied to hidden the border.
		v. Click on the home page to verify if the pages are linked to each order and if the navigation is responding to the command.
		vi. Close the navigation button clicking on the "X" to verify if the translateX function is working. 
		vii. Scroll down the page to check if the bar button is fixed and overflowing the background. During the test, the hamburger button was fixed on the top of the page even if the scroll down was applied. The fixed position
		     was applied to stick the bar navigation even if the page was scrolling down. 

	2. Profile image: 

		i. Refresh the home page screen
		ii. Verify if the zoom is working, the scale is properly sized, and if the time of the zoom animation is not too much.
		iii. Increase the shadow of the image profile and verify if the image is overflowing the subtitle.
		iv. Confirm if the width of the subtitle background is wider than the profile image. During the test, the background of the subtitle text wasn't wider than the image profile. So, the width calc applied is: 100% + 1.5em.
		v. On responsive view the image profile, greetings, and the subtitle text are center positioning. 
	
	3.  Work History: 

		i. Section slipped between 1/3 and 2/3 size screen classified in a container box.
		ii. During the test, the background color was too dark that was covering the image. So, a background blend mode was applied to keep the background image showing up.
		iii. On responsive view, the section is split into two parts. The work history is coming up on the top with its text-align to center, and then my skills section is underneath the personal information. 

	4. Footer
		i. Check if the hover property is applied. Once hovering the mouse pointer, a red color should come up hovering the font awesome button. 
		ii. Click on the download button. Check if a new tab is open. During the test, once the download button was clicked, the new tab was opening overflowing the current home page. A target_ blank attribute was applied.
		iii. Verify if the hovering property is applied to the download button. The font awesome button should become red. 
		iv. Confirm if the network links are linked to the candidate profile. Click on the font awesome button and verify if a new tab will come up if the network clicked (remain the user on the main page).
		v. Check if the hover property is applied. Once hovering the mouse pointer, a red color should come up hovering the font awesome button.   

#### Contact: 
	
	1. Form: 
			
		i. On contact form, type name, email and text to check if the placeholders vanishes.
		ii. Submit the empty form and verify that an error message about the required fields appears. 
		iii. Submit the form with an invalid email address and verify that a relevant error message appears.
		iv. Check if the contact form align in responsive screen. 

	2. Footer
		
		i. Verify if the e-mail address is a link and if it is hovering in red.
		ii. Check if the hover property is applied. Once hovering the mouse pointer, a red color should come up hovering the font awesome button. 
		iii. Click on the download button. Check if a new tab is open. During the test, once the download button was clicked, the new tab was opening overflowing the current home page. A target_ blank attribute was applied.
		iv. Verify if the hovering property is applied to the download button. The font awesome button should become red. 
		v. Confirm if the network links are linked to the candidate profile. Click on the font awesome button and verify if a new tab will come up if the network clicked (remain the user on the main page).
		vi. Check if the hover property is applied. Once hovering the mouse pointer, a red color should come up hovering the font awesome button.  

#### Download CV: 
    
    1. Download CV: 

        i. Click on hamburger button to open the navigation buttons and click on Download CV. 
        ii. Check if the CV is opening on a new tab.
        iii. Verify if the CV is in pdf format.


## DEPLOYMENT

This project is developed using the Gitpod as version control. It is commited and pushed to GitHub.

The GitHub repository for this project is: https://alexandregrego1.github.io/FinalVersion20-10-20/

i.    Log into GitHub.
ii.   On the right of the page, click on your profile. the list of repositories on the screen, select AJGreaves/portrait-artist.
iii.  Click on repositories, and click on the repository "FinalVersion20-10-20".
iv.   Above the Gitpod button,  click on settings.
v.    Scroll down until the section GitHub pages.
vi.   Under the Source, click to select the branch and tick the "master" option.
vii.  After the master branch is selected, a green tick appears with the following text "Your site is published at..."
viii. Copy that link and past it in your read. me file. 
ix.   Now the link is deployed and right to be shared.

### How to run this project locally

	Installing the GitHub:

			1. Use Google Chrome as your browse.
			2. Go to "https://github.com/", and create an account.
			3. Install the Gitpod extentions.
			4. Log in into your GitHub account.
			5. Click on the hamburger menu.
			6. Right down at the bottom, open web store.
			7. Search for Gitod.
			8. Click on the blue button "Add extension to chrome".


	Running this project locally: 

			1. Open the link: https://github.com/AlexandreGrego1/FinalVersion20-10-20.
			2. Click on the button "Code".
			3. Click on the button "Clone with HTTPs".
			4. Copy the repository.
			5. Click on the green button to open the "GitPod". 
			6. Type "git clone" followed by the link "https://github.com/AlexandreGrego1/FinalVersion20-10-20." on the terminal of your GitPod IDE.
			7. Press Enter and your local clone will be created.


## TESTING WRITE-UP

Responsivity for mobile devices tested on :

* Google Chrome Developer Tools

* Microsoft Edge

* Opera Browser

* Mozilla Firefox


## TYPOGRAPHY

I have operated with mostly darker in the background and lighter colors for the font-family. 

The most dominant colors are: 
- Black for the background;
- White and cyan for the font-family.

Google Fonts CDN is applied, Sans-Serif and Exo are the main attributes for font-family and body text.


## BARRIES TO TECHNOLOGY DEVELOPMENT

As my lack of knowledge in development tools, I have developed my portfolio in the same stands according to my resume project lecture. 

Although my limited knowledge was a barrier, I have applied to this project the characteristics that in my opinion are similar to my profile. 

After developed my first project, I noticed that is required to spend more time on the theory lectures to have more understanding of the subjects to facilitate the development 
process in future projects. 


## CONCLUSION

As a non-native English speaker, I have struggled to develop my texts in English. Please excuse my grammatical mistakes, typos, or any idea that is not clear enough explained.

This first project is crucial to keep me motivated to go throughout for the next modules on my course. 

As  I have got no idea what coding was before starting to study at Code Institute, I had several issues to develop this project and spending too much time sorting small problems
for being completely inexperienced. I have realized that I have to improve the way I was studying for the next modules.

Now I understand what our tutor Brian O Grady mean when he said "It is not a sprint, it is a marathon".

Please do not hesitate to contact me if I can be of any further assistance or provide further information on this matter. 


## CREDITS

	Content: 
		* Part of this content is from my resume project lecture adapt for my real details;
		* Part of the text of this website is from my resume project; 
		* The rest of the website is created by the developer of this project, Alexandre Gregorio

	Media:
		* The background photo on the home page came from an open library and can be reached on the link: "https://unsplash.com/photos/iacpoKgpBAM";
		* Profile image is from the developer of this project, Alexandre Gregorio.

	Acknowledgements: 
		* I received inspiration for this project from "https://scrimba.com/" - Portfolio settings;
        * Google Fonts - https://fonts.google.com - CDN for fonts used in the project;
        * Font Awesome - https://fontawesome.com - CDN for fonts used in the project;
        * W3schools - https://www.w3schools.com - Open research library.