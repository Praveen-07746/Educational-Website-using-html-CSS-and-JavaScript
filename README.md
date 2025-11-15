# Educational-Website-using-html-CSS-and-JavaScript
Today we have created an Educational Website for you using HTML CSS and JavaScript which is completely responsive and is an advanced project. You can use this for your website. 
~In this you can also sell your course and you can also use it as a portfolio. We have designed it very well. We have made this project quite advanced. In this, each page has been designed separately. In this, we have designed home page, about, course, blog page and contact page separately, which you can visit. We have also used Google Live Map in this, which is quite amazing. You can also suggest this website to your teacher. We have also created a teacher’s section in which we have added a teacher, so let’s go, now we will understand its code.
First of all we will create the structure of our project with the help of HTML which does not look good at all but HTML is very important for our project, without HTML you cannot create any website, so let us now understand the code of HTML.

<!DOCTYPE html> This tag is the most important tag of our email, from this we know that this code is the code of the email
<head> This element is that element of HTML in which we add the link of our website like the link of font etc. It also has a close tag </head>
If you want to add the title of the website then you can do it in this way <title>Developergtm – education website</title> In this you can add the title as per your choice
To link the css file to html you can add the url of your css file like this <link rel=”stylesheet” href=”css/style.css”>
We have used this template to add logo in html <a href=”home.html” class=”logo”> <i class=”fas fa-graduation-cap”></i> Developergtm </a> We have added text logo in it, you can add image as well
To create the navbar we have used <nav class=”navbar”>. In this we have used <ul> and <li> to add the menu items.
To create the home section, we have used <section class=”home”>. In this, we have added an image and text <img src=”images/home-img.png” alt=””>
We have also created a category section in the website <section class=”category”> in which we have added different category courses
To add category we have created a box like this in which we have added the text <a character=”#” class=”box”>
To create the footer section, we have created the section like this, in which we have also added some social links <section class=”footer”>
To add copyright in footer we have used <div> from this article <div class=”credit”> created by <span>mr. Ajay Pawar</span> | all rights reserved! </div>
  
CSS (Style.css)
  
This is our CSS code which adds styling to our web page. Using this we’ve styled all of our HTML elements. This code makes our project visually appealing to keep engaging the user to our website. Here’s the breakdown of our CSS code:

Code starts by importing the exporting the Poppins google font.
Universal selector sets the margin, padding and all the text and transition properties to the whole web page.
The .btn class contains some styling like display, color, border and hover properties for all the buttons of the webpage.
Heading tag contains all the essential styling for the several heading of the page to create interactive UI.
.header class contains position, display, margin and other properties like webkit etc. for the proper alignment and visually appealing UI for this section. All the logo, navbar and other elements are designed in this class.
The .home class sets styling for the home page of the website like image and content alignment, display properties along with color, height etc.
Category page styles all of its components like boxes and images by giving several properties like height, display, margin, padding, border etc.
About section aligns all the content including images and text in such a way that it attracts user UI. Font, colors and other aspects are styles in this section.
Course section is designed to represent each course. There are some styling provided to each of them. Each course section contains some margin, padding, font, color and other properties.Main video of the page is styled by giving some CSS properties to interact with user.

Teachers section contains all the teachers name, their identity and quick links and all these are styled under the main teacher container section.
Blog page is designed to upload daily blogs to the website. Each blog contains some images, heading and content all are styled using essential CSS properties.
The contact page contains some boxes, a form and map which displays the location. Each box is designed and aligned well along with the contact form. All these elements are styled well for better UI of the website.
Footer is designed using the essential aspects or properties like display, margin, font, height, width etc. for each page of the website. All these are designed well so that user can access quick links using footer at each page.
Lastly, media queries are used to provide same styling to smaller screens as well. Using media queries we’ve styled and formatted our website for the smaller screen so that users can easily access it in mobiles.
