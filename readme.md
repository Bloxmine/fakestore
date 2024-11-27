# FakeStore
![Header](header.jpg)
This project document represents a simple e-commerce webpage with a sale theme. 
It includes the following sections:

1. Head Section:
    - Sets the document type and language.
    - Defines meta tags for character set and viewport settings.
    - Includes a title for the webpage.
    - Contains internal CSS styles for various elements such as body, headings, product grid, images, and footer.
    - Defines a custom font using @font-face.

2. Body Section:
    - Displays a main heading indicating a sale.
    - Contains a marquee element with a promotional message.
    - Includes a div with id "products" where product information will be dynamically inserted.
    - Contains a footer with a copyright notice.

3. Script Section:
    - Fetches product data from an external API (https://fakestoreapi.com/products).
    - Dynamically creates and inserts product elements into the "products" div.
    - Each product element includes an image, title, description, and price.

CSS Styles:
    - Defines a primary color variable.
    - Sets global styles for body, headings, and product grid.
    - Styles individual product divs with background color, padding, border radius, and box shadow.
    - Adds hover effects to product divs and images.
    - Includes a custom font for the body text.
    - Contains commented-out media queries for responsive design (not used).

## Instructions to run:

1. Clone the repository
2. Load index.html in your live server of choice
3. Make sure you are connected to the internet for it to fetch the API data.