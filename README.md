# Berra Lounge Hotel

This project is a simple, static website for a fictional restaurant and hotel called **Berra Lounge Hotel**. It showcases the hotel's key information, services, menu, team, and contact options in a single-page layout. The project uses basic HTML, CSS, and a bit of JavaScript for interactive elements.

---

## Features

- **Navigation Header:**  
  Clickable buttons navigate to different sections of the page using `scrollIntoView()`.

- **Homepage Section:**  
  Welcomes users and displays the physical location and open hours of the hotel.

- **Services Section:**  
  Lists the services offered, such as meals, lounges, room service, breakfast, swimming, event hosting, and mobile catering.

- **Menu Section:**  
  Presents a table of products (burgers and burritos) with images, descriptions, varieties, and prices.

- **About Us Section:**  
  Shares a short history of the hotel and introduces the management team.

- **Contact Section:**  
  Clicking the contact icon reveals a contact form (using JavaScript) where users can enter their name, email, and message.

- **Footer:**  
  Includes social media buttons (Twitter, WhatsApp, Instagram) and a copyright.

---

## Code Highlights

- **HTML:**  
  - Uses semantic headings and sections for clarity.
  - Menu table includes images and product details.
  - JavaScript function (`showForm()`) displays the contact form dynamically.
  - Uses inline CSS for some elements and external CSS for most styling.

- **CSS:**  
  - Custom background image and color scheme (orangered & bisque).
  - Styled navigation buttons, tables, forms, footer, and responsive images.
  - Button hover effects and a styled popup form for contact.
  - Some classes (like `.b`, `.b1`, `.hover`, `.contact-icon`) are used for specific button and image styling.

- **Assets:**  
  - Image paths (e.g., `/images/burger.jpg`) are referenced for menu items and icons.  
    _Make sure these images exist in the `/images` directory for them to display correctly._

---

## How to Use

1. **Clone or Download the Repository.**
2. Ensure the following structure exists:
   ```
   /project-root
     |-- index.html
     |-- my.css
     |-- /images
           |-- burger.jpg
           |-- burrito cheese, mexican.jpg
           |-- dessert.jpg
           |-- dribbble.png
           |-- email.png
           |-- twitter.png
           |-- whatsapp.png
           |-- instagram.png
           ...
   ```
3. Open `index.html` in your browser.

---

## Customization

- Update menu, services, or team details directly in the HTML.
- Change images by replacing files in the `/images` directory.
- Adjust styles in `my.css` as desired.

---

## Note

This website is **for educational/demo purposes only**.  
It is not intended for production use.
