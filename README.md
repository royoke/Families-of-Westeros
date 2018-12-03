*** SI 339 Final Project Documentation ***

*** Responsive Design Choice Descriptions ***

.I really liked the header on my desktop view using my background image. However, when you went to a smaller device the image looked awkward and took up way to much of the screen, so I decided to create a media query for screens less that 1024px which would remove the background image and instead make a smaller banner with a color that matched the theme of the page. This makes the header content easier to read for users and all around provides a better look

.Another problem from the transition to desktop to mobile was my navigation. Small, horizontally aligned navigation is really difficult on phones so I created a hamburger menu navigation under the same media querey above (1024px)

.My content is really spread out on the desktop view, with an aside column containing overarching info that is positioned next to the main content of the site. I caused this to be removed, and have the column of information be placed above the main content on mobile views. If I did not do this the content would have been significantly more smushed and hard to read

.One of the tricky things about mobile is that it can be viewed in portrait or landscape mode. I decided to create a media query for when users are in landscape mode as well which spreads out my content a bit more, particularly my footer buttons, which makes it more accessible and more difficult to "fat finger" or misclick

.I also implemented CSS to make responsive images, which resize as the screen decreseases to increase clarity & visibility. 

*** Grid/flexbox Description ***

.I used grid on all of my pages of this site to place my content were I wanted it. I used grid to place my nav bar, header, maincontent and also used grid to layout the image gallery portion of the site. I thought that grid was really useful and effective for my site because it establish a strong heiarchy of the page. I wanted the lay out of my page to not just be one vertical column of different forms of content, so I used the columns functionality of the grid layout to place content side by side instead of just vertically.

*** Javascript/JQuery ***

.I used both Javascript and JQuery on my site

.JQuery - One concern about the content of my site is spoilers. Because this is about a show, some users that may be currently watching the show, they wont want to see some of the content on my page. Specifically, there is one section of content that shows images of of charachters and specifies weather they are currently dead or alive in the show. I used a JQuery function on my pages to hide this section that contains spoilers, and then added a button, that when clicked will toggle the visibility of the content. I made this script from scratch

.JavaScript - I also used the Javascript code from Colleen/Lokesh Dhakar to create a lightbox layout for one section of my site. I had to change a few things from the original code to customize this towards to my site. I added labels for the names of the charachters and I also needed to change the layout of the photos for when my site is being viewed on a mobile site to make the pictures look less crammed. 

*** aXe/w3 Errors ***

.Currently the only error I have on both aXe/w3 is a color contrast error which is only an error because it is refering to a background image and it cant detect what the actual background color is due to the background image. Other than this error, my site validates on both aXe and w3. 