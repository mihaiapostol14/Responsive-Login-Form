# Responsive Login Form

This project showcases a responsive login form with a modern and clean design. It includes structured elements such as labels, input fields, a submit button, and a circular span element.

## Preview

![Responsive Login Form Preview](https://github.com/mihaiapostol14/Responsive-Login-Form/blob/f6fb980fb2f9531889b644156cfe9267ebe2eda3/assets/preview.png)


## Getting Started

To set up and run the Responsive Login Form project locally, follow these steps:

## 1. Clone the repository:
```bash
git clone https://github.com/mihaiapostol14/Responsive-Login-Form.git
cd Responsive-Login-Form
```

### 2. Open File
`index.html` in your web browser to view the responsive login form


## Global Styling
- The universal selector (`*`) ensures all elements have `margin: 0`, `padding: 0`, and `box-sizing: border-box` for consistent spacing and layout.
- The `body` has a **dark blue background (`#1c3551`)**, full width and height, and uses `display: flex` to center the form.
- The font is set to `sans-serif` for readability.

## Form Styling
- The form is centrally aligned using `margin: auto`.
- It has a width of `30%` on larger screens, with a `max-width: 95%` for smaller screens.
- The background color is set to `#1c2833` (dark gray-blue).
- It has `padding: 20px`, rounded corners (`border-radius: 10px`), and a white font color (`color: #fff`).

## Heading (`h2`)
- Centered using `text-align: center`.
- Spaced out with `margin: 20px 0`.
- The font is inherited from `sans-serif`.

## Label Styling
- Labels are bold (`font-weight: bolder`) and white (`color: #fff`) for clear readability.

## Input Fields
- `width: 100%` ensures inputs take up the full available space.
- Margins and padding provide comfortable spacing.
- The font size is `20px` for easy readability.
- Background color is set to `#1c2833` to match the form’s theme.
- A bottom border (`border-bottom: 2px solid #aaa`) highlights the input field.
- `color: #aaa` ensures the text is subtly visible.
- The `::placeholder` selector capitalizes placeholder text.

## Input Focus Effect
- `outline: none` removes the default focus outline for a cleaner look.

## Submit Button
- The button has a **red background (`#ff0000`)** and white text.
- It has a `border-radius: 25px` for a rounded look.
- The padding is `15px`, making it easy to tap or click.
- It has a `transition: all 0.3s ease-in-out` for smooth hover effects.
- `cursor: pointer` ensures a clickable effect.

## Circular Icon (`span`)
- `display: block` centers the element.
- Positioned slightly above the form using `margin-top: -60px`.
- The background color is **light blue (`#00eeff`)**.
- Width and height are `90px`, creating a perfect circle.
- Font size of `60px` makes the icon visually prominent.
- `border-radius: 50%` ensures a circular shape.

## Responsive Design
- On screens **wider than 1024px**, the form remains at `30%` width.
- On screens **smaller than 1024px**, the form expands to `90%` width, making it more mobile-friendly.

## Potential Fixes
1. The `.enlace` class seems to be misplaced inside the `span` styles; it should be moved outside for proper formatting.
2. The `object-fit: cover;` property appears unnecessary for a `span` element.

This CSS provides a well-structured, **fully responsive**, and **visually appealing login form** that adapts to different screen sizes smoothly.

## Repository Details
- **Repository Name:** Responsive-Login-Form
- **Owner:** [mihaiapostol14](https://github.com/mihaiapostol14)
- **Languages Used:** CSS (73.1%), HTML (26.9%)
- **Visibility:** Public
- **Created:** 19 days ago
- **Last Updated:** 19 days ago
- **Stars:** 0
- **Forks:** 0
- **Open Issues:** 0
- **Watchers:** 0
