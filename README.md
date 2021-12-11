# Cork Grappling Academy

The website is for a grappling club based in Cork, Ireland. The club offers Brazilian Jiu Jitsu(BJJ), No-Gi & Judo classes. Users of this site will be able to find out a little bit about all classes offered, when the classes are on(timetable) and get in contact to arrange a class. The site is aimed for anybody who has an interest in learning BJJ, judo, self defence and getting fit and making new friends.

You can view the live site here [Cork Grappling Academy](https://adrian-1990.github.io/bjj-homepage/)

You can view the respository here [Github](https://github.com/adrian-1990/bjj-homepage)

![responsive](https://user-images.githubusercontent.com/79532281/144610386-e468e6af-0da0-405e-8112-a6cc9dc04e5e.png)

# UX - User Experience Design

## User Stories

The site is created for anybody who has an interest learning about what Cork Grappling Academy offers. 

* New users can learn about the club, what classes it offers and when the classes are on.
* Return visitors can learn a bit more about the club through the social media links.
* Anybody intrested in joining or visiting can make contact with the club through the contact form.

## Design Process

When I began to design my website I went back over the User Experience Essential module that we done earlier in the course and followed the 5 pillars of User Experience Design (UXD) in my design process to create a positive experience for those using the site.

* **Strategy** - What am I aiming to achive with this site and who is the target user.
* **Scope** - What features do I want on the site and reason behind them.
* **Structure** - How will I structure the site, what informaion will I have on each page.
* **Skeleton** - Wireframes created to see how the site will look and how the user will navigate the site.
* **Surface** - The design choices for the site. What fonts will I use, images relevent to the site, color choices.

## Strategy

The users of this site will be people interested in learning about the club and potentially joining. The site needs to have relevent information available so the user can learn about the club. There should be a way for the user to contact the club either through email or social media.

## Scope

It's important for the site to contain information on the classes offered, what time the classes are on and a contact form for the user to make contact. The user will get information on the classes are offered and learn a little bit about the differant styles of grappling taught. The timetable will show what time the classes are on and what level the class is sutible for. If a beginner turns up to an advance class and does not have an enjoyable experience he might not come back so with the timetable they will find when a class sutible for them will be on. The contact form will allow the user to make contact with the club with any questions or queries they have.

## Structure

The structure of the site will consistant throughout the differant pages. The header will be at the top of each page to allow the user to navigate the site easily. Below the header will be the main section of the page will will contain all the relevent information for the page the user is on. At the bottom of the page will be the footer witht he social media links. When a user hovers over an interactive element it will change color to let the user know it is interactive.

## Skeleton

I created my initial design on Wireframe to get an for the layout of the site. I initially wanted to do a single page with four differant sections but as my design evolved I amended it to four pages. The navbar and footer will be present on all pages of the site. The navbar will allow for easy navigation between the differant page and the footer will accesss the social media pages for the club.

## Design 1 
![BJJ Wireframe layout 1](https://user-images.githubusercontent.com/79532281/144373892-66e070a6-c7b5-4075-8c54-57059cc16ce0.png)

## Design 2 
![BJJ Wireframe layout 2](https://user-images.githubusercontent.com/79532281/144374230-100d65fc-e90c-42dd-a2e9-ad75e774f00b.png)
![BJJ wireframe Classes](https://user-images.githubusercontent.com/79532281/144374252-b48502f8-6f50-4ebe-89de-fd9e1b144753.png)
![BJJ Wireframe Timetable](https://user-images.githubusercontent.com/79532281/144374269-d93772fc-d673-44ef-b312-cdf3dfc2974c.png)
![BJJ Wireframe Contact Us](https://user-images.githubusercontent.com/79532281/144374289-f6c1fdb0-8041-4fc8-90f3-4dcb24d0ba8c.png)

## Surface

All the design choices I selected will be consitant throughout the site to allow easier use and reduce user error.

### Typography

I chose two fonts for the site. I chose **"Cairo"** as my font for headings with **Sans-Serif** as back up. For my paragraphs / timetable body / forms I have use the font **"Mohave"** with **Sans-Serif** as back up. The fonts selected compliment each other well and give the site a modern look.

### Color Scheme

The color scheme uses a minimal pallet and gets the majority of color from the images on the page. When you hover over an interactive link they change color to catch your attention and encourage you to explore the site by clicking the link.

The colors I used were:
* lightgrey
* rgb(228, 58, 58)
* black

### Imagery

All the images used on the site were taken from [Unsplash](https://unsplash.com/s/photos/judo). This site allows you to download images for free. I wanted the images to display people practicing BJJ / No-gi grappling so visitors to the site would get an idea of what the club offered and encourage a return visit to learn more.
The images used on the site were quite large so I compressed them using [Tinypng](https://tinypng.com/).

# Features

## Site Structure

The site consists of four pages:

* Homepage
* Classes
* Timetable
* Contact-us

The navbar and footer will be present on all pages. This will allow the user to easily navigate the site and to get in contact via social media.

The code for the footer was taken from the Love Running project walk through.

```html
    <footer>
        <ul class="social-networks">
            <li>
                <a href="https://facebook.com" target="_blank" rel="noopener" aria-label="Vitis our facebook page(opens in a new tab)"><i class="fab fa-facebook"></i></a>
            </li>
            <li>
                <a href="https://twitter.com" target="_blank" rel="noopener" aria-label="Vitis our twitter page(opens in a new tab)"><i class="fab fa-twitter-square"></i></a>
            </li>
            <li>
                <a href="https://youtube.com" target="_blank" rel="noopener" aria-label="Vitis our youtube page(opens in a new tab)"><i class="fab fa-youtube-square"></i></a>
            </li>
            <li>
                <a href="https://instagram.com" target="_blank" rel="noopener" aria-label="Vitis our instagram page(opens in a new tab)"><i class="fab fa-instagram"></i></a>
            </li>
        </ul>
    </footer>
```

## Landing page

This is the default page when visiting the site. There will be a header with the club logo and nav elements. A main image of people training BJJ. A message about the club, images with links to the other pages on the site and the footer at the end.

* When you land on the page you first see the navbar and a large image of people training BJJ. This will let the user know how they can naviagate the site and give them an idea of what the club offers. As a first time visitor you will have how to navigate the site and the image is shows members training BJJ.

![welcome-section](https://user-images.githubusercontent.com/79532281/144607551-80567aee-3154-4735-8fb3-ec91756f90a9.png)

* As you scoll down you encounter the welcome text. This is a brief description about what the club offers. It describes the facilites, instructors and the club ethos. This will give users information about what the club is about.

![welcome-text](https://user-images.githubusercontent.com/79532281/144599886-4dab3c38-dfb1-4c9e-9f66-fdf46d2cb465.png)

* As you scroll down the page you come to a section with three images and links to other pageS. On a PC or laptop when the user hovers over the text under the images they will change color to rgb(228, 58, 58) and let the user know they can be interacted with and encourage the user to click the links and find out more about what the club has to offer.

![page-links](https://user-images.githubusercontent.com/79532281/144599615-9a8a0d92-f975-4aa9-be9c-52afad94b9ff.png)

* At the end of the page is the footer with the links to our social media links. Again these change color when hovered over to encourage interaction.

![footer](https://user-images.githubusercontent.com/79532281/144599646-200be01c-5074-410b-86a8-42b347a85c8d.png)

## Classes

This page contains the classes offered and a brief description of each class. There is an image of the class type to give a visual idea of the classes.

* The first class displayed is Brazilian Jiujitsu (BJJ). I wanted the user to learn a bit of the history of the art, what the key principles are and who teaches the classes.

![BJJ class](https://user-images.githubusercontent.com/79532281/145643123-e5bf698a-e3c8-43d4-9ae8-cf2307c366dc.png)

* The next section is the No-gi grappling section. This section informs the user of the differances between No-gi grappling and BJJ / Judo.

![No-gi class](https://user-images.githubusercontent.com/79532281/145642991-2dac91d2-4a1a-4a74-8a7e-120b754d6abc.png)

* The final section is Judo. This section has a brief description of the history of Judo, the key principles behind Judo and who will teach the classes.

![Judo class](https://user-images.githubusercontent.com/79532281/145642976-711cabdf-ab94-4a0f-8f4c-4a16da9609a1.png)

* The section will give first time visitors information about the classes offered.

## Timetable

This page has the timetable which displays what days and times the classes are on.

![timetable](https://user-images.githubusercontent.com/79532281/144608252-9ff3a960-2fad-49fb-bba2-a6349b7bc462.png)

* There is a description of the classes underneath the timetable so users know what is expected in each class. 

![timetable-classes](https://user-images.githubusercontent.com/79532281/144608445-4e4ee297-8aa4-4ef1-8d91-299a18fd2f5a.png)

* New users can find out about the times classes are running and return users can learn about the advance classes as their progress on their grappling journey. This section will provide all the info required for guests who wish to visit the club. 

* I used [W3School Table](https://www.w3schools.com/html/html_tables.asp) for guidance when creating the timetable.

## Contact Us

* Users can contact the club and ask any questions they have with the form provided. This can be used by new and returning visitors.

![contact-form](https://user-images.githubusercontent.com/79532281/144609682-b6d0f5e8-b15b-4c0c-9aff-d8c85f16857c.png)

* A video at the end of the page shows BJJ highlights and shows the user what BJJ is about. The video shows the benefits training BJJ can have and encourage the user to get in contact.

![video](https://user-images.githubusercontent.com/79532281/144610074-06eaa031-e74d-40b9-9a42-43cb03b03f6b.png)

# Future Features

Below is list of features I would like to add to the site to improve the overall user experience and improve the visual look of the site.

* **Club Shop**
  * I would like to create a club shop where members would be able to buy club merchendise (t-shirts, hoodies, stickers etc.)

* **Burger Menu**
  * I would like to create a burger menu for mobile and smaller screen sizes. This would improve the design when viewing on smaller screens and the users experience.

* **Testimonials**
  * I would like to create a slideshow showing members testimonials and their experience training at the club.

# Technologies Used

For this projects the main tecnologies I used are:

* [Balsamiq](https://balsamiq.com/)
  * Balsamiq were used to create the wireframes

* HTML
  * This was the main language used in creating the website

* CSS
  * This was used to style the website

* [Font Awesome](https://fontawesome.com/)
  * Font awesome was used for theicon images on the footer

* [Github](https://github.com/)
  * This was used as the host site for the code for the website

 * [Tinypng](https://tinypng.com/)
   * This was used to compress the images used

* [Google Dev Tools](https://developer.chrome.com/docs/devtools/)
  * This was used to test responsiveness of the page and test out changes before adding to CSS

# Testing

## HTML Testing

I tested my HTML in HTML Validator. I fixed all the errors and warnings that were appearing and now all the site passes the test.

![HTML validator pass](https://user-images.githubusercontent.com/79532281/145018193-62978b6d-8736-4f17-a2f5-06d59ea37c50.png)

## CSS Testing

I tested my CSS in CSS Validator I fixed the errors and warnings found in my CSS and the site now passes all tests.

![CSS validator pass](https://user-images.githubusercontent.com/79532281/145210812-26f0bfae-e5e8-4c39-bb70-7ea5269bac83.png)

## Lighthouse Testing

### Error

* When I tested my webpage page my site was failing on performence. This was because the images on the site were to large and taking a long time to upload.

 ![lighthouse test (2)](https://user-images.githubusercontent.com/79532281/143593501-f9058ba4-41da-48b9-94ba-e3e278d56a59.png)

### Solution

* I resized my images through https://tinypng.com/ and replaced all the larger sized images with the new smaller sized images. This improved performence and reduced delays in the page uploading.

![lighthouse bug fixed (2)](https://user-images.githubusercontent.com/79532281/143593858-521c7566-ced7-4359-a35e-cbf4f7641b7c.png)

## Bugs Found

### Video

When viewing the video on the live site the below error was appearing.

![youtube video](https://user-images.githubusercontent.com/79532281/144613466-c504655d-1929-4640-9a22-6beac8da54e4.png)

* I searched Google and found the issue to be in the link I copied over. The link had the video as /watch which is incorrect when embedding into code.

![youtube watch](https://user-images.githubusercontent.com/79532281/144613626-b4a10fde-857d-45f4-9062-ce7e8c8feb22.png)

* I amended the link to /embed and this fixed the error. Video is now working on the site.

![youtube embed](https://user-images.githubusercontent.com/79532281/144614218-7d72728d-c246-46f3-a0c7-36eacb4aa783.png)

# Deployment
## Project Creation

The project was created by using Github and Gitpod pages. I created the code through Gitpod pages and then backed them up to Github. This allowed me to create a live site via Github.

**To deploy the project**

The site was deployed to GitHub pages. The steps to deploy the site are:
1. In the Github repository, select the **Settings** tab.
2. Once in the setting, select the **Pages** tab on the left hand side.
3. Under **Source**, select the branch to master, then click **save**.
4. Once the master branch has been selected, the page will automatically create a link for your site.
![Github pages link (2)](https://user-images.githubusercontent.com/79532281/143587694-59346abd-5c08-4af6-bb4a-5b294b3ce4ec.png)

# Credits

## Content
* The fonts came from [Google Fonts](https://fonts.google.com/).
* The icons for the footer came from [Fontawesome](https://fontawesome.com/start).
* The footer code came from the Love Running walkthrough project.
* The responsive image at the top of the README was created by [Am I responsive](http://ami.responsivedesign.is/).
* The footer code and icons were taken from the Love Running walkthrough project.[Love Running project](https://github.com/adrian-1990/love-running)
* The text on the BJJ classes came from [Wiki BJJ](https://en.wikipedia.org/wiki/Brazilian_jiu-jitsu).
* The text for the Judo classes came from [Wiki Judo](https://en.wikipedia.org/wiki/Judo).
* The timetable was created with guidance from [W3Schools](https://www.w3schools.com/html/html_tables.asp).

## Media
* All the images for the page came from [Unsplash](https://unsplash.com/)
* The Youtube video was taken from [Youtube](https://www.youtube.com/c/stuartcooperfilms)
* The photos were compressed using [Tinypng](https://tinypng.com/)
