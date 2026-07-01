# Quick Navigation Guide

## How to Interact with the Simulator

### 🏠 Home Page
- **Entry Point**: Opens by default
- **Elements**: Hero with typing animation, features grid, CTA buttons
- **Actions**: 
  - Click "Get Started" → Opens Auth Modal
  - Click "Sign In" → Opens Auth Modal  
  - Scroll down to see features
  - Use navbar to jump to sections

### 📊 Features Section
- **4 Feature Cards**: Deep Reasoning, Memory, Verifiability, Speed
- **Hover Effects**: Cards glow and lift on hover
- **Numbers**: Feature card numbers (01-04) in corner
- **Responsive**: Grid adapts to screen size

### 💰 Pricing Page
- **4 Plans**: Free, Pro, Pro+, Enterprise
- **Highlight**: Pro plan is "Best Value" (scaled and highlighted)
- **Features**: Lists included features with checkmarks
- **Buttons**: Each plan has a CTA button

### 🔐 Authentication Modal
- **2 Tabs**: Sign In / Sign Up
- **Fields** (Sign In): Email, Password
- **Fields** (Sign Up): First Name, Last Name, Email, Password, Confirm Password
- **Status**: Form is interactive but not functional (design-only)
- **After Submit**: Redirects to dashboard (in this simulator)

### 👤 Profile Page
- **4 Tabs**: Profile, Billing, Security, Danger Zone
- **Profile Tab**: Edit user info (first/last name, email)
- **Billing Tab**: Current plan, subscription management, billing history
- **Security Tab**: Change password form
- **Danger Tab**: Delete account warning
- **Logout Button**: Top right - returns to home

### 💬 Chat/Dashboard (Protected)
- **Access**: Click "Get Started" → Login → Redirects to chat
- **Sidebar**: Chat history list, "New Chat" button
- **Main Area**: Message display and input
- **Messages**: Type and send messages (simulated responses)
- **Input**: Press Enter or click Send button
- **Dark Theme**: Chat page has dark overlay background

### 📄 Other Pages
Available through footer or navigation:
- **About**: Company mission and values
- **Careers**: Team positions and opportunities
- **Press**: News and press releases
- **Blog**: Latest articles
- **Privacy/Terms**: Legal pages

### 🦶 Footer
- **Links**: Organized by category (Product, Company, Legal)
- **Social**: LinkedIn, Twitter/X, GitHub icons
- **Copyright**: Year and company info

---

## Page Navigation Map

```
Home
├── Hero → Get Started (Auth Modal)
├── Features (auto-visible)
├── Navigation → Pricing, About, Careers
└── Footer → All legal pages

Auth Modal (Overlay)
├── Sign In Tab
│   └── Success → Chat Dashboard
└── Sign Up Tab
    └── Success → Chat Dashboard

Protected Pages (Requires Login)
├── Profile Page (/profile)
│   ├── Profile Tab
│   ├── Billing Tab
│   ├── Security Tab
│   └── Danger Zone Tab
└── Chat Dashboard (/app)
    ├── Sidebar (Chat History)
    ├── Main (Messages)
    └── Input (Send)

Public Pages
├── About
├── Careers
├── Press
├── Blog
├── Privacy Policy
├── Terms of Service
└── Cookie Policy
```

---

## Interactive Elements

### Buttons & Links
- **btn-primary**: Gradient indigo-purple (Get Started, Sign In, Send)
- **btn-secondary**: Outlined style (Sign In from nav, Learn More)
- **All buttons**: Have hover animations (lift up, glow effect)

### Forms
- **All input fields**: Focus effect (border color changes to indigo)
- **Placeholders**: Shown in lighter text
- **Required fields**: Marked in auth forms (email, password, name)

### Cards
- **Feature Cards**: Border and glow effect on hover
- **Pricing Cards**: Scale and color change on hover
- **Pro plan**: Extra scale effect (1.05x)

### Text Effects
- **Navbar**: Blurs and colors on scroll
- **Typing Animation**: Cycles through 4 words in hero
- **Hover Text**: Color changes to indigo (#6366f1)

### Animations
- **Page Transitions**: Smooth fade-in
- **Message Arrival**: Slide up animation
- **Scroll**: Smooth scroll behavior throughout
- **Transitions**: All 0.2-0.4s ease for smoothness

---

## Login Flow (Simulated)

1. Click **"Get Started"** or **"Sign In"** in navbar
2. Auth modal appears with **Sign In** tab active
3. **Try these:**
   - Click **"Sign Up"** tab to see signup form
   - Enter any email/password in Sign In form
   - Click **"Sign In"** button
4. **Success**: Automatically redirects to chat dashboard
5. Now you can:
   - Visit **Profile page** (account settings)
   - Send **chat messages** (simulated AI responses)
   - View **billing history**

---

## Styling Customization Points

### Colors to Change
- Primary color: `#6366f1`
- Secondary color: `#8b5cf6`
- Accent orange: `#f97316`
- Accent cyan: `#06b6d4`
- Background: `#07080f`

### Fonts
- Display/Headings: `'Syne'` (serif-like)
- Body text: `'DM Sans'` (sans-serif)

### Dark Mode Only
- This simulator is dark-only (light mode not available)
- All backgrounds use `#07080f` or transparent overlays

---

## Testing Checklist

✅ **Navigation Works**
- [ ] Click logo → returns to home
- [ ] Navbar links navigate between pages
- [ ] Footer links work
- [ ] Back button works (browser)

✅ **Auth Modal**
- [ ] Sign In tab shows email/password
- [ ] Sign Up tab shows all fields
- [ ] Can switch between tabs
- [ ] Close button works
- [ ] Submit redirects to dashboard

✅ **Profile Page**
- [ ] All 4 tabs are clickable
- [ ] Tab content switches correctly
- [ ] Form fields are editable
- [ ] Logout button works

✅ **Chat Page**
- [ ] Messages appear in order
- [ ] Input field is functional
- [ ] Send button works
- [ ] Enter key sends messages
- [ ] Sidebar shows history

✅ **Responsive**
- [ ] Looks good on mobile (< 768px)
- [ ] Looks good on tablet (768px - 1024px)
- [ ] Looks good on desktop (> 1024px)

---

## Tips for Developers

1. **Copy Styles**: All CSS is self-contained - copy the `<style>` section
2. **Use Components**: Extract individual sections as starting points
3. **Modify Colors**: Use Find & Replace for color values
4. **Add Images**: Wrap image paths in `<img>` tags where needed
5. **Connect Backend**: Replace JavaScript handlers with API calls

---

**Need help?** Check the README.md for more details!
