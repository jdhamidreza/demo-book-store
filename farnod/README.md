# فرنود بوک (Farnod Book) - Persian Online Book Store

A modern, responsive Persian online book store website featuring both physical and audiobooks. This project demonstrates a complete e-commerce book store with Persian language support and RTL (Right-to-Left) layout.

## 📚 Project Overview

فرنود بوک is a Persian online book store that offers a comprehensive collection of books including:
- **Physical Books** - Traditional printed books
- **Audiobooks** - Audio versions of books for listening
- **E-books** - Digital versions for reading on devices

The website features a modern, responsive design with Persian language support and RTL layout, making it accessible to Persian-speaking users.

## ✨ Features

### 🏠 Homepage
- **Hero Section** - Eye-catching banner with call-to-action
- **Category Navigation** - Easy browsing by book categories (Novels, Business, Psychology, Educational, Crime)
- **Children's Books Slider** - Interactive carousel showcasing children's books
- **Hot Audiobooks** - Featured audio books section
- **Promotional Banners** - Marketing banners for special offers

### 🔍 Search & Discovery
- **Real-time Search** - Search books by title, author, publisher, or category
- **Category Filtering** - Browse books by specific categories
- **Book Details** - Comprehensive book information including ratings, reviews, and pricing

### 📱 Responsive Design
- **Mobile-First** - Optimized for mobile devices
- **Tablet Support** - Responsive layout for tablet screens
- **Desktop Experience** - Full-featured desktop interface
- **RTL Support** - Proper right-to-left layout for Persian text

### 🛒 Shopping Features
- **Shopping Cart** - Add books to cart with quantity management
- **Book Categories** - Organized by genre and type
- **Book Ratings** - Star-based rating system
- **Price Display** - Clear pricing with discount indicators

## 🛠️ Technical Stack

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icon library for UI elements

### Styling & Design
- **Custom Persian Font** - Tanha font family for proper Persian text rendering
- **CSS Variables** - Consistent color scheme and theming
- **Responsive Breakpoints** - Mobile, tablet, and desktop layouts
- **RTL Layout** - Right-to-left text direction support

### Assets
- **Images** - High-quality book covers and promotional banners
- **Fonts** - Custom Persian fonts with multiple formats (WOFF, TTF, EOT)
- **Icons** - Font Awesome icons for UI elements

## 📁 Project Structure

```
book demo/
├── assets/
│   ├── font/                    # Persian fonts (Tanha family)
│   │   ├── Tanha.eot
│   │   ├── Tanha.ttf
│   │   ├── Tanha.woff
│   │   └── Tanha.woff2
│   └── images/                  # Website images
│       ├── logo.png
│       ├── hero-1.jpg
│       ├── banner-1.jpg
│       ├── banner-2.jpeg
│       ├── about-avatar.jpg
│       └── contact.jpg
├── js/
│   ├── app.js                   # Main application logic
│   ├── category.js              # Category page functionality
│   ├── details.js               # Book details page
│   └── search.js                # Search functionality
├── pages/
│   ├── home.html                # Homepage
│   ├── about.html               # About us page
│   ├── contact.html             # Contact page
│   ├── category.html            # Category listing page
│   ├── details.html             # Book details page
│   └── search.html              # Search results page
└── styles/
    ├── home.css                 # Homepage styles
    ├── about.css                # About page styles
    ├── contact.css              # Contact page styles
    ├── details.css              # Book details styles
    ├── category.css             # Category page styles
    └── seach.css                # Search page styles
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the project files
2. Open `book demo/pages/home.html` in your web browser
3. The website will load with all functionality available

### Local Development
1. Navigate to the project directory
2. Start a local web server (optional):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```
3. Open `http://localhost:8000/book demo/pages/home.html` in your browser

## 📖 Usage

### Navigation
- **Home** - Browse featured books and categories
- **About** - Learn about فرنود بوک
- **Contact** - Get in touch with support
- **Search** - Find specific books
- **Categories** - Browse by book type

### Shopping
1. Browse books on the homepage or category pages
2. Click on any book to view details
3. Add books to your cart
4. View cart contents and proceed to checkout

### Search
1. Use the search bar in the header
2. Search by book title, author, publisher, or category
3. View search results on the dedicated search page

## 🎨 Design Features

### Color Scheme
- **Primary Red**: #b60000 (Brand color)
- **Secondary Red**: #881111 (Accent color)
- **Dark Gray**: #333333 (Text and accents)
- **Light Gray**: #f5f5f5 (Backgrounds)
- **White**: #ffffff (Clean backgrounds)

### Typography
- **Primary Font**: Tanha (Persian-optimized)
- **Fallback**: System fonts for better performance
- **RTL Support**: Proper right-to-left text rendering

### Layout
- **Grid System**: CSS Grid for book listings
- **Flexbox**: Flexible layouts for components
- **Responsive**: Mobile-first design approach
- **RTL Layout**: Proper Persian text direction

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🌟 Key Features in Detail

### Book Data Management
- Comprehensive book database with 50+ sample books
- Support for both physical and audiobook formats
- Detailed book information including:
  - Title, author, publisher
  - Categories and tags
  - Ratings and reviews
  - Pricing and discounts
  - Book covers and descriptions

### Interactive Components
- **Book Sliders**: Smooth carousel for featured books
- **Shopping Cart**: Real-time cart updates
- **Search**: Instant search with filtering
- **Mobile Menu**: Collapsible navigation for mobile
- **Rating System**: Visual star ratings for books

### Persian Language Support
- **RTL Layout**: Proper right-to-left text direction
- **Persian Fonts**: Custom Tanha font family
- **Persian Content**: All text content in Persian
- **Cultural Adaptation**: Persian book categories and content

## 🔧 Customization

### Adding New Books
1. Edit `js/app.js`
2. Add new book objects to the `books` array
3. Include all required fields: id, title, author, image, etc.

### Styling Changes
1. Modify CSS files in the `styles/` directory
2. Update CSS variables in `:root` for global changes
3. Adjust responsive breakpoints as needed

### Adding New Pages
1. Create new HTML files in `pages/` directory
2. Include the standard header and footer structure
3. Add corresponding CSS files in `styles/` directory
4. Update navigation links in all pages

## 📄 License

This project is created for educational and demonstration purposes. All book data and images are used for showcase purposes only.

## 🤝 Contributing

This is a demo project, but suggestions and improvements are welcome:
1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Contact

For questions about this project:
- **Email**: info@farnodbook.com
- **Phone**: ۰۲۱-۱۲۳۴۵۶۷۸
- **Location**: تهران، ایران

---

**فرنود بوک** - Your gateway to the world of Persian literature and knowledge! 📚✨
