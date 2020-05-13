# Blanca Mármol Webpage
Fantasy writer

**(MS front-end project - Code Institute by Ángel González)**

This is the website for an indie fantasy author. The site includes a showcase of her publishings and information about them as well as options to see reviews and proceed to purchase. The domain also includes a blog section and an about section with information like biography, next events or social feed. Finally, there's a contact section for fans, event or enquiries.

## UX
### User stories
Users of this webpage will be both fans and editors browsing the writer content for possible engagement in events and/or contracting.

The site **navigation bar** is very clear and as a user I can select the path desired easily, see next section.

[Homepage](/assets/images/screencaptures/Home_full-min.png "Home browser preview"), as a fan or editor I get to know the writer's latest title, which is the objective, also get a glimpse of the next events involving her.

[Titles](/assets/images/screencaptures/Titles_full-min.png "Titles browser preview") and [Reviews](/assets/images/screencaptures/Reviews_full-min.png "Reviews browser preview"), as a fan, I can browse through the current publishings and also get to know the name of the next title to be published; as editors I get information about the work in progress to maybe contact the write about it.

[About](/assets/images/screencaptures/About_full-min.png "About browser preview"), as a fan, I get to know more about the writer through the biography. Both as a fan and editor I find the whole agenda and have accessibility to contact her if needed.

[Blog](/assets/images/screencaptures/Blog_full-min.png "Blog browser preview"), as a fan, I love to get to read more content by the writer. As editor I find interesting to maybe get an angle to know her better before trying a commercial approach.

[Contact](/assets/images/screencaptures/Contact_full-min.png "Contact browser preview"), both as a fan and editor I find an easy way to easily reach the writer.

Check also homologue Landing page at a mobile device preview: [Homepage](/assets/images/screencaptures/Home_smart-min.png "Home phone preview").

### Strategy
The goal is to disseminate the site user towards their goal as soon as possible (via an intuitive navigation bar). But at the same time we want to promote the latest book launched in a very visual and attention gathering way to expand interest (via hero content).

Defined and clean navigation with clear section titles:

![Navbar-browser](/assets/images/screencaptures/Navbar_full-min.jpg "Navbar browser")

Small device navigation is collapsed and clean when opened:

![Navbar-phone-closed](/assets/images/screencaptures/Navbar_smart-closed-min.jpg "Phone browser")
![Navbar-phone-open](/assets/images/screencaptures/Navbar_smart-open-min.jpg "Phone browser")

### Scope
We want to take the make it easy for the users to access the different section that they were searching and also make them know the author's latest work to potencial the selling and also amplify interest.

### Structure
Header and footer stay fixed keeping the user familiar with the site environment. The main section is what changes from one page to the other:

* "home", displays the latest launched title and a peak of the author's agenda
* "titles", allows browsing through the author publishings
* "reviews", allows browsing through the publishings public reviews
* "about", includes full agenda, the author biography and a social feed
* "blog", displays the author's blog with an index
* "contact", allows contacting the author via a form

### Wireframes
Some original keyframes designed with the writer. Style improved overall during w.i.p.

Landing Page browser: 

![Landing-page-browser](/assets/wireframes/1_Pc_Main.png "Landing page browser")

Titles Page small device: 

![Titles-page-phone](/assets/wireframes/2_Phone_Works.png "Titles page phone")

Reviews Page browser: 

![Reviews-page-browser](/assets/wireframes/3_Pc_Review.png "Reviews page browser")

About Page small device: 

![About-page-phone](/assets/wireframes/4_Phone_About.png "About page phone")

Blog Page browser: 

![Blog-page-browser](/assets/wireframes/5_Pc_Blog.png "Blog page browser")

Contact Page small device: 

![Contact-page-phone](/assets/wireframes/6_Phone_Contact.png "Contact page phone")

### Surface
Color pattern following the latest book launch is kept consistent throughout the site with contrast and complimentary colors when needed for indicators, cta's and hover effects.

![Color-pattern](/assets/images/screencaptures/Color_pattern-min.jpg "Color palette base")

