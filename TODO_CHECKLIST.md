# University Events Website - Development Checklist

## 📌 Quick Reference
**Deadline:** July 22, 2026  
**Status:** In Progress  
**Estimated Time:** 35-45 hours

---

## Phase 1: Setup & Structure ✅

### Initial Setup
- [x] Create project folder structure
- [x] Create all 6 HTML files (empty)
- [x] Create style.css file
- [x] Create images folder with subfolders
- [ ] Gather/download images (events, speakers, hero, etc.)
- [ ] Create IMPLEMENTATION_PLAN.md
- [ ] Create README.md

### HTML Skeleton
- [ ] Create basic HTML5 structure for all pages
- [ ] Add `<head>` section with meta tags
- [ ] Link style.css in all pages
- [ ] Add semantic HTML5 elements

---

## Phase 2: CSS Foundation 🎨

### CSS Variables & Reset
- [ ] Add CSS reset (margin, padding, box-sizing)
- [ ] Define CSS variables (:root)
  - [ ] Colors (primary, secondary, text, background)
  - [ ] Spacing units
  - [ ] Font sizes
  - [ ] Border radius
  - [ ] Shadows
  - [ ] Transitions
- [ ] Set base typography (font-family, line-height)
- [ ] Add smooth scrolling (`scroll-behavior: smooth`)

### Global Components
- [ ] Style navigation bar
  - [ ] Horizontal menu
  - [ ] Logo placement
  - [ ] Sticky positioning
  - [ ] Link hover effects
- [ ] Style footer
  - [ ] Multi-column layout
  - [ ] Social media icons
  - [ ] Copyright text
- [ ] Create utility classes
  - [ ] Container
  - [ ] Button styles
  - [ ] Text alignment
  - [ ] Spacing helpers

---

## Phase 3: Home Page (index.html) 🏠

### Header & Navigation
- [ ] Add university logo
- [ ] Create navigation menu (6 links)
- [ ] Make navigation sticky
- [ ] Add hover effects to nav links

### Hero Section
- [ ] Add hero background image
- [ ] Create gradient overlay
- [ ] Add headline text
- [ ] Add subheadline
- [ ] Create 2 CTA buttons
- [ ] Add entrance animation

### Featured Events Section
- [ ] Create section title
- [ ] Design 3 event cards
- [ ] Add images to cards
- [ ] Add event details (title, date, venue)
- [ ] Add "Learn More" buttons
- [ ] Implement hover effects
- [ ] Create responsive grid (flexbox/grid)

### Statistics Section
- [ ] Create 4 stat cards
- [ ] Add numbers/icons
- [ ] Add labels
- [ ] Implement grid layout
- [ ] Add animation effects

### Additional Features for Home (Choose 5-6)
- [ ] Timeline section
- [ ] Testimonials section
- [ ] Gallery grid
- [ ] Sponsors section
- [ ] Newsletter signup
- [ ] FAQ section

---

## Phase 4: Events Page (events.html) 🎉

### Page Structure
- [ ] Add page header/title
- [ ] Create breadcrumb navigation (optional)

### Event Cards (Minimum 8)
- [ ] Event 1: AI & Machine Learning Workshop
- [ ] Event 2: Annual Sports Gala
- [ ] Event 3: Web Development Bootcamp
- [ ] Event 4: Career Counseling Seminar
- [ ] Event 5: Cultural Festival 2026
- [ ] Event 6: Hackathon 2026
- [ ] Event 7: Industry Meet & Greet
- [ ] Event 8: Research Symposium

### Card Components (for each card)
- [ ] Event image with hover effect
- [ ] Event title
- [ ] Date (with icon)
- [ ] Venue (with icon)
- [ ] Category badge
- [ ] Organizer name
- [ ] Short description
- [ ] "Register Now" button

### CSS Grid Layout
- [ ] Create CSS Grid container
- [ ] Set up 4 columns for desktop
- [ ] Add gap between cards
- [ ] Apply card styling (shadow, radius, etc.)
- [ ] Add hover effects (lift, shadow increase)

---

## Phase 5: Schedule Page (schedule.html) 📅

### Table Structure
- [ ] Create HTML `<table>` element
- [ ] Add `<thead>` with column headers
  - [ ] Time
  - [ ] Event
  - [ ] Speaker
  - [ ] Hall
  - [ ] Category
