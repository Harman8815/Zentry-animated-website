# Hero Section

- We first created the **hero section**, which consists of:
  - A **video background**
  - A **center div** with zero opacity initially and a video placed inside it
  - On click, the video shifts from the center div to the main div

- We're using **GSAP** to implement smooth animations:
  - To make the transitions look cool
  - To control scroll-based animations, giving the page a unique and engaging effect

- At the bottom, there's a **"Gaming" text effect**:
  - The text is duplicated: one on top and one below
  - Each has a different color
  - As the user scrolls, the video gets partially removed, revealing the second color of the text

# About Section

## Custom Text Component

- A unique component is created for the about text:
  - Each word is broken down individually
  - **GSAP** is used to animate each word separately
  - The animation is scroll-triggered

## About Section Video

- A video is embedded in the about section
- **GSAP** animates the video to stretch to full width after scrolling past a certain point
- Reverse animations are also used to return to the initial state when scrolling back

# Navbar

- The navbar is a simple component, similar to the ones used in previous projects
- Nothing new or custom added here

# Feature Section

- A basic **grid layout** is used
- Includes a **tilt effect** triggered on `mouseenter`, similar to techniques used before

# Story Section

- The standout feature here is the **text with a mix-blend property**
- It creates a visually appealing effect due to the **tilted background image**
- This is a reusable effect for future projects

# Contact Us & Footer

- Both sections are kept simple and minimal
- No unique elements or interactions added here
