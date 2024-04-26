# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents


- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)






## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
   <body>
    <div class="base_card">
        <img src="/qr-code-component-main/images/image-qr-code.png" >
        <h3>Improve your front-end skills by building Projects</h3>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>

    
</body>

```
```css

* {
    padding: 0px;
    margin: 0px;
    font-family: 'Outfit';
    
}
body {
    background-color: hsl(212, 45%, 89%);
    display: flex;
    justify-content: center;
    align-items: center;
    
   
    
}

.base_card {
    width: 250px;
    height: 420px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: hsl(0, 0%, 100%);
    display: flex;
    flex-direction: column;
    padding: 1rem;
    border-radius: 18px;
    text-align: center;
    box-shadow: 0 4px 8px 2px hsla(217, 45%, 22%, 0.2);

}
img {
    border-radius: 8px;
    
}

h3 {
    margin-top: 24px;
    font-weight: 700;
    padding-left: 8px;
    padding-right: 8px;
}

p {
    margin-top: 16px;
    font-weight: 400;
    font-size: 15px;
    padding-left: 8px;
    padding-right: 8px;
    color: hsl(220, 15%, 55%);
}
 


}
```




### Continued development

I want to more focus on things like border-radius and padding how they relate to eachother while giving parent-child border radius.



### Useful resources


- [W3Schools](https://www.w3schools.com/css/css3_shadows_box.asp) - This is an amazing website which helped me finally understand box shadowing. I'd recommend it to anyone still learning this concept.



## Author

- Frontend Mentor - [@shazminnasir67](https://www.frontendmentor.io/profile/shazminnasir67)



