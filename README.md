# CS50 Web Project 0: HomePage


## CS50 Web - Programming with Python and JavaScript


### Project Aims:

The aim of this project was to develop a simple homepage website, using the following technologies:

* **HTML**
* **CSS**
* **Bootstrap**
* **SASS / SCSS**


### Project Requirements:

* Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
* Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
* Your website must have at least one stylesheet file.
* Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
* Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
* You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
* Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
* In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.



### Project Writeup:

This project is a starting point for my personal homepage which I hope to continually add with additional content/projects etc. It has been created and styled using several Bootstrap components, as well as a Sass .scss stylesheet with some custom styles. Most pages use bootstrap navbar, jumbotron and footer components, as well as the bootstrap responsive grid system and cards to layout links to other sections of the website etc.

* index.html - homepage for the website, containing links to the rest of the site as well as links tom my GitHub and LinkedIn pages.
* about.html - a brief bio page with links to info about my cats.
* louis.html and boo.html - fun profiles for my two cats, including photos, lists of their favourite things and a nickname generator written in jQuery.
* projects.html - a mock-up for a page that will in the future have links to various projects I have built, displayed using bootstrap cards.
* blog.html - similar to projects.html, this is a mockup for a page that will have links to blog posts, and currently has a single blog post accessible.
* blog-n-queens.html - the start of a blog post about the N-Queens puzzle, which contains a table as well as images. An @media query in the main.scss stylesheet helps to resize the images here on smaller screens.

* main.scss - SCSS style sheet using Sass variable to handle the main color scheme as well as nesting and inheritance where appropriate. This is converted to the main.css stylesheet by Sass, which is referenced by the website.

* templates folder - contains a blog template for writing future blog posts.
* assets folder - contains image assets for various pages on the site.




