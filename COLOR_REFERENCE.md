# Dark Mode UI - Color Reference Guide

## Color Palette

### Primary Colors (Unchanged)
- **Primary Accent**: #6366f1 (Indigo) - Used for buttons, links, highlights
- **Secondary Accent**: #ec4899 (Pink) - Used in gradients

### Dark Mode Background Colors
```
#0f172a - Dark Surface (Main background)
#1e293b - Dark Secondary (About section, cards)
#334155 - Dark Tertiary (Header, hero gradients)
```

### Dark Mode Text Colors
```
#f1f5f9 - Primary Text (Main content)
#cbd5e1 - Secondary Text (Descriptions, muted content)
```

### Dark Mode UI Elements
```
#475569 - Border Color (Subtle section dividers)
#1e293b - Card Background (Feature cards, stats)
```

## Section Styling

### Header
- **Background**: Linear gradient from #1e293b to #334155
- **Logo Color**: #6366f1 (Primary)
- **Text Color**: #f1f5f9 (Primary text)
- **Border**: 1px solid #475569

### Hero Section
- **Background**: Linear gradient from #1e293b to #334155
- **Title Color**: #f1f5f9
- **Subtitle Color**: #cbd5e1
- **Button**: #6366f1 background with white text
- **Border**: 1px solid #475569

### Features Section
- **Background**: #0f172a
- **Card Background**: #1e293b
- **Card Border**: 1px solid #475569
- **Card Hover**: Border changes to #6366f1
- **Title Color**: #f1f5f9
- **Description Color**: #cbd5e1

### About Section
- **Background**: #1e293b
- **Card Background**: #1e293b
- **Stat Numbers**: #6366f1
- **Text Color**: #cbd5e1
- **Border**: 1px solid #475569

### Contact Section
- **Background**: #0f172a
- **Input Background**: #1e293b
- **Input Text**: #f1f5f9
- **Input Border**: 1px solid #475569
- **Input Focus**: Border #6366f1 with glow effect
- **Button**: Gradient #6366f1 to #ec4899

### Footer
- **Background**: #0f172a
- **Text Color**: #f1f5f9
- **Link Color**: #cbd5e1 (hover: #6366f1)
- **Border**: 1px solid #475569

## Accessibility Features
- ✅ WCAG AA contrast ratios met
- ✅ Clear focus states with primary color
- ✅ Readable text on all backgrounds
- ✅ Smooth transitions for visual feedback
- ✅ Proper hover states for interactive elements

## Implementation Details
- All colors use CSS variables for easy maintenance
- Smooth transitions (0.3s ease) on all interactive elements
- Box shadows adjusted for dark mode visibility
- Borders added for better section separation
- Responsive design maintained across all breakpoints
