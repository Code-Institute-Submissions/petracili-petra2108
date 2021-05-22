<h1 align="center">Pizzeria Amphora</h1>

Code Institute Diploma in Full-Stack Software Development Project 1

### View the live project: https://github.com/petracili/petra2108.git/

### <u>Scope of the project</u>

In today’s idea is to create a website for Amphora Pizzerias. In today’s situation with the coronavirus where most restaurants are closed, good promotion is key to keeping the restaurant in pole business and thus have preserved jobs. So this Italian restaurant needs a website where you will see the complete restaurant menu with an order form.

-----------------

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
    As we can see, a `<div>` element was used in which a `<h2>` element was added and a `<ul>` element with more `<li>` phrases, in which the text on food supply was included, in the same 
    part we have one `<img>` i with one i put link of photo which i want. 

    ```<div class="container-fluid menu">
		<p class="h2 text-center" id="menupage">Regular Menu</p>
		<div class="row" >
			
			<div class="col-md-4">
			  <div class="card mb-4 shadow-sm">
			
				<img src="https://pennysrecipes.com/wp-content/uploads/2014/11/vegetable-soup.jpg" style="height:225px" />
				
				
				<div class="card-body">
				  <h5 class="card-title text-center">Starter</h5>
				  <ul class="list-group">
					   <li class="list-group-item">Seasonal vegetable soup 5€ </li>
					   <li class="list-group-item">Bruschetta with marinated vegetables 5.50€ </li>
					   <li class="list-group-item">Bruschette with smoked fish 5.70€ </li>
					   <li class="list-group-item">Crispy prawns in sauce 6€ </li>
				   </ul>
				</div>
			  </div>
			</div>```


 4. The next content is Gallery which was created using bootstrap link for transferring photos, I used the same link for photos from google browser that I copied to the position "img".
    I was used more `<div>` element plus `<img>` source.

    ```<div class="container-fluid gallery">
		<p class="h2 text-center" id="gallerypage">Gallery</p>
		<div class="row">
			<div class="col-1 col-lg-2"> </div>
			<div class="col-10 col-lg-8">
			<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
				  <div class="carousel-inner">
					<div class="carousel-item active">
					  <img src="..." class="d-block w-100" alt="...">
					</div>
					<div class="carousel-item">
					  <img src="..." class="d-block w-100" alt="...">
					</div>
                    ...```

5. The contact is created in a "form" element with several windows that the user can use to send a message and one button is added.
   
        ```<form >
				  <div class="form-group">
					<label for="exampleFormControlInput1">Full Name</label>
					<input type="email" class="form-control" id="exampleFormControlInput1" placeholder="...">
                  </div>

                   <input class="btn btn-primary" type="submit" value="Submit">

            </form>```

 6. In the "footer" content and these icons have been added from Font Avesome, each link leads to the homepage of the social network.
   
     ```<footer>
			<ul class="social-networks socialnetworks">
               <li><a href="https://www.facebook.com" target="_blank"><i class="fab fa-facebook-square"></i></a></li>
               <li><a href="https://www.twitter.com" target="_blank"><i class="fab fa-twitter-square"></i></a></li>
               <li><a href="https://www.youtube.com" target="_blank"><i class="fab fa-youtube"></i></a></li>
               <li><a href="https://www.instagram.com" target="_blank"><i class="fab fa-instagram"></i></a></li>
            </ul>
         </footer>
         ...
         ```

### Design

#### Colour Scheme
-   As my choice for page style is an idea for industrial style, with 4 different colors.
      Dark orange on the background, white for menu frames, black letters and green shades for a slightly more interesting look.

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

* to style, the files (index.html) I used one Bootstrap CSS Style file was cut and only the layout of the page was created in it using elements for arranging the page.

   ``` <style>
			
			a.navbar-brand{
				font-size: xxx-large;
				
			}
			
			nav.navbar {
				background-color: darkorange !important;
			}
			
			img.heroimage{
				width:100%;
				height: auto;
			}
			
			.aboutus{
				background-color: darkorange !important;
				color: black;
				
            }
            
            .aboutus div.container, .menu, .gallery, .contactpage, {
				background-color: darkorange !important;
				color: black;
				
			}
			
			.gallery img {
				height: 550px;
				width:100%;
				
            }
            
            .menubutton {
                background-color: darkorange !important;
                color: black;
            }
            </style>```
		

#### Classes and IDs

*  I added classes and id to each `<div>` where needed to make visual changes later in the style section, so 
  I have, black for the text. to make it more readable on an orange background that looks 
   vibrant and alluring and in keeping with the whole concept of the restaurant. Then we have a green submit button and social network icons to give importance to the section and to make it easier to see.


### Acknowledgements

* My Mentor for continuous helpful feedback.

### End 

-  I learned a lot working on this project, things I wouldn't have had the opportunity to do in my normal life. as this is my first station I have ever made I am pleased with its work and appearance. I would like to thank the entire Code Institue for their help and my mentor who helped me to better understand the work of a developer. I look forward to the next project and the new things that follow.