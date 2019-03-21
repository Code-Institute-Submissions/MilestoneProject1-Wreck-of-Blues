# Pontus Snibb's Wreck of Blues

First Milestone project for Code Institute: User-Centric- Frontend Development.

A central website to show and advertise the band "Pontus Snibb's Wreck of Blues."
Currently the band has a lot of content on many different sites and this website should provide a central location so viewers can observe, example and interact with the band.

## Demo
You can view the website live on [GitGub Pages](https://brendanoshea84.github.io/MilestoneProject1-Wreck-of-Blues/).

## UX

 This website should help prospective clients to sample the band by highlighting their performance and keep viewers up-to-date with coming shows. 
 At the moment the band uses spotify, youtube and facebook as their main out-sourcing of their material. This site should help centralize their material, ensuring easier access for viewers under one site.

The band has their own style which this site tries to stay true to as well as using a stark contrast with orange to highlight and pop important information. 
As the band already has a lot of internet sources, this site centralizes these sites and also provides quick links. Therefore while this site showcases many of the highlights, 
it further encourages viewers to view their other source material. 

## Technologies

1- Html
2- Css
3- Bootstrap 4

## Features

### Navbar

Navbar is in a fixed top right position allowing users quick access around the page. Its a button that stays open until clicked and has quick links to the different sections.
The background is an opaque orange that highlights over the background without overpowering the page. 

### Introduction 

The site opens to a strong welcome page of the band with a quote, in Swedish, from Pontus Snibb. An eye catching "Latest News" in a contrast of orange against the soft blue 
highlights the next gig and their lastest song. 

### Tour Shows 

The bands next gigs/shows posters are advertised, also a quick link to their Facebook page for more detailed information on their shows.

### Music 

An embedded Spotify player which plays their current and previous album. The Spotify player allows for 30sec of samples before asking to join spotify for free, or if already a member a quick access to Wreck of blues. In Sweden spotify is a very common app on devices.
 
### Video 

A Youtube embedded player that shows a live 12min performance of the band. This shows the skills and the interaction of the band towards the audience. 
This is a show case if viewers would like to hire the band for private parties or gigs, or are simply interested in what they sound like live.

### Contact form 

Allows future customers to approach the band to increase bookings for the band or to ask questions.
The form is not currently complete, for the writer has not learnt the next process. 

### Social link 

A quick link to other sources for the band.

### Future Inclusions

At the moment the band's merchandise is limited but the band wants to increase their stock. When this happens, a merchandise area on this site will be needed.
At current the only object you can physically purchase is their albums from Amazon. 
The band has said merchandise is not as important, it will however be a needed feature in the future. 
An extra page for gig and tour photos should be included in future developments. 
 
## Technologies Used

1.- [9 Cloud](https://c9.io)
    - The project uses **9 Cloud** for creating the website.
2.- [GitHub](https://github.com/)
    - The project uses **GitHub** for backup saving and to host the site.
3.- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
4.- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** for website responsive and correct structure though out the site.
5.- [Font Awesome](https://fontawesome.com/)
    - The project uses **Font Awesome** modify text and use for social links and logos.
6.- [Google Font](https://fonts.google.com/)
    - The project uses **Google Font** modify text font.
7.- [Google Color Picker](https://www.google.com/search?client=firefox-b-d&q=css+color+picker)
    - The project uses **Google CSS Color Picker** to test and use correct colour schemes.

    
## Testing

### Introduction

Through out the project, the different sections has their own id. The navbar links has been checked and go to the right positions.
The Navbar is from bootstrap and has been modified by using the provided documentation. I did run into some problems for placement of the navbar for the right hand side.
 

### Latest News

Both buttons open links to outsourced material. First is to their next gig on facebook. Second opens youtube page. 

### Tour Shows

This area show cases future gigs/shows. Under is a quick link to their Facebook events. As up-to-date events happen, the posters will have a link to the events. At this time, the information about
these events are limited. At middle devices, one of the posters disappears allowing better visual appearances. Also shows the writer has an understanding of the process.

### Music

I used Spotify embedded players, for these was the only source to their music without purchasing the music tracks myself. Spotify has a free service where the viewer is able to listen to 30secs per track, 
before been told to 'sign in.' For a premium member, these players allow full access to these two cds. These players worked on the writers computer and tested on his personal phone.

### Video

To show different skill set, these video is embedded youtube and not a link to a youtube page.  

### Contact form

Form is not completed as such that the form will not submit but will reset. A mondal will drop, with a warning that the band is not taking any bookings as such. Once I understand the next process,
I will make these available for the public. 
At this moment, an error sign will open if the required field is not filled in (only address is optional).

### Social link

Social logos has been taken from [Font Awesome](https://fontawesome.com/) and been linked to outsourced material, like facebook, youtube, Amazon, spotify.
All these links will open new pages.

### Writer's Notes

My first attempt at this site was using Bootstrap v3. While the site looked correct, after talking to my mentor, the site was not a professional site. I was asked to redo the project and use the latest 
version of Bootstrap. While annoyed after working on the first version for some time, the second attempt did truly show a lack of knowledge of the first attempt. I spent allot more time reading the 
documentation of Bootstrap and I believe, I have a better understand of trouble shooting my own site.

A major problem I have, is the use of percentages in HTML. On this site I first used percentages on the iframes, I changed and modified iframes though CSS. While testing on [W3C Markup Validation Service](https://validator.w3.org/) this showed that I forgot
To add 'alt' to my pictures, the use of percentages on HTML and that some sections don't have any headings (Navbar). Another warning I received was the use of Swedish for the quote, as the main viewers for the site,
I believe leaving the quote as it is, is better than translating it back to English. I could have changed it just for the assignment, but by highlighting it here, I believe I have shown knowledge that I'm aware
of the issue and has a valid point. 

I also had issues with deplovement of the website on github. My files were named wrong, and also on the same level. After renaming the files, move the main.css to the assest folder and move the pictures into a new 
folder in the assests. After doing so, the site worked. 

## Deployment

You can see the website live on [GitGub Pages](https://brendanoshea84.github.io/MilestoneProject1-Wreck-of-Blues/).

This page was created using 9Cloud and hosted from GitHub. I deployed this site by logging in, choosing the right GitHub reposity and going into settings. By going down half the page, theres the option on making your 
site live. Then you website address is aviable. 


### Quote
Pontus Snibbs quote has been acquired from "Wreck of Blues" facebook page (Permission from Mr. Snibb).

### Media

All photos and videos has been given permission from "Pontus Snibb's Wreck of Blues." 
Photos has been gathered from "Pontus Snibb's Wreck of Blues" facebook and Google search.
Videos are from Youtube.
Music are from Spotify.

### Acknowledgements

Additional help from outsource pages

Modal-  https://getbootstrap.com/docs/4.3/components/modal/

navbar- https://getbootstrap.com/docs/4.3/components/navbar/

forms- https://www.w3schools.com/css/tryit.asp?filename=trycss_forms

spotify- https://developer.spotify.com/documentation/widgets/guides/adding-a-spotify-play-button/

Youtube- https://www.w3schools.com/HTML/html_youtube.asp

color finder- https://imagecolorpicker.com/

Spell checker- https://www.jspell.com/public-spell-checker.html