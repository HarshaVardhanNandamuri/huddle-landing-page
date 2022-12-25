# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). 

## Overview

### The challenge
This is a landing page for the company Huddle which was built using bootstrap and some CSS. It is a single page landing-page which consists of three sections: Navbar, Content & Social. The navbar is simple as it only displays the logo of the company. The content section can also be considered as the hero section of landing-pages as it consists of an image, few lines of text which shows the motto of the company and a button to register for the services. Finally, the social section consists of the social media icons through which users can connect with the company.

### Screenshots
The preview of the website will be as follows:
./images/preview.png

The review button has a hover effect and the following image will show the result of it.
./images/review-hover.png

The social icon also have a hover effect and the images following will show the result of this.
-Facebook icon
![](./images/facebook-hover.png)
-Twitter icon
![](./images/twitter-hover.png)
-Instagram icon
![](./images/instagram-hover.png)


### Links

- Solution URL: (https://github.com/HarshaVardhanNandamuri/huddle-landing-page)
- Live Site URL: (https://huddle-landingpage-solution.netlify.app/)

## My process
First, I started with the navbar which only consists of a single element-the logo. The whole body uses a violet background and an Open sans font. I first add a nav tag which has a image container containing the logo image. The navbar has a padding px-lg-5 on the x axis, which means left and right padding for large screens and the div containing the logo img has a padding py-lg-5 on the y- axis(top and bottom for large screens) and the logo image width is set to 200px in the custom css. Next a content section is added which consists of the main content of the website. It has an image and a div which consists of the text and a button. Inside the div a h2 and a p tag are used to represent the text and they both have a bottom padding of pb-3 and their line height is set to lh-base and the text color is white. The heading uses the Poppins font, the font-weight is 600 and font-size is 2.5rem. The button occupies 35% of the width of its container and it fits the content, border radius is 2rem, text color is violet, font-size is 1rem and font-weight is 600. The border has a hover effect which changes its background color and text color and the cursor to pointer. The container containing the text and the button uses padding on left, right & top(px-5 & pt-5), and uses display flex and column(d-flex & flex-column) to align items vertically. The container containing the image and the product-description div uses padding top(pt-4), margin top(mt-2), on small screens it uses display flex(d-sm-flex) and col-md is used to get a column layout for this container for medium sized screens. Finally the social section consists of a container which has three icons. These icons are provided by fontawesome. They use i tag and the container has padding top(pt-3) and to align the icons to the right side display flex(d-flex) and justify content end(justify-content-end) are used. These icons have a white rounded border, color white margin of 0.5rem and a padding of 0.75rem & while hovering over the icons both the border and the icon change color and pointer changes to cursor.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Bootstrap 5

### Continued development

The desktop design is almost same as the design view given. However the website is partially responsive. While switching to mobile view

### Useful resources

- [Bootstrap 5](https://getbootstrap.com/docs/5.3/getting-started/introduction/) - This helped me to use the bootstrap classes used in the design process of the website.
- [W3schools-Bootstrap](https://www.w3schools.com/bootstrap5/index.php) - This helped me to use several bootstrap concepts which I couldn't properly understand in the bootstrap documentation.
- [W3schools-CSS](https://www.w3schools.com/css/css_intro.asp) - This helped me to understand several custom css properties used in the website.

## Author

- Github - [Bhanu Harsha Vardhan Nandamuri](https://github.com/HarshaVardhanNandamuri)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/HarshaVardhanNandamuri)

