![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/assets/images/website-mockup-generator.png)

# The Lambretta Circle

---

## Aim of the site

The Lambretta Circle Club is more than just a website, where likeminded enthusiasts of lambretta owners
can find all the imformation about their local club and social events in Gloucestershire.

With the easy and intuitive navigation menu, the user can find themself inmerse in a world of Lambrettas to either find information about the club or social events. Where they can submit their interest to join.

---

## UX

This is a website where the user can find information about a Gloucestershire lambretta social club.

* The visitors can submit their details to join the club.
* The visitors can see a gallery of photos about Lambrettas.
* The visitors can find out where will be the future social events.

In order to achieve this, the client wanted a website which meets the following criteria:

1. A maximum 3 pages long website.
2. Plain simple colors theme with blue and white feel.
3. Small amount of photos displaying Lambrettas.
4. A couple of comments from members about the club and the social events organised in the past.
5. A form where the visitors can submit their details and comments to join the club as members.

---

## Client Stories

"Another visitor wanted to read about the experience of other users."

"A visitor wanted to see photos of other lambrettas in the club".

"A visitor wanted to find out more information about the social events by submiting a form."

"An visitor wanted links to the different social media."

---

## Features

### - A slide of photos

* Three Images slide on a carousel style at the top of the website

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/carousel-slide.png)

### - Members Experience 

* A couple of members comments about the club and their experience in social events.

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/members-comment.png)

### - Gallery 

* A showdown of images of Lambrettas

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/gallery.png)

### - Contact Form.

* A form where the visitor can submit their details and possible comment about the website or interest to join the club

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/contact-form.png)

### - Address and Social Media links

* The address and social media 

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/address-section.png)

### - Burger dropdown menu

* A burger style where a dropdown menu with 3 choices "Home", "Gallery", "About Us". Links to be implemented in the future.

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/dropdown-menu.png)

## Wireframes Mockups:

### Desktop

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/the-lambretta-circle-desktop.png)

<br>

### Tablet

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/the-lambretta-circle-tablet.png)


<br>

### Mobile

![](https://raw.githubusercontent.com/Dhracko/the-lambretta-circle-club/master/wireframes/the-lambretta-circle-phone.png)

---

## Future Goals

* The introduction of another page where members can post their own images and comments of social events they have taken part, either with the club or a different organiser.

* The implementation of a drop down menu from a burger icon fixed at the top.

---

## Technology Used

* HTML & CSS programming languages
* [Bootstrap](https://getbootstrap.com/) - to easily adapt the website to be responsive for all users. Version 4.4.1
* [Google Fonts](https://fonts.google.com/) - Chango and Mukta Styles
* [Font Awesome](https://fontawesome.com/) - Social Media Logos version 5.0.0
* [GIT](https://git-scm.com/) - Version Control
* [GitHub](https://github.com/) - to host the repositories for this project and the live website preview
* [Balsamiq Wireframe](https://balsamiq.com/) - to create the Wireframes Mockups
---

## Testing

Initially i was using the evelopers tools from Google Chrome to make sure the colors and the code was the correct one, making sure the project look good on mobile devices first and build up from there.

I also used the tools below:

* [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) to help to locate the overflow and position of the diferent containers.

* [W3C Markup Validation Service](https://validator.w3.org/) to check the markup validity of the HTML.

* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) to validate CSS file.

Finally i tested in different browser:
* Google Chrome Version 81.0.4044.122 (Official Build) (64-bit)
* Firefox Version 75.0 (64-bit)
* Microsoft Edge Version 44.18362.449.0
* Opera Version 68.0.3618.46

### Issues and resolutions

During my first conversation with my mentor he pointed out about the README.md updates. Wireframes placed in the github, divided wireframes for each individual feature. Also the version library of the techonoly used.

During the creation of the different feature i came across some issues:

* After the creation of the carousel slider at the top, the images expanded 0.1% which meant that after the first image the second would revert to the original size container which made an abrupt jump on the size. The solution was adding 2 containers on top of the initial so the 0.1% on each side would be cover, also gave a gradient look so it wouldn't look like 2 container placed on top of the initial.

* During the second feature "members fedback" I couldn't center the 2 icons "Lambrettas" to the center of the text, which was easily resolve at the end with a top padding to bring it down.

* The initial size of the lambretta images where too big and having to customized each one using idividual classes would have been too much coding resulting in a confusing ccs file so instead i apply individual heigh and width in the html code. Also while my initial idiea wasn't of a border and shadow for the images, the implementation of them makes the mobile version more attractive.

* On the last feature "Form", I though it needed a sense of aproach to the visitor, that it didn't have any attractive  for the visitor to leave the details or comments so i created a more small title and a chane of lettering. Also while creating the form using bootstrap on the last section about leaving a comment, the bootstrap code didn't fit the the uniformity of the rest of the form as it was creting the box under the "comment" text instead of side to it, so I had to change the original bootstrap code.

* When I coded the http links for the social icons, the icons turn blue instead of the the black as intended. This was easily rectified by adding color:black to the icons class.

* Finally during the use of the validation the W3C markup, I found there were a problem with the section and the missing heading on each section. I added a heading to each section that was missing one.
---

## Deployment

In order to deploy the project I did these steps:

1. I went to the repositories [the-lambretta-circle-club](https://github.com/Dhracko/the-lambretta-circle-club).
2. on the top right click at Settings.
3. Scroll down until the section GitHub Pages.
4. Within that section there is a scrolldown option in "Source" and select "master branch".
5. Once the page has refreshed, scroll down again to GitHub Pages and a new link should have appeared with the link: https://dhracko.github.io/the-lambretta-circle-club/.

To run the project locally:

1. Go to the repositories [the-lambretta-circle-club](https://github.com/Dhracko/the-lambretta-circle-club).
2. Click on the green button that says "Clone or download".

3. To clone the repository using HTTPS, under "Clone with HTTPS", click . To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click .
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.

6. Type git clone, and then paste the URL you copied in Step 2.

> $ git clone https://github.com/Dhracko/the-lambretta-circle-club

7. Press Enter. Your local clone will be created.

Further information on how to clone a repository can be found [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## Credits

### Content
All the images have been obtained from different royalty free images:

* [flickr](https://www.flickr.com/)

* [freeimages](https://www.freeimages.com/photo/15-vespas-1422685)

* [pixabay](https://pixabay.com/photos/motorcycles-wasp-lambretta-san-leo-775453/), (https://pixabay.com/photos/lambretta-wasp-moto-2003276/)

* [Pexels](https://www.pexels.com/photo/architecture-automotive-building-cafe-221299/)


### Acknowledgements

* I would like to thank Rohit Sharma (my mentor) for his invaluable feed back, help and advice.

* [Simen Daehlin](https://github.com/Eventyret) for the fatastic Unicorn Chrome add-on.

* [Richard Wells](https://github.com/D0nni387) 



## Disclaimer
Please note the content and images on this website are for educational purposes only.