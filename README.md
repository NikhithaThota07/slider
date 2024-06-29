# slider

# Responsive Horizontal Scrolling Product Gallery

This code creates a responsive horizontal scrolling product gallery with the following features:

Clean and organized design: The code utilizes HTML for structure, CSS for styling, and JavaScript for interactivity, maintaining separation of concerns.
Smooth scrolling: The product container uses smooth scrolling behavior for a visually appealing user experience.
Flexible product cards: Each product card is designed with a discount tag, image, brand name, description, price, and an "add to wishlist" button. You can easily customize these elements to fit your needs.
Responsive navigation: The "next" and "previous" buttons allow users to navigate through the products easily on various screen sizes.

# How to use:

Replace the placeholder image paths in the HTML code with your actual product images (src="images/card1.jpg").
Update the product information (brand name, description, price) for each card.
You can further customize the styling using the provided CSS classes.
Save the HTML, CSS, and JavaScript files together in a directory.
Open the HTML file in a web browser to view the product gallery.

# HTML:

Defines the basic structure of the webpage.
Includes sections for the product category, product container, and potentially other content (not shown).
Each product card has an image, discount tag, brand name, description, price, and an "add to wishlist" button.

# CSS:

Styles the various elements of the webpage including:
Product container to enable horizontal scrolling with smooth behavior (scroll-behavior: smooth).
Product cards to have a specific width and margin.
Discount tag, product information, button styles, etc.

# JavaScript:

Uses DOM manipulation to target all elements with the class product-container.
Loops through each container and retrieves its width using getBoundingClientRect().
Attaches click events to the "next" and "previous" buttons for each container.
When the "next" button is clicked, it scrolls the container by its width to the right using scrollLeft += containerWidth.
Similarly, clicking the "previous" button scrolls the container by its width to the left using scrollLeft -= containerWidth.
