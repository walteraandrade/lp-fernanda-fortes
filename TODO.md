# Design Implementation TODO List

This document outlines the tasks required to make the website a faithful implementation of the provided design mockups.

## General Tasks

- [X] **Fonts:**
    - [X] Identify the correct heading font from the design and replace 'Lora'.
    - [X] Identify the correct body font and replace 'Montserrat'.
    - [X] Host fonts locally or ensure correct Google Fonts import.
- [X] **Colors:**
    - [X] Use a color picker to get the exact hex codes from the design for:
        - Background (including the subtle texture/gradient).
        - Primary text color.
        - Secondary text color.
        - Accent colors.
    - [X] Update the CSS variables in `global.css`.
- [X] **Decorative Elements:**
    - [X] Extract the hand-drawn lines from the design or recreate them as SVG/PNG.
    - [X] Add the lines to the appropriate sections.
    - [ ] Ensure the "plantinha" illustration is used as a divider and accent as shown in the design.

## Section-Specific Tasks

### Hero Section (`atendimento psicológico...`)
- [X] **Layout:**
    - [X] Wrap the entire section in a container.
    - [X] Style the container to have a light beige background, rounded corners, and a border, as per the design.
- [X] **Typography:**
    - [X] Remove the background color from the "especialista em..." text.
    - [X] Adjust font sizes and weights to match the design.

### Image Gallery
- [X] **Layout:**
    - [X] Ensure the desktop layout is a horizontal row with minimal spacing.
    - [ ] Ensure the mobile layout stacks the images vertically as shown in the design.

### Features Section (`modalidades presencial...`)
- [X] **Typography:**
    - [X] Adjust font sizes, weights, and line breaks to match the visual hierarchy of the design.

### About Me Section (`sobre mim`)
- [X] **Layout:**
    - [X] Left-align the "sobre mim" title on desktop.
    - [X] Justify the paragraph text.
- [ ] **Mobile:**
    - [ ] Ensure the mobile layout includes the bordered box around the text.

### Footer
- [X] **Layout:**
    - [X] Add contact icons (phone, email, location).
    - [ ] Adjust spacing and alignment to precisely match the design.
- [ ] **Mobile:**
    - [ ] Ensure the mobile layout stacks the elements correctly within a bordered box.

## Responsive Implementation
- [ ] Review and adjust all media queries to ensure the mobile layout is a single, scrolling column with bordered boxes for each section, as shown in the mobile design.
