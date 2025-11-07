# Push-Up Counter App

A real-time push-up counter using AI-powered pose detection.

## 🎯 Current Status: Working Prototype (v0.1)

### Features
- ✅ Real-time pose detection using TensorFlow.js MoveNet
- ✅ Automatic push-up rep counting
- ✅ Visual skeleton overlay
- ✅ 60-second timed sessions
- ✅ Front-facing camera support
- ✅ Form feedback (down/up status)

## 🚀 Quick Start

1. Open `index.html` in a modern web browser (Chrome/Safari recommended)
2. Allow camera access when prompted
3. Position yourself 6-8 feet from camera (full body visible)
4. Press "Start Session" to begin
5. Perform push-ups - reps are counted automatically!

## 📋 Requirements

- Modern web browser with:
  - WebGL support
  - Camera access (getUserMedia API)
  - JavaScript enabled
- Internet connection (for loading TensorFlow.js libraries)

## 🎨 Design Vision

This is a prototype toward a full fitness gamification app featuring:
- Retro digital display aesthetic (pink/orange theme)
- Points/multiplier system
- Session history tracking
- Blockchain integration ("burn to earn")
- Social/leaderboard features

See `/designs` folder for UI mockups.

## 🛠️ Technical Stack

- **TensorFlow.js** - Machine learning framework
- **MoveNet Lightning** - Pose detection model
- **Vanilla JavaScript** - No framework dependencies
- **HTML5 Canvas** - Skeleton overlay rendering
- **WebRTC** - Camera access

## 🐛 Known Issues

- Works best in good lighting
- Requires full body in frame
- May struggle with very fast movements
- Calibration needed for different camera angles

## 📝 Roadmap

### Next Features:
- [ ] Form validation (body alignment checks)
- [ ] Sound effects on rep count
- [ ] Session history with localStorage
- [ ] Personal best tracking
- [ ] Multiple exercise types (squats, sit-ups)
- [ ] Difficulty levels
- [ ] Dashboard UI matching design mockups

### Future:
- [ ] Backend API for user accounts
- [ ] Blockchain wallet integration
- [ ] Mobile app (React Native)
- [ ] Multiplayer challenges

## 🧪 Development Notes

### Debugging
Use `diagnostic-test.html` to troubleshoot issues:
- Browser compatibility checks
- Camera access verification
- Network/CDN connectivity
- Library loading validation
- Model initialization testing

### Key Configuration
```javascript
CONFIG = {
    ELBOW_ANGLE_DOWN: 120,  // Bent elbow threshold
    ELBOW_ANGLE_UP: 140,    // Extended elbow threshold
    MIN_CONFIDENCE: 0.3,    // Pose detection confidence
    DEBOUNCE_FRAMES: 3,     // Anti-double-count delay
    SESSION_DURATION: 60    // Workout time in seconds
}
```

## 📄 License

MIT

## 🙏 Acknowledgments

- Built with TensorFlow.js and MoveNet by Google Research
- Inspired by fitness gamification and Web3 innovation
