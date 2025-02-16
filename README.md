# Frontend Mentor - Testimonials Grid Section

This is a solution to the **Testimonials Grid Section** challenge on [Frontend Mentor](https://www.frontendmentor.io/). This project helped me improve my skills in **CSS Grid**, **BEM methodology**, and responsive design.

## 🎯 Overview

### The challenge

Users should be able to:

- View the testimonials in a grid layout
- See different styles for each testimonial card
- Experience a responsive design that adapts to various screen sizes

### Screenshot

![](./images/screenshot_1.jpeg)
![](./images/screenshot_2.jpeg)


### Links

- 📂 [GitHub Repository](https://github.com/ivanpehar/testimonials_grid_section)
- 🌍 [Live Site](https://ivanpehar.github.io/testimonials_grid_section/)

## 🛠️ Built with

- Semantic **HTML5**
- **CSS Grid** for layout
- **Flexbox** for positioning elements within cards
- **BEM (Block Element Modifier)** methodology for structuring CSS
- **Responsive design** using media queries

## 🚀 What I learned

During this project, I improved my understanding of:

- **Using CSS Grid** to create a structured and responsive layout.
- **Applying BEM methodology** to keep my CSS scalable and maintainable.
- **Handling typography** by using global styles and class modifiers.
- **Positioning elements inside a grid** and aligning them properly.

### Challenges & Solutions

1. **Issue with positioning the quotation mark (`"`)**  
   - It needed to be placed at the end of a testimonial card but also **behind the text**.  
   ✅ *Solution:* Used `position: absolute;` with `z-index` to place it correctly.

2. **Targeting elements inside specific card types**  
   - The **white cards** needed different text colors.  
   ✅ *Solution:* Used `.testimonials__card--white` as a parent selector to apply styles to child elements.

3. **Centering the grid properly**  
   - The testimonials grid was slightly off-centered.  
   ✅ *Solution:* Wrapped the entire grid in a `display: flex; flex-direction: column; align-items: center;`.

## 📌 Continued development

For future projects, I want to:

- Explore **more advanced CSS Grid techniques**.
- Improve **accessibility (ARIA attributes)** for better screen reader support.
- Implement **CSS animations** for better UI interactions.

## 📚 Useful resources

- 🔗 [CSS Tricks - Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)  
  *(Helped me structure the grid layout properly.)*  
- 🔗 [BEM Naming Convention](https://getbem.com/)  
  *(Helped maintain a clean and scalable CSS structure.)*  
- 🔗 [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)  
  *(Great reference for grid properties.)*

## 👨‍💻 Author

- **GitHub** - [ivanpehar](https://github.com/ivanpehar)
- **Frontend Mentor** - [@ivanpehar](https://www.frontendmentor.io/profile/ivanpehar)

## 🎉 Acknowledgments

A big thanks to **Frontend Mentor** for this amazing challenge and the community for their support. 🚀  