- [ ] Add `<tbody>` with minimum 15 rows

### Table Styling
- [ ] Style table (width, border-collapse)
- [ ] Style headers (background, text color, padding)
- [ ] Apply alternate row colors (nth-child)
- [ ] Add border styling
- [ ] Implement hover effect on rows
- [ ] Add padding to cells

### Sample Entries (15+)
- [ ] 09:00 AM - Opening Ceremony
- [ ] 09:30 AM - Keynote Speech
- [ ] 10:30 AM - AI Workshop Session 1
- [ ] 10:30 AM - Web Development Basics
- [ ] 11:30 AM - Coffee Break
- [ ] 12:00 PM - Panel Discussion
- [ ] 01:00 PM - Lunch Break
- [ ] 02:00 PM - AI Workshop Session 2
- [ ] 02:00 PM - Advanced CSS Techniques
- [ ] 03:00 PM - Career Guidance Session
- [ ] 04:00 PM - Tea Break
- [ ] 04:30 PM - Project Presentations
- [ ] 05:30 PM - Hackathon Kickoff
- [ ] 06:00 PM - Networking Session
- [ ] 07:00 PM - Closing Ceremony

---

## Phase 6: Speakers Page (speakers.html) 🎤

### Speaker Profiles (Minimum 6)
- [ ] Speaker 1: Dr. Ahmed Khan
- [ ] Speaker 2: Prof. Sara Ali
- [ ] Speaker 3: Mr. Hamza Malik
- [ ] Speaker 4: Ms. Ayesha Khan
- [ ] Speaker 5: Dr. Bilal Ahmed
- [ ] Speaker 6: Eng. Fatima Noor

### Profile Components (for each speaker)
- [ ] Professional photo (circular or square)
- [ ] Name (bold, prominent)
- [ ] Designation
- [ ] Department
- [ ] Biography (3-4 lines)
- [ ] Social media icons (LinkedIn, Twitter, Email)

### Layout & Styling
- [ ] Create grid/flexbox layout
- [ ] Style profile cards
- [ ] Add image effects (border, shadow)
- [ ] Implement hover effects
- [ ] Style social media icons
- [ ] Make layout responsive

---

## Phase 7: Registration Page (register.html) 📝

### Form Structure
- [ ] Create `<form>` element
- [ ] Add form title/heading

### Personal Information Fields
- [ ] Full Name (text input, required)
- [ ] Registration Number (text input, required)
- [ ] Department (dropdown, required)
  - [ ] Add 5+ department options
- [ ] Semester (number input, required, 1-8)
- [ ] Email (email input, required)
- [ ] Phone Number (tel input, required)

### Event Selection Fields
- [ ] Gender (radio buttons)
  - [ ] Male
  - [ ] Female
  - [ ] Other
- [ ] Event Selection (dropdown/checkboxes)
  - [ ] Add all 8 events as options

### Additional Options
- [ ] Food Preference (radio buttons)
  - [ ] Vegetarian
  - [ ] Non-Vegetarian
  - [ ] Vegan
- [ ] T-shirt Size (dropdown)
  - [ ] XS, S, M, L, XL, XXL
- [ ] Special Requirements/Comments (textarea)

### Form Buttons
- [ ] Submit button (styled)
- [ ] Reset button (styled)

### Form Styling
- [ ] Style form container (max-width, center, shadow)
- [ ] Style form groups (spacing)
- [ ] Style labels (font-weight, spacing)
- [ ] Style input fields (padding, border, focus states)
- [ ] Style select dropdowns
- [ ] Style radio buttons (custom if possible with CSS)
- [ ] Style textarea
- [ ] Style buttons (gradient, hover effects)
- [ ] Add validation styling (required indicators)

---

## Phase 8: Contact Page (contact.html) 📞

### Contact Information Section
- [ ] University address card
- [ ] Phone number card
- [ ] Email card
- [ ] Office hours card
- [ ] Style info cards (icons, layout)

### Map Section
- [ ] Add static campus map image
- [ ] Style map container
- [ ] Add caption/description

### Contact Form
- [ ] Full Name (required)
- [ ] Email (required)
- [ ] Phone (optional)
- [ ] Subject (dropdown)
  - [ ] General Inquiry
  - [ ] Event Information
  - [ ] Registration Support
  - [ ] Technical Issue
  - [ ] Other
