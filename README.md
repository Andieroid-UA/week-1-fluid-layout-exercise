## Exercise: FluidBiz Co. 

A part of the CodeLabs FrontEnd Bootcamp. Original source code: https://github.com/Codefi-Code-Labs/FE-VIdeo-Exercises/blob/main/class-2-intermediate-css/exercises.md

**Objective**: Create a responsive, fluid layout for a fictional business website. The website should contain a header, three columns (services, main content, testimonials), and a footer.

Instructions:
Setup: Create a new folder named fluid-layout-exercise. Inside this folder, create two files: index.html and styles.css.

HTML Structure: Open index.html in VS Code and add the following elements:

- A `<header>` with the title "FluidBiz Co." and a navigation bar containing links: Home, Services, Testimonials, and Contact.
- Three `<div>` elements with the classes .services, .main-content, and .testimonials.
- A `<footer>` mentioning "Copyright © 2023 FluidBiz Co."
- Basic Styling: Link your styles.css in your HTML. 
  
  **Set a basic style:**

- Set a background color for the body and different background colors for the header, columns, and footer to distinguish them.

**Fluid Layout:**

- Set the width of the .services and .testimonials columns to 25% and the .main-content to 50%.
- Float the .services to the left, .testimonials to the right, and .main-content to the left.
- Ensure that the columns sit side by side.

**Populate Content:**

- Inside the .services column, list down at least 3 fictional services offered by FluidBiz Co.
- For the .main-content, write a brief introduction about FluidBiz Co. and what they specialize in.
- In .testimonials, include 3 fictional testimonials from satisfied customers.

**Responsiveness:**

- Ensure your layout is fluid. Test by resizing your browser window.
- Bonus: Add media queries to stack the columns vertically when the screen width goes below 768px.

**Review:**

- Make sure there's no horizontal scrollbar at any screen size.

**Tips**:
- Remember to clear floats after your columns to prevent layout issues.
- Ensure proper content hierarchy with the use of `<h1>`, `<h2>`, and so on.
- If you finish early, enhance your design by adding images, hover effects, or any other additional styling.

