# Horiseon-refactor
![horiseon](https://user-images.githubusercontent.com/110440453/185319905-a66a52b1-d017-4c17-aaa7-4bd68a64252e.PNG)
<<<<<<< HEAD

## Description 

The Horiseon-refactor is created to restruct the existing code to make sure all the code/links are functioning correctly, organizing the semantic structure of the HTML elements, as well as consolidating the CSS selectors and properties, so the code works more effecient.

## Installation 
N/A

## Usage 

In the HTML, using properly semantic tags will make HTML more comprehensive that helps defining the different sections and layout for the webpage. 

Changing the title from "website" to "Horiseon-Search Engine optimization and Social Media" as it will be more specific about the website instead of just a vague title. 

Adding the <nav class= header> in order to create a nagivation bar. 

Adding three separate <section> for each heading of the webpage. 

Adding header under the <body> to help defined the header for this section as it contains the three big heading for the webpage. 


In the CSS, organizing or consolidating the formatting, and images properties is important. All of the same format elements should put together, so the team members will easy to keep track and maintainable. 
There are five formattings needed to be consolidated in the CSS. 

For example, benefit-lead, benefit-brand, and benefit-cost have the same margin-bottom and color, they should consolidate into the same section instead of make each of them with the similar format.

/*consolidated the formatting*/
.benefit-lead, 
.benefit-brand, 
.benefit-cost
{
    margin-bottom: 32px;
    color: #ffffff;
}

 Similarily, benefit-lead img, benefit-brand img, and benefit-cost img also have the similar margin and color. 

/*consolidated the images properties*/
.benefit-lead img, 
.benefit-brand img, 
.benefit-cost img 
{
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

 /*consolidated the formatting*/
.search-engine-optimization,
.online-reputation-management, 
.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}
/*consolidated the images properties*/
.search-engine-optimization img, 
.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px;
}
/*consolidated the formatting*/
.search-engine-optimization h2, 
.online-reputation-management h2,
.social-media-marketing h2
 {
    margin-bottom: 20px;
    font-size: 36px;
}

## Credit
N/A

## License
 
 Distributed under the MIT License. 
=======
