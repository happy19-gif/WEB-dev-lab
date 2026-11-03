# P13: Choosing Between Flexbox and Grid for a Shared Layout

## Aim
To understand and implement CSS Flexbox and CSS Grid together in a responsive portfolio layout.

## Technologies Used
- HTML5
- CSS3
- CSS Flexbox
- CSS Grid
- Media Queries

## Description
This practical demonstrates how Flexbox and CSS Grid can work together to create a responsive portfolio website.

The page contains a header, navigation bar, sidebar, project cards, layout comparison section, and footer.

## Flexbox Implementation

Flexbox is used for one-dimensional layouts.

It is implemented in:
1. Header navigation.
2. Alignment of navigation links.
3. Project card action rows.
4. Footer alignment.

Important properties:
- `display: flex`
- `justify-content`
- `align-items`
- `flex-wrap`
- `gap`
- `flex-direction`

## CSS Grid Implementation

CSS Grid is used for two-dimensional layouts.

It is implemented in:
1. Main page layout with sidebar and content.
2. Project cards section.
3. Flexbox vs Grid comparison section.

Important properties:
- `display: grid`
- `grid-template-columns`
- `gap`
- `minmax()`
- `repeat()`

## Responsive Design
- Desktop: Sidebar and content appear side by side.
- Tablet: Main layout changes to a single-column structure.
- Mobile: Project cards and comparison sections display in one column.

Media queries are used to adjust the layout for different screen sizes.

## Flexbox vs CSS Grid

| Flexbox | CSS Grid |
|---|---|
| One-dimensional layout | Two-dimensional layout |
| Works with rows or columns | Works with rows and columns |
| Useful for navigation | Useful for page layouts |
| Useful for button alignment | Useful for project card grids |

## Conclusion
Successfully implemented Flexbox and CSS Grid together to create a responsive portfolio website and understood when to use each layout system.