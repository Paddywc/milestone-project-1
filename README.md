# The Monkees Website
## Overview 
![Screenshot](https://i.snag.gy/VUqIeF.jpg)

## What is the website for?
To create a place where fans of The Monkees can listen to their music, book them for a private function, and keep up-to-date with their news and social media

### What does it do? 
Displays media of past private events featuring The Monkees, as well as a form that users can fill in to get a free booking quote. The website has audio and video collections of The Monkees’ music, along with hyperlinks to stores where users can purchase these songs. There are also forms where users can subscribe to various Monkees mailing lists. The website also displays the latest Monkees social media posts, and gives users the option to quickly follow these accounts.  
Please note that these forms and mailing lists are fictitious. No data is submitted upon completion of these forms

### How does it work?
Bootstrap enables the responsive, grid-based layout of the website. Certain photos change depending on the screen width of the user’s device, and some sections and features only appear on larger devices. [Google Material Design Icons](https://material.io/tools/icons/?style=baseline) and [Font Awesome Icons](https://fontawesome.com/) are used for the site’s icons, and keyframe rules are used for their animations. Most animations (e.g. buttons changing from grayscale to colour on hover) work via CSS selectors and transitions. HTML anchors enable navigation across the same page (e.g. clicking the down arrow in the header to navigate to the content). The collapsible cards are a feature of Bootstrap. YouTube videos are displayed as an inline frame (iframe). Audio clips are played via saved files in the project directory. Instagram images are embedded using the embedding code found on the [Instagram website]( https://www.instagram.com/developer/embedding/)

## Features

### Existing Features
-	A responsive design that adapts to phone, tablet, and desktop-sized screens
-	Hover effects that add or remove grayscale filters
-	Embedded photos, videos, audio files, and hyperlinks
-	A footer with website navigation and social media icons
-	Imported fonts that match the fonts used on previous Monkees’ album covers
-	Semantic HTML5 elements that improve SEO

### Features Left to Implement
-	None

## Tech Used

### Some of the tech used includes:
-	**HTML5**  and **CSS**
    *	Aside from some Bootstrap components which use JavaScript, the entire website is built using HTML and CSS
    *	CSS enables hover effects and transitions, such as page headers’ down arrows slowly fading in
    *	The down arrow scrolls to the main section upon click via HTML id anchors  
    *	CSS is used to display the image background, and to change their colour upon mouse hover
    *	CSS media rules enable the responsive design across various screen widths  
    *	CSS pseudo-classes are used to display icons and form titles within the input forms (e.g. displaying ‘Event Date’ before the date in the booking form)
    *	Element classes facilitate integrations with Bootstrap  
- [**Bootstrap**](http://getbootstrap.com/)
    *	The Bootstrap grid system is the source of the responsive, grid-based layout of the website
    *	Any JavaScript functionality in the website is a product of Bootstrap. This includes collapsible cards and carrousels.  
    *	Bootstrap content used includes cards, tables, and buttons 
- [**Online Web Fonts**](https://www.onlinewebfonts.com/), [**Google Material Design Icons**](https://material.io/tools/icons/?style=baseline) and [**Font Awesome**](https://fontawesome.com/)
    *	Imported fonts and font icons

## Deployment
The site is hosted on [GitHub Pages](https://paddywc.github.io/milestone-project-1/). The source of this code is the [gh-pages branch](https://github.com/Paddywc/milestone-project-1/tree/gh-pages) of the project GitHub repository. It mirrors the master branch in every way, with the exception of some media URLs.  The leading slash is removed for CSS imports from the project directory (“project-assets/..” rather than “"/project-assets/..”), and absolute, rather than relative URLs are used for the image sources. 

## Credits
-	Code for embedding Instagram code is from the [Instagram website]( https://www.instagram.com/developer/embedding/)
-	Kalligraphia, Hobo, Quotes, and Noteworthy  fonts are from [Online Web Fonts](https://www.onlinewebfonts.com/), 
-	Font icons are from [Google Material Design Icons](https://material.io/tools/icons/?style=baseline) and [Font Awesome](https://fontawesome.com/)
