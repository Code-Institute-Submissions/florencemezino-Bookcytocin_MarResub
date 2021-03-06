# Bookcytocin, evolve to your best self

[View the live project here](https://bookcytocin-project.herokuapp.com/)

![Bookcytocin](static/assets/img/bookcytocin_responsive.png)



## User Experience (UX)

### End user 

1. Goal
End users for this project are readers who wants to focus on their personal development and use the book as a real tool to grow in every area of life (Love, finance, career, spiritual, intellectual, health etc.) 
The site owner goal is to make money ot of each sell thanks to a affiliate link but also to create a readers community.


2.  Profile : Readers

Users who want to focus on their personnal development and want to include more readings in their life. They want to integrate more readings in their life by using the book as a real tool on their personnal development journey. They want to take time to read more and share their recommendations/reviews. They want to have the possibility to see recommandations, save books for later and buy books online.


a. identity and behaviours

Readers interacting with the site are English speaker and we can determine different reader profiles :
- Beginner : between 1 - 12 books per year : Mostly users who read very rarely.
- Intermediate : between 12 - 24 books per year : Mostly users who read minimum 1 book per month
- Expert : between 24 - 36 books per year : Users who reads very frequently and it is part of their habits 
- Master : 36+ books per year : User who can read several books a month and is keen to share their recommendations online / interact with a community. At this level, users might work in the field such as book writer or book publisher. They have a important recommendations books library and wish to expand their knowledge by accessing more books, reading more books and reviews

b. expectations 
- Readers want to extend their knowledge on different dimensions of personal development such as nutrition, career, finance etc.
- Readers have a strong willingness to integrate reading more books in their personal development.
- Readers want to have access to a large library of books about personal development.
- Readers wants to read reviews with great insights to esily choose their next reading

c. restraints
- Readers believe they don't have time to read and rarely commit to make reading a real activity, part of their daily life.
- Readers feel overwhelmed about all the great books they could read and they don't dare to start
- Beginner readers might feel impostor symdrome when seeing other reading progress and recommendations


### User stories

1. First Time Visitor Goals

* As a reader, I want to have access to a great book library online so that I can have plenty of choice to select my next book to read
* As a reader, I want to buy a book in few steps so that I can progress quickly on my reading goals
* As a reader, I want to have access to recommendations/ reviews about books so that it can help me to choose the next book to read
* As a reader, I want to save book in a wishlist so that I can buy it later
* As a reader, I want to sell books I read already so that I can invest in buying new ones
* As a reader, I want to exchange the books I read with other readers so that I can save money and interact with the readers community


2. Returning Visitors Goals

* As a reader, I want to be encouraged to read more so that I can reach my reading goal 
* As a reader, I want to see my reading goals progress so that I can be motivated to read more
* As a reader, I want to be able to share reviews about my readings so that I can also help others to decide their reading 
* As a reader, I want to recommend the books I read so that I can have the feeling to be part of a community and it will motivates me to reach my goal
* As a reader, I want to be able to eupload online a book to sell so that I can market it better or remove it when it is sold out


3. Frequent User Goals

* As a reader, I want to see the most liked/successful/trendy books on a certain period to not miss out so that I can be up to date about trendy readings
* As a reader, I want to be informed about new books releases, events, masterclass so that I can improve my learning skils in general. 


### Design

1. Colour Scheme

The color scheme choosen is in blue , purple, grey tones as these colors reflects "knowledge", "trust", 'mind" in correlation with personal growth.

The main colours used for this project are as follow : 
" 
* `#fafafa`: this is creamy white for the light shades.
This color will be used as the background for the dark on light designs and the text color of an inverted design

* `RoyalBlue`: this is a grey-blue color for the light accent. A simmilar version  is also use on certain elements.
This color is used to bring attention to design elements by contrasting with the rest of the palette.

* `var(--bs-purple)`: "Purple heart" is a deep bright purple for the dark accent and `#B24DD1` : "Cindy' is a pop magenta. These colors will be to work on the dark accents. for the dark accents
They are used to catch the eye of the user to show some important information but it can be link also to temporary information

* `#2A294A` : "Martinique" is a dark-grey color for the dark shades or the outline
This color is used for dark on ligh design and as background for inverted design.


2. Typography
The `Lato` font is the main font used throughout the whole website with `sans-serif`
as fallback fonts in case for any reason the font isn't being imported into the site correctly. 
The space between letters and the conforting shape makes `Lato`font a great choice for this website as it makes reading easy and accessible.


3. Imagery / Video
Imagery is important in this website in order to illustrate the books library and experts opinions
*  A carousel component has been integrated and it has been designed to be striking and catch the user's attention on the different options that the website could offer.
* Free images from topic "reading" "books" "library" "purple" were selected on websites sush as [Pexel](https://www.pexels.com/fr-fr/) and [Unsplash](https://unsplash.com/login) in order to illustrate the colors chosen. Also each book has their own book image displayedbooks datatbase.
* Book image were taken from amazon and hosted in Cloudinary

### Branding research 

[Smashinglogo maker]() program was used to generate branding ideas and color scheme. Below see some materials :
* Logo
    - Bookcytocin white / plum purple - [View](static/mindmap/logo1.png)
    - Bookcytocin dark blue/ plum purple - [View](static/mindmap/logo2.png)
    - Bookcytocin white / light grey - [View](static/mindmap/logo3.png)

* Covers / Hero image examples
    - Bookcytocin global cover - [View](static/mindmap/cover1.png)
    - Bookcytocin white / outdoor window - [View](static/mindmap/cover2.png)
    - Bookcytocin white / plum purple - [View](static/mindmap/cover3.png)

* Merchandise 
    - Bookcytocin cup / business card - [View](static/reasearch_branding/merchandise.png)


### Wireframes

1. All Wireframes - [View](static/assets/wireframes/all_wireframes.pdf)
2. Mobile Wireframes - [View](static/assets/wireframes/mobile_wireframes.pdf)
3. Tablet Wireframes - [View](static/assets/wireframes/tablet_wireframes.pdf)
4. Desktop Wireframes - [View](static/assets/wireframes/desktop_wireframes.pdf)

### Database CRUD (Create, Read, Update, Delete)

#### Mindmap with Lucidchart
1. Database Structure - [View](static/mindmap/database_structure.png)
2. Mindmap programs : 
    - programs / functions overview - [[View](static/mindmap/programs.png)
        - register / login / search bar - [[View](static/mindmap/program1.png)
        - view books selections / browse books collections / browse recommendations - [View](static/mindmap/program2.png)
        - view and edit goal statement / manage reading performance / add and view review / view reading or review insights - [View](static/mindmap/program3.png)
    

#### MongoDB database / collections structure
1. Books - [[View](static/mongo_data/books.png)
2. Collections - [[View](static/mongo_data/collections.png)
3. Users - [[View](static/mongo_data/users.png)


## General Features

* The website is called Bookcytocin, a mix between Book and oxytocyn, the love hormone. The idea here is to inspire readers to find their true self and find the love/passion for reading as it is connected ot self development.
* The website is structured in 4 pages : `Readflix`, `Collections`, `Community`, `MyBookLog`, + 2 extra pages for sign up and login.
* The website's pages and different features are responsive on all device sizes. 
* Each page features a responsive header with navigation bar and a conventional placing of logo (top left).
* Users can find a sign up option 
* Users can find a log in option if they already hacreated an account
* There is a carousel components with 4 slides to match the structure of the site.
* There is a form in which user dan request to receive a free ebook about reading/personal development
* There is a footer with copyright information and social media links. 
* The general features of the site are in one space base_template.

#### Readflix
* The `Readflix` page features a special selection of books for the month.
* There is a navigation bar with a logo and a hamburger menu for mobile.
* A caroussel will allow to slide to different pages to access the different sections of the website. 
* A section called Readflix will present a selection of 12 books for the month belonging to different type of collection

#### Collections
* The `Collections` page features 1 column wide for mobile devices, 2 columns wide for tablets and 4 columns wide for desktop.
* THere is a search bar in which isers can search books by titlte and by author name.
* There are 12 dimensions for personal development with a button format
    - Health and fitness
    - Intellectual
    - Emotionnal
    - Character
    - Spititual 
    - Love relationship
    - Parenting
    - Social
    - Career
    - Financial 
    - Quality of life
    - Life vision
* In each section, readers  can find a list of books related to the genre.
* From each book, users has the option to be redirected to Amazon website to buy the book.


#### Experts
* The `Community` page features 1 column wide for mobile devices, 2 columns wide for tablets and 4 columns wide for desktop. 
* This page displays people and their readings recommandations/reviews
* User can leave a review about a book if they are registered and logged in.
* Users can find also multiples articles on how to integrate more reading into their life and make it part of their persoal development.
For example : 10 ways to make mre time for reading

#### MyBookLog
* The `MyBookLog` page features 1 column wide for mobile devices, 2 columns wide for tablets and 4 columns wide for desktop. 
* Users can set their reading goals and edit them if needed.
* Users can have an history and insights of the the reviews and recommendations they made on the site


### Existing features 

1. On every page
* Header Logo - Clicking the logo returns users to the home page.
* Header Fixed Navigation Bar - Allows all users to easily navigate all the website's pages and find what they are looking for quickly.
In the mobile version the navigation bar is turning into a hamburger menu for a user friendly experience.
* Footer copyright info - Proof of brand and content protection is available on each page.
* Footer social media icons - Allows users to be redirected to social media platform to stay connected.

2. Summary page features specificities
* `Reaflix`: Allows users to 
    - specificity 1 : have an oveview of the most trendy books.
    - specificity 2 : be redirected in one click to amazon site to buy the book
* `Collections`: Allows users to 
    - specificity 1 : search books via a search bar by book title and book author
    - specificity 2 : search books to read via collections/genre 
* `Community`: Allows users to 
    - specificity 1 : leave a review about a book and read other reviews
    - specificity 2 : read news about reading tips and personal development
* `MyBooklog`: Allows users to 
    - specificity 1 : set and edit their reading goal statement
    - specificity 2 : view history and insights about the reviews left.
* `Account/Profile` : 2 pages / Allows users to :
    - specificity 1 : sign up to MyBooLog profile
    - specificity 2 : log in and log out from account


### Features to implement in the future

* Buy directly on the Bookcytocin platform directly and not go through affiliate link via Amazon
* Users can exchange their books with other member
* Users can give away their book in exchange of discounts
* Users can have access to an history of their activities. A record is accessible if they buy a book, exchange a book or leave a review etc.
* Users can contact the website owner to request general information thanks to a contact form
* Users receives a confirmation email once the contact form is completed.
* Users can follow a profile from experts to receive recommendations by email
* Users can track their readings with more status than saved (ie : status : saved, reading or finished )
* Users can sell their books edit their entry
* Possibility to edit review via MyBookLog page profile / history review
* Vote for the readflix of the month
* Share a book with a friend via social media
* Extend feature save to wishlist into collections\
* Delete a save book


## Technologie Used 

### Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
* [Python](https://en.wikipedia.org/wiki/Python_(programming_language))


### Frameworks, Librairies & Programs Used

1. [Git](https://git-scm.com/)
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

2. [GitHub](https://github.com/)
GitHub is used to store the projects code after being pushed from Git.

3. [Heroku](https://dashboard.heroku.com/)
Heroku was used to deploy the website

4. [Balsamiq](https://balsamiq.com/)
Balsamiq was used to create [the wireframes](All Wireframes.pdf) during the design process.

5. [Flask](https://en.wikipedia.org/wiki/Flask_(web_framework))
Flask was used as a library to facilitate running all python functons

6. [MongoDB](https://en.wikipedia.org/wiki/MongoDB#:~:text=MongoDB%20(de%20l'anglais%20humongous,est%20%C3%A9crit%20en%20C%2B%2B.)
MongoDB was used to build databases / collections

7. [Cloudinary](https://cloudinary.com/)
Cloudinary was used to host images, specifically tje book images

8. [Hover.css](https://ianlunn.github.io/Hover/)

Hover.css was used on`social media icons for styling and give dynamim
9. [Google Fonts](https://fonts.google.com/)

Google fonts were used to import the `Lato` font into the style.css file which is used on all pages throughout the project.

10. [Font Awesome](https://fontawesome.com/)
Font Awesome was used on all pages throughout the website to add icons for aesthetic purposes.

11. [StartBootstrap](https://startbootstrap.com/theme/landing-page)
StartBootstrap was used to get a landing page template to build the app

12. [Lucidchart](https://lucid.app/)
Luci app was used to have mindmp and have an overview of the database strategies and structure


## Testing 

Testing information can be found in the following file [View](testing.md))

## Deployment

### Heroku

The project was deployed to Heroku following the next steps:

1. Create a requirements.txt file using the terminal command `pip freeze > requirements.txt`
2. Create a Procfile with the terminal command `echo web : python app.py > Procfile`
3. Proceed with git add and git commit the new requirements and Procfile and then git push the project to GitHub
4. Create a new app on [Heroku website](https://dashboard.heroku.com/) by clicking the "New" button in your dashboard. Give it a name an set the region to Europe.
5. From the heroku dashboard of your newly created application, click on "Deploy", "Deployment method" and "select Github"
6. Confirm the linking if the heroku app to the correct Github repository 
7. in the heroku dashboard for the application, click on "Settings" > "Reveal Config Vars" 
8. Set the following confi vars
IP : 
MONGO_URI : 
PORT : 
SECRET_KEY : 
9. Click on enable deployment
10. Wait until you get notified a the bottom of the page that your app is deployed and vie the deployment


## Credits

### Code

1. Readflix
* Using for loop in Flask [Here](https://www.geeksforgeeks.org/python-using-for-loop-in-flask/)
* how to position an element bootstrap [Here](https://www.geeksforgeeks.org/bootstrap-positioning-an-element-with-examples/)
* Python string length | len() method Example [Here](https://www.guru99.com/python-string-length-len.html)
* Using the len() Function in Python [Here](https://realpython.com/len-python-function/)
* MongoDB ??? What is the best way to retrieve a random document from a collection? [Here](MongoDB ??? What is the best way to retrieve a random document from a collection?)


2. Collections
* ???how to display information if button is pressed flask??? [Here](https://www.codegrepper.com/code-examples/python/how+to+display+information+if+button+is+pressed+flask)
* how to detect which update button was clicked with Flask python(mongoDB) [Here](https://stackoverflow.com/questions/55089384/how-to-detect-which-update-button-was-clicked-with-flask-pythonmongodb)
* HTML DOM addEventListener() Method for the button collections [Here](https://www.w3schools.com/jsref/met_element_addeventlistener.asp)


3. Community
* get bootstrap blog features for the community [Here](https://getbootstrap.com/docs/5.1/examples/blog/)


4. MyBooklog
* How To Create Icon Buttons : [Here](https://www.w3schools.com/howto/howto_css_icon_buttons.asp)
* How can I randomly select an item from a list? for the MyBookLog goal statement form / dropdown reading level [Here](https://stackoverflow.com/questions/306400/how-can-i-randomly-select-an-item-from-a-list)
* HTML textarea tag [Here]https://www.w3schools.com/tags/tag_textarea.asp
* How to use $set for the goal statment [Here](https://docs.mongodb.com/manual/reference/operator/update/set/)
* How do I partially update an object in MongoDB so the new object will overlay / merge with the existing one [Here](https://stackoverflow.com/questions/10290621/how-do-i-partially-update-an-object-in-mongodb-so-the-new-object-will-overlay)

5. Sign up / Log in / Log out
* Code Institute task's manager project : [Here](https://github.com/Code-Institute-Solutions/TaskManagerAuth)
* Jinja loops and conditionnal tutorial [Here](https://ttl255.com/jinja2-tutorial-part-2-loops-and-conditionals/)

5. General 

* Werzeug security helpers [Here](https://werkzeug.palletsprojects.com/en/2.0.x/utils/#module-werkzeug.security)
* Code Institute task's manager project  for the authenfication : [Here](https://github.com/Code-Institute-Solutions/TaskManagerAuth)
* Code Institute flask project Thorin et company (comparing json and mongo)


### Content 

* All content was written by the developer.
* Color scheme was found on the website Colormind, you can view it [Here](http://colormind.io/)
* Psychological properties of colours was found [Here](http://www.colour-affects.co.uk/psychological-properties-of-colours)
* Psychological properties of fonts was found [Here](https://designmodo.com/font-psychology/)
* Readme.md inspiration models : 
Readme.md sample from Code Institute [View](https://github.com/Code-Institute-Solutions/SampleREADME)
Readme.md sample from Anna Greaves's portrait artist [View](https://github.com/AJGreaves/portrait-artist/blob/master/README.md)

* Websites benchmark :
- Optimize [Here](https://www.optimize.me/?gclid=Cj0KCQjw_fiLBhDOARIsAF4khR0VuMLVgM7upWtouIID8wwwlaDQ3zpRCrrKqvt46zWOAqQkaHNgW8AaAkaKEALw_wcB)
- Bookauthority [Here](https://bookauthority.org/)
- Bingebooks [Here](https://bingebooks.com/)
- Mindvalley [Here](https://www.mindvalley.com/lifebook)


### Media
* All photos and images were edited by the developer. 

### Acknowledgements
- My Mentor [Jack Washira](https://github.com/iamjackwachira) for continuous helpful feedback.
- Tutor support at Code Institute for their support. Special mention for Igor and Fatima.
- Peer to peer support from Code Institute Slack community.

## Author 
- Florence Mezino, studying Full Stack Software Development at Code Institute (March 2021 - March 2022)
[Github](https://github.com/florencemezino)

## Feedback
If you have any feedback, please reach out to the developper of the this project Florence Mezino at florence.mezino@outlook.com
Thank you!