# Creating an Image Gallery with Lightbox
## Introduction

In this project, we will create a beautiful and functional image gallery using Lightbox. Lightbox is a simple, customizable image viewer that overlays images on the current page, allowing users to browse through a gallery with ease. This guide will walk you through the steps to integrate Lightbox into your HTML page, ensuring your gallery is both visually appealing and user-friendly.

## Steps:

1. Include Lightbox CSS and JS Files
    + In the `<head>` section of your HTML file, include the Lightbox CSS file.
    + Just before the closing `</body>` tag, include the Lightbox JavaScript file.

2. HTML Structure for the Gallery
    + Create a `<div>` container with a class for your gallery.
    + Inside this container, add `<a>` tags for each image. Use the `data-lightbox` attribute to group the images and `data-title` to add titles.

3. CSS Styles for the Gallery
    + Use Flexbox to align the images and add spacing between them.
    + Ensure that the images are properly sized and centered.

4. Image Paths
    + Use reliable image URLs for testing, such as `https://picsum.photos`.

5. Debugging
    + Open the browser console (`F12` or `Ctrl+Shift+I`) to check for errors.
    + Clear the browser cache (`Ctrl+F5`) to ensure that changes are correctly applied.

#### Additional Notes:

+ **Using Lightbox with jQuery:** Use `lightbox-plus-jquery.min.js` to include jQuery and Lightbox together, which can help avoid conflicts.
+ **Relative/Absolute Paths:** If you are using your own local images, ensure that the paths are correct relative to your file structure.

By following these steps, you should be able to create a functional and visually appealing image gallery using Lightbox. For more information about Lightbox, you can refer to the official documentation.

## Usage

1. Clone the repository or download the files.

    + SSH

        ```bash
        git clone git@github.com:Shinzoku/Image-gallery.git
        ```

    + HTTPS

        ```bash
        git clone https://github.com/Shinzoku/Image-gallery.git
        ```

2. Open index.html in a web browser.


## Author

- **Nicolas Bernon**

## License

this project is under [MIT license](https://choosealicense.com/licenses/mit/)