- [ ] Message (textarea, required)
- [ ] Submit button

### Additional Elements
- [ ] Quick contact cards (departments)
  - [ ] Admissions Office
  - [ ] IT Support
  - [ ] Event Coordinator
  - [ ] Student Affairs

---

## Phase 9: Additional Features ✨

### Required: Implement 10+ Features

#### Selected Features (Check 10+)
- [ ] 1. Hero Banner (with animation)
- [ ] 2. Statistics Section (with counters)
- [ ] 3. Timeline (vertical design)
- [ ] 4. Gallery (image grid with hover)
- [ ] 5. Testimonials (card-based)
- [ ] 6. FAQ Section (accordion CSS-only)
- [ ] 7. Sponsors Section (logo grid)
- [ ] 8. Newsletter Section (signup form)
- [ ] 9. Animated Buttons (hover effects)
- [ ] 10. Animated Cards (3D transforms)
- [ ] 11. Hover Overlay Images (opacity effects)
- [ ] 12. Gradient Buttons (color transitions)

#### Feature Implementation Details

**Timeline:**
- [ ] Create vertical timeline structure
- [ ] Add timeline connector line
- [ ] Add timeline items (alternating sides)
- [ ] Add dates and descriptions
- [ ] Style with animations

**Gallery:**
- [ ] Create image grid (CSS Grid)
- [ ] Add 6-12 gallery images
- [ ] Implement hover overlay
- [ ] Add zoom effect on hover
- [ ] Make responsive

**Testimonials:**
- [ ] Create 3-4 testimonial cards
- [ ] Add user photos
- [ ] Add star ratings
- [ ] Add quote text
- [ ] Add user names and titles
- [ ] Style with shadows and borders

**FAQ Accordion:**
- [ ] Create 5-8 FAQ items
- [ ] Implement checkbox hack for accordion
- [ ] Style questions (clickable headers)
- [ ] Style answers (hidden by default)
- [ ] Add transition effects
- [ ] Add icons (+ / -)

**Sponsors:**
- [ ] Add 6-12 sponsor logos
- [ ] Create grid layout
- [ ] Apply grayscale filter
- [ ] Remove grayscale on hover
- [ ] Add background cards

**Newsletter:**
- [ ] Create newsletter section
- [ ] Add gradient background
- [ ] Add heading and description
- [ ] Create email input field
- [ ] Add subscribe button
- [ ] Center content

---

## Phase 10: Responsive Design 📱

### Desktop (≥992px)
- [ ] Test navigation layout
- [ ] Test 4-column event grid
- [ ] Test all page layouts
- [ ] Verify spacing and typography
- [ ] Check all images display correctly

### Tablet (768-991px)
- [ ] Create media query for tablet
- [ ] Adjust event grid to 2 columns
- [ ] Adjust navigation if needed
- [ ] Scale down font sizes slightly
- [ ] Adjust spacing (padding/margins)
- [ ] Test form layouts
- [ ] Test table responsiveness

### Mobile (<768px)
- [ ] Create media query for mobile
- [ ] Adjust event grid to 1 column
- [ ] Implement mobile navigation
  - [ ] Create checkbox hack for hamburger menu
  - [ ] Style hamburger icon (3 lines)
  - [ ] Make menu vertical when open
- [ ] Scale down font sizes
- [ ] Reduce padding/margins
- [ ] Make tables responsive (stack or scroll)
- [ ] Make forms single column
- [ ] Test button sizes (touch-friendly)
- [ ] Hide/show elements as needed

### Universal Responsive Elements
- [ ] Use relative units (rem, em, %)
- [ ] Make images responsive (max-width: 100%)
- [ ] Test flexbox wrapping
- [ ] Test grid responsiveness
- [ ] Verify no horizontal scroll

---

## Phase 11: Polish & Animations 🎨

### Hover Effects
- [ ] Navigation links hover
- [ ] Button hover effects
- [ ] Card hover effects (lift, shadow)
- [ ] Image hover effects (zoom, overlay)
- [ ] Social icon hovers

### Transition Effects
- [ ] Button transitions
- [ ] Link color transitions
- [ ] Shadow transitions
- [ ] Transform transitions
- [ ] Background transitions

### Keyframe Animations
- [ ] Hero text entrance animation
- [ ] Statistics counter animation
- [ ] Card fade-in animations
- [ ] Icon bounce/pulse animations
- [ ] Loading animations (if applicable)

