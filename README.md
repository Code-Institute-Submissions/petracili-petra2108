<h1 align="center">Amphora MS1</h1>

[View the live project here.](https://8000-edfec628-a3ee-44df-a81f-735ddd00892b.ws-eu03.gitpod.io/)

This is my first Web Page create in GitPod and push in GitHub, my idea was to create Web page for Italian Restorant.
The page will contain 3 subpages: Menu, Gallery and Contact. 

<h2 align="center"><img src="https://8000-edfec628-a3ee-44df-a81f-735ddd00892b.ws-eu03.gitpod.io/"></h2>

   ### Who

   I'm Petra. Security officer in Amazon working space. In my current job, I started to get acquainted with the business of software development, and I gained interest in learning more about it.
   At this stage of my course we learned how to create a simple web page with HTML and CSS programs.

   ### What

   In this text, I explained how I started creating the my first Web Page, sing HTML and CSS programs. 

   ## Table of Contents
 * HTML5
	* Heading Structure
    * Body Structure
	* Tag Structure
	* Text Structure
	* Other tags
		* Images
		* Input Text
		* Submit Butten
		* Text Styles
	* The `<head>` tag
 * CSS3
	* Classes and IDs and other Elements
		* Classes
		* IDs
		* Other Segregation
			* The `<span>` tag
			* The `<div>` tag
				* Background color
				* Floating
				* Positioning
				* Margins and Padding
                * Color
                * Border
                * Text Style		
	* The `<link>` Tag, Comments, and other Developer Editing
		* The `<link>` tag
		* Commenting
			* HTML Comments
			* CSS Comments
		* Other 
			* Forms
			* HTML5 and CSS3       
 * [Final Project!](https://8000-edfec628-a3ee-44df-a81f-735ddd00892b.ws-eu03.gitpod.io/)

## Subpages

  a. I was create 3 subpages Home, Gallery and Contact. Fisrt one was home pages with 3 separate section, About Us, Menu of restaurant and Social Network links. 
  b. Secund subpages was Gallery with content listing photos of the food provided by the restaurant. 
  c. The third page is composed of information about the restaurant and the restaurant contact form.

## HTML5

   1. For start i create basic structrure in Index.html file , for `<title>` put the name of the restaurant I do the website for "Pizza Amphora".

```html
<!doctype html>
<html>
	<head>
		<title>
			Pizza Amphora
		</title>
	</head>
	<body>
		Menu	
	</body>
</html>
```

   *  At the begining I added a bootstrap link so I could use the elements and links in the bootstrap .

   * The first section created was the logo of the restaurant itself, I opted for a simpler variant to make it look more sophisticated. 

   * The the next thing that was created is  one more  `<div>` which is used to create a navigation  in the `<div>` we have one `<ul>` and 3 differet `<li>` which will be one for each subpage , as well will change depending on the screen size.
         
    ```<div>
         <h2></h2>
             <hr>
                <p>
                     <ul>
                       <li></li>
                       <li></li>
                       <li></li>
                    </ul>
                </p>
     </div>```

 * Next thing will be "hero-image" create with 3 `<div>` element and helping with class "row" and one `<img>` element bin which one I was put link form picture. 

    ```<<div class="container-fluid">
		<div class="row">
			<img class="heroimage" src="https://www.slo-foto.net/modules/Galerija/data/media/10/2166659148.jpg" />
		</div>
     </div>  ```

 2.  Next think what which was creating is one `<section>` crated for Abouth Us part of webpage. Where the first visitor can learn more about place and concept of the restaurant. As well creating with bootstrap.

    ```<section class="jumbotron text-center aboutus">
		<div class="container">
		  <h1>About us</h1>
		  <p class="lead"></p>
		  <p class="lead"></p>
		  <p id="menubutton">
			<a href="#menupage" class="btn btn-primary my-2"></a>
			<a href="#gallerypage" class="btn btn-secondary my-2"></a>
			<a href="#contactpage" class="btn btn-secondary my-2"></a>
		  </p>
		</div>
  </section>```


 3. I created a part of the page that serves for the menu of the restaurant offering food. In that section there are 2 different parts,
    one is a food offer and the other is a part with special offers and prices, both contents are created using bootstrap. I copied one continent several times and changed the text and photo to get the desired look.


 3. in the third subpages called "contact.html" the skeleton from the "Index.html" file was copied. Then I created one section with a
  `<form>` element and `<div>` element. The form element is composed of several `<label>` and `<input>` elements for creating 
  a form for which it is used to contact the restaurant owner, and in the `<div>`
  element which is composed of the content of the restaurant information (working hours, location, email and phone number).
  I also added social media links to the `<footer>` section.

### Design

#### Colour Scheme
-   As my choice for page style is an idea for industrial style, with 4 different colors.
      Green for the headings of the subpage titles, orange for their hay, was for the color of the letters and light gray for the background color.

####  Typography
-   To select syila letters I used the Google Fonts page which chose the desired font there, my choice was Castoro font.
     [Google Fonts](https://fonts.google.com/)

#### Imagery
-    I found the photos I used on google and copied the photo link and used those images to create the page . 

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [W3Schools:](https://www.w3schools.com/)
    - w3schools was used for halp with some element. 
1. [HTML Color Codes:](https://htmlcolorcodes.com/)
    - HTML Color Colos used for color codes and names.
1. Code Institute:
    - CodeInstitute was used as a reminder of how the element is used.
    

## CSS3

* to style, the files (index.html, gallery.html and contact.html) I used one  style.css file was cut and only the layout of the page was created in it using elements for arranging the page

#### Classes and IDs

*  

