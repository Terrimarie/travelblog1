# Travel Blog

Milestone Project: User-Centric Frontend Development‚ Code institute

This is my travel blog website to demonstrate my frontend development skills to prospective employers, the site was created using HTML, HTML5, CSS, CSS3, Bootstrap 4, Googlefonts.
The travel blog site includes 4 pages every page has a title, text, links to other pages, navigation bars on every page, drop down nagivation menu on every page, homepage title link in top left corner on every page and social media links. The index.html home page has a sub title as well as main title, a simple introduction with a youtube video, a button link to the about me page. 
The index.html home page has then an image blurb going into more detail about the travel blog and the reason for the website on index.html and about.html. About page has a home page link top left, navigation bar, main title, heading image, blurb about the site. Then onto another page posts.html again with link to home page and navigation bar where the viewer can explore travel tips via embedded youtube videos, starts with some text about the page, then youtube videos and links to travel guides. 
Finally a contact.html page where the viewer can sign up and get in contact maybe for ask for to travel tips, advice or a collaboration. Validation form added to make sure email address and name/ text is entered.

Link to website https://terrimarie.github.io/travelblog1/

# UX

My intention making this travel blog website is to provide a website for people who are interested in travelling and looking for inspiration for where to travel to, they may be new to travelling or already be a frequent traveller. I have designed the site to be very simple easy to use and navigate with a simplistic design and user-friendly features.
I have included links to Youtube videos, images, text and links to travel guides links to provide the user with different ways of gathering travel tips and travel inspiration. 
The user is also given an opportunity to use a contact form to get more travel information and tips by using the contact page to contact the travel blogger.

User stories:
* As a user I want to discover new and interesting destinations.
* As a user I want to be recommended destinations so I can decide where to travel to next.
* As a user I want to be recommended destinations based on location.
* As a user I want to create an experience in a foreign place.
* As a user I want to browse videos and guides to create a new travel experience.

Wireframe/mock up 
Wiredrame pdf uploaded to git repository

# Features
## Existing Features
* Homepage title link feature in top left hand corner allows user to click to be directed back to home page on every page without have to use back button for easier user experience.
* Navigation bar feature allows user to navigate through the web sites pages with ease, allowing them to decide what they want to look at next in any order.
* Main title for each page clear description for user match naigation bar titles so the user knows what each page is referring to.
* Sub title feature on home page for more information on introduction to the website giving the user a clearer quick snapshot on bloggers reason for creating the website.
* Text on each page telling user more about the website and the way you can use each page for better user experience.
* Third party travel guide links useful for user to get more information and links to other pages from your website.

# Features Left to Implement
Things that could be implemented:
* Add an audio mp3 travel guide.
* Hook up form to server making the contact form work and data recorded and emailed to blogger.
* More content and information on travelling.

# Technology
* HTML5 http://www.google.fr/ "https://en.wikipedia.org/wiki/HTML5
    * HTML5 mark up language code used for basic description and layout of website.
* CSS3 https://en.wikipedia.org/wiki/Cascading_Style_Sheets
    * CSS3 style sheet language used to create content structure and design of website.
* Bootstrap 4 https://getbootstrap.com/docs/4.3/getting-started/introduction/
    * Bootstrap 4 CCS framework used to design of website.
    * Jquery and JS - basic Jquery and JS as apart of bootstrap for used.
    * Used to create validation form on posts.html page.
* Cloud9 https://ide.c9.io/terrimarie/travelblog1
    * Cloud9 online IDE tool used to create code and push up to GitHub using Git. 
* Git https://ide.c9.io/terrimarie/travelblog1
    * Git tool used for version-control system for tracking changes in source code during software development for website.
* GitHub https://terrimarie.github.io/travelblog1/index.html
    * GitHub used a Git repository for website.
* Fontawesome 7.5 https://fontawesome.com/
    * Fontawesome used to creat social media icon links.
* Googlefonts https://fonts.google.com/
    * Googlefonts used for fonts style on evey page of website.
* W3C https://validator.w3.org/
    * W3C validator used to test html code.
* W3C CSS https://jigsaw.w3.org/css-validator/
    * W3C CSS validator used to text css code.

# Testing
Open website on various browsers to make sure it is responsive on all.
Test all links.
Use W3C validator for html and CSS.
1. Home page link:
    1. Go to "About page", "Posts page" and "Content page".
    2. Click on title in top left hand corner 'Travel with me'.
    3. Click to see if link takes you back to home page index.html.
