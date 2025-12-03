# 120 Fruit Therapy - Sparkling Gold Features Documentation

This document outlines the new sparkling gold features added to the 120 Fruit Therapy website.

## Features Implemented

### 1. ✨ Sparkling Gold Diagonal Straw in Logo
- **Location**: Header and Footer
- **Description**: A diagonal sparkling gold straw appears next to the "120" logo
- **Features**:
  - Animated SVG straw with gold gradient
  - Diagonal positioning from left to right
  - Bent tip pointing to the right
  - Sparkle animation with rotating circles
  - Shimmer effect that pulses continuously
  - Responsive design for mobile devices

### 2. 📸 Special Plan Menu Image Upload Section
- **Location**: Admin Settings > Special Plan Menu Icons
- **Description**: Upload custom images for special plan menu categories
- **Features**:
  - Upload fields for:
    - 🍎 Weight Loss
    - 💪 Weight Gain
    - ❤️ Libido
    - ⚖️ Weight Maintenance
  - Image preview functionality
  - Falls back to emoji icons if no image is uploaded
  - Images appear on landing page special plan menu section

### 3. ✦ Sparkling Gold Footer Links
- **Location**: Footer section
- **Description**: All footer links now have sparkling gold styling
- **Features**:
  - Gold color by default (not just on hover)
  - Continuous shimmer animation
  - Rotating sparkle icon (✦) appears on hover
  - Smooth color transitions
  - Enhanced glow effects on hover

### 4. 💬 Chat Icon with Place Order Popup
- **Location**: Bottom right corner (floating button)
- **Description**: Replaced shopping cart with chat icon
- **Features**:
  - Chat emoji icon (💬) instead of cart
  - Gold gradient background with sparkle
  - "Place Order" popup with gold styling
  - Bouncing animation on popup
  - Rotating border effect
  - Wiggle animation on hover
  - Pulsing glow effect

### 5. ✨ Lively Sparkling Gold Icons
- **Location**: Throughout the site (all sections)
- **Description**: All icons now have sparkling gold effects
- **Affected Sections**:
  - Menu section cards
  - Special plans cards
  - Wellness events
  - Contact cards
  - Gift packages
- **Features**:
  - Gold drop-shadow effects
  - Continuous sparkle animation
  - Scale and rotation on hover
  - Enhanced glow with white highlights
  - Wiggle animation on interaction

### 6. 🌟 Follow Us Section - Sparkling Gold Social Icons
- **Location**: Footer social media icons
- **Description**: Instagram and TikTok icons with gold styling
- **Features**:
  - Gold gradient backgrounds by default
  - Pulsing animation continuously
  - Rotating border effect
  - Scale and rotate on hover
  - Special hover effects maintained:
    - Instagram: Gradient background
    - TikTok: Black background with gold border
  - Enhanced glow effects

### 7. 🖼️ Hero Section - Image Upload Alternative
- **Location**: Admin Settings > General Settings
- **Description**: Choose between video or image for hero section
- **Features**:
  - Hero Display Mode selector (Video/Image)
  - Hero Image upload field
  - Hero Video upload field
  - Image preview in admin
  - Seamless switching between video and image
  - Same overlay effects for both options

## Admin Settings Guide

### Accessing Settings
1. Log in to WordPress admin
2. Navigate to "120 Fruit Therapy" in the sidebar
3. Click on "120 Fruit Therapy Settings"

### Uploading Images

#### Special Plan Menu Icons
1. Scroll to "Special Plan Menu Icons" section
2. Click "Upload" button for the desired category
3. Select image from media library or upload new
4. Click "Save Settings"

#### Hero Section
1. Scroll to "General Settings" section
2. Select "Hero Display Mode" (Video or Image)
3. For Image mode:
   - Click "Upload Image" under "Hero Image"
   - Select image from media library
4. For Video mode:
   - Click "Upload Video" under "Hero Video"
   - Select video file
5. Click "Save Settings"

## Color Reference

All sparkling gold effects use these color values:
- Primary Gold: `#FFD700`
- Light Gold: `#FFEB3B`
- Dark Gold: `#FFC107`
- Gold Glow: `rgba(255, 215, 0, 0.4-0.9)`
- White Highlights: `rgba(255, 255, 255, 0.4-0.8)`

## Animations

### Shimmer Effect
- Duration: 2-3 seconds
- Type: Ease-in-out infinite
- Effect: Color transitions and glow pulsing

### Sparkle Rotation
- Duration: 2-3 seconds
- Type: Linear infinite
- Effect: Rotating border gradients

### Wiggle Effect
- Duration: 0.5-0.6 seconds
- Type: Ease-in-out
- Effect: Scale and rotation on hover

### Icon Sparkle
- Duration: 2 seconds
- Type: Ease-in-out infinite
- Effect: Scale and glow pulsing

## Browser Support

All features are compatible with:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Accessibility

- All animations respect `prefers-reduced-motion` settings
- Proper ARIA labels maintained
- Keyboard navigation supported
- Screen reader friendly

## Performance

- CSS animations used for better performance
- SVG for crisp graphics at any size
- Minimal JavaScript dependencies
- Optimized for mobile devices

## Troubleshooting

### Icons not showing gold color
- Clear browser cache
- Check CSS is loading correctly
- Verify plugin is activated

### Straw not appearing
- Check browser console for errors
- Verify SVG is rendering
- Test in different browser

### Images not uploading
- Check WordPress media permissions
- Verify file size limits
- Check file format (JPG, PNG, GIF, WebP)

### Hero image not displaying
- Verify "Hero Display Mode" is set to "Image"
- Check image URL is correct
- Ensure image is uploaded successfully
- Clear cache and refresh page

## Future Enhancements

Potential additions for future updates:
- Custom color picker for gold variations
- Animation speed controls
- Additional icon animation styles
- More hero layout options
- Advanced sparkle patterns
