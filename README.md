# Madjar - Premium E-commerce Website

A modern, responsive e-commerce website built with React, TypeScript, and Tailwind CSS. Madjar offers a complete online shopping experience with product browsing, shopping cart functionality, and a beautiful user interface.

## 🚀 Features

### Core Features
- **Product Catalog**: Browse products by category with filtering and sorting
- **Shopping Cart**: Add, remove, and update quantities with real-time calculations
- **Responsive Design**: Mobile-first design that works on all devices
- **Search Functionality**: Search products by name, description, or tags
- **Product Filtering**: Filter by category, price range, and ratings
- **Modern UI/UX**: Beautiful, intuitive interface with smooth animations

### Product Categories
- Electronics (Smartphones, Laptops, Headphones, etc.)
- Fashion (Clothing, Accessories, Shoes)
- Home & Garden (Kitchen, Tools, Decor)
- Sports & Outdoors (Fitness, Camping, Exercise)
- Books & Media (Books, Movies, Music)

### Technical Features
- **TypeScript**: Full type safety and better development experience
- **React Router**: Client-side routing for smooth navigation
- **Context API**: Global state management for shopping cart
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Lucide React**: Beautiful, customizable icons
- **Responsive Grid**: CSS Grid and Flexbox for perfect layouts

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **Icons**: Lucide React
- **Build Tool**: Create React App
- **Package Manager**: npm

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd madjar
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🏗️ Project Structure

```
madjar/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   ├── Hero.tsx
│   │   ├── ProductCard.tsx
│   │   └── ProductGrid.tsx
│   ├── context/
│   │   └── CartContext.tsx
│   ├── data/
│   │   └── products.ts
│   ├── pages/
│   │   ├── Home.tsx
│   │   ├── Products.tsx
│   │   ├── Cart.tsx
│   │   ├── About.tsx
│   │   └── Contact.tsx
│   ├── types/
│   │   └── index.ts
│   ├── App.tsx
│   ├── index.tsx
│   └── index.css
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## 🎨 Design System

### Colors
- **Primary**: Blue (#3B82F6) - Main brand color
- **Secondary**: Gray (#64748B) - Supporting text and elements
- **Success**: Green (#10B981) - Positive actions and status
- **Warning**: Yellow (#F59E0B) - Cautions and highlights
- **Error**: Red (#EF4444) - Errors and destructive actions

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700
- **Responsive**: Scales from mobile to desktop

### Components
- **Cards**: Rounded corners with subtle shadows
- **Buttons**: Primary and secondary variants with hover states
- **Forms**: Clean inputs with focus states
- **Navigation**: Sticky header with mobile menu

## 📱 Pages

### Home Page (`/`)
- Hero section with call-to-action
- Featured products showcase
- Category highlights
- Customer testimonials
- Newsletter signup

### Products Page (`/products`)
- Product grid with filtering
- Category selection
- Price range slider
- Sorting options (name, price, rating, reviews)
- Search functionality

### Cart Page (`/cart`)
- Shopping cart items
- Quantity controls
- Price calculations (subtotal, tax, shipping)
- Order summary
- Checkout button

### About Page (`/about`)
- Company mission and values
- Team information
- Company statistics
- Story and history

### Contact Page (`/contact`)
- Contact form
- Company information
- FAQ section
- Office location

## 🔧 Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run eject` - Ejects from Create React App (not recommended)

## 🌟 Key Features Explained

### Shopping Cart System
The cart uses React Context API for global state management:
- Add/remove products
- Update quantities
- Real-time total calculation
- Persistent cart state (can be extended with localStorage)

### Product Filtering
Advanced filtering system with:
- Category filtering
- Price range selection
- Search by name/description/tags
- Multiple sorting options
- URL parameter synchronization

### Responsive Design
Mobile-first approach with:
- Responsive grid layouts
- Mobile navigation menu
- Touch-friendly interactions
- Optimized images and content

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `build`
4. Deploy!

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [Lucide React](https://lucide.dev/) - Beautiful & consistent icon toolkit
- [Unsplash](https://unsplash.com/) - High-quality stock photos for product images

## 📞 Support

For support, email support@madjar.com or create an issue in this repository.

---

**Madjar** - Your trusted destination for quality products. 🛍️ 