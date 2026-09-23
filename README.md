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
<img width="435" height="352" alt="image" src="https://github.com/user-attachments/assets/fa5c501e-3e2d-402f-b818-47edaab8477c" />
<img width="435" height="187" alt="image" src="https://github.com/user-attachments/assets/f92f4b91-9ff6-4d3c-8aa7-e90bad89ed1e" />

### Task 1.2: Card Row
**Description:**
A container holds three cards, each containing an image, title, text, and a button. The container is a flex container (`display: flex`), allowing cards to appear in a row. `flex: 1` ensures all cards have equal height, and `gap` provides consistent spacing. A hover effect (shadow and scale) is added to each card.

**Screenshot:**
![Card Row Screenshot](path/to/your/cards_screenshot.png)

---

## Part 2: Grid System

### Task 2.1: Page Layout with Grid Areas
**Description:**
A page layout was created with a header, sidebar, main content, and footer. The parent container uses `display: grid`. Grid areas were defined using `grid-template-areas` to place the header across the top, the sidebar on the left, the main content on the right, and the footer across the bottom.

**Screenshot:**
![Grid Layout Screenshot](path/to/your/grid_layout_screenshot.png)

### Task 2.2: Image Gallery
**Description:**
A gallery container holds at least nine images. It is set as a grid container (`display: grid`) with multiple equal-width columns and rows using `grid-template-columns: repeat(3, 1fr)`. Consistent gaps are added. A hover effect displays a caption overlay on the image using absolute positioning and opacity transitions.

**Screenshot:**
![Image Gallery Screenshot](path/to/your/gallery_screenshot.png)

---

## Part 3: Combining Flexbox & Grid

**Description:**
A portfolio page structure was created with a header, main section (projects area on the left, sidebar on the right), and footer.
- **Header:** Uses **Flexbox** for the navigation bar.
- **Main Section:** Uses **CSS Grid** to separate the projects area and the info sidebar.
- **Project Cards:** Uses **Flexbox** internally to arrange the content (title, description, button).
- **Footer:** Spans across the bottom of the page.

**Screenshot:**
![Combined Layout Screenshot](path/to/your/combined_layout_screenshot.png)

---

## Summary of Work Process

For this assignment, I started by building the HTML structure for each task separately to ensure semantic correctness. I then applied CSS styling, focusing on modern layout techniques.

For **Part 1**, I utilized Flexbox to handle the header navigation and the card row, experimenting with `justify-content`, `align-items`, and `flex` properties to achieve the desired alignment and equal heights.

For **Part 2**, I transitioned to CSS Grid. I found `grid-template-areas` particularly useful for the page layout task, as it made the structure very readable. For the image gallery, `repeat()` and `1fr` units helped create a responsive grid quickly.

For **Part 3**, the main challenge was combining both layout models effectively. I used Flexbox for the micro-layout (inside the cards and header) and Grid for the macro-layout (the overall page structure). This combination proved to be very powerful and efficient. I also ensured the design was responsive and consistent throughout.

---

## How to Run

1. Clone this repository.
2. Open `index.html` in any modern web browser.
