# ShopHub - Modern Ecommerce Frontend

A modern, responsive ecommerce frontend built with React, featuring a beautiful UI and comprehensive shopping functionality.

## Features

- 🏠 **Modern Homepage** with hero section, features, and testimonials
- 🛍️ **Product Catalog** with search, filtering, and sorting
- 🔍 **Product Details** with image gallery and reviews
- 🛒 **Shopping Cart** with quantity management
- 💳 **Checkout Process** with form validation
- 📱 **Responsive Design** that works on all devices
- 🎨 **Beautiful UI** with Tailwind CSS styling
- ⚡ **Fast Performance** with React optimization

## Tech Stack

- **React 18** - Modern React with hooks
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icons
- **Context API** - State management for cart

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open your browser and visit `http://localhost:3000`

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Header.js       # Navigation header
│   ├── Footer.js       # Site footer
│   └── ProductCard.js  # Product display card
├── pages/              # Page components
│   ├── Home.js         # Homepage
│   ├── Products.js     # Product listing
│   ├── ProductDetail.js # Product details
│   ├── Cart.js         # Shopping cart
│   └── Checkout.js     # Checkout process
├── context/            # React Context providers
│   └── CartContext.js  # Shopping cart state
├── data/               # Mock data
│   └── products.js     # Sample products
└── App.js              # Main app component
```

## Features Overview

### Homepage
- Hero section with call-to-action
- Feature highlights (shipping, security, support)
- Featured products showcase
- Customer testimonials

### Product Catalog
- Grid and list view options
- Category filtering
- Search functionality
- Sort by price, rating, or name
- Responsive design

### Product Details
- Image gallery with thumbnails
- Product information and reviews
- Quantity selector
- Add to cart functionality
- Related products

### Shopping Cart
- View all cart items
- Update quantities
- Remove items
- Order summary with tax calculation
- Proceed to checkout

### Checkout
- Contact information form
- Shipping address form
- Payment information form
- Order summary
- Form validation

## Customization

### Adding New Products
Edit `src/data/products.js` to add or modify products:

```javascript
{
  id: 9,
  name: "Your Product Name",
  price: 99.99,
  image: "https://your-image-url.com/image.jpg",
  category: "Your Category",
  description: "Product description",
  rating: 4.5,
  reviews: 100,
  inStock: true
}
```

### Styling
The app uses Tailwind CSS. You can customize the design by:
- Modifying `tailwind.config.js` for theme customization
- Editing component classes for specific styling
- Adding custom CSS in `src/index.css`

### Adding New Pages
1. Create a new component in `src/pages/`
2. Add the route in `src/App.js`
3. Update navigation in `src/components/Header.js`

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the MIT License.