### Final Visual Polish
- [ ] Check all spacing consistency
- [ ] Verify color consistency
- [ ] Check font sizes hierarchy
- [ ] Verify all borders and shadows
- [ ] Check alignment throughout

---

## Phase 12: Testing & Validation ✅

### HTML Validation
- [ ] Validate index.html (W3C)
- [ ] Validate events.html
- [ ] Validate schedule.html
- [ ] Validate speakers.html
- [ ] Validate register.html
- [ ] Validate contact.html
- [ ] Fix all HTML errors

### CSS Validation
- [ ] Validate style.css (W3C)
- [ ] Fix all CSS errors
- [ ] Remove unused CSS rules
- [ ] Add vendor prefixes if needed

### Cross-Browser Testing
- [ ] Test in Google Chrome
- [ ] Test in Mozilla Firefox
- [ ] Test in Microsoft Edge
- [ ] Test in Safari (if available)
- [ ] Fix any browser-specific issues

### Responsive Testing
- [ ] Test on desktop (1920×1080)
- [ ] Test on laptop (1366×768)
- [ ] Test on tablet (iPad size)
- [ ] Test on mobile (iPhone size)
- [ ] Test on large mobile (Android)
- [ ] Use browser DevTools responsive mode

### Functionality Testing
- [ ] All navigation links work
- [ ] All internal anchors work
- [ ] All buttons are styled correctly
- [ ] Forms have proper validation
- [ ] Tables display correctly
- [ ] All images load
- [ ] No broken links

### Performance
- [ ] Optimize images (compress)
- [ ] Check page load times
- [ ] Verify CSS file size reasonable
- [ ] Check for rendering issues

---

## Phase 13: Code Quality 🧹

### Code Organization
- [ ] Organize CSS by sections
- [ ] Add comments to CSS sections
- [ ] Ensure proper indentation (HTML & CSS)
- [ ] Use meaningful class names
- [ ] Remove commented-out code
- [ ] Remove console logs (if any)

### File Organization
- [ ] Verify folder structure is clean
- [ ] Ensure all images are in correct folders
- [ ] Check file naming conventions
- [ ] Remove unused files

### Accessibility
- [ ] Add alt attributes to all images
- [ ] Use semantic HTML tags
- [ ] Ensure sufficient color contrast
- [ ] Add labels to form fields
- [ ] Test keyboard navigation

---

## Phase 14: Documentation 📄

### README.md
- [ ] Add project title
- [ ] Add course information
- [ ] Add live demo link (placeholder)
- [ ] List all pages
- [ ] List all features
- [ ] Add technologies used
- [ ] Add responsive breakpoints
- [ ] Add color theme info
- [ ] Add project structure
- [ ] Add author information
- [ ] Add testing information
- [ ] Add references

### PDF Report
- [ ] Create title page
  - [ ] Your name
  - [ ] Registration number
  - [ ] Section
  - [ ] Course details
  - [ ] Instructor name
- [ ] Take screenshots of all 6 pages
  - [ ] Desktop view screenshots
  - [ ] Mobile view screenshots (optional but recommended)
- [ ] Write page descriptions
  - [ ] Home page explanation
  - [ ] Events page explanation
  - [ ] Schedule page explanation
  - [ ] Speakers page explanation
  - [ ] Registration page explanation
  - [ ] Contact page explanation
- [ ] Document design decisions
  - [ ] Color theme choice
  - [ ] Layout approach
  - [ ] Additional features chosen
- [ ] List technical details
  - [ ] CSS techniques used
  - [ ] Responsive approach
  - [ ] Challenges faced
- [ ] Format professionally (10-15 pages)

---

## Phase 15: GitHub & Deployment 🚀

### Git Setup
- [ ] Initialize git repository (`git init`)
- [ ] Create .gitignore file (if needed)
- [ ] Add all files (`git add .`)
- [ ] Create initial commit

### GitHub Repository
- [ ] Create new repository on GitHub
- [ ] Name it "University-Events"
- [ ] Make it public
- [ ] Don't initialize with README (already have one)
- [ ] Copy repository URL

### Push to GitHub
- [ ] Add remote origin
  ```bash
  git remote add origin https://github.com/username/University-Events.git
  ```
