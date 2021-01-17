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

   *  At the begining of page i created `<a>` element for logo and `<header>` with 3 differetn `<li>` (index.html,gallery.html and contact.html). One for each subpages. Then I created 3 different `<section>` and `<footer>` element. 

   * The first section contains "hero-images" wich is first photo on the page. Next thing what i crete was one more section, wich one will be section About Us and text whitc will be interesting text about restornat. Next section have few `<div>` element, 
      each for every pat of page. (About Us,Menu and Special Offer.)

   * Next thing what i crete was one more section, with 6 `<div>` element. Each of that element have has a built structure with `<h2>`, `<hr>`, `<p>`, `<ul>` and `<li>` elememt , as we can see. 
         
    ```<div>
         <h2></h2>
             <hr>
                <p>
                     <ul>
                       <li></li>
                       <li></li>
                       <li></li>
                       <li></li>
                    </ul>
                </p>
     </div>```

 * Next think was one more `<section>` for Special Offer part of Web page , wagain with few more `<div>` element. Each of that `<div>` have `<h2>` and `<h2>`. 
        
    ```<div>
         h2></h2>
         <h3></h3>
         <h3></h3>
         <h3></h3>
     </div>```

 *  Next think what i maket is `<footer>` elemeny, for social network `<link>`. 

 2. On the second subpage we have made content about photos with food in a restaurant. was created by copying the skeleton from index.html. files, 
   and then created a new section with the `<ul>` element and photos for the page, in the added footer I also put links for social networks.
     
    ```<div>
         <img src="...">
         <img src="...">
         <img src="...">
         <img src="...">
         ...
     </div>```

 3. in the third subpages called "contact.html" the skeleton from the "Index.html" file was copied. Then I created one section with a
  `<form>` element and `<div>` element. The form element is composed of several `<label>` and `<input>` elements for creating 
  a form for which it is used to contact the restaurant owner, and in the `<div>`
  element which is composed of the content of the restaurant information (working hours, location, email and phone number).
 