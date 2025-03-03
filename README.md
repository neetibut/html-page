# HTML Styling Techniques Demonstration

This project demonstrates two different approaches to styling HTML documents:

- **Main Branch: Vanilla CSS**

  - This branch showcases the use of traditional CSS within HTML files.
  - It serves as a baseline example for understanding core CSS concepts.
  - You'll find embedded `<style>` tags or linked `.css` files used to style the HTML elements.

- **Develop Branch: Tailwind CSS (CDN)**
  - This branch explores the use of Tailwind CSS, a utility-first CSS framework, implemented via CDN.
  - It demonstrates how to rapidly style HTML elements using Tailwind's pre-defined utility classes.
  - This branch uses the CDN link to include tailwind, and therefore requires an internet connection to view the styles.
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

3.  **View the Develop Branch (Tailwind CSS - CDN):**
    ```bash
    git checkout develop
    ```
    - Open the `index.html` (or any other HTML file) in your web browser.
    - Ensure you have an active internet connection.

## Purpose

This project is intended for educational purposes, providing a simple comparison between traditional CSS and a utility-first CSS framework like Tailwind CSS. It allows you to observe the differences in syntax and workflow between the two approaches.

## Considerations

- The Tailwind CSS implementation in the `develop` branch uses a CDN for simplicity. For production environments, it's recommended to install Tailwind CSS as a dependency and configure it appropriately.
- The Main branch provides a very basic example of css. More complex projects will typically utilize more complex css structures, and potentially preprocessors such as SASS or LESS.
