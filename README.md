# Cork Grappling Academy

The website is for a grappling club based in Cork, Ireland. The club offers Brazilian Jiu Jitsu(BJJ), No-Gi & Judo classes.Users of this site will be able to find out a little bit about all classes offered, when the classes are on(timetable) and get in contact to arrange a class for themselves.The site is aimed for anybody who has an interest in learning BJJ or judo and learn self defence, get fit and make new frinds.

You can view the live site here. [Cork Grappling Academy](https://adrian-1990.github.io/bjj-homepage/)

![responsive (2)](https://user-images.githubusercontent.com/79532281/143540733-2d2d2aee-a63f-4626-bfd2-23e69c409fdf.png)

## Design process

I created my initial deisgn on wireframe to get a feel for the deisgn and layout. I initially wanted to do a single page with four differant sections but as my design evolved I amended it to four pages.

Below are the design ideas I had before eventully settling on my current design.

#### Design 1 
![BJJ Wireframe layout 1](https://user-images.githubusercontent.com/79532281/144373892-66e070a6-c7b5-4075-8c54-57059cc16ce0.png)

#### Design 2 
![BJJ Wireframe layout 2](https://user-images.githubusercontent.com/79532281/144374230-100d65fc-e90c-42dd-a2e9-ad75e774f00b.png)
![BJJ wireframe Classes](https://user-images.githubusercontent.com/79532281/144374252-b48502f8-6f50-4ebe-89de-fd9e1b144753.png)
![BJJ Wireframe Timetable](https://user-images.githubusercontent.com/79532281/144374269-d93772fc-d673-44ef-b312-cdf3dfc2974c.png)
![BJJ Wireframe Contact Us](https://user-images.githubusercontent.com/79532281/144374289-f6c1fdb0-8041-4fc8-90f3-4dcb24d0ba8c.png)


### Typography

I chose two fonts for the page. I chose "Cairo" as my font for headings with sans-serif as back up if it does not load. For my paragraphs / timetable body / forms I have use the font "Mohave" with sans-serif as back up.

* I feel these two fonts give the page a clear and modern look and both fonts compliment each other.

### Color scheme

The color scheme uses a minimal pallet and gets the majority of color from my images on the page. When you hover over interactive links they change color to bring your attention to them and to encourage you to explore.

The colors I used were:
* lightgrey
* rgb(228, 58, 58)
* black


## Site Structure.

The site consists of four pages:
* Homepage
* Classes
* Timetable
* Contact-us

The navbar and footer will be present on all pages. The navbar will allow for the user to navigate the site easily and allow them to navigate to the differant sections of the page. The footer will contain all the links to the clubs social media account if they want to connect that way.

### Landing page.

This is the default page when people visit the site. There will be a header element with the club logo and nav elements. A main image of people training BJJ. 3 links to the other pages on the site and the footer at the end.

### Classes page.

This page contains the classes offered and a brief description of each class. There is an image of the class type to give a visual idea of the classes.

### Timetable

This page has the timetable which displays what days and times the classes are on. There is a description of the classes underneath the time table so you know what to expect at each class.

### Contact Us

This page contact a form for people who are intrested in learning more about the club / classes. There is a video at the bottom of the page showing some highlights of BJJ.

## Future features

* Club shop
  * I would like to create a club shop where members would be able to buy club merchendise (t-shirts, hoodies, stickers etc.)

* Burger menu
  * I would like to create a burger menu for mobile and smaller screen sizes. I feel this would clean up the navbar and improve the overall apperance of the site.

* Testimonials
  * I would like to create a slideshow showing members testimonials and their experience.

# Testing

## HTML Testing

I tested my HTML in https://validator.w3.org/

## CSS Testing

I tested my CSS in https://jigsaw.w3.org/css-validator/

## Lighthouse Testing

### Error

* When I tested my webpage page my site was failing on performence. This was because the images on the site were to large and taking a long time to upload.

 ![lighthouse test (2)](https://user-images.githubusercontent.com/79532281/143593501-f9058ba4-41da-48b9-94ba-e3e278d56a59.png)

### Solution

* I resized my images through https://tinypng.com/ and replaced all the larger sized images with the new smaller sized images. This improved performence and reduced delays in the page uploading.

![lighthouse bug fixed (2)](https://user-images.githubusercontent.com/79532281/143593858-521c7566-ced7-4359-a35e-cbf4f7641b7c.png)

## Bugs Found

### Navbar

When I was resizing the page and width dropped below 1080 px the sequence of my navbar went out of sequence.

![Bug on my header page (2)](https://user-images.githubusercontent.com/79532281/143681092-0e13e548-fb35-483b-a7dc-03a09b681b90.jpg)

To fix this but I amended the display to inline flex, changed the direction to reverse.

# Deployment
**To deploy the project**

The site was deployed to GitHub pages. The steps to deploy the site are:
1. In the Github repository, select the **Settings** tab.
2. Once in the setting, select the **Pages** tab on the left hand side.
3. Under **Source**, select the branch to master, then click **save**.
4. Once the master branch has been selected, the page will automatically create a link for your site.
![Github pages link (2)](https://user-images.githubusercontent.com/79532281/143587694-59346abd-5c08-4af6-bb4a-5b294b3ce4ec.png)

# Credits
### Content
* The fonts came from https://fonts.google.com/
* The icons for the footer came from https://fontawesome.com/start
* The footer code came from the Love Running walkthrough.
* The responsive image at the top of the README was created by http://ami.responsivedesign.is/
* The footer code and icons was taken from the love running project.
* The text on the BJJ classes page was found here https://en.wikipedia.org/wiki/Brazilian_jiu-jitsu
* The text for the Judo classes page was found here https://en.wikipedia.org/wiki/Judo

### Media
* All the images for the page came from https://unsplash.com/
* The Youtube video was taken from a https://www.youtube.com/c/stuartcooperfilms
* The photos were compressed using https://tinypng.com/
