# TJ Dean Tattoo Portfolio

This project came to light as a good friend of mine is an apprentice tattoo artist and he wanted a way to show the world his work.   
I wanted to build him a webpage where not only could he display his art work, but a place where people can find out all the information needed when choosing a new tattoo artist. 
As Tj progresses so will the web page, In the future people will be able to see his progression through the portfolio section.

 
## UX
 
For this project I wanted to create a sight that was easy to navigate and had all the information no more than 2 clicks away, for that reason I decided to go for a single page design broken in to different sections as I believe this also creates a smoother experience for the user.  


- As someone who wants to get a tattoo, I want to be able to view the tattoo artists previous work and if I like what I see I would want a way to contact him so that I can schedule a appointment.


[Wireframes / Mockups!](https://github.com/danielclements/TJ-Dean-Portfolio/tree/master/Wireframes)

## Features

- Landing section: With this page the goal was to create a minimalistic landing that on first glance a user would be able to get a general feel for the webpage. With the help of the nav bar located at the top of the page the user would be able to navigate to the desired page with out having to scroll through the entire page.  

- Portfolio Section: The goal with this page was to display all of Tj's art work in one place, With the use of FancyBox this allowed me to create a clean and easy to navigate image gallery.  

- Testimonial Section : This page has a simple goal in mind, To display the comments left by previous clients. Not only does this build credibility but also reassures the user that Tj has the skills needed to give them the tattoo experience they deserve.  

- Bio Section: With this page I wanted the user to be able to familiarize them selves with Tj and a little bit about him and his background. Added social media links so the user can connect with him online.  

- FAQ section: On this page you will find a list of frequently asked questions. My goal with this page was to compile all the FAQs a tattoo artist would get, the goal is to educate the user straight away instead of having them wait for Tj to reply to a email, with this it stop the user losing interest.  

- Contact: This page was built so the user can ask any questions that may not be on the FAQ page, This fully functional form was built using bootstrap and also allows the user to upload a file if they want to reference a specific design when enquiring about a Tattoo.  

- Location/Hours Section: With this page the user will be able to find where the tattoo studio is located and what the opening hours are along with further contact details.  



### Existing Features
- Image Gallery - Fully functional image gallery using Fancybox by Fancyapps.    
- Form Validation - Form that allows the user to input details and upload files to ask more specific questions. Also uses bootstraps code to validate the form for any potential errors.
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.


### Features Left to Implement

- smooth scroll: yet to add a smooth scroll function when pressing any buttons / nav links.
- Contact form: Need to enable data from the form to be sent to the tattoo artist.

## Technologies Used

- [HTML 5](https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML 5** to write the front end of the website.

- [CSS 3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - This project uses **CSS 3** to style the front end of the website.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to change the navbar opacity at a certain scroll point, and also validates the form for any user errors.

- [Bootstrap 4](https://getbootstrap.com)
    - This project uses **Bootstrap** to improve scaling to mobile and to add the contact form.

- [Sketch](https://www.sketch.com/)
    - This project uses **Sketch** to create mockups / wireframes, also used to create the background for the Contact page.
    


## Testing

### Browsers used for testing:

- [Google Chrome](https://www.google.com/chrome/)
- [Firefox](https://www.mozilla.org/en-GB/firefox/new/)
- [Safari](https://www.apple.com/uk/safari/)
- [Microsoft Edge](https://www.microsoft.com/en-gb/windows/microsoft-edge)

### Devices used for testing:

- MacBook Pro 13"
- Office PC with 28" monitor 
- Oneplus 6T
- Samsung Galaxy Note 9
- Samsung S6

### Feature testing:

1. Portfolio Gallery:
    1. Go to the "Portfolio" section. 
    2. Click on any image.
    3. Uses the arrows to navigate between images.
    4. Click the play button for a montage.
    5. Click the magnifying glass to search for a specific image.  

2. NavBar color change:
    1. Begin scroll and check color changes on scroll.
    2. Use nav buttons, check color changes when navigating between sections.

3. Form Validation:
    1. Go to the "Contact" Page
    2. Attempt to submit the form with out filling in the fields, and verify error message shows up.
    3. Attempt to submit with only the name field filled out, ensure name field goes green and rest goes red.
    4. Repeat on all other fields that are required.
    5. Fill in all required fields and ensure form submits 
    

### Bugs:

1. Home page: Contact Me button only works when you click the text "Contact me"
2. Contact : Form accepts incomplete emails when validating.



## Deployment

This site is hosted on github pages.The page is being hosted directly from the master branch, that way any updates that are committed will be updated straight away.  
By using the file name `index.html` github pages knows what file to display as the main page, with out this you GP wont know what to display.

### Running Code locally:


1. Using Download:
    1. Navigate to `https://github.com/danielclements/TJ-Dean-Portfolio`.
    2. Click the green button that says "Clone or Download".
    3. Click download zip.
    4. Extract zip file.
    5. Import in to preferred IDE.

2. Using Git Clone:
    1. Open terminal in preferred IDE.
    2. Type "git clone https://github.com/danielclements/TJ-Dean-Portfolio.git"
    



## Credits

### Content
- The text for the bio section was written by me.

### Media
- The photos used in the portfolio section were provided by [TJ Dean](https://www.facebook.com/tjdean97)
- Background for the Home section was provided by [Pexels](https://www.pexels.com/)

### Acknowledgements

- I received inspiration for the FAQ section from [Nintendo UK](https://www.nintendo.co.uk/Nintendo-Switch/Nintendo-Switch-Online/FAQ-1374625.html).
- I used code by [Chris Coyier](https://css-tricks.com/perfect-full-page-background-image/) to add full view height background images.
- The image gallery in the Portfolio section was created by [Fancybox](https://fancyapps.com/fancybox/3/).
- Background gradient provided by [W3schools](https://www.w3schools.com/css/css3_gradients.asp).
- Code for color changing Navbar was taken from [Stack Overflow](https://stackoverflow.com/questions/23706003/changing-nav-bar-color-after-scrolling).


Addresses, emails and phone numbers are all fake! 

Live version of the site : https://danielclements.github.io/TJ-Dean-Portfolio/