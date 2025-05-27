# 🚀 Run Portfolio Locally for Screenshots

## Quick Commands to Start Your Portfolio

### **Option 1: Using npx serve (Recommended)**

```bash
# Navigate to your private portfolio directory
cd ../vcard-personal-portfolio

# Start local server on port 3000
npx serve . -p 3000

# Open in browser: http://localhost:3000
```

### **Option 2: Using Python (if installed)**

```bash
# Navigate to your private portfolio directory
cd ../vcard-personal-portfolio

# Python 3
python -m http.server 3000

# Python 2
python -m SimpleHTTPServer 3000

# Open in browser: http://localhost:3000
```

### **Option 3: Using VS Code Live Server**

1. Open `vcard-personal-portfolio` folder in VS Code
2. Install "Live Server" extension if not already installed
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. Browser will open automatically

### **Option 4: Using Node.js (if package.json exists)**

```bash
# Navigate to your private portfolio directory
cd ../vcard-personal-portfolio

# If you have a start script
npm start

# Or if you have serve installed globally
serve . -p 3000
```

## 📸 **Ready for Screenshots!**

Once your server is running:

1. **Desktop Screenshots**:
   - Open browser to http://localhost:3000
   - Set window to 1920x1080 (or your preferred size)
   - Take full-page screenshots

2. **Mobile Screenshots**:
   - Press F12 to open DevTools
   - Click device toggle icon (mobile view)
   - Select iPhone/Android size (375px width recommended)
   - Take screenshots of mobile experience

3. **Feature Demos**:
   - Use ScreenToGif to record interactions
   - Show particle system responding to mouse
   - Demonstrate cursor effects and animations
   - Capture smooth scrolling behavior

4. **Performance Screenshots**:
   - Run Lighthouse audit in Chrome DevTools
   - Screenshot the performance scores
   - Show optimization results

## 🎯 **Screenshot Checklist**

- [ ] **Hero section** - Full desktop view
- [ ] **Mobile navigation** - Responsive design
- [ ] **Glassmorphism cards** - UI components
- [ ] **Particle system** - Interactive background
- [ ] **Custom cursor** - Magnetic effects
- [ ] **Lighthouse scores** - Performance metrics
- [ ] **Animations** - GSAP effects in action
- [ ] **Cross-browser** - Chrome, Firefox, Safari

Save all screenshots to the `assets/screenshots/` and `assets/demos/` directories in this public repository, then update the main README.md to showcase your amazing work! 🎨 