- [ ] Push to main branch
  ```bash
  git branch -M main
  git push -u origin main
  ```
- [ ] Verify all files uploaded

### Enable GitHub Pages
- [ ] Go to repository Settings
- [ ] Scroll to "Pages" section
- [ ] Select "main" branch
- [ ] Select root folder
- [ ] Save settings
- [ ] Wait for deployment (2-5 minutes)
- [ ] Copy GitHub Pages URL

### Test Live Website
- [ ] Visit GitHub Pages URL
- [ ] Test all pages load
- [ ] Test all navigation links
- [ ] Test all images load
- [ ] Test on mobile (responsive)
- [ ] Fix any issues with paths
- [ ] Commit and push fixes if needed

---

## Phase 16: Submission 📤

### Google Classroom Submission

#### Private Comment
- [ ] Copy GitHub Repository URL
- [ ] Copy GitHub Pages (live) URL
- [ ] Paste both in private comment section
- [ ] Format clearly:
  ```
  GitHub Repository: [URL]
  GitHub Pages (Live): [URL]
  ```

#### PDF Upload
- [ ] Name file properly:
  `YourName_RegNo_WebTech_Assignment1.pdf`
- [ ] Upload to Google Classroom
- [ ] Verify file uploaded successfully

### Final Checks Before Deadline
- [ ] Deadline: July 22, 2026 ✓
- [ ] Both URLs work and are accessible
- [ ] PDF is uploaded correctly
- [ ] Private comment contains both links
- [ ] All requirements met
- [ ] No broken links or images
- [ ] Website is fully functional
- [ ] Code is clean and well-organized

---

## 🎯 Assignment Requirements Checklist

### A. Website Pages ✓
- [ ] Home (index.html) - with all required components
- [ ] Events (events.html) - 8+ event cards with CSS Grid
- [ ] Schedule (schedule.html) - 15+ row table
- [ ] Speakers (speakers.html) - 6+ speaker profiles
- [ ] Registration (register.html) - complete form
- [ ] Contact (contact.html) - all required sections

### B. CSS Requirements ✓
- [ ] Single external CSS file (style.css)
- [ ] Flexbox layouts implemented
- [ ] CSS Grid layouts implemented
- [ ] CSS Variables used
- [ ] Gradient backgrounds
- [ ] Card shadows
- [ ] Sticky navigation
- [ ] Hover effects
- [ ] Transition effects
- [ ] Keyframe animations
- [ ] Media queries for responsiveness
- [ ] Smooth scrolling

### C. Responsive Layout ✓
- [ ] Desktop (≥992px): 4 cards per row
- [ ] Tablet (768-991px): 2 cards per row
- [ ] Mobile (<768px): 1 card per row

### D. Color Theme ✓
- [ ] Professional color theme chosen and applied consistently

### E. Additional Features (10+) ✓
- [ ] Minimum 10 features from the list implemented

---

## ⏱️ Time Tracking

| Phase | Estimated Time | Actual Time | Status |
|-------|---------------|-------------|--------|
| Setup & Structure | 2-3 hours | | ⏳ |
| CSS Foundation | 3-4 hours | | ⏳ |
| Home Page | 4-5 hours | | ⏳ |
| Events Page | 3-4 hours | | ⏳ |
| Schedule Page | 2-3 hours | | ⏳ |
| Speakers Page | 3-4 hours | | ⏳ |
| Registration Page | 3-4 hours | | ⏳ |
| Contact Page | 2-3 hours | | ⏳ |
| Additional Features | 4-5 hours | | ⏳ |
| Responsive Design | 3-4 hours | | ⏳ |
| Polish & Animations | 2-3 hours | | ⏳ |
| Testing & Validation | 2-3 hours | | ⏳ |
| Documentation | 2-3 hours | | ⏳ |
| GitHub & Deployment | 2-3 hours | | ⏳ |
| **Total** | **35-45 hours** | | ⏳ |

---

## 📝 Notes & Ideas

### Color Theme Finalized:
- Primary: #1e3a8a (Blue)
- Secondary: #3b82f6
- Accent: #60a5fa

### Font Choices:
- Headings: [To be decided]
- Body: [To be decided]

### Additional Notes:
- [Add your notes here as you work]

---

## ❓ Questions / Issues

- [ ] [List any questions or issues you encounter]

---

**Last Updated:** [Date]  
**Progress:** 0% Complete
