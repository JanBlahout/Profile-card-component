# Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

- Build out the project to the designs provided

### Links

- Live Site URL: https://distracted-jennings-cb187c.netlify.app/

## My process
Started with the background. Took me a while to understand what is needed from me. 
Then I created a DIV and centered it. Made couple of more divs to seperate the texts.
Styled it and then fiddled with margins and paddings.

### Built with

- Semantic HTML5 markup
- Flexbox
- Desktop-first workflow

### What I learned

```css
.bg-top {
  position: absolute;
  top: 0;
  left: 0;
  transform: translate(-25%, -50%);
  z-index: -1;
}

.profile-img {
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translate(-50%, 50%);
  border: 5px solid #fff;
  border-radius: 50%;
}
```

### Continued development

I have to focus more on positioning of divs.
I think I could have solved better the stats section at the bottom of the card.

Also I dont know how to make the images in top left and bottom right corner scale down with the window
