# Portfolio_April_Reitan


## Description

The task was to create a deployed portfolio website for my work that scales for different media screen sizes. This included creating an HTML file and a CSS file with no beginning code. I had a .gif file to work from with a suggested layout. Please see the example screenshot and my website screenshot below.

Example Screenshot from .gif layout

![Example Portfolio Website](/assets/images/portfolio_example.png)

Screenshot of Deployed Portfolio Website

![Portfolio of April Reitan](/assets/images/Portfolio_April_Reitan_Pic.png)


## Process

After creating a GitHub repository for this project, I drew out a sketch on paper of how the layout should look to look to match the example. Then I started creating an index.html file. I tried to break the example website up into logical blocks--the pieces from biggest to smallest--that were needed to recreate the same layout as the example picture. I started with the biggest blocks and worked my way down to the details. Then I worked through styling in the my style.css for layout, color scheme, and effects. See the links to my repository and the portfolio website below.

- [April Reitan's Portfolio Git Hub Repository](https://github.com/areitan/Portfolio_April_Reitan)
- [April Reitan's Portfolio Website](https://areitan.github.io/Portfolio_April_Reitan/)


### Wireframing

1. I used pencil and paper to make a sketch of the website layout to determine the best way, using the tools I have a the moment, to acheive a similar layout to the example.


### index.html

1. I started a generic HTML document with DOCTYPE, HTML, head, and body.
2. I started by adding ```<meta>``` tags to the header for language and viewport size and a ```<link>``` to my style sheet "style.css".
3. In the body, I added a ```<header>``` tag with internal ```<nav>``` links to the sections in the page. 
4. I gave the webpage a descriptive ```title```.
5. I also added a heading, a background picture, and a picture of myself to the ```header```. 
6. I added a ```main``` tag for the main content of the page where I added 2 sections (About me and Work) and a footer for my contact info.
7. To the About Me section, I added an ```<h2>``` header and some text to tell about myself. 
8. To the Work section, I added an ```<h2>``` header used an ```<a>``` tag combined with an ```<img>``` tag to make images that are links to my repositories. 
9. Since I only have 2 projects as of the end of this project, the other links are to music to enjoy while you wait for my next projects.
10. I added text to use as titles for the picture links.
11. To the Contact Me footer, I added an ```<h2>``` header and some text and links to my email and GitHub profile.


### style.css

1. I added variables for common properties to make managing some of the styling easier.
2. I styled the header with a background image and used flex box to determine how the section should layout.
3. I added a media query at the end of the file so the website would display properly on different screen sizes.
4. I added styling and flex for the about-me, work, and contact-me classes. All three of these classes have the same styling for consistency.
5. Within the work section, I added a class I called grid to control the layout of the links to my work.
6. I gave the first work link an image that is larger than the others.
7. I added positioning and styling in order to place text from the HTML as a title or caption on top of the images which are links to my work.
8. I added a media query at the end of the style.css file so that the page will display differently for different screen sizes.
9. I added a pseudo-class ```:hover``` selector to my links and images in my work and contact me sections to add a border and/or change the background color when the cursor hovers over them. 


## How To Contribute

In order to create this website, I used the skills I have at the moment. I am open to suggestions, if there are ways to streamline the code.


## Credits

- [Net Ninja: CSS Flexbox Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9i3FXJSUfmsNOx8E7u6UuhG)
- [Mastery Games: Flexbox Zombies](https://mastery.games/flexboxzombies/)
- [MDN Web Docs: Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
- [MDN Web Docs: Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
- [W3 Schools: HTML Links](https://www.w3schools.com/html/html_links.asp)
- [Pexels stock photos](https://www.pexels.com/)
- Trilogy Education Services, LLC for the example .gif
- Travis Bates, a classmate, who shared a screenshot of the .gif example
- Chris Baird, my tutor, helped me smooth out the rough edges.





