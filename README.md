# 🎮 JS DOOM - Browser DOOM Experience

<div align="center">
  
![DOOM Logo](https://www.howtogeek.com/wp-content/uploads/2012/02/dosbox-header.png?width=1198&trim=1,1&bg-color=000&pad=1,1)

**Experience the classic 1993 DOOM game directly in your browser!**

*Built with JS-DOS API for authentic DOSBox emulation*

</div>

---

## 🚀 **Features**

### 🖥️ **Cross-Platform Gaming**
- **Desktop Support**: Full keyboard controls with visual reference guide
- **Mobile Optimized**: Touch controls with virtual D-pad and action buttons
- **Responsive Design**: Automatic device detection and appropriate interface
- **Canvas Scaling**: Maintains game aspect ratio across all screen sizes

### 📱 **Mobile Touch Controls**
- **Movement D-Pad**: 4-directional virtual joystick for precise movement
- **Action Buttons**: 
  - 🔴 **FIRE** (Ctrl) - Primary weapon firing
  - 🟢 **USE** (Space) - Activate switches, open doors
  - 🟡 **RUN** (Shift) - Sprint modifier
  - 🔵 **STRAFE** (Alt) - Side movement modifier
- **Utility Controls**:
  - **MENU** (Escape) - Access game menus
  - **MAP** (Tab) - View automap
  - **START** (Enter) - Start game/confirm selections

### ⌨️ **Desktop Controls**
| **Movement** | **Key** | **Actions** | **Key** |
|-------------|---------|-------------|---------|
| Move Forward | ↑ | Fire | Ctrl |
| Move Backward | ↓ | Use/Open | Space |
| Turn Left | ← | Menu | Esc |
| Turn Right | → | Map | Tab |
| Run | Shift | Start/Enter | Enter |
| Strafe | Alt | | |

### 🎨 **Modern Interface**
- **Interactive Overlay**: CSS-animated "Click to Play" message
- **Gradient Backgrounds**: Modern visual design
- **Responsive Layout**: Optimized for mobile and desktop
- **Touch Feedback**: Visual button press animations
- **Clean Typography**: Improved readability and accessibility

### 🔧 **Technical Features**
- **JS-DOS Integration**: Authentic DOSBox emulation
- **Canvas Optimization**: Prevents overflow and cropping issues
- **Memory Management**: Proper event cleanup and key state management
- **Cross-Browser Support**: Works on modern browsers
- **Performance Optimized**: Efficient touch event handling

---

## 🎯 **How to Play**

### **Desktop:**
1. Open the page in your browser
2. Click the animated "🎮 CLICK TO PLAY" overlay
3. Use keyboard controls (reference table shown below game)
4. Enjoy classic DOOM gameplay!

### **Mobile:**
1. Open the page on your mobile device
2. Tap the "🎮 CLICK TO PLAY" overlay
3. Use touch controls (automatically displayed below game)
4. Hold and drag the D-pad for movement
5. Tap action buttons for firing, using items, etc.

---

## 🛠️ **Technology Stack**

- **Emulation**: JS-DOS API (DOSBox in JavaScript)
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Game**: Ultimate DOOM (1993) - Classic FPS
- **Controls**: Touch events, Keyboard events, Canvas interaction
- **Responsive**: CSS Grid, Flexbox, Media queries

---

## 📂 **Project Structure**

```
jsdoom/
├── index.html          # Main game interface
├── script.js           # JS-DOS API implementation
├── style.css           # Game overlay and basic styling
├── styles/
│   └── button.css      # Additional button styles
├── components/
│   └── js-dos-apiv3.js # JS-DOS library
├── roms/
│   └── ultimate-doom.zip # Game files
└── assets/
    └── img/
        └── overlay.png  # (Legacy - now CSS-based)
```

---

## 🎮 **About**

This project brings the legendary 1993 DOOM experience to modern browsers using the JS-DOS API. It features:

- **Authentic Emulation**: Real DOSBox running Ultimate DOOM
- **Modern Interface**: Touch controls and responsive design
- **Cross-Platform**: Works on desktop and mobile devices
- **No Installation**: Runs directly in browser
- **Classic Gaming**: Full DOOM experience with all original features

Perfect for retro gaming enthusiasts and anyone wanting to experience this gaming milestone!

---

## 🔥 **Experience Classic DOOM Today!**

*Rip and tear through Mars facilities, battle demons, and save humanity - all from your browser!*
