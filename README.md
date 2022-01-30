# Sandwiches of Dublin

Sandwiches of Dublin is a site which the user can use to find the best sandwiches in Dublin and also add their own suggestions as to what those sandwiches are via the contact page. The user will also be able to subscribe to a newsletter, which will keep them up to date on all of the sandwich related happenings in the city. As stated in the manifesto, Sandwiches of dublin exists to create an easy to understand guide to help the user find the amazing sandwiches nearest to them and to build a community of like minded sandwich connoisseurs. 

In addition to the contact page, there is an interactive sandwich map page that gives the user an oportunity to view the best sandwiches in each postal code of Dublin. There is also a gallery of sandwich images, which will be updated as the site grows in participation. The overall intention of the site is to give both an education about the sandwiches in dublin, and to create a community of like minded sandwich lovers.

![Mockup](https://github.com/nschloesserm/project1/blob/379b58c6b693804846678981867ccaf6f5303dc6/assets/images/mockup.png)

## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all of the pages of the webiste, the navigation bar includes the title of the website which adjusts and changes with the screen size. It also has a home button which returns the user to the first top of the page. Finally, it has a menu which, when hovered over, displays the sandwich origins and manifesto in page links, and the links to the Sandwich Map, Gallery, and Contact pages.
  - The home and menu part of the navigation bar is sticky, which allows the user to have access to them at all time and in all formats. This gives the user access to all parts of the site without the need of the back button or unnecessary scrolling.

![Nav Bar](https://github.com/nschloesserm/project1/blob/e2d0eec6f8b85f6606c83f3fb593a4c45c6d5ae4/assets/images/nav-bar.png)

- __The landing page image__

  - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Landing Page](https://github.com/nschloesserm/project1/blob/d191eee24836acf3c88da42352e134054a5098b9/assets/images/landingscreen.png)

- __Sandwich Animation Section__

  - The sandwich animation was added ain an effort to draw the user into the website and guide them to continue scrolling through the parrallax images between the section.
  - It is an eye catching way to keep the user interested and is done with layers of PNG files animated with css to create the effect of the opening and closing sandwich.

![Sandwich Animation](https://github.com/nschloesserm/project1/blob/436a9022fa345b69b06a28c19f28d6bb59f88c5a/assets/images/sandwich-animation-page.png)

- __Sandwich Origins Section__

  - This section gives the user a brief and fun introduction into the history of where sandwiches originated.

![Meetup Times](https://github.com/nschloesserm/project1/blob/436a9022fa345b69b06a28c19f28d6bb59f88c5a/assets/images/origins-page.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Sandwiches of Dublin.  Each link will lead to the relevant social media site connect to Sandwiches of Dublin.
  - The footer allows people to connect through social media, and has a fun inverted color scheme when hovered over.

![Footer](https://github.com/nschloesserm/project1/blob/bbb1b61771ab8e15286847ff74ff61ccb68aa698/assets/images/footer-page.png)

- __Sandwich Map__

  - The map provides an interactive way to see the best places to get a sandwich in each of Dublin's postal codes.  It also shows the user where Sandwiches of Dublin has yet to find the best sandwich, encouraging them to give sugestions.
  - This section is very useful in finding the best sandwiches in Dublin. 

![Map](https://github.com/nschloesserm/project1/blob/5b63b554be099412a59fcaf39ab528314d5cf3bb/assets/images/map-page.png)

- __Gallery__

  - This page allows the sandwich loving user to see some images of some of the best sandwiches in the area, as well as get to have more intimate acces to the website owners and their sandwich adventures. 

![gallery](https://github.com/nschloesserm/project1/blob/436a9022fa345b69b06a28c19f28d6bb59f88c5a/assets/images/gallery-page.png)

- __Contact Page__

  - This page will allow the user to contact the website owners with sugestions for sandwiches in the Dublin area, or with any comments about the site.  It also gives the user a chance to sign up for the Sandwiches of Dublin Newsletter with their email address.

![Contact](https://github.com/nschloesserm/project1/blob/436a9022fa345b69b06a28c19f28d6bb59f88c5a/assets/images/contact-page.png)

### Features Left to Implement

- One ideal feature would be an event page or an event callender. This would give more opportunity for interation between the sandwich loving community in Dublin.
- Another feature that I would like to add is the ability for the user to submit their own images, and for those images to instantly be a part of the gallery.

## Testing 

Using the developer tools of the browser, I was able to adjust the position and sizing of the elements using media queries.  This was mostly a process of trial and error, systematically adjusting for the size of the screen.  Then I ran a series of lighthouse test to make sure the website was running efficently.  The result of that can be seen in the pdf links below.  I firsts ran these test through the server created in gitpod, then on the github pages final site.  Occasionally having to readjust my media queries to make the site run smoothly regardless of screen size.

[Lighthouse Main Page](https://github.com/nschloesserm/project1/blob/c16e4d5c190666ed96b39207ec85b699e25d452e/assets/images/index-lighthouse.pdf#L1)
[Lighthouse Map Page](https://github.com/nschloesserm/project1/blob/c16e4d5c190666ed96b39207ec85b699e25d452e/assets/images/map-lighthouse.pdf#L1)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

There were some bugs left unfixed with the external links on the map, but it still functions well.  In retrospect, the interactive map feature would have probably functions better ans some sort of iframe google map setup or a map made with JS. Though I thought that the boutique aspect and style of the map was an important feature to the sight.  I also had a "favicon.ico failed to load" error, but after some forum surfing an easy fix was discovered.

## Deployment

The live link can be found here - https://nschloesserm.github.io/project1/ 


## Credits 

### Content 

- The code for the parrallax scrolling, the dropdown menu, and the CSS animations was learned through tutorials at https://www.w3schools.com/
- The footer and the contact form code came from the love running Essentials project through the Code Institute tutorials.
- In order to get the corrodinates for the map image I used http://www.image-map.net/
- The interactive image map and pop ups were implimented with code from a tutorial on Medium entitled "Interactive Image Maps and Closable Popups with HTML and CSS only" at https://matemarschalko.medium.com/interactive-image-maps-and-closable-popups-with-html-and-css-only-31fe36c70092
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Some of the fonts were taken from [Google Fonts](https://fonts.google.com)
- The text for the Origins section of the sight was taken from [Wikipedia](https://en.wikipedia.org/wiki/Sandwich) and [History.com](https://www.history.com/news/the-story-of-the-sandwich) articles


### Media

- The photos used throughout the site, with the exception of the map pop ups, came from the free stock images site https://www.pexels.com/
- The images used for the pop ups came from the sites for the restaurants linked directly beneath them.
- The painting featured in the Origins section came from https://en.wikipedia.org/wiki/John_Montagu,_4th_Earl_of_Sandwich and is by  Thomas Gainsborough.