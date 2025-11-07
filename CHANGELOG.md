# Changelog

All notable changes to this project will be documented in this file.

## [0.1.0] - 2025-11-06

### Added
- Initial working prototype
- Real-time pose detection using TensorFlow.js MoveNet
- Push-up rep counting based on elbow angle analysis
- Visual skeleton overlay with green glowing lines
- 60-second timed workout sessions
- Rep counter display
- Down/up status indicator
- Screen flash visual feedback on successful rep
- Debug mode for angle visualization
- Front-facing camera support
- Mirrored video for natural movement
- Responsive layout (mobile-friendly)

### Technical
- TensorFlow.js v4.11.0 integration
- MoveNet Lightning model for fast pose detection
- Fixed async initialization issue (await tf.ready())
- Canvas-based skeleton rendering
- State machine for rep detection with debouncing
- Configurable angle thresholds

### Known Issues
- Requires good lighting conditions
- Full body must be visible in frame
- May have reduced accuracy with fast movements
