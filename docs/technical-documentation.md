# Technical Documentation

## 1. Project Overview

This project is an interactive personal portfolio website developed using HTML, CSS, and JavaScript. It is an improved version of Assignment 1 with added interactivity and better user experience.

The website includes sections for About, Projects, and Contact, and allows users to interact with features such as filtering projects, switching themes, and submitting a form.

---

## 2. Technologies Used

HTML was used to structure the content of the website using semantic elements such as navigation, sections, and forms.

CSS was used for styling, layout, and responsiveness. CSS Grid and Flexbox were used to create structured layouts. CSS variables were used to manage light and dark themes.

JavaScript was used to add interactivity, including theme switching, project filtering, modal functionality, and form validation.

Git and GitHub were used for version control and managing the project files.

---

## 3. Project Structure

The project is organized as follows:

- index.html → main structure of the website  
- css/styles.css → styling and layout  
- js/script.js → interactivity and functionality  
- assets/images → images used in the project  
- docs → documentation files  
- README.md → project overview  

This structure helps keep the project clean and organized.

---

## 4. Features

### 4.1 Dynamic Content

The project includes a filtering system in the Projects section. Users can click buttons (All, Web Apps, UI/UX) to show or hide projects dynamically.

### 4.2 Data Handling

The theme toggle uses localStorage to save user preference. When the user selects light or dark mode, the choice is saved and applied when the page reloads.

The contact form also handles user input and validates it before submission.

---

### 4.3 Interactivity

- Theme toggle button switches between light and dark mode  
- Modal window shows project details when clicking “Details”  
- Back-to-top button appears when scrolling  
- Greeting message changes based on time of day  

---

### 4.4 Form Validation

The contact form checks:

- Name must be at least 2 characters  
- Email must be valid  
- Message must be at least 5 characters  

If the input is invalid, error messages are displayed.  
If valid, a success message appears after a short delay.

---

### 4.5 Animations and Transitions

- Hover effects on buttons and navigation links  
- Card hover animation with movement and glow effect  
- Smooth transitions for better user experience  

---

## 5. Responsive Design

The website is responsive and works on different screen sizes.

- CSS Grid is used for project layout  
- Flexbox is used for navigation and form layout  
- Media queries adjust layout for tablets and mobile devices  

The layout was tested by resizing the browser and using developer tools.

---

## 6. Accessibility

- Images include alt text  
- Form inputs have labels  
- Buttons use proper types  
- Colors have good contrast for readability  

---

## 7. Testing

The project was tested to ensure:

- All features work correctly  
- Filtering works properly  
- Modal opens and closes  
- Form validation works  
- No console errors appear  
- Layout does not break on smaller screens  

---

## 8. Performance

The website is lightweight because:

- No external frameworks are used  
- Files are organized and optimized  
- Images are stored locally  

---

## 9. Learning Outcomes

Through this project, I learned:

- How to add interactive features using JavaScript  
- How to improve user experience with dynamic behavior  
- How to use localStorage  
- How to design responsive layouts  
- How to organize code and documentation  

---

## 10. Conclusion

This project demonstrates improvement from Assignment 1 by adding interactivity and better user experience. It shows my understanding of front-end development and prepares me for building more advanced web applications in the future.