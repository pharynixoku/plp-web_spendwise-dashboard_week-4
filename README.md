# SpendWise Dashboard Shell

## Project Description

SpendWise is a responsive personal finance dashboard created using HTML and CSS. The project provides a modern dashboard interface for viewing financial information such as food, transport, rent, entertainment, savings, and utilities.

The project focuses on CSS Grid, Flexbox, responsive design, CSS custom properties, and card micro-interactions.

## Files

### index.html

Contains the structure of the SpendWise dashboard, including:

- Sidebar navigation
- Header
- Financial summary
- Six category cards
- Recent activity section

### style.css

Contains all the styling for the dashboard. It uses:

- CSS Grid for the main dashboard and category cards
- Flexbox for the sidebar, header, summary cards, and dashboard content
- CSS custom properties for the theme
- Responsive media queries
- Hover and keyboard focus effects
- Dark theme support

## CSS Grid

CSS Grid is used for the overall dashboard layout and category card layout. The desktop layout has a sidebar and a main content area, while the category cards are arranged in three columns.

## Flexbox

Flexbox is used inside the sidebar, navigation links, header, profile section, summary cards, and individual dashboard cards.

## Responsive Design

The dashboard changes to a single-column layout when the screen width is below 768px. This makes the dashboard easier to use on tablets and mobile devices.

## Micro-interactions

The category cards use a 200ms transition. When a user hovers over or focuses on a card, it moves slightly upward and receives a shadow.

## Dark Theme

A dark theme is included using:

@media (prefers-color-scheme: dark)

Only the CSS custom properties are overridden to change the theme colors.

## How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Use browser DevTools to test the responsive layout.

## Author

Simon Ohure
