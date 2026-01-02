# Maternal & Baby Healthcare Website

A fully responsive frontend web application for maternal and baby healthcare with a calm, soothing, trust-building design.

## 🎨 Features

### Landing Page
- Hero section with gradient background
- Smooth scroll navigation
- Features showcase
- About section with statistics

### Authentication
- **Login Page**: Secure login with email and password validation
- **Register Page**: User registration with password strength indicator
- Form validation with real-time error messages
- Password show/hide toggle
- Session management using localStorage

### Dashboard (After Login)

#### 1. Patient Details Storage
- Store mother and baby information (name, age, trimester, baby age)
- Editable profile card
- Data persistence using localStorage

#### 2. Healthcare Chatbot
- Floating chatbot icon (bottom-right)
- Predefined FAQs for pregnancy and baby care
- Typing indicator animation
- Keyword-based response matching
- Topics: pregnancy care, baby care, nutrition, exercise, general health

#### 3. Healthcare Monitoring
- **Mother Vitals**: BP, Blood Sugar, Weight, Mood tracking
- **Baby Vitals**: Weight, Height, Mood tracking
- Emoji-based status indicators:
  - 😊 Happy (normal ranges)
  - 😟 Worried (slightly off)
  - 🚨 Alert (critical)
- Color-coded status cards
- Vitals history storage

#### 4. Fitness Tracker
- Week selector (1-40 weeks)
- Animated progress bar
- Baby size comparison using vegetables:
  - Weeks 1-4: Poppy seed, Sesame seed
  - Weeks 5-8: Blueberry, Kidney bean
  - Weeks 9-12: Grape, Lime
  - Weeks 13-16: Lemon, Avocado
  - Weeks 17-20: Sweet potato, Banana
  - Weeks 21-24: Carrot, Corn
  - Weeks 25-28: Eggplant, Zucchini
  - Weeks 29-32: Cabbage, Squash
  - Weeks 33-36: Pineapple, Honeydew
  - Weeks 37-40: Watermelon, Pumpkin

#### 5. Garbhasamskara Section
- Daily positive affirmations (auto-rotating)
- Mantras display
- Breathing exercise with animated circle
- Calm, peaceful UI

#### 6. Pleasant Music Section
- Music player UI with controls
- Play/pause, previous/next track buttons
- Volume control
- Track list
- *Note: Placeholder controls (no actual audio files)*

#### 7. Doctor Consultation
- List of doctors with specialties
- Filter by specialty (Gynecologist, Pediatrician, Nutritionist, Psychologist)
- Availability status badges
- Book appointment button (frontend demo)

#### 8. Nearby Hospitals
- Hospital listings with address and distance
- City-based filter (Mumbai, Delhi, Bangalore, Hyderabad, Chennai)
- Card layout design

#### 9. Baby & Mother Store
- Product categories (Baby Products, Pregnancy Care)
- Product cards with image placeholders
- Add to cart functionality
- Cart count in navigation
- localStorage for cart items

#### 10. Live Community
- Community feed with posts
- Create new posts
- Like functionality with animation
- Comment section (expandable)
- Post storage in localStorage

#### 11. Daily Tips
- Auto-rotating tips carousel
- Pregnancy tips
- Baby care tips
- Smooth fade transitions

## 🎨 Design Features

### Color Theme
- **Primary**: Light Pink (#FFB6C1)
- **Secondary**: Mint Green (#B0E0E6)
- **Accent**: Lavender (#E6E6FA)
- **Background**: Sky Blue (#E0F2F1)
- Soft pastel gradients throughout

### Typography
- Clean sans-serif fonts (Segoe UI, Tahoma, Geneva, Verdana)
- Large, readable text
- Soft headings with proper hierarchy

### Animations
- Fade-in animations
- Pulse effects
- Slide-up transitions
- Hover effects
- Smooth scrolling
- Breathing animation
- Typing indicator

### Responsive Design
- **Mobile-first** approach
- Breakpoints:
  - Mobile: < 768px
  - Tablet: 768px - 1024px
  - Desktop: > 1024px
- Hamburger menu for mobile
- Sticky bottom navigation for mobile
- Touch-friendly button sizes (min 44px)

## 📁 Project Structure

```
maternal-baby-healthcare/
├── index.html          # Landing page
├── login.html          # Login page
├── register.html       # Registration page
├── dashboard.html      # Main dashboard with all sections
├── css/
│   └── style.css       # All styles (responsive, animations, themes)
├── js/
│   ├── auth.js         # Authentication logic & localStorage
│   ├── dashboard.js    # Dashboard functionality & data management
│   └── chatbot.js      # Chatbot logic & FAQs
└── README.md           # This file
```

## 🚀 Getting Started

1. **Open the project**: Simply open `index.html` in a web browser
2. **No build process required**: This is a pure frontend project with no dependencies
3. **No server needed**: All files can be opened directly in the browser

## 💾 Data Storage

All data is stored in the browser's localStorage:

- `users` - Array of registered users
- `currentUser` - Currently logged-in user email
- `patientData_{email}` - Patient details for each user
- `vitalsHistory_{email}` - Health monitoring data
- `cartItems_{email}` - Shopping cart items
- `communityPosts_{email}` - Community posts

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Animations, Variables
- **Vanilla JavaScript**: No frameworks or libraries
- **localStorage**: Client-side data persistence

## 📱 Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## ⚠️ Important Notes

- **Frontend Only**: No backend server required
- **No Real Data**: All data is stored locally in the browser
- **No Real Audio**: Music player is a UI placeholder
- **Demo Purpose**: Doctor appointments and hospital listings are for demonstration only

## 🎯 Key Features Implementation

### Form Validation
- Email format validation
- Password strength checking
- Required field validation
- Real-time error messages

### Animations
- CSS keyframe animations
- Smooth transitions
- Hover effects
- Loading states

### User Experience
- Smooth scrolling
- Toast notifications
- Loading indicators
- Error handling
- Success feedback

## 📝 Code Organization

- **Well-commented code**: All files include descriptive comments
- **Modular JavaScript**: Separate files for different functionalities
- **Reusable CSS classes**: Consistent styling throughout
- **Semantic HTML**: Proper HTML5 elements

## 🔐 Security Notes

- Passwords are stored in plain text in localStorage (for demo purposes only)
- In a production environment, passwords should be hashed
- No actual authentication server is used

## 📄 License

This is a frontend demonstration project. Feel free to use and modify as needed.

---

**Made with 💕 for mothers and babies**

