# EcoLearn Platform Design Guidelines

## Design Approach
**Reference-Based Approach** inspired by educational platforms like Khan Academy and gamified learning platforms like Duolingo, with eco-conscious design elements reminiscent of sustainability-focused brands.

## Core Design Elements

### Color Palette
**Primary Colors:**
- Light Mode: 142 69% 58% (vibrant green)
- Dark Mode: 142 45% 70% (softer green)

**Supporting Colors:**
- Earth Brown: 25 65% 35%
- Sky Blue: 200 85% 60%
- Neutral Grays: 220 10% 95% (light), 220 15% 20% (dark)

**Accent Colors (minimal use):**
- Achievement Gold: 45 95% 65% (badges only)
- Alert Red: 0 70% 55% (warnings)

### Typography
- **Primary:** Inter (Google Fonts)
- **Headings:** Inter Semi-bold (600)
- **Body:** Inter Regular (400)
- **UI Elements:** Inter Medium (500)

### Layout System
**Tailwind Spacing Units:** Consistently use 2, 4, 6, 8, 12, and 16 units
- Small elements: p-2, m-2
- Standard spacing: p-4, gap-4
- Section spacing: py-8, my-8
- Large layouts: p-12, gap-16

## Component Library

### Navigation
- Clean header with EcoLearn logo, main navigation, and user profile
- Sidebar navigation for dashboard areas
- Breadcrumb navigation for deep content

### Gamification Elements
- **Progress Bars:** Rounded corners, animated fills in primary green
- **Badge Cards:** Circular badges with nature-inspired icons
- **Point Counters:** Prominent display with leaf/tree iconography
- **Leaderboards:** Card-based layout with ranking indicators

### Educational Components
- **Challenge Cards:** Image headers, clear CTAs, difficulty indicators
- **Quiz Interface:** Clean question layout, multiple choice styling
- **Learning Modules:** Expandable sections, progress tracking

### Data Displays
- **Carbon Tracker:** Visual charts with green color gradients
- **Achievement Timeline:** Vertical timeline with milestone markers
- **Statistics Dashboard:** Grid layout with metric cards

## Visual Treatments

### Gradients
- Hero sections: Subtle green to blue gradients (142 69% 58% to 200 40% 65%)
- Cards: Very subtle gray gradients for depth
- Buttons: Gentle hover state gradients

### Background Treatments
- Light, nature-inspired patterns (subtle leaf textures)
- Soft gradient overlays on hero sections
- Clean white/dark backgrounds for content areas

### Animations
**Minimal and purposeful:**
- Subtle hover states on interactive elements
- Progress bar animations for achievements
- Gentle fade-in for new content loading

## Images
### Hero Image
Large hero image featuring diverse students in nature/school environment engaging in eco-activities. Place prominently on landing page.

### Supporting Images
- Challenge thumbnails: Nature scenes, recycling activities, renewable energy
- Student avatars: Diverse, friendly cartoon-style illustrations
- Achievement graphics: Nature-themed icons (leaves, trees, earth)
- Background elements: Subtle environmental patterns, eco-friendly illustrations

### Image Placement
- Hero: Full-width header image with overlay text
- Dashboard: Small profile images and achievement badges
- Challenges: Card header images (16:9 aspect ratio)
- About sections: Side-by-side image and text layouts

## Accessibility
- Maintain WCAG AA contrast ratios
- Consistent dark mode across all components including forms
- Clear focus indicators with green outline
- Readable font sizes (minimum 16px for body text)

## Key Design Principles
1. **Educational Focus:** Clean, distraction-free layouts prioritizing content
2. **Gamified Engagement:** Playful elements without overwhelming the interface
3. **Eco-Conscious:** Green-centric palette reflecting environmental values
4. **Student-Friendly:** Age-appropriate design with clear visual hierarchy
5. **Mobile-First:** Responsive design optimized for tablet and mobile usage