# Project: Using Bootstrap (Newsweek-Clone)

> This project requires to build a replica of the news site Newsweek.com using the Bootstrap framework.

## Desktop version

![Screenshot from 2020-02-09 09-25-33](https://user-images.githubusercontent.com/55361440/74095966-7d35c780-4b1e-11ea-87dc-26fcf964ba68.png)

## Mobile version

![Screenshot from 2020-02-09 09-26-52](https://user-images.githubusercontent.com/55361440/74095974-976fa580-4b1e-11ea-97d4-53118b1919af.png)

## Details  

### Nav Bar 
- The Nav bar have Newsweek headline (in center) ,and have two icons and two buttons(login and subscribe) on right side.(The nav-bar was created with the tag `<nav>` , and the buttons and icons have their sepreated `<div>` tags)

### Main Content Section

- The main content of the page (being the actual article and the right side sections) was made by creating some `<section>` tags only divided by the *Advertisement* spaces which are individual `<div>` tags.

- Since the main article container has already a *fixed* width and its container won't change even if the viewport does (because of it being at its minimal width already) the horizontal centering was achieved by using the `padding` property with an absolute value to its left and so allow the *aside* boxes to align using only the `float` property.

- The top bar icons were made using [Font Awesome](https://fontawesome.com/) and were contained and aligned with *flexboxes-bootstrap*

- As for each image, they were wrapped inside `<figure>` tags and took advantage of the `<figcaption>` elements to describe what was shown above.

### The Position: sticky;

- One of the main requirement of this project is to create Sticky-top using bootstrap.

- multilpe `<section>` was created with the id `#grid-boxes` to create three coloums with 3 imgs in each of it.

- Right side content created using the `<aside>` tag andthe property float:right is applied on it.

### footer and footnotes 

- The `<footer>` tag was created for the content at the bottom. In this we have created multiple `<divs>` with multiple `<uls>` and `<lis>`

- Uses the Newsweek logo as the heading of the `<footer>` and used The font awesome icons
at the left side.

## Built With

- HTML5, CSS3
- VSCode

## Live Demo

https://raw.githack.com/jaspreet-singh-sahota/NewsWeek-clone/feature-branch/index.html

## Authors

👤 **Jaspreet Singh**
- Github: [@jaspreet-singh-sahota](https://github.com/jaspreet-singh-sahota)
- Twitter: [@jaspree88033250]https://twitter.com/jaspree88033250
- Linkedin: [jaspreet Singh]https://www.linkedin.com/in/jaspreet-singh-a28286146/
