# Project Documentation

## Overview
This project appears to be a web application with multiple components including a Flutter web app, HTML pages, and various JavaScript and CSS assets. The codebase indicates it's a client-side application with features for user interaction, animations, and data visualization.

## Directory Structure
- `/` - Root directory containing main entry points and configuration
- `/lestey` - Main application HTML pages and assets
- `/rid` - Flutter web application
- `/video` - Video-related content
- `/cdnjs.cloudflare.com` - CDN-hosted third party libraries

## Key Components

### Frontend UI
- Multiple HTML pages with Bootstrap styling
- Font Awesome icons integration
- AOS animations library for scroll effects
- Jquery for DOM manipulation
- Magnific Popup for modal windows

### Flutter Web App
Located in `/rid` directory:
- Main Dart application code
- Asset handling
- CanvasKit WebGL rendering
- Service worker for offline functionality

### Third Party Libraries
- Bootstrap 4.x
- Font Awesome 5.x 
- jQuery 1.4.1+
- AOS 2.3.4
- Magnific Popup 1.1.0

## Configuration
The application uses configuration files for:
- Font loading (FontManifest.json)
- Asset management (AssetManifest.json) 
- Service worker setup (flutter_service_worker.js)
- Version control (version.json)

## Building & Deployment
The Flutter web app requires:
1. Flutter SDK setup
2. Build web assets (`flutter build web`)
3. Deploy static files to web server

## Browser Support
- Modern browsers with WebGL support
- Service worker capabilities for offline mode
- JavaScript enabled

## Dependencies
See `manifest.json` and package files for complete dependency list.

The application combines traditional web technologies with Flutter web for an enhanced user experience. Care should be taken when updating dependencies due to the mixed technology stack.
