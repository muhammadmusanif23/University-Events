# University Event Management Website - Implementation Plan

**Course:** Web Technologies (CS 311 / CS 224)  
**Semester:** Summer 2026  
**Deadline:** July 22, 2026  
**Total Marks:** 20

---

## 📋 Table of Contents
1. [Project Overview](#project-overview)
2. [Folder Structure](#folder-structure)
3. [Color Theme Selection](#color-theme-selection)
4. [CSS Architecture](#css-architecture)
5. [Page-by-Page Implementation](#page-by-page-implementation)
6. [Responsive Design Strategy](#responsive-design-strategy)
7. [Additional Features Selection](#additional-features-selection)
8. [Implementation Timeline](#implementation-timeline)
9. [Testing Checklist](#testing-checklist)
10. [Submission Checklist](#submission-checklist)

---

## 🎯 Project Overview

### Objective
Design a fully responsive University Event Management Website using HTML5 and CSS3 only (No JavaScript).

### Key Requirements
- 6 HTML pages (Home, Events, Schedule, Speakers, Registration, Contact)
- Single external CSS file (style.css)
- Fully responsive design (Desktop, Tablet, Mobile)
- Professional color theme
- 10+ additional design features
- Clean, well-indented code

---

## 📁 Folder Structure

```
University-Events/
│
├── index.html                 # Home page
├── events.html               # Events listing page
├── schedule.html             # Event schedule page
├── speakers.html             # Speakers profiles page
├── register.html             # Registration form page
├── contact.html              # Contact page
├── style.css                 # Single CSS file for entire website
│
├── images/                   # All images folder
│   ├── logo/
│   │   └── university-logo.png
│   ├── events/
│   │   ├── event1.jpg
│   │   ├── event2.jpg
│   │   └── ... (8 event images)
│   ├── speakers/
│   │   ├── speaker1.jpg
│   │   ├── speaker2.jpg
│   │   └── ... (6 speaker images)
│   ├── hero/
│   │   └── hero-banner.jpg
│   ├── gallery/
│   │   └── ... (gallery images)
│   ├── sponsors/
│   │   └── ... (sponsor logos)
│   └── map/
│       └── campus-map.png
│
├── IMPLEMENTATION_PLAN.md    # This file
└── README.md                 # Project documentation
```

---

## 🎨 Color Theme Selection

### Recommended Theme: **UET Professional Blue Theme**

```css
Primary Colors:
- Primary Blue: #1e3a8a
- Light Blue: #3b82f6
- Dark Blue: #1e40af
- Accent Blue: #60a5fa

Secondary Colors:
- Gray Dark: #1f2937
- Gray Medium: #6b7280
- Gray Light: #f3f4f6
- White: #ffffff

Accent Colors:
- Success Green: #10b981
- Warning Orange: #f59e0b
- Error Red: #ef4444
- Info Cyan: #06b6d4
```

### Alternative Themes (Choose one):
1. **Green Theme:** #047857, #10b981, #34d399
2. **Purple Theme:** #7c3aed, #a78bfa, #c4b5fd
3. **Dark Theme:** #111827, #1f2937, #374151

---

## 🎨 CSS Architecture

### CSS File Structure (style.css)

```css
/* ================================
   1. CSS RESET & VARIABLES
   ================================ */

/* ================================
   2. GLOBAL STYLES
   ================================ */

/* ================================
   3. UTILITY CLASSES
   ================================ */

/* ================================
   4. NAVIGATION BAR
   ================================ */

/* ================================
   5. FOOTER
   ================================ */

/* ================================
   6. HOME PAGE STYLES
   ================================ */

/* ================================
   7. EVENTS PAGE STYLES
   ================================ */

/* ================================
   8. SCHEDULE PAGE STYLES
   ================================ */

/* ================================
   9. SPEAKERS PAGE STYLES
   ================================ */

/* ================================
   10. REGISTRATION PAGE STYLES
   ================================ */

/* ================================
   11. CONTACT PAGE STYLES
   ================================ */

/* ================================
   12. ANIMATIONS & EFFECTS
   ================================ */

/* ================================
   13. RESPONSIVE DESIGN (MEDIA QUERIES)
   ================================ */
```

### Key CSS Techniques to Implement

1. **CSS Variables (Custom Properties)**
   ```css
   :root {
     --primary-color: #1e3a8a;
     --secondary-color: #3b82f6;
     --text-color: #1f2937;
     --bg-color: #ffffff;
     --spacing-unit: 1rem;
     --border-radius: 8px;
     --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
     --transition: all 0.3s ease;
   }
   ```

2. **Flexbox Layouts**
   - Navigation bar
   - Footer
   - Card layouts
   - Form layouts

3. **CSS Grid Layouts**
   - Events page (responsive grid)
   - Speakers page
   - Statistics section
   - Gallery section

4. **Advanced Styling**
   - Gradient backgrounds
   - Box shadows
   - Border radius
   - Hover effects
   - Transition effects
   - Keyframe animations

5. **Sticky Navigation**
   ```css
   .navbar {
     position: sticky;
     top: 0;
     z-index: 1000;
   }
   ```

6. **Smooth Scrolling**
   ```css
   html {
     scroll-behavior: smooth;
   }
   ```

---

## 📄 Page-by-Page Implementation

### 1. Home Page (index.html)

#### Components:
1. **Header Section**
   - University Logo (top-left)
   - Navigation Bar (sticky)
     - Links: Home | Events | Schedule | Speakers | Register | Contact
   - Responsive hamburger menu indicator (CSS only)

2. **Hero Section**
   - Full-width background image
   - Overlay with gradient
   - Headline: "Welcome to UET Events"
   - Subheadline
   - CTA buttons: "View Events" & "Register Now"
   - Animated entrance

3. **Featured Events Section**
   - Section title: "Featured Events"
   - 3 event cards (flexbox/grid)
   - Each card:
     - Image
     - Title
     - Date & venue
     - Short description
     - "Learn More" button
   - Hover effects

4. **Statistics Section**
   - 4 stat cards (grid layout)
   - Animated counters (static numbers with CSS animation)
   - Icons/numbers:
     - Total Events: 50+
     - Active Students: 2000+
     - Departments: 15+
     - Guest Speakers: 30+

5. **Additional Features (Select from list)**
   - Timeline section
   - Testimonials slider (CSS only)
   - Newsletter signup section
   - Sponsors section
   - Gallery grid

6. **Footer Section**
   - University info
   - Quick links
   - Social media icons
   - Copyright notice
   - Contact details

#### HTML Structure:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>UET Events - Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav class="navbar">
      <!-- Navigation content -->
    </nav>
  </header>
  
  <main>
    <section class="hero">
      <!-- Hero content -->
    </section>
    
    <section class="featured-events">
      <!-- Featured events -->
    </section>
    
    <section class="statistics">
      <!-- Statistics -->
    </section>
    
    <!-- Additional sections -->
  </main>
  
  <footer>
    <!-- Footer content -->
  </footer>
</body>
</html>
```

---

### 2. Events Page (events.html)

#### Requirements:
- Display at least **8 event cards**
- Use **CSS Grid** layout
- Responsive grid (4-2-1 cards per row)

#### Event Card Components:
1. Event Image (hover zoom effect)
2. Event Title
3. Date (with icon)
4. Venue (with icon)
5. Category Badge (colored)
6. Organizer
7. Short Description (2-3 lines)
8. "Register Now" Button

#### Layout Structure:
```css
.events-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 2rem;
}

/* Tablet */
@media (max-width: 991px) {
  .events-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Mobile */
@media (max-width: 767px) {
  .events-grid {
    grid-template-columns: 1fr;
  }
}
```

#### Event Categories:
1. Technical Workshop
2. Seminar
3. Sports Event
4. Cultural Event
5. Career Fair
6. Hackathon
7. Conference
8. Social Event

#### Sample Events (8):
1. **AI & Machine Learning Workshop**
   - Date: August 15, 2026
   - Venue: CS Lab 1
   - Category: Technical Workshop
   - Organizer: CS Department

2. **Annual Sports Gala**
   - Date: August 20, 2026
   - Venue: Main Ground
   - Category: Sports Event
   - Organizer: Sports Committee

3. **Web Development Bootcamp**
   - Date: August 25, 2026
   - Venue: Main Auditorium
   - Category: Technical Workshop
   - Organizer: CS Department

4. **Career Counseling Seminar**
   - Date: September 1, 2026
   - Venue: Conference Hall
   - Category: Seminar
   - Organizer: Career Services

5. **Cultural Festival 2026**
   - Date: September 10, 2026
   - Venue: Main Campus
   - Category: Cultural Event
   - Organizer: Student Affairs

6. **Hackathon 2026**
   - Date: September 15, 2026
   - Venue: CS Labs
   - Category: Hackathon
   - Organizer: CS Society

7. **Industry Meet & Greet**
   - Date: September 20, 2026
   - Venue: Executive Hall
   - Category: Career Fair
   - Organizer: Industry Relations

8. **Research Symposium**
   - Date: September 25, 2026
   - Venue: Main Auditorium
   - Category: Conference
   - Organizer: Research Cell

---

### 3. Schedule Page (schedule.html)

#### Requirements:
- HTML Table with minimum **15 rows**
- Columns: Time | Event | Speaker | Hall | Category
- Alternate row colors
- Responsive table design

#### Table Structure:
```html
<table class="schedule-table">
  <thead>
    <tr>
      <th>Time</th>
      <th>Event</th>
      <th>Speaker</th>
      <th>Hall</th>
      <th>Category</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>09:00 AM</td>
      <td>Opening Ceremony</td>
      <td>Vice Chancellor</td>
      <td>Main Auditorium</td>
      <td>General</td>
    </tr>
    <!-- More rows -->
  </tbody>
</table>
```

#### CSS Styling:
```css
.schedule-table {
  width: 100%;
  border-collapse: collapse;
}

.schedule-table tbody tr:nth-child(odd) {
  background-color: #f3f4f6;
}

.schedule-table tbody tr:nth-child(even) {
  background-color: #ffffff;
}

.schedule-table tbody tr:hover {
  background-color: #e5e7eb;
  transform: scale(1.02);
  transition: var(--transition);
}
```

#### Sample Schedule (15+ Rows):
1. 09:00 AM - Opening Ceremony - Vice Chancellor - Main Auditorium - General
2. 09:30 AM - Keynote Speech - Dr. Ahmed Khan - Main Auditorium - Technical
3. 10:30 AM - AI Workshop Session 1 - Prof. Sara Ali - CS Lab 1 - Workshop
4. 10:30 AM - Web Development Basics - Mr. Hamza Malik - CS Lab 2 - Workshop
5. 11:30 AM - Coffee Break - - Cafeteria - Break
6. 12:00 PM - Panel Discussion - Industry Experts - Conference Hall - Seminar
7. 01:00 PM - Lunch Break - - Cafeteria - Break
8. 02:00 PM - AI Workshop Session 2 - Prof. Sara Ali - CS Lab 1 - Workshop
9. 02:00 PM - Advanced CSS Techniques - Mr. Hamza Malik - CS Lab 2 - Workshop
10. 03:00 PM - Career Guidance Session - Ms. Ayesha Khan - Room 301 - Seminar
11. 04:00 PM - Tea Break - - Cafeteria - Break
12. 04:30 PM - Project Presentations - Students - Main Hall - Competition
13. 05:30 PM - Hackathon Kickoff - Organizing Team - CS Labs - Hackathon
14. 06:00 PM - Networking Session - All Participants - Lawn Area - Networking
15. 07:00 PM - Closing Ceremony - Dean CS - Main Auditorium - General

---

### 4. Speakers Page (speakers.html)

#### Requirements:
- Display at least **6 speaker profiles**
- CSS Grid/Flexbox layout
- Responsive design

#### Speaker Card Components:
1. Professional photo (circular/square)
2. Name (bold, large)
3. Designation
4. Department
5. Short biography (3-4 lines)
6. Social media icons (LinkedIn, Twitter, Email)
7. Hover effects

#### Sample Speakers (6):

1. **Dr. Ahmed Khan**
   - Designation: Professor & Head
   - Department: Computer Science
   - Bio: Expert in Artificial Intelligence with 20+ years of experience. Published 50+ research papers in top-tier conferences.
   - Social: LinkedIn, Twitter, Email

2. **Prof. Sara Ali**
   - Designation: Associate Professor
   - Department: Software Engineering
   - Bio: Specialist in Machine Learning and Data Science. Leading researcher in AI applications for healthcare.
   - Social: LinkedIn, Twitter, Email

3. **Mr. Hamza Malik**
   - Designation: Senior Lecturer
   - Department: Computer Science
   - Bio: Full-stack web developer and educator. 10+ years of industry experience before joining academia.
   - Social: LinkedIn, Twitter, Email

4. **Ms. Ayesha Khan**
   - Designation: Career Counselor
   - Department: Student Affairs
   - Bio: Professional career advisor helping students achieve their goals. Certified career coach with 15 years experience.
   - Social: LinkedIn, Twitter, Email

5. **Dr. Bilal Ahmed**
   - Designation: Assistant Professor
   - Department: Cyber Security
   - Bio: Cyber security expert and ethical hacker. Consultant for government and private organizations.
   - Social: LinkedIn, Twitter, Email

6. **Eng. Fatima Noor**
   - Designation: Industry Expert
   - Department: Guest Speaker
   - Bio: Senior Software Engineer at a leading tech company. Speaker at international tech conferences.
   - Social: LinkedIn, Twitter, Email

---

### 5. Registration Page (register.html)

#### Requirements:
- Comprehensive registration form (design only)
- All required fields
- Proper form validation attributes
- Styled form elements

#### Form Fields:

**Personal Information:**
1. Full Name (text input, required)
2. Registration Number (text input, required, pattern validation)
3. Department (dropdown, required)
   - Computer Science
   - Software Engineering
   - Electrical Engineering
   - Mechanical Engineering
   - Civil Engineering
   - Other
4. Semester (number input, required, 1-8)
5. Email (email input, required)
6. Phone Number (tel input, required)

**Event Selection:**
7. Gender (radio buttons)
   - Male
   - Female
   - Other
8. Event Selection (dropdown/checkboxes, required)
   - AI Workshop
   - Sports Gala
   - Web Development Bootcamp
   - Career Seminar
   - Cultural Festival
   - Hackathon
   - Industry Meet
   - Research Symposium

**Additional Options:**
9. Food Preference (radio buttons)
   - Vegetarian
   - Non-Vegetarian
   - Vegan
10. T-shirt Size (dropdown)
    - XS, S, M, L, XL, XXL
11. Special Requirements/Comments (textarea)

**Buttons:**
- Submit Button (styled)
- Reset Button (styled)

#### Form Styling:
```css
.registration-form {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
  background: white;
  border-radius: var(--border-radius);
  box-shadow: var(--box-shadow);
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-group label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: 600;
}

.form-group input,
.form-group select,
.form-group textarea {
  width: 100%;
  padding: 0.75rem;
  border: 2px solid #e5e7eb;
  border-radius: var(--border-radius);
  transition: var(--transition);
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary-color);
  box-shadow: 0 0 0 3px rgba(30, 58, 138, 0.1);
}
```

---

### 6. Contact Page (contact.html)

#### Requirements:
1. University address
2. Google Map image (static)
3. Contact information
4. Contact form
5. Office hours

#### Sections:

**1. Contact Information Cards**
```
📍 Address
University of Engineering & Technology
Peshawar, Khyber Pakhtunkhwa
Pakistan

📞 Phone
+92-91-9216701-14

📧 Email
info@uetpeshawar.edu.pk

🕒 Office Hours
Monday - Friday: 8:00 AM - 4:00 PM
Saturday: 9:00 AM - 1:00 PM
Sunday: Closed
```

**2. Google Map Section**
- Static image of campus map
- Or embedded map image (screenshot)

**3. Contact Form**
Fields:
- Full Name (required)
- Email (required)
- Phone (optional)
- Subject (dropdown)
  - General Inquiry
  - Event Information
  - Registration Support
  - Technical Issue
  - Other
- Message (textarea, required)
- Submit Button

**4. Quick Contact Cards**
Grid of department contacts:
- Admissions Office
- IT Support
- Event Coordinator
- Student Affairs

---

## 📱 Responsive Design Strategy

### Breakpoints:

```css
/* Desktop First Approach */

/* Large Desktop (default) */
/* 1200px and above */

/* Desktop */
@media (max-width: 1199px) {
  /* Styles for screens up to 1199px */
}

/* Tablet */
@media (max-width: 991px) {
  /* 2 cards per row */
  /* Stack some sections */
  /* Adjust font sizes */
}

/* Mobile */
@media (max-width: 767px) {
  /* 1 card per row */
  /* Hamburger menu */
  /* Stack all sections */
  /* Reduce padding/margins */
}

/* Small Mobile */
@media (max-width: 480px) {
  /* Further optimizations */
}
```

### Responsive Patterns:

#### 1. Navigation
- Desktop: Horizontal menu
- Tablet: Horizontal menu (smaller)
- Mobile: Checkbox hack for hamburger menu (CSS only)

```css
/* Hamburger Menu (CSS Only) */
.menu-toggle {
  display: none;
}

.menu-icon {
  display: none;
}

@media (max-width: 767px) {
  .menu-icon {
    display: block;
    cursor: pointer;
  }
  
  .nav-links {
    display: none;
  }
  
  .menu-toggle:checked ~ .nav-links {
    display: flex;
    flex-direction: column;
  }
}
```

#### 2. Grid Layouts
```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}
```

#### 3. Typography
```css
:root {
  --heading-1: 3rem;
  --heading-2: 2.5rem;
  --heading-3: 2rem;
  --body-text: 1rem;
}

@media (max-width: 767px) {
  :root {
    --heading-1: 2rem;
    --heading-2: 1.75rem;
    --heading-3: 1.5rem;
    --body-text: 0.875rem;
  }
}
```

#### 4. Spacing
```css
.container {
  padding: 4rem 2rem;
}

@media (max-width: 767px) {
  .container {
    padding: 2rem 1rem;
  }
}
```

#### 5. Tables
```css
@media (max-width: 767px) {
  table, thead, tbody, th, td, tr {
    display: block;
  }
  
  thead tr {
    display: none;
  }
  
  tr {
    margin-bottom: 1rem;
    border: 1px solid #ddd;
  }
  
  td {
    text-align: right;
    position: relative;
    padding-left: 50%;
  }
  
  td::before {
    content: attr(data-label);
    position: absolute;
    left: 0;
    padding-left: 1rem;
    font-weight: bold;
    text-align: left;
  }
}
```

---

## ✨ Additional Features Selection (10 Required)

### Recommended 12 Features:

1. **✅ Hero Banner**
   - Full-width background image
   - Gradient overlay
   - Animated text entrance
   - Call-to-action buttons

2. **✅ Statistics Section**
   - Animated counter numbers
   - Icon-based stat cards
   - Grid layout
   - Hover effects

3. **✅ Timeline**
   - Vertical timeline design
   - Event milestones
   - Animated connectors
   - Responsive layout

4. **✅ Gallery**
   - CSS Grid layout
   - Hover overlay effects
   - Responsive image grid
   - Lightbox-style hover (CSS only)

5. **✅ Testimonials**
   - Card-based design
   - Star ratings
   - User photos
   - Quote styling

6. **✅ FAQ Section**
   - Accordion-style (CSS only with :target or checkbox)
   - Expandable questions
   - Smooth transitions
   - Clean typography

7. **✅ Sponsors Section**
   - Logo grid
   - Grayscale to color on hover
   - Responsive layout
   - Filter effects

8. **✅ Newsletter Section**
   - Email subscription form
   - Gradient background
   - Centered design
   - Success message styling

9. **✅ Animated Buttons**
   - Hover effects
   - Ripple effects (CSS only)
   - Gradient backgrounds
   - Transform animations

10. **✅ Animated Cards**
    - Float on hover
    - Scale transforms
    - Shadow depth changes
    - Smooth transitions

11. **✅ Hover Overlay Images**
    - Opacity overlays
    - Text reveal on hover
    - Zoom effects
    - Color overlays

12. **✅ Gradient Buttons**
    - Linear gradients
    - Gradient shift on hover
    - Border animations
    - Glow effects

### Implementation Examples:

#### Timeline CSS:
```css
.timeline {
  position: relative;
  padding: 2rem 0;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 4px;
  height: 100%;
  background: linear-gradient(to bottom, var(--primary-color), var(--secondary-color));
}

.timeline-item {
  display: flex;
  margin-bottom: 2rem;
}

.timeline-item:nth-child(odd) {
  flex-direction: row;
}

.timeline-item:nth-child(even) {
  flex-direction: row-reverse;
}
```

#### FAQ Accordion (CSS Only):
```css
.faq-item input[type="checkbox"] {
  display: none;
}

.faq-answer {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease;
}

.faq-item input[type="checkbox"]:checked ~ .faq-answer {
  max-height: 500px;
}
```

#### Animated Card:
```css
.card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-10px) scale(1.02);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
}
```

---

## 🚀 Implementation Timeline

### Phase 1: Setup & Structure (Day 1)
- ✅ Create folder structure
- ✅ Set up HTML skeleton for all pages
- ✅ Create basic navigation and footer
- ✅ Initialize CSS file with variables and reset
- ⏱️ Time: 2-3 hours

### Phase 2: CSS Foundation (Day 1-2)
- ⏱️ Set up CSS variables and color scheme
- ⏱️ Create utility classes
- ⏱️ Style navigation bar (sticky + responsive)
- ⏱️ Style footer
- ⏱️ Implement base typography
- ⏱️ Time: 3-4 hours

### Phase 3: Home Page (Day 2)
- ⏱️ Hero section with animation
- ⏱️ Featured events section
- ⏱️ Statistics section
- ⏱️ Additional features (select 5-6 for homepage)
- ⏱️ Time: 4-5 hours

### Phase 4: Events Page (Day 3)
- ⏱️ Create 8 event cards with content
- ⏱️ Implement CSS Grid layout
- ⏱️ Add hover effects and transitions
- ⏱️ Make responsive (4-2-1 layout)
- ⏱️ Time: 3-4 hours

### Phase 5: Schedule Page (Day 3)
- ⏱️ Create HTML table with 15+ rows
- ⏱️ Style table with alternate colors
- ⏱️ Add hover effects
- ⏱️ Make table responsive
- ⏱️ Time: 2-3 hours

### Phase 6: Speakers Page (Day 4)
- ⏱️ Create 6 speaker profiles
- ⏱️ Design card layout
- ⏱️ Add social media icons
- ⏱️ Implement hover effects
- ⏱️ Make responsive
- ⏱️ Time: 3-4 hours

### Phase 7: Registration Page (Day 4)
- ⏱️ Design comprehensive form
- ⏱️ Style all form elements
- ⏱️ Add validation attributes
- ⏱️ Create custom radio/checkbox styles
- ⏱️ Style buttons
- ⏱️ Make form responsive
- ⏱️ Time: 3-4 hours

### Phase 8: Contact Page (Day 5)
- ⏱️ Create contact information section
- ⏱️ Add map image
- ⏱️ Design contact form
- ⏱️ Create office hours display
- ⏱️ Add quick contact cards
- ⏱️ Time: 2-3 hours

### Phase 9: Additional Features (Day 5-6)
- ⏱️ Implement remaining 4-5 features from the list
- ⏱️ Distribute across different pages
- ⏱️ Add animations and effects
- ⏱️ Time: 4-5 hours

### Phase 10: Responsive Design (Day 6)
- ⏱️ Test all pages on different screen sizes
- ⏱️ Fine-tune media queries
- ⏱️ Adjust spacing and typography
- ⏱️ Fix any layout issues
- ⏱️ Time: 3-4 hours

### Phase 11: Polish & Animations (Day 7)
- ⏱️ Add keyframe animations
- ⏱️ Refine hover effects
- ⏱️ Add smooth transitions
- ⏱️ Implement smooth scrolling
- ⏱️ Final visual polish
- ⏱️ Time: 2-3 hours

### Phase 12: Testing & Optimization (Day 7)
- ⏱️ Cross-browser testing
- ⏱️ Validate HTML & CSS
- ⏱️ Check responsiveness on all devices
- ⏱️ Optimize images
- ⏱️ Clean up code
- ⏱️ Time: 2-3 hours

### Phase 13: Documentation & Submission (Day 7)
- ⏱️ Create README.md
- ⏱️ Take screenshots of all pages
- ⏱️ Write PDF report
- ⏱️ Upload to GitHub
- ⏱️ Enable GitHub Pages
- ⏱️ Test live website
- ⏱️ Submit on Google Classroom
- ⏱️ Time: 2-3 hours

**Total Estimated Time: 35-45 hours (7 days)**

---

## ✅ Testing Checklist

### HTML Validation
- [ ] All HTML files pass W3C validation
- [ ] Proper DOCTYPE declaration
- [ ] Semantic HTML5 elements used
- [ ] All images have alt attributes
- [ ] Forms have proper labels and structure

### CSS Validation
- [ ] CSS passes W3C validation
- [ ] No unused CSS rules
- [ ] Proper vendor prefixes where needed
- [ ] CSS is well-organized and commented

### Responsive Design Testing
- [ ] Desktop (≥1200px) - 4 cards per row
- [ ] Large Tablet (992-1199px) - 3 cards per row
- [ ] Tablet (768-991px) - 2 cards per row
- [ ] Mobile (<768px) - 1 card per row
- [ ] Navigation works on mobile
- [ ] All content readable on small screens
- [ ] Tables responsive on mobile
- [ ] Forms usable on mobile

### Browser Compatibility
- [ ] Google Chrome (latest)
- [ ] Mozilla Firefox (latest)
- [ ] Microsoft Edge (latest)
- [ ] Safari (if available)

### Functionality Checklist
- [ ] All navigation links work
- [ ] Smooth scrolling implemented
- [ ] Sticky navigation works
- [ ] All forms have proper validation
- [ ] All buttons have hover effects
- [ ] All images load properly
- [ ] Footer displays on all pages

### Design Requirements
- [ ] Consistent color theme across all pages
- [ ] Professional typography
- [ ] Proper spacing and alignment
- [ ] Hover effects on interactive elements
- [ ] Animations are smooth and not jarring
- [ ] Minimum 10 additional features implemented

### Performance
- [ ] Images optimized (reasonable file sizes)
- [ ] CSS file is organized and efficient
- [ ] No broken links
- [ ] Fast loading times

### Content Requirements
- [ ] Home page: Logo, Nav, Hero, 3 featured events, Stats, Footer ✓
- [ ] Events page: 8 event cards with all required details ✓
- [ ] Schedule page: 15+ row table with all columns ✓
- [ ] Speakers page: 6 speaker profiles with complete info ✓
- [ ] Registration page: Complete form with all fields ✓
- [ ] Contact page: Address, map, contact info, form, hours ✓

### Code Quality
- [ ] Code is properly indented
- [ ] Meaningful class names used
- [ ] Comments added where necessary
- [ ] File organization is logical
- [ ] No redundant or duplicate code

### GitHub & Submission
- [ ] All files uploaded to GitHub
- [ ] Folder structure is clean
- [ ] README.md created
- [ ] GitHub Pages enabled
- [ ] Live website is functioning
- [ ] Repository is public/accessible

### PDF Report
- [ ] Title page with Name, Reg No., Section
- [ ] Screenshots of all 6 pages
- [ ] Brief explanation of each page
- [ ] Design decisions documented
- [ ] Professional formatting

---

## 📦 Submission Checklist

### Before Submission (Final Review):

#### 1. GitHub Repository
- [ ] Create GitHub repository named "University-Events"
- [ ] Upload all HTML files
- [ ] Upload style.css
- [ ] Upload images folder with all assets
- [ ] Create README.md with:
  - Project title
  - Description
  - Technologies used
  - Features list
  - How to view (GitHub Pages link)
  - Author information
- [ ] Commit with meaningful messages
- [ ] Ensure repository is public

#### 2. GitHub Pages
- [ ] Go to Settings > Pages
- [ ] Select main branch
- [ ] Save and wait for deployment
- [ ] Test the live URL
- [ ] Verify all pages work
- [ ] Check all images load
- [ ] Test navigation
- [ ] Test on mobile (responsive check)

#### 3. PDF Report Creation
**Title Page:**
- Student Name
- Registration Number
- Section
- Course: Web Technologies (CS 311/CS 224)
- Instructor: Mr. Mohammad
- Semester: Summer 2026

**Content:**
- Screenshots of all 6 pages (desktop view)
- Additional screenshots (tablet/mobile views)
- Page descriptions:
  - Home Page: Purpose, features, design choices
  - Events Page: Grid layout, card design, features
  - Schedule Page: Table structure, styling approach
  - Speakers Page: Profile layout, design elements
  - Registration Page: Form fields, validation, styling
  - Contact Page: Information display, form design

**Technical Details:**
- Color theme used
- CSS techniques implemented
- Additional features list (10+)
- Responsive design approach
- Challenges faced and solutions

#### 4. Google Classroom Submission
**Private Comment:**
```
GitHub Repository: [Your repo URL]
GitHub Pages (Live): [Your live website URL]
```

**PDF Upload:**
- File name: StudentName_RegNo_WebTech_Assignment1.pdf
- Maximum 15 pages
- Professional formatting

#### 5. Final Checks Before Deadline
- [ ] Submission deadline: July 22, 2026
- [ ] Both links are accessible
- [ ] PDF is uploaded
- [ ] Private comment contains both URLs
- [ ] All files are in repository
- [ ] Live website is fully functional
- [ ] No broken links or images
- [ ] Code is clean and commented

---

## 📝 README.md Template

```markdown
# University Event Management Website

A fully responsive University Event Management Website for UET Peshawar, built using HTML5 and CSS3.

## 🎓 Academic Project

**Course:** Web Technologies (CS 311 / CS 224)  
**Semester:** Summer 2026  
**Instructor:** Mr. Mohammad  
**Institution:** University of Engineering & Technology, Peshawar

## 🌐 Live Demo

**GitHub Pages:** [View Live Website](https://yourusername.github.io/University-Events/)

## 📄 Pages

1. **Home** - Landing page with hero section, featured events, and statistics
2. **Events** - Grid of 8 event cards with details
3. **Schedule** - Event timetable in table format
4. **Speakers** - Profiles of 6 guest speakers
5. **Registration** - Event registration form
6. **Contact** - Contact information and inquiry form

## ✨ Features

- Fully Responsive Design (Desktop, Tablet, Mobile)
- Sticky Navigation Bar
- CSS Grid & Flexbox Layouts
- Smooth Scrolling
- Hover Effects & Animations
- Professional Color Theme
- Form Validation
- Accessible & Semantic HTML

### Additional Features Implemented
1. Hero Banner with gradient overlay
2. Statistics Section with animated counters
3. Timeline Design
4. Gallery Grid
5. Testimonials Section
6. FAQ Accordion
7. Sponsors Section
8. Newsletter Signup
9. Animated Buttons
10. Hover Overlay Images
11. Gradient Buttons
12. Card Animations

## 🛠️ Technologies Used

- HTML5
- CSS3
- No JavaScript (Pure CSS)

## 📱 Responsive Breakpoints

- Desktop: ≥992px (4 cards per row)
- Tablet: 768-991px (2 cards per row)
- Mobile: <768px (1 card per row)

## 🎨 Color Theme

Blue Professional Theme
- Primary: #1e3a8a
- Secondary: #3b82f6
- Accent: #60a5fa

## 📁 Project Structure

```
University-Events/
├── index.html
├── events.html
├── schedule.html
├── speakers.html
├── register.html
├── contact.html
├── style.css
├── images/
│   ├── logo/
│   ├── events/
│   ├── speakers/
│   └── hero/
└── README.md
```

## 👨‍💻 Author

**[Your Name]**  
Registration No: [Your Reg No]  
Section: [Your Section]

## 📝 License

This project is submitted as an academic assignment for UET Peshawar.

---

**Note:** This is a student project for academic purposes only.
```

---

## 🎯 Grading Criteria (20 Marks)

### Expected Breakdown:

1. **HTML Structure (3 marks)**
   - Proper semantic HTML5
   - All required pages present
   - Clean, well-indented code

2. **CSS Styling (4 marks)**
   - Professional design
   - Proper use of Flexbox & Grid
   - CSS variables and techniques
   - Single external stylesheet

3. **Responsive Design (4 marks)**
   - Works on all screen sizes
   - Proper breakpoints (4-2-1 layout)
   - Mobile-friendly navigation
   - Responsive tables and forms

4. **Required Components (4 marks)**
   - All page requirements met
   - 8+ event cards
   - 15+ schedule rows
   - 6+ speaker profiles
   - Complete registration form
   - Contact information

5. **Additional Features (3 marks)**
   - Minimum 10 features implemented
   - Quality animations and effects
   - Creative design elements

6. **Code Quality & Submission (2 marks)**
   - GitHub repository proper
   - GitHub Pages functional
   - PDF report complete
   - Clean, organized code

---

## 💡 Pro Tips

### Design Tips:
1. Use consistent spacing (multiples of 8px or 4px)
2. Limit font families to 2 (heading + body)
3. Use whitespace effectively
4. Keep color palette simple (3-5 colors)
5. Ensure good contrast for readability

### CSS Tips:
1. Use CSS variables for consistency
2. Mobile-first approach is easier
3. Use shorthand properties
4. Group related styles
5. Comment your CSS sections

### Performance Tips:
1. Optimize images (compress before upload)
2. Use appropriate image formats (JPG for photos, PNG for graphics)
3. Minimize CSS file (remove unused rules)
4. Use CSS sprites for icons if needed

### Common Mistakes to Avoid:
1. ❌ Inline styles (use external CSS only)
2. ❌ Fixed pixel widths (use percentages/rem)
3. ❌ Too many colors (stick to theme)
4. ❌ Unreadable font sizes on mobile
5. ❌ Missing alt attributes on images
6. ❌ Broken links or navigation
7. ❌ Inconsistent spacing
8. ❌ Poor contrast (text hard to read)

### GitHub Tips:
1. Commit frequently with clear messages
2. Test GitHub Pages link before submission
3. Check all images load from GitHub
4. Ensure paths are correct (case-sensitive)
5. Make repository public

---

## 📚 Resources

### Learning Resources:
- **HTML5:** [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **CSS3:** [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- **Flexbox:** [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- **Grid:** [CSS-Tricks Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Validation Tools:
- HTML Validator: https://validator.w3.org/
- CSS Validator: https://jigsaw.w3.org/css-validator/

### Color Tools:
- Coolors: https://coolors.co/
- Color Hunt: https://colorhunt.co/

### Image Resources (Free):
- Unsplash: https://unsplash.com/
- Pexels: https://www.pexels.com/
- Pixabay: https://pixabay.com/

---

## 📞 Support

If you encounter issues:
1. Check HTML/CSS validation first
2. Test responsiveness using browser DevTools
3. Review assignment requirements
4. Check GitHub Pages deployment status
5. Consult with instructor during office hours

---

## ✅ Final Notes

- Start early - don't wait until the last day
- Test frequently on different screen sizes
- Keep your code clean and organized
- Back up your work regularly
- Ask for help if needed
- Double-check submission requirements

**Remember:** This is an individual assignment. Any plagiarism will result in zero marks.

---

**Good luck with your assignment!** 🚀

---

**Last Updated:** July 22, 2026
