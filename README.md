# 🚄 Railway Reservation Booking App Frontend

A modern, responsive railway ticket booking application built with HTML and CSS. This project demonstrates a complete frontend design system for a railway reservation platform similar to IRCTC or Ixigo.

## ✨ Features

### 🎨 Modern Design System
- **Clean, professional UI** with modern design principles
- **Responsive design** that works on all devices (mobile, tablet, desktop)
- **Consistent color palette** and typography throughout
- **Smooth animations** and hover effects
- **Accessibility features** with proper focus states

### 🚂 Core Functionality
- **Homepage** with train search form
- **Search Results** page showing available trains
- **PNR Status** checker with detailed booking information
- **Responsive navigation** with sticky header
- **Interactive forms** with validation

### 🎯 Design Components
- **Navigation Bar**: Sticky top navigation with logo and menu
- **Search Forms**: Clean input fields with icons and validation
- **Train Cards**: Detailed train information with pricing and availability
- **Status Badges**: Color-coded status indicators (Confirmed, Waitlist, Cancelled)
- **Buttons**: Primary and secondary button styles with hover effects
- **Cards**: Consistent card layouts with shadows and rounded corners

## 🎨 Design System

### Color Palette
- **Primary**: `#1E88E5` (Blue) - Main brand color
- **Secondary**: `#43A047` (Green) - Success states
- **Background**: `#F5F7FA` (Light gray) - Page backgrounds
- **Text Primary**: `#212121` (Dark gray) - Main text
- **Text Secondary**: `#757575` (Medium gray) - Secondary text
- **Error**: `#E53935` (Red) - Error states

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Headings**: Bold weights (600, 700)
- **Body Text**: Regular weight (400)
- **Font Sizes**: 
  - H1: 28px, H2: 22px, H3: 18px
  - Body: 16px, Small: 14px

### Layout Principles
- **Container**: Max-width 1200px with centered content
- **Grid System**: CSS Grid and Flexbox for responsive layouts
- **Spacing**: Consistent 8px grid system
- **Shadows**: Subtle shadows for depth and hierarchy
- **Border Radius**: 12px for cards, 8px for buttons

## 📁 Project Structure

```
RRBA/
├── index.html          # Homepage with train search
├── results.html        # Train search results page
├── pnr.html           # PNR status checker
├── style.css          # Complete CSS design system
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Navigate between pages using the navigation menu

### Usage

#### Homepage (`index.html`)
- **Train Search Form**: Enter source, destination, date, and class
- **Features Section**: Highlights of the platform
- **Responsive Design**: Works on all screen sizes

#### Search Results (`results.html`)
- **Train Listings**: Detailed train cards with pricing
- **Filters**: Sort by departure time, arrival time, duration, or price
- **Booking Actions**: View details or book directly
- **Pagination**: Navigate through multiple result pages

#### PNR Status (`pnr.html`)
- **PNR Search**: Enter 10-digit PNR number
- **Status Display**: Shows confirmed, waitlist, or cancelled status
- **Journey Details**: Complete booking information
- **Demo PNRs**: Sample numbers for testing

## 🎯 Key Features Demonstrated

### 1. Responsive Design
- **Mobile First**: Optimized for mobile devices
- **Breakpoints**: 768px (tablet) and 480px (mobile)
- **Flexible Layouts**: Grid and flexbox for adaptive designs

### 2. Form Design
- **Input Styling**: Rounded corners with focus states
- **Icon Integration**: Font Awesome icons for visual appeal
- **Validation**: HTML5 form validation with custom styling
- **Accessibility**: Proper labels and focus indicators

### 3. Component System
- **Reusable Classes**: Consistent button, card, and form styles
- **State Management**: Hover, focus, and active states
- **Animation**: Smooth transitions and hover effects
- **Consistency**: Unified design language across all pages

### 4. User Experience
- **Clear Navigation**: Intuitive menu structure
- **Visual Hierarchy**: Proper use of typography and spacing
- **Interactive Elements**: Hover effects and button states
- **Loading States**: Placeholder for future functionality

## 🔧 Customization

### Colors
Update the CSS custom properties in `style.css`:
```css
:root {
    --primary-color: #1E88E5;
    --secondary-color: #43A047;
    --background-color: #F5F7FA;
    --text-primary: #212121;
    --text-secondary: #757575;
}
```

### Typography
Change the font family in the CSS:
```css
body {
    font-family: 'Your-Font', sans-serif;
}
```

### Layout
Modify container widths and spacing:
```css
.container {
    max-width: 1400px; /* Increase for wider layouts */
    padding: 0 30px;   /* Adjust padding */
}
```

## 📱 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile Browsers**: iOS Safari, Chrome Mobile

## 🚀 Future Enhancements

### Planned Features
- **Booking Flow**: Complete passenger details and payment forms
- **User Authentication**: Login and registration systems
- **Real-time Updates**: Live train status and delays
- **Advanced Search**: Filters for train types, amenities, etc.
- **Dark Mode**: Toggle between light and dark themes

### Technical Improvements
- **JavaScript Framework**: React or Vue.js integration
- **State Management**: Redux or Vuex for complex state
- **API Integration**: Backend connectivity for real data
- **Progressive Web App**: Offline functionality and app-like experience

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different devices and browsers
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or support:
- **Email**: support@railbook.com
- **Phone**: +91 1800-111-139
- **Documentation**: Check this README for usage instructions

---

**Built with ❤️ for modern web development and railway enthusiasts**

*This is a frontend demonstration project. For production use, additional backend services, security measures, and real-time data integration would be required.*
