# TicketHub - Premium Ticket Sales Website

A modern, responsive website for ticket sales built with React, featuring a beautiful UI, smooth animations, and comprehensive e-commerce functionality.

## 🚀 Features

### Core Functionality
- **Event Discovery**: Browse and search through various event categories
- **Advanced Filtering**: Filter by category, city, and search terms
- **Shopping Cart**: Add, remove, and manage ticket quantities
- **Secure Checkout**: Complete payment process with form validation
- **Responsive Design**: Optimized for all devices and screen sizes

### User Experience
- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Real-time Updates**: Live cart updates and inventory management
- **Mobile-First**: Responsive design that works perfectly on mobile devices
- **Smooth Navigation**: Seamless routing between pages with animations

### Technical Features
- **React 18**: Latest React features with hooks and modern patterns
- **Framer Motion**: Smooth animations and transitions throughout
- **Tailwind CSS**: Utility-first CSS framework for rapid development
- **Context API**: Global state management for shopping cart
- **Local Storage**: Persistent cart data across browser sessions

## 🛠️ Tech Stack

- **Frontend**: React 18, React Router DOM
- **Styling**: Tailwind CSS, PostCSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Package Manager**: npm

## 📁 Project Structure

```
ticket-sales-website/
├── public/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx          # Navigation component
│   │   └── Footer.jsx          # Footer component
│   ├── context/
│   │   └── CartContext.jsx     # Shopping cart state management
│   ├── data/
│   │   └── events.js           # Sample event data
│   ├── pages/
│   │   ├── Home.jsx            # Landing page
│   │   ├── Events.jsx          # Events listing page
│   │   ├── EventDetail.jsx     # Individual event page
│   │   ├── Cart.jsx            # Shopping cart page
│   │   └── Checkout.jsx        # Checkout process page
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # App entry point
│   └── index.css               # Global styles
├── package.json                 # Dependencies and scripts
├── vite.config.js              # Vite configuration
├── tailwind.config.js          # Tailwind CSS configuration
├── postcss.config.js           # PostCSS configuration
└── README.md                   # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ticket-sales-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## 🎯 Key Components

### Home Page (`/`)
- Hero section with call-to-action
- Featured events showcase
- Statistics and social proof
- Responsive design with animations

### Events Page (`/events`)
- Grid layout of all events
- Advanced search and filtering
- Pagination for large event lists
- Sort by date, price, or name

### Event Detail Page (`/event/:id`)
- Comprehensive event information
- Image gallery and venue details
- Ticket quantity selector
- Add to cart functionality

### Shopping Cart (`/cart`)
- Cart item management
- Quantity updates
- Price calculations
- Order summary

### Checkout (`/checkout`)
- Multi-step checkout process
- Form validation
- Payment information
- Order confirmation

## 🎨 Design System

### Color Palette
- **Primary**: Blue (#3b82f6) - Main brand color
- **Secondary**: Purple (#a855f7) - Accent color
- **Neutral**: Gray scale for text and backgrounds
- **Success**: Green for positive actions
- **Error**: Red for errors and warnings

### Typography
- **Font Family**: Inter (system font fallback)
- **Headings**: Bold weights for hierarchy
- **Body Text**: Regular weight for readability

### Components
- **Buttons**: Primary, secondary, and ghost variants
- **Cards**: Consistent shadow and border radius
- **Forms**: Clean input fields with validation states
- **Navigation**: Sticky header with mobile menu

## 📱 Responsive Design

The website is built with a mobile-first approach and includes:
- Responsive grid layouts
- Mobile-optimized navigation
- Touch-friendly interactions
- Optimized images for different screen sizes

## 🔧 Customization

### Adding New Events
Edit `src/data/events.js` to add new events:
```javascript
{
  id: 9,
  title: "New Event",
  artist: "Artist Name",
  date: "2024-12-01",
  time: "20:00",
  venue: "Venue Name",
  city: "City Name",
  category: "Category",
  price: 99.99,
  image: "image-url",
  description: "Event description",
  availableTickets: 500,
  tags: ["Tag1", "Tag2"]
}
```

### Styling Customization
- Modify `tailwind.config.js` for theme changes
- Update `src/index.css` for custom component styles
- Use Tailwind utility classes for rapid styling

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### Deploy to Netlify
1. Build the project: `npm run build`
2. Drag the `dist` folder to Netlify
3. Configure build settings if needed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support or questions:
- Create an issue in the repository
- Contact the development team
- Check the documentation

## 🔮 Future Enhancements

- User authentication and accounts
- Real payment processing integration
- Event recommendations
- Social media integration
- Multi-language support
- Advanced analytics
- Admin dashboard for event management

---

Built with ❤️ using modern web technologies