## Technologies Present
1. HTML
2. CSS
3. Bootstrap (4.4.x)

## Features
This site consists of six different pages, however they all keep the same structure to help the user establish familiarity as it browses throughout.

* Fixed **header and navbar**: navigation is fixed under brand name but shows collapsed on small devices on top left corner.

* Fixed **footer**: footer parallels the header position and colours. It contains a "pop-up on hover" copyright disclaimer on the left side and social icons on the right end with a small hover animation.

* Landing page (**Home**): contains a hero banner that takes all the available space. A button placed in it allows to access the purchase of the promoted title. Downwards a sample of the agenda is shown, with a button that allows access to the whole agenda in it.

* **Titles** page: showcases title covers beside the synopsis in a carousel. A button to access the purchase is included.

* **Reviews** page: showcases title covers beside the reviews in a carousel. A button to access the site where the review was placed originally is included.

* **About** page: contains the full agenda with a button underneath that forwards the user to the contact page for new event proposals. Biography of the writer appears here and also a social media feed on large screens.

* **Blog** page: showcases the blog entries of the writer with newer on the top part. There is an index fixed on the right side on large screens. There are also "back to top" buttons on the end of every blog entry to facilitate navigation.

* **Contact** page: features a form that alows user to contact the writer for diferent reasons. Form has several required fields and prompts a message once submitted.

The whole site has response from small device to large screen, moving sections from sideways to top/bottom when needed to achieve best display. Not responsive on 4k at the moment.

### Future Features Objectives
As the project didn't involve anything but HTML and CSS, I didn't implement but kept for future practice/development:

* Real time social feed in about.html (Jquery code to present a real time feed instead of having to manually update)

* The Carousel feature will be replaced by interactive tabs, making it easier to target from one page to the other making the relation between titles.html and reviews.html closer in order to facilitate transference from one to the other easing UX

* Making contact.html form actually work with PHP and DB

* 4k response

## Testing
During the development, using Brackets by Adobe and its built-in live preview made it very easy to adjust response and test the majority as was coded.

After finishing the coding, used "HTML validators" and "CSS lint" checking for possible warnings or errors. Some CSS warnings for possible errors in some browsers were fixed (providing color fallbacks, for example).

**Display:** tests were made on browsers, tablets and phones. Giving this last ones problems with the background image in some of the pages. The display problem was solved by resizing down the image itself.

**Buttons (interactions):** tests were made manually in different devices, ensuring users can successfully access and navigate through the whole domain via using them.

**Links:** tests were made manually, ensuring they all lead to either a new tab or the intended path inside the site. 

**Form:** tests were made manually, ensuring the required fields are working as intended and the prompt message displays.

### Notes
In general, custom scrollbars dont work off "-webkit" browsers.

On reviews.html, users that submitted reviews are made up and links go to generic sites to avoid personal information issues.

Also take account that, despite all required fields to press "submit", the form in contact.html doesn't do any "action" and has no "target" either.

## Deployment
This site is temporarily hosted on GitHub Pages, from Master branch.

Deployment on Pages was made only before submitting the project for final testing. The project was kept on Brackets "live preview" for modifications, even though it was committed to GitHub and updated via GitBash on a frequent basis. 

## Credits

### Content & Media
All materials displayed belong to Blanca Mármol and all the site designs belong to Angel González.

**Disclaimer:** This site and its contents or any portion thereof may not be reproduced or used in any manner whatsoever without the express written permission of the publisher except for the use of brief quotations in a book review. Copyright © 2020.

### Acknowledgements
Great help from the documentation of these two sites:

* https://www.w3schools.com/
* https://getbootstrap.com/

Really incredible work this people do for the coding community, especially for beginners. Huge shout out.

Also a small note to mention **"https://css-tricks.com/"** where I did find not the specific solutions I was trying, but got plenty of inspiration from the solid amount of snipets posted and shown there.

## Contact

**E-mail:** a.cruzana88@gmail.com :technologist:

**Slack-id:** U012EE0G6CR :speech_balloon: