# ResonateAI Frontend Simulator

A vanilla HTML/CSS/JavaScript recreation of the ResonateAI frontend for demonstration, UI reference, and prototyping purposes.

## Features Included

### Pages & Components
- ✅ **Home Page** - Hero section with typing animation, features showcase
- ✅ **Features Section** - 4 core capability cards with hover effects
- ✅ **Pricing Page** - 4 pricing tiers with region-specific pricing
- ✅ **Auth Modal** - Sign In / Sign Up tabs with form validation
- ✅ **Profile/Account Page** - Settings, Billing, Security, Danger Zone tabs
- ✅ **Chat/AI Dashboard** - Message interface with sidebar history (requires login)
- ✅ **Additional Pages** - About, Careers, Press, Blog, etc.
- ✅ **Footer** - Complete footer with links and social media

### Interactive Elements
- 🎨 Smooth page navigation without page reloads
- ⌚ Typing animation in hero section
- 📜 Navbar that adapts on scroll
- 🖱️ Hover effects on cards and buttons
- 💬 Chat interface with message sending
- 🔐 Authentication flow (simulated)
- 📱 Responsive design (works on mobile)

## How to Use

### Opening the Simulator
1. Open `index.html` in your web browser
2. All functionality is contained in this single file - no dependencies needed!

### Navigation
- Click **logo** to go to home
- Use **navbar links** to navigate between sections
- Click **"Get Started"** or **"Sign In"** to trigger auth modal
- Complete the form to simulate login (no real authentication)
- After login, access **Profile page** and **Chat Dashboard**

### Key Interactions
- **Navbar**: Smooth scroll on load, changes on scroll
- **Auth Modal**: Switch between Sign In / Sign Up tabs
- **Chat**: Type a message and hit Enter or click Send button
- **Profile**: Switch between tabs for different settings
- **Pricing**: Hover on cards to see effects

## File Structure

```
vansh/
└── index.html          # Complete single-file simulator (entire app in one file)
└── README.md           # This file
```

## Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients, animations, flexbox, grid
- **Vanilla JavaScript** - No frameworks or dependencies
- **Google Fonts** - DM Sans & Syne fonts (self-hosted via CDN)

### Styling Features
- Dark theme with accent colors (#6366f1 primary, #8b5cf6 secondary)
- Responsive grid layouts
- Smooth transitions and animations
- Glassmorphism effects on navbar
- Gradient buttons and elements

### JavaScript Features
- Page state management
- Event listeners for navigation
- Typing animation simulation
- Chat message handling
- Form tab switching
- Navbar scroll detection

## Color Scheme

- **Primary**: #6366f1 (Indigo)
- **Secondary**: #8b5cf6 (Purple)
- **Accent**: #f97316 (Orange), #06b6d4 (Cyan)
- **Background**: #07080f (Almost Black)
- **Text**: White with transparency variations

## Asset References

This simulator uses:
- **SVG icons** - Embedded directly in HTML (no external files needed)
- **Google Fonts** - DM Sans & Syne (loaded via CDN)
- **No image dependencies** - All styled with CSS

To integrate with actual images from `frontend/src/assets/`, simply add `<img>` tags pointing to those paths.

## Customization

You can easily customize:
- **Colors**: Search for color values and replace (#6366f1, #8b5cf6, etc.)
- **Text**: Update hero text, feature descriptions, pricing plans
- **Pages**: Add new sections by duplicating the page structure
- **Styles**: Modify CSS variables and transitions

## Limitations (By Design)

As a simulator, these features are NOT functional:
- ❌ Authentication doesn't actually validate
- ❌ Forms don't submit to backend
- ❌ Chat messages don't call any AI API
- ❌ Payment processing not implemented
- ❌ Database integration not present

**This is intended as a visual reference and interactive mockup for design/development work.**

## Performance

- Single HTML file = instant loading
- No build process needed
- Works offline
- ~50KB uncompressed
- All CSS and JS embedded

## Browser Support

Works on all modern browsers:
- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## How to Use as Reference

1. **Design Reference**: Copy CSS styles and layouts
2. **Component Examples**: Extract specific components and adapt them
3. **Color Palette**: Use the color values throughout your projects
4. **Animation Patterns**: Reference the smooth transitions and keyframe animations
5. **Responsive Patterns**: Study the grid and flex layouts for mobile adaptation

## Next Steps

To make this fully functional:
1. Connect auth forms to real API endpoints
2. Link chat interface to AI backend
3. Integrate payment processing for pricing page
4. Add user profile API calls
5. Implement real-time messaging if needed

## Notes

- This is a **blackboard simulator** - use it as a starting point to build upon
- All components are styled to match the original React app exactly
- You can copy-paste styles and structures into production code
- The code is well-commented for easy navigation and modification

---

**Created as a vanilla HTML/CSS/JS recreation of the ResonateAI frontend.**
**Perfect for design reference, prototyping, and understanding the UI architecture.**
