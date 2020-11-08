
# Jane Smith Ceramic Studio

### Milestone Project 1
User-Centric Frontend Development - Code Institute

Jane Smith Ceramic Studio is a website about a fictional ceramist who wants to present her work for a potential new customer and/or client. The site presents her work in form of a gallery of four different categories. You can also find a page with information about the ceramist, a page with links to her stockists and a contact page with information how to get in contact with her.

## UX

#### User Stories
- As a retailer I want to find the contact information so that I can get in touch with her for business inquiries.
- As a fan of the ceramist I would like to find where the stockists are located so that I can purchase her products.
- As a follower on social media I want to see the ceramist collection so that I can see if it’s something I want to buy.

#### Strategy 
I wanted to make a user-friendly website for the ceramist where she could present her collection for potential customers. I wanted the site to be easy navigated with a minimalistic design. It’s important both for a customer and a retailer to see what kinds of products the ceramist offers and they should immidiately see where to navigate to do this.

#### Surface
The colors I’ve used for the project is a light grey, #777777 and a warm terracotta, #E2725B. I choose these colors because they are the two most common colors on clay that’s used for pottery and it gives the site an earthy tone. 

#### Wireframes


## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

**Header**

A fixed header that exists on every page. The logo is located to the left and by clicking it the user returns to the home page. The navigation menu is located to the right so that the user easy can navigate through the different pages.

**Navbar**

Each page features a responsive Bootstrap navbar that’s collapsed when viewing on smaller screens. The navbar has an extra JavaScript function with a dropdown menu so the user easily can view the different categories in the collection.

The navbar has an hover effect so when the user hovers over the different pages the text changes color to a warm terracotta orange. The same color is used to show wich page the user is currently on.

##### Home
The home page features a hero image that shows some of the items in the collection. This will give the user an idea of what type of items the ceramist offers. 

On top of the image is a call to action button that guides the user to view the collection.

###### Collection
- The collection page features a menu of the different categories followed by a masonry gallery with images of all the products. You can easily click on each category to get a better view of the category you’re intrested in.

###### About
- The about page features a photo of the ceramist to give a personal feeling to who’s making the items. 
- The page also provides a short text that gives some information about who she is and her thoughts about her work. You can also read that she’s available for collaborations.

###### Stockists
- The stockist page features a list with links to all her stockists so that users easily can access their websites and get information on where to purchase the items.

###### Contact
-     

###### Footer
- A fixed footer that exists on every page. Located in the center of the footer are four social media icons with links to the ceramist social media pages. The links have the same hover effects as the navbar and changes color when hovering over them.

##### Features Left to Implement
- A feature I would like to implement is a webshop so that customers easily can buy her work online.

- I would also like to add a lightbox to the different images so that customers can get a better view of the items.


## Technologies Used

###### Languages
-HTML5
-CSS3

*Github* - 
*Gitpod* -
*Bootstrap* - The project uses Bootstrap to make the site responsive and to implement features such as the navbar and the button.
*FontAwesome* - The project uses FontAwesome for social media icons and icons on the contact page.
*Google Fonts* - The project uses Work Sans from Google Fonts.
*Balsamiq* - Used in the beginning of the project to create wireframes.


## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
1. Contact form:
    * Go to the "Contact Us" page
    * Try to submit the empty form and verify that an error message about the required fields appears
    * Try to submit the form with an invalid email address and verify that a relevant error message appears
    * Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.


#### During development

 - Mobile responsiveness for about page not worked as intended.
Image appears too small and does not move to underneath the text.
	- changed setting from col-6 to col-12 col-lg-6 

 - Mobile responsiveness for stockists page not worked as intended.
Image appears too small and does not move to underneath the text.
	- changed setting from col-6 to col-12 col-lg-6 

 - Mobile responsiveness for contact page not worked as intended.
Image appears too small and does not move to underneath the text.
	- changed setting from col-6 to col-12 col-lg-6 

 - Header remained transparent when scrolling which made the menu difficult to read.
	- Added bg-white to navbar class.

 - Unable to customize color on navbar menu when hovering.
	- Added !important;  to .menu a

 - Unable to customize color on active pages.
	- Added !important;  to .active


 - Collection menu on collection page not responsive on mobile devices.
	 

 - Collection link in navbar is not working

	
 - Mobile responsiveness for hero image not worked as intended. Image size appears too small.


 - Mobile responsiveness for hero text not worked as intended. Text size does not decrease and is overlapping.


## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).
In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
* Different values for environment variables (Heroku Config Vars)?
* Different configuration files?
* Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

#### Content
The content of the website is fictional but to seek information and inspiration about what others ceramist puts on their websites I have visited these talented ceramist and their sites:
https://madokarindal.com
https://www.catherinedixceramics.com
https://www.handandfire.com
https://www.victoriamorrispottery.com
https://www.epocaceramic.com


#### Media
Unsplash - used for ceramic images
Shutterstock - used for hero image and about image

#### Acknowledgements
Stack Overflow was used for solving small issues  







`python3 -m http.server`
