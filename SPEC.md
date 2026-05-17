# Priti's Kitchen - Website Specification

## 1. Project Overview
- **Project Name:** Priti's Kitchen
- **Type:** Single-page dynamic restaurant website
- **Core Functionality:** Showcase Odia cuisine restaurant with menu, location, and gallery
- **Target Users:** Local customers, food enthusiasts, tourists in Bhubaneswar

## 2. UI/UX Specification

### Layout Structure
- **Header:** Fixed navigation with logo and menu links
- **Hero Section:** Full-width hero with background image and tagline
- **About Section:** Restaurant story and chef introduction
- **Menu Section:** Grid of Odia dishes with images
- **Gallery Section:** Image gallery of cuisine photos
- **Contact Section:** Address, phone, hours
- **Footer:** Social links and copyright

### Responsive Breakpoints
- Mobile: < 768px (single column)
- Tablet: 768px - 1024px (2 columns)
- Desktop: > 1024px (3-4 columns)

### Visual Design

#### Color Palette
- **Primary:** #D4380D (Odia-inspired deep red/orange)
- **Secondary:** #1A1A1A (Rich black)
- **Accent:** #F4A024 (Warm golden yellow)
- **Background:** #FFF8F0 (Warm cream)
- **Text Primary:** #2D2D2D
- **Text Light:** #FFFFFF

#### Typography
- **Headings:** "Playfair Display", serif (elegant, traditional)
- **Body:** "Nunito", sans-serif (clean, readable)
- **Accent:** "Sacramento", cursive (decorative for special elements)

#### Spacing System
- Section padding: 80px vertical
- Card padding: 24px
- Grid gap: 32px

#### Visual Effects
- Subtle box shadows on cards
- Hover scale transform on menu items (1.05)
- Smooth scroll behavior
- Fade-in animations on scroll
- Gradient overlay on hero

### Components

#### Navigation
- Logo with restaurant name
- Links: Home, About, Menu, Gallery, Contact
- Mobile hamburger menu

#### Hero
- Background image of Odia cuisine
- Headline: "Authentic Odia Flavors"
- Subheadline: "A Culinary Journey Through Odisha"
- CTA Button: "View Menu"

#### Menu Cards
- Dish image (300x200px)
- Dish name
- Description (short)
- Price badge
- Hover effect: slight lift + shadow

#### Contact Card
- Map placeholder/image
- Address: Rasulgarh, Bhubaneswar, Odisha
- Phone number
- Opening hours

## 3. Functionality Specification

### Core Features
1. **Responsive navigation** - Works on all devices
2. **Smooth scroll** - Anchor links scroll to sections
3. **Menu display** - 8+ Odia dishes with images and prices
4. **Gallery** - Grid of cuisine images
5. **Contact info** - Full address and contact details
6. **Interactive elements** - Hover effects on cards and buttons

### Menu Items (Odia Cuisines)
1. **Dalma** - Lentil curry with vegetables - ₹120
2. **Pakhala Bhata** - Fermented rice with sides - ₹80
3. **Rasabali** - Sweet cottage cheese dessert - ₹100
4. **Chhena Poda** - Baked cheese dessert - ₹90
5. **Prawns Malai Curry** - Prawns in coconut gravy - ₹250
6. **Machha Bhaja** - Fish fry - ₹180
7. **Vegetable Ghansi** - Mixed vegetable curry - ₹140
8. **Mitha Boondi** - Sweet boondi dessert - ₹70

### User Interactions
- Click navigation to scroll to sections
- Hover on menu items for visual feedback
- Click CTA button to jump to menu

## 4. Acceptance Criteria
- [ ] Website loads without errors
- [ ] All 8 Odia dishes displayed with images
- [ ] Address shows: Rasulgarh, Bhubaneswar, Odisha
- [ ] Responsive on mobile, tablet, desktop
- [ ] Smooth animations and hover effects
- [ ] All images load correctly
- [ ] Color scheme matches specification