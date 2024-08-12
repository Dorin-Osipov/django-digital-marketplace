# Digital Marketplace

**Digital Marketplace** is a Django-based web application that allows users to set up accounts, list products for sale, and manage their transactions. The platform offers comprehensive statistics for both sellers and buyers, and it integrates with Stripe for secure payment processing. The application is designed with a clean and modern user interface using Tailwind CSS and Chart.js for data visualization.

## Features

### User Authentication
- **Registration and Login:** Users can register and log in to access their personalized dashboards.
- **Secure Authentication:** User data is securely handled with Django’s built-in authentication system.

### Seller Functionality
- **Product Management:** Sellers can add, edit, and delete products. Only authenticated users can manage their listings.
- **Sales Statistics:** Sellers can view detailed statistics on their sales, including:
  - Total sales per product.
  - Sales statistics for the past year, 30 days, and 7 days.
  - Revenue generated from each product.
- **Revenue Tracking:** Sellers can see how much revenue they have made from their sales over different time periods.

### Buyer Functionality
- **Product Browsing:** Buyers can browse and purchase products listed by sellers.
- **Purchase History:** Buyers can view their purchase history, including:
  - Detailed statistics of their purchases.
  - Total money spent on each product.
  - Purchase statistics for the past year, 30 days, and 7 days.
- **Secure Payments:** Buyers can complete their purchases using Stripe, ensuring a secure transaction process.

### Additional Features
- **Tailwind CSS:** The frontend is styled using Tailwind CSS, providing a responsive and modern design.
- **Chart.js Integration:** The application uses Chart.js for interactive and visually appealing data charts.
- **JavaScript Enhancements:** JavaScript is used for added interactivity and dynamic content loading on the frontend.

## Technologies Used

- **Django:** The primary web framework used for building the application.
- **Stripe API:** Integrated for handling payments and transactions securely.
- **Tailwind CSS:** For styling and responsive design.
- **Chart.js:** For rendering charts and graphs to visualize sales and purchase statistics.
- **JavaScript:** Used for frontend interactivity and dynamic content.
