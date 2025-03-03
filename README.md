# HTML Styling Techniques Demonstration - Mobile-First Responsive Webpage

This project demonstrates two different approaches to styling HTML documents, focusing on creating a mobile-first responsive webpage:

- **Main Branch: Vanilla CSS (Media Queries, Flexbox, Grid)**

  - This branch showcases the use of traditional CSS, including media queries for responsiveness, flexbox for layout, and grid for complex layouts.
  - It serves as a demonstration of core CSS concepts for building responsive designs.
  - You'll find embedded `<style>` tags or linked `.css` files with media queries, flexbox properties, and grid properties used to style the HTML elements.
  - This branch prioritizes a mobile-first approach, designing for small screens first and then enhancing the layout for larger screens.

- **Develop Branch: Tailwind CSS (CDN - Flexbox, Grid)**
  - This branch explores the use of Tailwind CSS, a utility-first CSS framework, implemented via CDN.
  - It demonstrates how to rapidly create a responsive layout using Tailwind's pre-defined utility classes for flexbox and grid.
  - This branch uses the CDN link to include tailwind, and therefore requires an internet connection to view the styles.
  - This branch also prioritizes a mobile-first approach, using tailwind's responsive prefixes.
  - This is a quick and easy way to demonstrate tailwind, but for production, a local installation is recommended.

## How to View

1.  **Clone the Repository:**

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **View the Main Branch (Vanilla CSS):**

    ```bash
    git checkout main
    ```

    - Open the `index.html` (or any other HTML file) in your web browser.
    - Resize your browser window to see how the layout adapts to different screen sizes.

3.  **View the Develop Branch (Tailwind CSS - CDN):**
    ```bash
    git checkout develop
    ```
    - Open the `index.html` (or any other HTML file) in your web browser.
    - Ensure you have an active internet connection.
    - Resize your browser window to see how the layout adapts to different screen sizes.

## Purpose

This project is intended for educational purposes, providing a simple comparison between traditional CSS and a utility-first CSS framework like Tailwind CSS, specifically in the context of building responsive, mobile-first webpages. It allows you to observe the differences in syntax and workflow between the two approaches when implementing flexbox, grid, and media queries (or tailwind's responsive prefixes).

## Considerations

- The Tailwind CSS implementation in the `develop` branch uses a CDN for simplicity. For production environments, it's recommended to install Tailwind CSS as a dependency and configure it appropriately.
- The Main branch provides a basic example of responsive web design. More complex projects will typically utilize more complex css structures, potentially preprocessors such as SASS or LESS, and more complex media queries.
- Both branches demonstrate mobile-first design, meaning the initial styles are designed for smaller screens, and then enhanced for larger ones.
