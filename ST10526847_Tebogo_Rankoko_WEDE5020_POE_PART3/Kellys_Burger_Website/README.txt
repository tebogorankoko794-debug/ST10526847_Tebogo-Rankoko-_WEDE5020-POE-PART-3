KELLY'S BURGER - PART 2 CSS UPDATE
===================================

WHAT WAS UPDATED
- Expanded the Products page with four menu categories: Burgers, Drinks, Food and Ice Cream.
- Added six editable product cards to each category. Copy a product-card to add more.
- Expanded the Burgers and Drinks pages with eight editable cards each.
- Added a creative responsive footer to all pages.
- Expanded the About Us biography/story section.
- Kept the brown, cream and gold colour palette from the previous design.
- No supplied logos or food pictures are included.

HOW TO ADD A PRODUCT IMAGE
1. Create an images folder inside Kellys_Burger_Website.
2. Put your JPG, PNG or WEBP image in that folder.
3. Inside a product-card, replace the placeholder div with:

<div class="product-image">
    <img src="images/your-image.jpg" alt="Your Product Name">
</div>

HOW TO ADD YOUR LOGO
Replace the content inside .logo-area or .star-circle with:
<img src="images/logo.png" alt="Kelly's Burger logo">

HOW TO ADD MORE PRODUCTS
Copy any complete <article class="product-card">...</article> block and paste it into the relevant .product-grid. Then edit the name, description, price and image.

HOW TO CHANGE COLOURS
Open css/style.css and edit the values under :root. The main colours are --primary, --primary-dark, --accent, --cream and --dark.

NOTE
The website remains a beginner-friendly HTML/CSS/JavaScript project. The CSS is external and can be edited independently.
