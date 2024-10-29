# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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



## Overview

Project Overview:
I created a responsive product preview card that follows the design specifications. The card is structured with an image on top, and below it, product details, including the product title, description, price, and a button.

Key Details:
Responsive Layout: The layout adjusts for desktop and mobile views. On mobile, the image takes up the top half of the card, and content is displayed below it in a single column.

Styling:

Image: The image fills the top half of the card using object-fit: cover to maintain aspect ratio.
Text Alignment: Text is aligned to the left to enhance readability.
Button Styling: The button has custom styling for color, padding, and rounded corners and is centered below the text for a clean look.
Media Queries: The CSS includes a media query to adjust styling on smaller screens, making the layout user-friendly on mobile devices.

CSS Techniques Used:
flexbox for layout and alignment
object-fit for image scaling
media queries for responsiveness.

### The challenge

Challenges Faced
Text and Image Positioning: Arranging the image alongside text to ensure it aligns well on various devices.
Responsiveness: Making the layout adapt for both desktop and mobile views was challenging, especially ensuring the image adjusts naturally to smaller screens without distorting.
Button Styling and Alignment: Positioning the "Add to Cart" button to balance the overall layout, with particular attention to spacing and alignment, required careful CSS adjustments.

### Screenshot

![](images/Screenshot%20(73).png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process


Here’s a summary of your development process to share on Frontend Mentor:

My Development Process
Structuring the HTML: I started by setting up a semantic HTML structure, organizing the image and text sections within a container for easier styling.

Applying CSS for Layout and Styling: I used Flexbox to arrange the image and text side-by-side for the desktop view, adjusting padding, colors, and typography to match the design’s intended style.

Button Design: Styling the button to match the brand color was a focus, ensuring it stands out while maintaining simplicity. I adjusted padding, font size, and alignment to make it visually appealing.

Making It Responsive: Using media queries, I shifted the layout for mobile, stacking the image at the top with text and button aligned below in a single column. I adjusted the image's height and width to keep proportions consistent and prevent overflow.

Testing and Refining: I tested the design on different devices to ensure it maintained structure and readability, tweaking font sizes and spacing for clarity.

### Built with

- HTML for the structure and semantic markup.
- CSS for layout, styling, and responsive design.
- Flexbox for aligning elements in a row for desktop view.
- Media Queries to ensure responsiveness and optimize the layout for mobile screens.
- Google Fonts to bring in custom typography for a polished look.


### What I learned

### What I Learned

1. Responsive Design:
   I learned how to implement responsive design using media queries and Flexbox. This project helped me understand how to adjust layouts based on screen size.

   ```css
   @media (max-width: 768px) {
       .box {
           flex-direction: column;
           align-items: center;
       }
       .box img {
           width: 100%; /* Adjust image width for mobile */
           height: auto; /* Maintain aspect ratio */
       }
   }
   ```

2. **CSS Flexbox**:
   Utilizing Flexbox allowed me to easily center elements and create a layout that adapts to various screen sizes.

   ```css
   .container {
       display: flex;
       justify-content: center;
       align-items: center;
   }
   ```

3. Semantic HTML:
   I focused on using semantic HTML elements, which not only improves accessibility but also enhances SEO.

   ```html
   <h5>P E R F U M E</h5>
   <h2>Gabrielle Essence Eau De Parfum</h2>
   <p>A floral, solar and voluptuous interpretation composed by Olivier Polge, Perfumer-Creator for the House of CHANEL.</p>
   ```

4. Button Styling and Interaction:
   I learned how to style buttons to make them visually appealing and enhance user experience.

   ```css
   .button {
       background-color: hsl(158, 36%, 37%);
       color: white;
       border-radius: 5px;
       padding: 5px;
       cursor: pointer;
   }
   ```

5. Using Google Fonts:
   I explored how to integrate Google Fonts into my project to enhance typography.

   ```html
   <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:wght@400;700&display=swap">
   ```

6. Visual Hierarchy:
   I practiced creating a clear visual hierarchy with headings, paragraphs, and buttons, ensuring users can easily navigate the content.

   ```css
   h2 {
       font-weight: 700;
       color: hsl(158, 36%, 37%);
   }
   ```

These learnings have not only improved my coding skills but also boosted my confidence in building responsive and user-friendly web applications.

### Continued Development

1. Advanced CSS Techniques:
   I want to deepen my understanding of advanced CSS features, such as CSS Grid and animations. These techniques can enhance the user experience and add visual interest to my projects.

   ```css
   .grid-container {
       display: grid;
       grid-template-columns: repeat(3, 1fr);
       gap: 10px;
   }
   ```

2. JavaScript for Interactivity:
   I aim to improve my JavaScript skills, particularly in manipulating the DOM and adding interactivity to my web applications. This will allow me to create more dynamic user experiences.

   ```js
   document.querySelector('.button').addEventListener('click', () => {
       alert('Item added to cart!');
   });
   ```

3. Accessibility Best Practices:
   I want to focus on ensuring that my projects are accessible to all users, including those with disabilities. Learning more about ARIA roles and semantic HTML will help achieve this.

   ```html
   <button aria-label="Add to Cart">Add to Cart</button>
   ```

4. **Performance Optimization**:
   Understanding how to optimize web performance is a key area for continued development. I want to learn more about image optimization, minifying CSS/JavaScript, and reducing load times.

   ```bash
   # Example of minifying CSS with a build tool
   npm run build-css
   ```

5. Version Control with Git:
   I plan to enhance my skills with Git for version control. Understanding branching, merging, and pull requests will help me manage code more effectively, especially when collaborating on larger projects.

   ```bash
   git checkout -b feature/new-feature
   ```

6. Responsive Frameworks:
   I want to explore responsive design frameworks like Bootstrap or Tailwind CSS. These can speed up development time and provide pre-built components that can enhance design consistency.

   ```html
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
   ```

By focusing on these areas, I aim to continually improve my skills and create even more polished, user-friendly web applications in future projects.

### Useful resources

CSS Tricks: A comprehensive website with tutorials and articles on CSS, responsive design, and modern web development techniques.

## Author

- Website - [Khaisar](https://khaisar-tech.github.io/Product-card/)
- Frontend Mentor - [@Khaisar-tech](https://www.frontendmentor.io/profile/Khaisar-tech)

## Acknowledgments

I would like to extend my heartfelt thanks to the following individuals and resources for their support and inspiration throughout this project:

Frontend Mentor Team: For providing an excellent platform with well-structured challenges that helped me apply my skills in real-world scenarios.
