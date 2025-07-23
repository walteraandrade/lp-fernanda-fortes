# Design Implementation TODO List

This document outlines the tasks required to make the website a faithful implementation of the provided design mockups.

## General Tasks

- [ ] **Fonts:**
    - [ ] Identify the correct heading font from the design and replace 'Lora'.
    - [ ] Identify the correct body font and replace 'Montserrat'.
    - [ ] Host fonts locally or ensure correct Google Fonts import.
- [ ] **Colors:**
    - [ ] Use a color picker to get the exact hex codes from the design for:
        - Background (including the subtle texture/gradient).
        - Primary text color.
        - Secondary text color.
        - Accent colors.
    - [ ] Update the CSS variables in `global.css`.
- [ ] **Decorative Elements:**
    - [ ] Extract the hand-drawn lines from the design or recreate them as SVG/PNG.
    - [ ] Add the lines to the appropriate sections.
    - [ ] Ensure the "plantinha" illustration is used as a divider and accent as shown in the design.

## Section-Specific Tasks

### Hero Section (`atendimento psicológico...`)
- [ ] **Layout:**
    - [ ] Wrap the entire section in a container.
    - [ ] Style the container to have a light beige background, rounded corners, and a border, as per the design.
- [ ] **Typography:**
    - [ ] Remove the background color from the "especialista em..." text.
    - [ ] Adjust font sizes and weights to match the design.

### Image Gallery
- [ ] **Layout:**
    - [ ] Ensure the desktop layout is a horizontal row with minimal spacing.
    - [ ] Ensure the mobile layout stacks the images vertically as shown in the design.

### Features Section (`modalidades presencial...`)
- [ ] **Typography:**
    - [ ] Adjust font sizes, weights, and line breaks to match the visual hierarchy of the design.

### About Me Section (`sobre mim`)
- [ ] **Layout:**
    - [ ] Left-align the "sobre mim" title on desktop.
    - [ ] Justify the paragraph text.
- [ ] **Mobile:**
    - [ ] Ensure the mobile layout includes the bordered box around the text.

### Footer
- [ ] **Layout:**
    - [ ] Add contact icons (phone, email, location).
    - [ ] Adjust spacing and alignment to precisely match the design.
- [ ] **Mobile:**
    - [ ] Ensure the mobile layout stacks the elements correctly within a bordered box.

## Responsive Implementation
- [ ] Review and adjust all media queries to ensure the mobile layout is a single, scrolling column with bordered boxes for each section, as shown in the mobile design.
