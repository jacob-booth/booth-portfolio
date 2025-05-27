# 📸 Assets Directory

This directory contains all visual content for the BOOTH Portfolio showcase.

## 📁 Directory Structure

```
assets/
├── screenshots/     # Static images of the website
├── demos/          # Animated GIFs and videos
├── branding/       # Logos and design assets
└── README.md       # This file
```

## 🎯 How to Add Content

### **Taking Screenshots**

1. **Run your portfolio locally**:
   ```bash
   # Navigate to your private repository
   cd ../vcard-personal-portfolio
   
   # Start a local server
   npx serve . -p 3000
   # OR use Live Server extension in VS Code
   ```

2. **Open in browser**: http://localhost:3000

3. **Take screenshots**:
   - **Desktop**: Full window at 1920x1080
   - **Mobile**: Use browser dev tools responsive mode (375px width)
   - **Features**: Individual components and animations

### **Creating Animated Demos**

1. **Download ScreenToGif** (Windows): https://www.screentogif.com/
2. **Record interactions**:
   - Mouse hovering over elements
   - Particle system responding to cursor
   - Smooth scrolling and animations
   - Mobile touch interactions

3. **Optimize GIFs**:
   - Keep under 2MB for GitHub
   - 3-8 seconds duration
   - Smooth loops

### **Adding to README**

Once you have visual content, update the main README.md:

```markdown
### 🖥️ **Desktop Experience**
![BOOTH Portfolio Desktop](./assets/screenshots/desktop-preview.png)

### 📱 **Mobile Experience**  
![BOOTH Portfolio Mobile](./assets/screenshots/mobile-preview.png)

### ✨ **Animations Demo**
![Particle System](./assets/demos/particles-demo.gif)
```

## 🚀 Quick Start

1. **Navigate to your private repo**: `cd ../vcard-personal-portfolio`
2. **Start local server**: `npx serve . -p 3000`
3. **Take screenshots** of your amazing portfolio
4. **Save to appropriate folders** in this assets directory
5. **Update the main README.md** with image paths
6. **Commit and push** to see your visual showcase!

Your stealth mode repository will transform from text-only to a compelling visual preview that showcases the incredible work you've built! 🎨✨ 