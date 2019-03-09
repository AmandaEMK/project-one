# A website for The Monkees

This is a website for a band called The Monkees. The band wanted a website on which their fans could listen to their music, watch videos and book them for their events. They also wanted their photos displayed and for there to be links to their YouTube and social media profiles.

## Demo

You can find a live demo of the site [right here](https://project-one-amandaw.c9users.io/).

## UX
 
The target audience of this site is fans (and potential fans) of The Monkees, of which many are not digital natives.
I therefore wanted to make a easy to use, fast loading, no-frills one page website with a clean UX that anyone could navigate either on desktop, tablet or a smartphone.
I made the wireframes with desktop in mind as default. As I was going along though, I switched over to a mobile first approach, which led to a few design changes.

### User stories

- As a fan, I want to see when they are touing next, so that I can buy tickets.
- As an event coordinator, I want to see if the are available for private concerts, and if they are I want to be able to contact them.
- As a long time fan, I want to listen to some of their songs to bring back old memories.
- As a fan, I want to be able to find out on where to follow them, so that I  can stay up to date.
 
### Wireframes

You can find the wireframes in the wireframes folder, on here or by clicking [this link](https://project-one-amandaw.c9users.io/wireframes/TheBand.png).

## Features

### Existing Features

- About - Allows the user to learn more or refresh their memory of the band and the members
- Music - Allows the user to see their discography, listen to a few of the songs and watch a video of theirs.
- Tours - Allows the user can stay up to date with tour dates and also buy tickets to them by clicking the button
- Book us - Allows the user to enquire about having The Monkees come play at their event by submitting a form
- Footer with social links - Allows the user to find and follow the social media sites that the band use

### Features Left to Implement (Imaginary)

- Photo gallery - Fans, old and new, would surely love it if there was a photo gallery to be found
- Shop - Minor one selling printed goods, or at least linking the album covers in "Music" to the Amazon page for the corresponding album

## Technologies Used

- HTML
    - Used to create the sctructure of the website

- CSS
    - Used to customize the look of the website

- [Bootstrap](https://www.bootstrapcdn.com)
    - Bootstrap was used to speed up development and help with the concistency of the websites layout

- [jQuery](https://jquery.com/)
    - To make Bootstraps JavaScript plugins function


## Testing

I was not able to automate any of the testing seeing as the website itself and my skills are on a very basic level. I did test the website on a range of different screen sizes using
Chrome dev tools in a structured way (top to bottom basically) to make sure there were no function hindering bugs or major design flaws on any screen size, but put my main focus on making it look good on iPhone 6 and screens bigger than that.
The CSS and HTML has been tested using [W3C Developer tools](https://w3c.github.io/developers/tools/).

### This is the process I went through to test my website

1.  Menu: 
    1. Click all links to verify that they work and bring you to the right section
    2. Also verify that where they bring you makes sense visually (no white spaces before section clicked etc)

1. About
    1. Verify that photos and text align properly and that the right band member photo/photos are displayed on the right screen sizes

1. Music
    1. Verify that photos, text and video align properly
    2. Click the play button next to the songs to verify that they open up in a new browser window to play
    3. Try watching the video to verify that it plays in browser

1. Tour
    1. Verify that photos, text and video align properly and according to screen size
    2. Try clicking the buttons to verify that they open up a new browser window to what would be a ticket website

1. Book us
    1. Verify that photos, text and form align properly
    2. Try to submit numbers as a name, an invalid email and letters as a phone number and verify that the form gives an error message
    3. Try to submit an empty form and verify that the form gives an error message to user
    4. Try to submit an invalid form (email is letters only) and verify that the form gives an error message to user

1. Footer
    1. Verify that the font size and the amound of space the footer takes up makes visual sense 
    2. Click the icons to verify that they open in a new window and bring the user to what would be the right corressponing social media site for each icons


### Differences in layout and function depending on screen size

The overall functionality and design is the same across all devices though there are some minor differences. On smaller screens, a group photo will be show in the about section instead of everyones individual photo.
Larger devices will have the albums next to each other in the music section, while smaller devices will find them stacked vertically.
Same thing will happen for the tour section, it will split into two sections (photo and text) and stack on smaller screens.
The little cartoon at the bottom of the website will move around depending on the device screen size, just thought it looked nicer that way.
The menu will turn into a burger style drop down menu on smaller screen in order to save pixels/space (is that the correct term even?).

### Bugs

- Not really a bug maybe but: the Parallax scrolling! Making the parallax scrolling look good on all devices was hard since I wanted both the curtains at the top of the photo and the entire drum that said "The Monkees" to fit on every screen size. I had to set different positions for different screen sizes using x% y% rather than center or top, and then adjusting the percentage of the screen that it would cover as well. I could have just gone with another picture I suppose, but why make it easy for yourself. It is still not perfect (iPad Pro vs desktop, which one to prioritize, ugh), but at lot better than when I started.

- The tour schedule was at first a table, which apart from the less-flattering gray bootstrap broders looked alright on larger screens. As in it looked awful on smartphones, began to scroll horizontally and everything. At the end of the project my mentor recommended me to simply use divs, which I did. 

### User stories testing

- "As a fan, I want to see when they are touring next, so that I can buy tickets."
    - The touring section offers an easy to comprehend list of upcoming concerts along with a "buy" button that opens a link in a few window (could be linked to an external website such as viagogo)

- "As an event coordinator, I want to see if the are available for private concerts, and if they are I want to be able to contact them."
    - The website clearly states that they are available for this and the form is easy to find. The form will not send unless the email address is vaild (aka has got an @ in it)
    
- "As a long time fan, I want to listen to some of their songs to bring back old memories.
    - Right net to their albums a track list is provided. Next to the songs, play buttons can be found. When clicked, the song will play in a few tab.

- "As a fan, I want to be able to find out on where to follow them, so that I  can stay up to date."
    - In the page footer, large icons representing the social media they are active on can be clicked on to open up a link to the corresponding profile of theirs in a new tab.

## Deployment

The project has been backed up using Git. It is deployed on GitHub Pages directly from the master branch. The development version and the deployed one are the same.

## Credits

### Content
- All information and text on The Monkees was taken from [their Wikipedia article](https://en.wikipedia.org/wiki/The_Monkees)

### Media
- The photos used in this site were obtained from the modules asset folder

### Acknowledgements

- Navbar was taken from here and then customized by removing unneccessary parts [Bootstrapdocs](https://bootstrapdocs.com/v3.3.6/docs/components/#navbar)
- Basic form snippet taken from here [Bootstrapdocs](https://bootstrapdocs.com/v3.3.6/docs/css/#forms)
- Parallax scrolling taken from here and then customized  [W3Schools](https://www.w3schools.com/howto/howto_css_parallax.asp)
- Balsamiq was used to create the wireframes [Balsamiq](https://balsamiq.cloud)
- My README is based on the template provided in the course