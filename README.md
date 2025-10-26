# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
  - [Analysis of The Design](#analysis-of-the-design)
  - [Planning the Solution](#planning-the-solution)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Analysis of The Design

1. **Desktop Design:**

- Grid layout with 5 testimonials arranged in 4 columns
- First testimonial (Daniel Gifford) spans 2 columns
- Different background colors for each testimonial
- Verified Graduate badge with checkmark
- Quotes with personal stories

2. **Mobile Design:**

- Stacked single-column layout

- Same content but rearranged in different order
- Slightly modified text in some testimonials

## Planning the Solution

1. **HTML Structure**
   We'll need:

- A main container for the grid
- Individual testimonial cards

Each card will contain:

- Author info (name, verified status)
- Highlighted testimonial summary
- Detailed testimonial quote

2. **CSS Approach**

- Use CSS Grid for desktop layout
- Flexbox for card internal layouts
- Media queries to switch between grid and stacked layout
- Custom properties for colors and spacing

3. **Responsive Strategy**

- Mobile-first approach (~320px start with single column)
- Breakpoint at ~664px to switch to 2 column grid layout
- Breakpoint at ~1024px to switch to 3 column grid layout
- Breakpoint at ~1200px to switch to desktop grid layout

  **Workflow**

- I will use article element for each post
- In the CSS I will apply 4columns and two rows
- Then apply grid-area to assign each grid item their respective start and end point.
- Classes: all the articles share similar properties like border-radius, box-shadow, padding... so they shall have common class as well as specific classes.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Mobile Design](./Screenshots/mobile%20design.png)
![Desktop Design](./Screenshots/desktop%20design.png)

### Links

- Solution URL: [Testimonials grid section](https://github.com/Dadir-Dev/testimonials-grid-section-main)
- Live Demo URL: [Testimonials grid section]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
