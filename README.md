# Portfolio
Portfolio of finished web apps and contact info. Get to know me! 


## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) , [https://developer.mozilla.org/en-US/docs/Web/SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)    |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

## Description 

[Visit my portfolio](https://youtu.be/BFyeuLhjcPY)

My portfolio is a place where potential employers can view work samples as well as have access to my github, linkedin and contact information.  

At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation? Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out? 


If you're new to Markdown, read the GitHub guide on [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

If you need an example of a good README, check out [the VSCode repository](https://github.com/microsoft/vscode).


![Site Langing Page](./site.gif)


## Table of Contents 

If your README is very long, add a table of contents to make it easy for users to find what they need.

* [Code Example](#html-and-css-examples)
* [Usage](#usage)
* [Learning Points](#learning-points)
* [Author Info](#author-info)
* [Credits](#credits)
* [License](#license)


## HTML and CSS examples


Creating a button that is within my anchor tag so that when a user clicks anywhere within the outlined space it will take them to the associated link.  This also allows for the hover effects to take place when the user hovers anywhere in the outlined space.  

```html
<section id="contact">
                <h2>CONTACT</h2>
                <!-- have to create another section so that the contact will not become a flex item -->
                <section class="buttons">
                    <a class=button href="mailto:sunroomthelabel@gmail.com"> Email</a>
                    <a class=button href="https://www.linkedin.com/in/shea-schwennicke-76a378210/"> LinkedIn</a>
                    <a class=button href="https://github.com/sheaschwenn"> Github</a>
                </section>
            </section>
```

This CSS styling makes the text of each item in the navigation bar to go bold and grow in size from x-large to xx-large when the user hovers over it.  The styling on the li also forces each item to stay along the base line even when another item is hovered over instead of adjusting to align with the other items. 


```css
  li{
        width: 33%;
        text-align: center;
        align-self: baseline;
       }
 /* specific styling for the anchor tag text in the header */
    header a{
        color: var(--color-button);
        font-family:var(--font-button) ;
        font-size: x-large;
        font-weight: 500;  
        
    }
/* whenever user is hovering over a link it will go bold and the font will get bigger  */
   header a:hover{
        font-weight: bolder;
        font-size: xx-large;
    }
```





## Usage 

Check out my previous work! If you like what you see, check out my github. 


To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

```md
![alt text](assets/images/screenshot.png)
```


## Learning Points 

Creating this webpage presented me with a lot of challenges but with those challenges came a lot of learning opportunities.  I now have a much better grasp on how HTML and CSS work together to create the structure and style of a web application. The most important thing that I learned this week was an understanding of the structure of an HTML document and how that structure influences the ways you can manipulate the styling in CSS.  For example my biggest struggle was getting my portfolio images to align in the way that I wanted them to.  They were just simply not responding to what I thought were the correct commands.  After messaging a tutor on Ask BCS I found out that I needed to create different sections for my web applications so that they could sit next to one another in the ways that I wanted them to.  Learning this later helped me to include my section headers within their respective ids by sectioning off the correct bits of code together.  After strugging for a few hours this is something I will now never forget. Along the way I also learned a lot of really cool new ways to style and new tools to add to my CSS tool box. 


## Author Info

### Shea Schwennicke 


* [Portfolio](https://youtu.be/bHX54GCrDB4)
* [LinkedIn](https://www.linkedin.com/in/shea-schwennicke-76a378210/)
* [Github](https://github.com/sheaschwenn)



## Credits
The two main tutorials that I followed were for creating the blob shape of my profile photo and to create the transition effect on my contact buttons.  

[Blob tutorial](https://isotropic.co/making-blob-images/)

[Button Tutorial](https://codepen.io/jennyhmc/pen/qBavyVg)



## License

MIT License

For more information please refer to the LICENSE in the repo. 


---



© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.