2. Navigation bar, drop down and links:
    1. Go to "Home page", "About page", "Posts page" and "Content page".
    2. On larger screens click title links in navigation bar HOME, ABOUT, POSTS or CONTACT. Click to see if it link takes you to these pages.
    3. On a mobile screen or smaller device, click burger Menu for dropdown navigation bar again click title links HOME, ABOUT, POSTS or CONTACT to see if they take you to these pages.
3. Embedded Youtube videos:
    1. Go to "About page and "Posts page".
    2. Click on Youtube videos to see if video link sound and image is working.
4. Button:
    1. Go to "Home page".
    2. Click blue button and bottom of "Home page" to take you to the "About page".
4. Form/Button:
    1. Go to "Contact page".
    2. Enter valid name, email, phone number, message into form on "Contact page"
    3. Click on Click blue button and bottom of "Contact page" to submit and check that the form has validation and check the data inputted.
    4. Message will be deisplayed after submitting.
5. Travel guide title links:
    1. Go to "Posts page".
    2. Click on travel guides at bottom of page.
    3. Each guide is highlighted and underlined when you hover the cursor over it.
    3. Check if travel guide links work.
6. Social media icon links:
    1. Go to "Home page", "About page", "Posts page" and "Content page".
    2. Click on Twitter, Facebook and GitHub icon on each page to test links to social media pages.

## Bugs 
Validation on contact form needed to be added using jqBootstrapValidation.
Took out JS from form to get it working.
Removed absolute links and used relative links to get thing working.
Cleaned up errors in GitHub.
Added comments to HTML and CSS code.
Used beautify to clean up code. Command shift B.
Fixed href="/" to link index.html homepage.
Got rid of 404 errors caused by fontawesome links not working added links to fontawesome using travelblog1 links in all.min.css and html head of each page. Moved CSS to its own folder. 
Alignment issue checked if I missed a tab. Copy pasted from other pages to fix and match.
Tested responsiveness or site and links.

# Deployment
Deployed project using hosting platform GitHub pages.
Running code using cloud9.
Used Cloud9 IDE to run and debug my code from within your workspace. 
Open Cloud9 and create GitHub page.
Use console in Cloud9 to write code and use terminal and Git commands to sent code to GitHub repository.
Push code frequently from Cloud9 to GitHub using Git.
Use Git to save code and view changes made.
Use GitHub repository to save code.
* Git commands:
    * Initial commit:
    * git init
    * git add .
    * git commit -m "initial commit"
    * git remote add origin https://github.com/Terrimarie/travelblog1.git
    * git push -u origin master
    * git remote add origin https://github.com/Terrimarie/travelblog1.git
    * git push -u origin master
* Other commit example:
    * git add .
    * git commit -m "added youtube video"
    * git push
    * git status
* Git pull used to revert back to previous code

# Credits
The text for Travel guides - by Dan Flying Solo https://www.danflyingsolo.com/
The text for text blurbs where my own.

## Content

## Media
* Photos - Unsplash https://unsplash.com/
* Photo campervan.jpg campervan1.jpg - yellow Volkswagen van on road - Photo by Dino Reichmuth on Unsplash
* Photo lakelandscape.jpg lakelandscape1.jpg - man sitting on gray dock - Photo by Simon Migaj on Unsplash
* Photo beach.jpg beach1.jpg - seashore during golden hour - Photo by Sean O. on Unsplash
* Photo laptop.jpg laptop1.jpg - Photo by Sergey Zolkin on Unsplash
* Youtube videos - By Dan Flying Solo https://www.danflyingsolo.com/
* Travel guide links - By Dan Flying Solo https://www.danflyingsolo.com/

## Acknowledgements
* Photos - Unsplash https://unsplash.com/
* Photo campervan.jpg campervan1.jpg - yellow Volkswagen van on road - Photo by Dino Reichmuth on Unsplash
* Photo lakelandscape.jpg lakelandscape1.jpg - man sitting on gray dock - Photo by Simon Migaj on Unsplash
* Photo beach.jpg beach1.jpg - seashore during golden hour - Photo by Sean O. on Unsplash
* Photo laptop.jpg laptop1.jpg - Photo by Sergey Zolkin on Unsplash
* Youtube videos - By Dan Flying Solo https://www.danflyingsolo.com/
* Travel guide links - By Dan Flying Solo https://www.danflyingsolo.com/