# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help me improve my coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
  - [Analysis of The Design](#analysis-of-the-design)
  - [Planning the Solution](#planning-the-solution)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [🔧 Built With](#-built-with)
    - [What I learned](#what-i-learned)
  - [Continued Development](#continued-development)
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
- Live Demo URL: [Testimonials grid section](https://dadir-dev.github.io/testimonials-grid-section-main/)

## My process

### 🔧 Built With

- Semantic **HTML5**
- **CSS Grid**
- **Responsive design**
- **VS Code** and **Live Server**
- **Git + GitHub**

### What I learned

Here’s a small snippet I’m proud of 👇:

```css
.daniel-clifford {
  grid-column: 1 / 3;
  grid-row: 1 / 2;
}
.jonathan-walters {
  grid-column: 3 / 4;
  grid-row: 1 / 2;
}
.jeanette-harmon {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
}
.patrick-abrams {
  grid-column: 2 / 4;
  grid-row: 2 / 3;
}
.kira-whittle {
  grid-column: 4 / 5;
  grid-row: 1 / 3;
}
```

## Continued Development

In the future, I want to:

- Add smooth animations to each grid item

- Explore using CSS variables for better maintainability

- Recreate this layout using a CSS framework like Tailwind CSS

## Author

- Frontend Mentor - [Dadir-Dev](https://www.frontendmentor.io/profile/Dadir-Dev)
- GitHub - [Dadir-Dev](https://github.com/Dadir-Dev)
- LinkedIn - [Abdikadir Mohammed](https://www.linkedin.com/in/abdikadir-mohammed-54717318b/)

## Acknowledgments

Thanks to Frontend Mentor for the great design and to the developer community for inspiration and feedback.
