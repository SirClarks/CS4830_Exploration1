# CS4830 Exploration 1 - Bootstrap

<p align="center">
<b><a href="#overview">Overview</a></b>
|
<b><a href="#sources">Sources</a></b>
|
<b><a href="#code">Code</a></b>
|
<b><a href="#recap">Recap</a></b>

</p>

## Overview 

For my *Exploration 1* I wanted to delve deeper into using Bootstrap as a frontend design tool. Specifically, I wanted to explore several different Bootstrap components: 

- The grid system.
- The tooltip component.
- The collapse component.

Also, I wanted to further explore using GitHub as a resource, by hosting all of my files as well as writing out the assignment documentation using the `README.md`.

<p align="right"><a href="#top">:arrow_up:</a></p>

## Sources 

- Grid System Component:
http://v4-alpha.getbootstrap.com/layout/grid/

- Issue: img-responsive changed to img-fluid in Bootstrap 4:
http://v4-alpha.getbootstrap.com/content/images/

- Bootstrap Collapse Component:
http://v4-alpha.getbootstrap.com/components/collapse/

- Bootstrap v4 buttons:
http://v4-alpha.getbootstrap.com/components/buttons/

- Bootstrap v4 Forms:
http://v4-alpha.getbootstrap.com/components/forms/

- Bootstrap v4 Tooltip:
http://v4-alpha.getbootstrap.com/components/tooltips/

- Issue: Bootstrap Tooltip reference not so easy to understand, went to w3 schools instead:
http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_js_tooltip&stacked=h

<p align="right"><a href="#top">:arrow_up:</a></p>

## Code 


I decided to create a single web page for my Exploration 1. The code samples are in orderly format and can be found at:  https://aws.humblepixel.com

For version control, I used the Github desktop app in combination with the web version of this as well. You can find the `index.html` file here: https://github.com/SirClarks/CS4830_Exploration1/blob/master/index.html


<p align="right"><a href="#top">:arrow_up:</a></p>

## Recap 

####Introduction####

This was not my first time using Bootstrap; however, this was the first time I took an in-depth look into a few of the components that Bootstrap offers instead of only using it for the scalability feature. I also chose to mess around with the Bootstrap v4 alpha, just as an added bonus to the experience. 

Setting up Bootstrap was simple and easy. I chose to use their CDN services for the first time, instead of downloading all of the CSS and JS files locally. I figured for something simple like this, I wouldn't need to mess around with the local files. 

####Grid System####

Starting with the Bootstrap grid system. It turned out to be extremely simple. The grid simply relies on a row element which can consist of multiple column elements, which must add up to 12. So you could have 12 tiny identical columns with the class col-md-1 in a single row. You could also go for 3 columns with the class col-md-4, which 3*4=12. This was relatively simple to understand, and I can imagine how web designers could benefit from a simple system like this. 

I also explored a responsive column design, one which would have multiple column settings for different display sizes. For example, on a small screen, the row would have two columns using the col-sm-6 class, or instead, on a larger display, it could show 4 columns with the class col-lg-3 in the same div. One could even add the -md class to try to accommodate for medium displays such as tablets. 

####Collpase Component####

Next, I focused on exploring the collapse component of Bootstrap v4. I really wanted to take a look at this, because it's something that most modern websites / web apps have to have in order to send along that "modern responsive feel." Once again, I was earnestly surprised how easy Bootstrap made the component implement:

Using a simple link or button, one would then need to add the data-toggle="collapse" and add an href by ID to the div, which holds the content waiting to collapse. There are also a few classes for formatting such as "aria-expanded". Finally, the div which is meant to collapse out just needs to have the bootstrap class="collapse" and the ID which was referenced by the href on the link or button. All of this was really easy to setup, and one could even fit entire forms under a collapse button very easily using the same method. Though I found out that the form must be wrapped in a div, which is something common anyway, in order to collapse out.   

####Tooltip Component####

Finally, I took a quick look at the Tooltip component for Bootstrap, which    isn't an important feature of a web page/app; however, I felt that I wanted to explore it, just because I enjoy the occasional tooltip providing further information on a certain element. It was really easy to setup, with the help of w3schools, just because the Bootstrap documentation got a bit confusing on this. The basic example I provided was easy to follow, and can't be much different than every other use of the tooltip component. Once again though Bootstrap made it easy and simple to get up and going without having to use another JS plugin. 

####Final Remarks####

Overall I was extremely satisfied with exploring Bootstrap 4. I have really only previously used Bootstrap 3 for the scalability on multiple devices, but never really took a look at the documentation in detail. It was enjoyable to read through the few components which I explored, and I hope to come back and look at many more (especially after finding out they are so simple to implement). My favorite of the 3 components I looked at was the collapse, which was simple, but immediately brought up the face value of the design making it look more modern and clean. I hope to implement this on a website of my own soon. The tooltip was an interesting find, but I can't see myself using it too much, other than maybe rarely to describe an element on a page. Finally, the Grid system, which Bootstrap offers, is very unique and I can see how it could become complex especially when dealing with different sized elements; therefore, I hope to also explore this and more components in the near future. 

<p align="right"><a href="#top">:arrow_up:</a></p>

## Extra Information 

####External####
- This `README.md` top link layout and *Extra information* section based on [@b4b4r07's README.md](https://github.com/b4b4r07/dotfiles)
- This `README.md` general layout based on [@jxons's README.md](https://gist.github.com/jxson/1784669)

<p align="right"><a href="#top">:arrow_up:</a></p>

## License

At the current state of this exploration, there is no need for a license.

<p align="right"><a href="#top">:arrow_up:</a></p>
