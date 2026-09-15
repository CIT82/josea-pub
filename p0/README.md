# External CSS Libraries:
<!-- list the external CSS libraries used in your project: js folder and css folder -->
1. js library: scripts.js
2. css library: styles.css (file name)
3. Custom CSS link: [Go to Custom CSS](css/styles.css)

# Major Functional Blocks:

### 1. Navigation/Menu
- **Lines:** 15–28
- **Opening tag/classes:** `<nav class="navbar navbar-expand-lg navbar-dark bg-dark">`
- **Power Classes:**
  - `navbar`: Creates a responsive flexbox navigation layout.
  - `navbar-expand-lg`: Keeps the menu collapsed below the large breakpoint and expands it at 992px and wider.
  - `navbar-dark`: Uses light-colored text and a light toggler icon for dark backgrounds.
  - `bg-dark`: Gives the navigation bar a dark background.

### 2. Logo/Branding
- **Lines:** 17–17
- **Opening tag/classes:** `<a class="navbar-brand" ...>`
- **Power Class:**
  - `navbar-brand`: Styles the brand name with larger text, spacing, navbar colors, and prevents the text from wrapping.

The logo is positioned inside the navigation’s `.container`, alongside the menu toggle and navigation links.

### 3. First Content Section: “Full Width Backgrounds”
- **Lines:** 36–46
- **Opening tag/classes:** `<section class="py-5">`
- **Power Class:**
  - `py-5`: Adds vertical padding of 3rem to the top and bottom of the section.

Supporting layout classes include `container my-5`, `row justify-content-center`, and `col-lg-6`, which center the content, add spacing, and limit the text column to half-width on large screens.

### 4. Second Content Section: “Engaging Background Images”
- **Lines:** 52–62
- **Opening tag/classes:** `<section class="py-5">`
- **Power Class:**
  - `py-5`: Adds 3rem of vertical spacing above and below the section.

Like the first section, its nested `container`, `row justify-content-center`, and `col-lg-6` classes control the centered, responsive text layout.

# Additional Functional Blocks:

1. Full-Width Image Section
- **Lines:** 48–52
- **Opening tag/classes:** `<div class="py-5 bg-image-full">`
- **Power Classes:**
  - `py-5`: Adds 3rem of vertical padding.
  - `bg-image-full`: Applies full-width background image styling, including background positioning and sizing.
The inline style supplies the background image, while the inner spacer gives the image section a height of 20rem.

2. Second Content Section: “Engaging Background Images”
- **Lines:** 53–62
- **Opening tag/classes:** `<section class="py-5">`
- **Power Class:**
  - `py-5`: Adds 3rem of vertical padding above and below the section.
  - Its nested classes `container`, `my-5`, `row`, `justify-content-center`, and `col-lg-6` control spacing, centering, and responsive width.

3. Footer
- **Lines:** 63–65
- **Opening tag/classes:** `<footer class="py-5 bg-dark">`
- **Power Classes:**
  - `py-5`: Adds 3rem of vertical padding.
  - `bg-dark`: Applies Bootstrap’s dark background color.
The footer contrasts with the white content sections through its dark background. Its nested classes `container`, `m-0`, `text-center`, and `text-white` constrain, align, and color the copyright text.