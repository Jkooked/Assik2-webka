# Assignment #2: Advanced CSS (Flexbox & Grid)

**Student Name:** Abitay Ainaz
**Group:** IT-2502

## Project Overview

This repository contains the solution for Assignment #2, focusing on advanced CSS layout techniques using Flexbox and CSS Grid. The project is structured into three main parts as per the assignment requirements.

---

## Part 1: Header & Card Row (Flexbox)

### Task 1.1: Header Section
**Description:**
A header section was created with a logo on the left and a navigation list on the right. The header container uses `display: flex` to align items horizontally. `justify-content: space-between` is used to push the logo and links apart, and `align-items: center` ensures vertical centering. The links have spacing applied using Flexbox `gap` property.

**Screenshot:**
<img width="459" height="368" alt="image" src="https://github.com/user-attachments/assets/167399e0-3958-4878-8226-aea0697a1f40" />

<img width="575" height="422" alt="image" src="https://github.com/user-attachments/assets/fa815e8e-5405-41ea-977a-0ced31e206f9" />
<img width="575" height="458" alt="image" src="https://github.com/user-attachments/assets/45eb604b-730a-4051-9f7b-3c80f9d2c918" />


### Task 1.2: Card Row
**Description:**
A container holds three cards, each containing an image, title, text, and a button. The container is a flex container (`display: flex`), allowing cards to appear in a row. `flex: 1` ensures all cards have equal height, and `gap` provides consistent spacing. A hover effect (shadow and scale) is added to each card.

**Screenshot:**
<img width="1074" height="455" alt="image" src="https://github.com/user-attachments/assets/7f82d9aa-976e-45c8-935a-5e95f643ad31" />
<img width="457" height="585" alt="image" src="https://github.com/user-attachments/assets/d2ded18c-3128-44ee-a61a-80a4470f6393" />
<img width="457" height="377" alt="image" src="https://github.com/user-attachments/assets/08201a93-8daf-4272-8636-c466467aa231" />


---

## Part 2: Grid System

### Task 2.1: Page Layout with Grid Areas
**Description:**
A page layout was created with a header, sidebar, main content, and footer. The parent container uses `display: grid`. Grid areas were defined using `grid-template-areas` to place the header across the top, the sidebar on the left, the main content on the right, and the footer across the bottom.

**Screenshot:**
<img width="676" height="437" alt="image" src="https://github.com/user-attachments/assets/7cb74ccd-3ce0-471f-9ab1-e808f16fd5a2" />
<img width="457" height="544" alt="image" src="https://github.com/user-attachments/assets/2e4b71be-8d59-4e45-864e-64d68d1b3cf3" />
<img width="457" height="452" alt="image" src="https://github.com/user-attachments/assets/93f6202d-8080-4a1f-a810-a9ef5b5c52c3" />

### Task 2.2: Image Gallery
**Description:**
A gallery container holds at least nine images. It is set as a grid container (`display: grid`) with multiple equal-width columns and rows using `grid-template-columns: repeat(3, 1fr)`. Consistent gaps are added. A hover effect displays a caption overlay on the image using absolute positioning and opacity transitions.

**Screenshot:**
<img width="402" height="526" alt="image" src="https://github.com/user-attachments/assets/4d21481c-8aa4-4e84-9253-a1203cd8f1a0" />
<img width="503" height="275" alt="image" src="https://github.com/user-attachments/assets/809c459a-0531-41a4-aaec-366f94f5000d" />
<img width="503" height="564" alt="image" src="https://github.com/user-attachments/assets/24fdf187-da13-4771-8d33-4ea149344ca9" />
<img width="503" height="401" alt="image" src="https://github.com/user-attachments/assets/ceee232e-247a-456c-bfb6-a578b3d3495f" />

---

## Part 3: Combining Flexbox & Grid

**Description:**
A portfolio page structure was created with a header, main section (projects area on the left, sidebar on the right), and footer.
- **Header:** Uses **Flexbox** for the navigation bar.
- **Main Section:** Uses **CSS Grid** to separate the projects area and the info sidebar.
- **Project Cards:** Uses **Flexbox** internally to arrange the content (title, description, button).
- **Footer:** Spans across the bottom of the page.

**Screenshot:**

<img width="676" height="511" alt="image" src="https://github.com/user-attachments/assets/7d61d22d-0336-487c-a7b7-a7cfe799e5bf" />
<img width="777" height="452" alt="image" src="https://github.com/user-attachments/assets/66be08b6-5f5f-4a83-b1fb-b23605911f1f" />

<img width="777" height="141" alt="image" src="https://github.com/user-attachments/assets/a8f9d6a2-5fb8-4e16-9d7e-f4d548204273" />



---

## Summary of Work Process

For this assignment, I started by building the HTML structure for each task separately to ensure semantic correctness. I then applied CSS styling, focusing on modern layout techniques.

For **Part 1**, I utilized Flexbox to handle the header navigation and the card row, experimenting with `justify-content`, `align-items`, and `flex` properties to achieve the desired alignment and equal heights.

For **Part 2**, I transitioned to CSS Grid. I found `grid-template-areas` particularly useful for the page layout task, as it made the structure very readable. For the image gallery, `repeat()` and `1fr` units helped create a responsive grid quickly.

For **Part 3**, the main challenge was combining both layout models effectively. I used Flexbox for the micro-layout (inside the cards and header) and Grid for the macro-layout (the overall page structure). This combination proved to be very powerful and efficient. I also ensured the design was responsive and consistent throughout.

## https://jkooked.github.io/Assik2-webka/
