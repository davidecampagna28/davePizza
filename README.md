# Davide's Pizzeria Website

A modern, responsive restaurant website featuring online ordering, table reservations, and an engaging user experience.

## 🌟 Features

### Home Page
- **Hero Section**: Eye-catching welcome with call-to-action buttons
- **Features Section**: Highlights wood-fired oven, fresh ingredients, and family recipes
- **Menu Display**: Showcases pizzas, beverages, and desserts with images
- **Customer Reviews**: Authentic testimonials with star ratings
- **Contact Section**: 
  - Google Maps integration
  - Opening hours
  - Contact form
  - Social media links
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop

### Online Ordering
- **Interactive Menu**: Browse pizzas, drinks, and desserts
- **Shopping Cart**: Real-time cart with quantity controls
- **Dynamic Pricing**: Automatic subtotal and delivery fee calculation
- **Delivery Address**: Smart delivery fee based on location
- **Secure Checkout**: Professional checkout modal with order summary

### Table Reservations
- **Booking Form**: Easy-to-use reservation interface
- **Table Layout Map**: Visual representation of available tables
- **Date/Time Selection**: Calendar and time picker
- **Guest Management**: Support for 1-8 guests
- **Special Requests**: Optional notes field
- **Confirmation System**: Modal confirmation with booking details

## 🎨 Design

### Color Palette
- **Warm Red** (#C41E3A): Primary brand color
- **Cream** (#FFF8E7): Background and accents
- **Wood Brown** (#8B6F47): Secondary elements
- **Gold** (#D4AF37): Highlights and accents

### Typography
- **Headings**: Dancing Script (elegant, cursive)
- **Body**: Poppins (clean, modern sans-serif)
- **Icons**: Font Awesome 6

### Technologies
- **Tailwind CSS**: Utility-first CSS framework
- **Vanilla JavaScript**: No jQuery dependencies
- **Google Fonts**: Web typography
- **Font Awesome**: Icon library
- **Google Maps**: Location integration

## 📱 Responsive Design

The website is fully responsive across all devices:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Mobile Features
- Hamburger menu navigation
- Touch-friendly buttons
- Optimized image sizes
- Sticky cart for orders
- Mobile-first approach

## ⚡ Performance

### Optimizations
- CDN-hosted resources (Tailwind, Font Awesome)
- Inline styles for critical CSS
- Lazy loading images
- Smooth scroll animations
- Efficient JavaScript

### Accessibility
- Semantic HTML5 elements
- ARIA labels where appropriate
- Keyboard navigation support
- Color contrast compliance
- Screen reader friendly

## 🚀 Getting Started

1. **Open in Browser**
   - Simply open `index.html` in any modern web browser
   - No build process or dependencies required

2. **Development**
   - All files are static HTML/CSS/JS
   - Edit directly with any code editor
   - Test locally before deployment

3. **Deployment**
   - Upload all files to web hosting
   - Ensure HTTPS for Google Maps integration
   - Configure domain and DNS as needed

## 📂 File Structure

```
/
├── index.html          # Home page
├── ordina.html         # Online ordering page
├── prenota.html        # Reservation page
├── images/             # Image assets
│   ├── hero-pizza.jpg
│   ├── pizza-margherita.jpg
│   ├── pizza-capricciosa.jpg
│   └── ...
├── style.css           # Legacy styles (not used)
├── README.md           # This file
└── ...
```

## 🔧 Customization

### Update Menu Items
Edit the `menuData` object in each HTML file:
```javascript
const menuData = {
  pizze: [
    { nome: "Pizza Name", ingredienti: "Ingredients", prezzo: 12.99, id: "unique-id" }
  ],
  // ...
};
```

### Change Colors
Update CSS variables in the `<style>` section:
```css
:root {
  --warm-red: #C41E3A;
  --cream: #FFF8E7;
  --wood-brown: #8B6F47;
  --gold: #D4AF37;
}
```

### Update Contact Information
Search and replace:
- Restaurant name: "Davide's"
- Phone: "(555) 123-4567"
- Address: "123 Main Street, City Center"
- Email: "info@davidespizza.com"

## 🌍 Google Maps Integration

The Google Maps embed on the contact section requires your actual location coordinates. Update the `src` attribute in the iframe:

```html
<iframe src="https://www.google.com/maps/embed?pb=YOUR_LOCATION"></iframe>
```

Get your embed code from [Google Maps](https://www.google.com/maps).

## 📝 Notes

- All text is in English for international audiences
- Prices are displayed in USD (can be easily changed)
- Delivery fee calculation is simulated
- Reservation system uses mock data
- Forms are client-side only (no backend integration)

## 🔐 Security Considerations

For production deployment:
- Add backend validation for forms
- Implement proper payment processing
- Add CSRF protection
- Secure API endpoints
- Add rate limiting

## 📄 License

This project is created for demonstration purposes. All images and content are examples and should be replaced with actual restaurant content.

## 👨‍💻 Development

Built with modern web standards and best practices:
- Clean, semantic HTML
- Mobile-first responsive design
- Progressive enhancement
- Accessibility-first approach
- Performance optimization

## 🎯 Future Enhancements

Potential additions:
- Backend integration for real orders
- Payment gateway integration
- Email notifications
- Loyalty program
- Menu filters (vegetarian, gluten-free, etc.)
- Customer account system
- Order tracking
- Multi-language support
