Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents

  - The challenge (Product Preview challenge)
  - Screenshots
  - Links
  - My Process
  - Built with
  - What I learned
  - Continued development
  - Useful resources
  - Author


### The challenge

"Your challenge is to build out this product preview card component and get it looking as close to the design as possible.

        

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.


Users should be able to: 

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements."


### Screenshot

Desktop view of solution.    			
https://github.com/Lauz7/Lauz7.github.io/blob/main/Screenshot-solution-desktop.png?raw=true             

Mobile view.
https://github.com/Lauz7/Lauz7.github.io/blob/main/Screenshot-solution-mobile.png?raw=true

### Links

- Solution URL: https://www.frontendmentor.io/solutions/product-preview-card-component-KZRK-BFvjX
- Live Site URL: https://lauz7.github.io

## My process

I began the process by building my index.html. I then created an external CSS file and linked this into my html and began testing. I created my design first to mobile view specification and then used Media Queries to allow the site to be responsive.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I learnt a great deal putting the knowledge I have gained surrounding html5 and css into practice. I spent a lot of time on the community learning from other developers. I'd say the main piece of knowledge that I have gained by working on this project was how to use media queries to allow for responsive web design.

An example of media queries in my code - 
img{
    display:block;
    max-width: 100%;
    max-height: 100%;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}
@media only screen and (min-width:801px){
    img{
        display: flex;
        justify-content: flex-start;
        width: 800px;
        height:500px;
        padding-right: 10px;
        border-top-left-radius: 10px;
        border-bottom-left-radius: 10px;
        position: relative;
    }
}

Another thing that I have learnt during this project was how to interchange images depending on screen width. 

An example of this from my code -

                 "<source 
                   media="(min-width: 801px)"
                   srcset="https://github.com/Lauz7/Lauz7.github.io/blob/main/image-product-desktop.jpg?raw=true">
                <source 
                   media="(min-width: 300px)"
                   srcset="https://github.com/Lauz7/Lauz7.github.io/blob/main/image-product-mobile.jpg?raw=true">
                <img src="https://github.com/Lauz7/Lauz7.github.io/blob/main/image-product-mobile.jpg?raw=true" 
                alt="perfume pic">"
                
### Continued development

I would like to continue working on and practicing the positioning element as well as the flex element. I have used them within my code but I would like to become more comfortable with using them both through practice in future projects.


### Useful resources

- https://web.dev/learn/design/ This website helped me gain a really solid understanding of responsive web design.
- https://open-props.style/#media-queries This website also helped be me greatly with media queries.

## Author

- Github - https://github.com/Lauz7 
- Frontend Mentor - https://www.frontendmentor.io/profile/Lauz7
- LinkedIn - https://www.linkedin.com/in/lauren-struthers-b760861a6/
