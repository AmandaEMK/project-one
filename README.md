# A website for The Monkees

This is a website for a band called The Monkees. The band wanted a website on which their fans could listen to their music, watch videos and book them for their events. They also wanted their photos displayed and for there to be links to their YouTube and social media profiles.

## Demo

You can find a live demo of the site [right here](https://project-one-amandaw.c9users.io/).

## UX
 
The target audience of this site is fans (and potential fans) of The Monkees, of which many are not digital natives. I therefore wanted to make a easy to use, fast loading, no-frills one page website with a clean UX that anyone could navigate either on desktop, tablet or a smartphone. I made the wireframes with desktop in mind, but the goal was always to make the website look good and funtion well on all major devices. I made it responsive by making sure to use percentages instead of px whenever possible, and using Bootstrap columns for the layout.

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

### Features Left to Implement

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

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.


In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.


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

The project has been backed up using Git. It is deployed on GitHub Pages. The development version and the deployed one are the same.

## Credits

### Content
- All information and text on The Monkees was taken from [their Wikipedia article](https://en.wikipedia.org/wiki/The_Monkees)

### Media
- The photos used in this site were obtained from the modules asset folder

### Acknowledgements

- Navbar was taken from here and then customized [Bootstrapdocs](https://bootstrapdocs.com/v3.3.6/docs/components/#navbar)
- Basic form snippet from here [Bootstrapdocs](https://bootstrapdocs.com/v3.3.6/docs/css/#forms)
- Parallax scrolling taken from here and then customized [W3Schools](https://www.w3schools.com/howto/howto_css_parallax.asp)
- Browsing through [CSSTricks](https://css-tricks.com/) has helped me agreat deal
- Learnt how to make icons accessable here [FontAwesome](https://fontawesome.com/v4.7.0/accessibility/)
- Balsamiq was used to create the wireframes [Balsamiq](https://balsamiq.cloud)