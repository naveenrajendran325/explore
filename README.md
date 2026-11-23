# Explore India - Complete Tourism Website

Explore India is a responsive, beginner-friendly tourism and culture website created for an MCA HTML and CSS practical assignment.

## Pages

- `index.html` - three-column homepage
- `destinations.html` - two-column destination guide
- `culture.html` - culture, festivals, dance, CSS-only carousel, audio and PDF

## Open the Project

1. Open the `Explore-India` folder in Visual Studio Code.
2. Install the Live Server extension if it is not already installed.
3. Right-click `index.html` and select **Open with Live Server**.
4. The homepage opens in the browser. Use the navigation links to visit all pages.

You can also open `index.html` directly in a modern browser.

## Technology Used

Only HTML5, CSS3 and Bootstrap 5.3 CSS are used. The project does not use JavaScript, Python or Bootstrap JavaScript components.

## Image Sources

The website uses locally stored, subject-specific photography from Wikimedia Commons rather than broken or random external image links. The banner is an original three-panel photograph composite. Image licensing and attribution details should be preserved before publishing the project outside an educational setting.

## Viva Questions and Answers

1. **What is HTML5?** HTML5 is the latest standard for structuring web pages and applications.
2. **What is CSS3?** CSS3 is the modern standard used to style HTML, including layout, colors and responsive design.
3. **What is Bootstrap?** Bootstrap is a CSS framework that provides a grid system, components and utility classes.
4. **Why did you choose Bootstrap?** It provides consistent responsive layouts and reusable components.
5. **What is the Bootstrap Grid System?** It arranges page content in rows and twelve responsive columns.
6. **What is a Bootstrap Container?** A container centers content and sets suitable horizontal widths.
7. **What is a Bootstrap Card?** A card is a bordered box used to present an image and related content.
8. **What is a Bootstrap Navbar?** A navbar is a styled navigation area for links.
9. **What is responsive web design?** It is an approach that makes a website adapt to phones, tablets and desktops.
10. **What are media queries?** Media queries apply CSS rules only when a specified screen condition is true.
11. **What is CSS float?** Float positions an image or element to the left or right so text can wrap around it.
12. **What is the difference between margin and padding?** Margin creates space outside an element; padding creates space inside it.
13. **What are borders?** Borders are visible lines placed around the edges of an element.
14. **What is Normalize.css?** Normalize.css makes default browser styles more consistent.
15. **What is the difference between HTML and CSS?** HTML defines content and structure; CSS controls appearance and layout.
16. **What is a CSS-only carousel?** It is an image slider controlled by CSS and HTML inputs instead of JavaScript.
17. **How does the carousel work without JavaScript?** Radio buttons store the selected slide, and CSS selectors move the slide container.
18. **How is an audio file added in HTML?** The `<audio>` element with a `<source>` element loads and plays the MP3.
19. **How is a PDF downloaded using HTML?** An anchor uses the `download` attribute and links to the PDF file.
20. **What is the purpose of the images folder?** It stores all photographs used by the HTML pages.
21. **Why do we use separate CSS files?** Separate files organize styles and keep the homepage and content pages maintainable.
22. **What is the purpose of the figure element?** It groups self-contained visual content such as an image.
23. **What is the purpose of figcaption?** It provides a descriptive caption for a figure.
24. **What are HTML entities?** They are special character codes such as `&amp;`, `&copy;` and `&uarr;`.
25. **How does navigation work between HTML pages?** Normal `<a href="">` links open other pages or page sections.

## Important Code Parts

- `index.html` uses a Bootstrap `row` with `col-lg-3`, `col-lg-6` and `col-lg-3` to create the three-column layout.
- `destinations.html` and `culture.html` use `col-lg-3` and `col-lg-9` for two-column layouts.
- `.float-image` in `main.css` demonstrates CSS text wrapping.
- `.css-carousel` uses hidden radio buttons and the `:checked` selector to display one of five slides.
- The audio player uses browser-native controls and a local MP3 file.
- The PDF download link uses the HTML `download` attribute.
