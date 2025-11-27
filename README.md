# 🛍️ NepasysShop - Product Listing Application

**Internship Assignment Submission for Nepasys**  
**Developer:** Nikhil Oli  
**GitHub:** [github.com/nikhiloli](https://github.com/nikhiloli)  
**Portfolio:** [nikhiloli.tech](https://nikhiloli.tech)

---

## 🎯 Project Overview

A modern, fully-featured product listing web application built with **Next.js 14**, **TypeScript**, and **Tailwind CSS**. This application demonstrates clean code architecture, smooth UX, and all requested features plus bonus enhancements.

### ✅ Required Features (All Implemented)
- ✓ Homepage with product list (Fake Store API)
- ✓ Search bar to filter products by name
- ✓ Category filter dropdown
- ✓ Infinite scroll for loading more products
- ✓ Fully responsive design

### 🎁 Bonus Features (All Implemented)
- ✓ Dark/Light theme toggle
- ✓ Sort by price (low to high, high to low) and rating
- ✓ Add to cart functionality with cart count
- ✓ Smooth loading states and animations
- ✓ Professional UI with hover effects

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18.x or higher
- npm or yarn package manager

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/nikhiloli/product-listing-nepasys.git
cd product-listing-nepasys
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Run the development server**
```bash
npm run dev
# or
yarn dev
```

4. **Open in browser**
Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production
```bash
npm run build
npm start
```

---

## 🛠️ Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **API:** Fake Store API (https://fakestoreapi.com)
- **Deployment:** Vercel

---

## 📁 Project Structure

```
product-listing-nepasys/
├── app/
│   ├── page.tsx              # Main product listing page
│   ├── layout.tsx            # Root layout
│   └── globals.css           # Global styles
├── components/
│   └── ProductList.tsx       # Product listing component
├── public/                   # Static assets
├── package.json
├── tsconfig.json
├── tailwind.config.ts
├── next.config.js
└── README.md
```

---

## 🎨 Features in Detail

### 1. Product Listing
- Fetches products from Fake Store API
- Clean card-based layout
- Product images, titles, descriptions, prices, and ratings
- Smooth fade-in animations on load

### 2. Search Functionality
- Real-time search as you type
- Filters products by title
- Case-insensitive matching

### 3. Category Filter
- Dynamic category dropdown
- Extracted from API data
- "All Categories" option to reset

### 4. Infinite Scroll
- Loads 6 products initially
- Automatically loads more as you scroll
- Smooth loading indicator
- Uses Intersection Observer API

### 5. Sorting Options
- Default order
- Price: Low to High
- Price: High to Low
- By Rating (highest first)

### 6. Dark/Light Theme
- Toggle button in header
- Smooth color transitions
- Persists throughout the app
- Professional color schemes

### 7. Add to Cart
- Click to add/remove from cart
- Visual feedback (button changes color)
- Cart count badge in header
- Maintains cart state

### 8. Responsive Design
- Mobile-first approach
- Breakpoints: mobile, tablet, desktop
- 1 column (mobile) → 2 columns (tablet) → 3 columns (desktop)
- Touch-friendly interactions

---

## 🎯 Key Technical Decisions

1. **Next.js 14 with App Router**: Modern React framework with excellent performance
2. **TypeScript**: Type safety and better developer experience
3. **Tailwind CSS**: Rapid styling with utility classes, consistent design
4. **Intersection Observer**: Efficient infinite scroll implementation
5. **Component-based Architecture**: Clean, maintainable, reusable code
6. **Optimistic UI Updates**: Immediate feedback for better UX

---

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🧪 Testing the Application

1. **Search**: Type "shirt" in search bar → Should filter products
2. **Category**: Select "electronics" → Should show only electronics
3. **Sort**: Choose "Price: Low to High" → Products reorder by price
4. **Infinite Scroll**: Scroll to bottom → More products load automatically
5. **Theme Toggle**: Click sun/moon icon → Theme switches
6. **Add to Cart**: Click "Add to Cart" → Button turns green, cart count increases
7. **Responsive**: Resize browser → Layout adapts smoothly

---

## 🚀 Deployment

This project is configured for easy deployment on **Vercel**:

1. Push code to GitHub
2. Import repository on Vercel
3. Deploy (zero configuration needed)

**Live Demo:** https://nepasys-project.vercel.app

---

## 💡 Performance Optimizations

- Lazy loading of images
- Efficient state management
- Debounced search (minimal re-renders)
- Virtualized infinite scroll
- Optimized animations with CSS transforms

---

## 👨‍💻 About the Developer

**Nikhil Oli** - Full Stack Developer  
Final-year Software Engineering student with expertise in Next.js, React, Node.js, and modern web technologies.

- 📧 Email: [Your email from CV]
- 🔗 LinkedIn: [Your LinkedIn]
- 🌐 Portfolio: [nikhiloli.tech](https://nikhiloli.tech)
- 💻 GitHub: [github.com/nikhiloli](https://github.com/nikhiloli)

---

## 📝 Assignment Requirements Checklist

- [x] Homepage with product list from API
- [x] Search bar to filter products
- [x] Category filter dropdown
- [x] Infinite scroll
- [x] Responsive design
- [x] Dark/light theme toggle (BONUS)
- [x] Sort by price and rating (BONUS)
- [x] Add to cart functionality (BONUS)
- [x] Loading states and animations (BONUS)
- [x] Clean, professional code
- [x] GitHub repository
- [x] README with setup instructions
- [x] Ready for live demo

---

## 🙏 Thank You

**Contact:** +977-9806158371 | nikhiloli@email.com

---

**by Nikhil Oli**