## 0.0.1 - Initial Release (April 2025)

### Features
* Initial implementation of image to 3D model conversion
* AR visualization for 3D models using ARKit (iOS) and ARCore (Android)
* Face AR for glasses try-on (iOS only)
* Comprehensive error handling and platform compatibility checks
* Example app demonstrating all features

### Components
* `ImageTo3DConverter` - Convert 2D images to 3D models
* `ARViewer` - Display 3D models in AR environment
* `FaceARViewer` - Try on glasses in AR using face tracking (iOS only)
* `ModelData` - Data model for 3D models
* `FileUtils` - Utility functions for file operations
* `Flutter3dArConverter` - Main package class with initialization and platform checks

### Platform Support
* iOS 11.0+ (iOS 12.0+ recommended for face tracking)
* Android with ARCore support (Android 7.0+ with Google Play Services for AR)

### Known Limitations
* Face tracking is only available on iOS devices
* Current implementation uses placeholder 3D models
* Integration with real 3D conversion services required for production use
