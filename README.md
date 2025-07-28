# 💖 Romantic Birthday Website

A stunning, animated birthday website created with pure HTML, CSS, and JavaScript for your special someone.

## ✨ Features

- **🎨 Beautiful Design**: Romantic theme with soft pink, lavender, and pastel gradients
- **⏰ Countdown Timer**: Counts down to July 29, 12:00 AM
- **🖼️ Image Carousel**: Full-screen slideshow with all your images
- **📱 Mobile Responsive**: Works perfectly on all devices
- **✨ 100+ Animations**: Text reveals, hover effects, parallax, and more
- **💫 Particle Effects**: Floating hearts, twinkling stars, and background particles
- **🎵 Music Player**: Optional background music (you can add your own file)
- **🚀 Performance Optimized**: Lazy loading and smooth animations

## 🚀 Deployment to Firebase

### Quick Start (3 Steps)

1. **Install & Login**:
   ```bash
   npm install -g firebase-tools
   firebase login
   ```

2. **Initialize Project**:
   ```bash
   firebase init hosting
   ```
   - Choose "Create a new project"
   - Public directory: `.` (current directory)
   - Single-page app: `Y` (Yes)
   - Overwrite index.html: `N` (No)

3. **Deploy**:
   ```bash
   firebase deploy
   ```

### Your Website URL
After deployment, your website will be live at: `https://your-project-id.web.app`

### Detailed Guide
For step-by-step instructions with screenshots and troubleshooting, see `DEPLOYMENT_GUIDE.md`

## 🎵 Background Music

The website includes `abc.mp3` as background music. To change it:

1. Replace `abc.mp3` with your own music file
2. Update the audio source in `index.html`:
   ```html
   <source src="your-music-file.mp3" type="audio/mpeg">
   ```

## 🎨 Customization

### Changing the Birthday Date
Edit the `birthdayDate` variable in the JavaScript:
```javascript
const birthdayDate = new Date('2025-07-29T00:00:00');
```

### Adding More Images
Simply add more image paths to the `images` array in the JavaScript section.

### Modifying Colors
Update the CSS variables and gradient colors in the `<style>` section.

## 📱 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎉 Features Included

- **Loading Animation**: Beautiful spinner while content loads
- **Particle Background**: Animated floating particles
- **Floating Hearts**: Hearts that float up the screen
- **Twinkling Stars**: Starry background effect
- **Countdown Timer**: Real-time countdown with heartbeat animation
- **Image Carousel**: Auto-advancing slideshow with navigation
- **Image Grid**: Hover effects and overlays
- **Scroll Animations**: Elements animate as you scroll
- **Music Player**: Background music with controls
- **Responsive Design**: Perfect on mobile and desktop
- **Performance Optimized**: Lazy loading and smooth animations

## 💝 Perfect for Your Special Someone

This website is designed to be:
- **Romantic**: Soft colors and loving messages
- **Interactive**: Multiple animations and effects
- **Personal**: Uses all your special photos
- **Memorable**: Creates a unique birthday experience

Enjoy creating this special moment for your loved one! 💖 "# temp" 
