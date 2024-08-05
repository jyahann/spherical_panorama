# Panorama

A 360-degree panorama viewer.

This package is an updated porting of the plugin https://github.com/zesage/panorama.

## Getting Started

Import and add the Panorama widget to your project.

```dart
import 'package:spherical_panorama/panorama.dart';
... ...
  
@override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: Panorama(
          child: Image.asset('assets/panorama360.jpg'),
        ),
      ),
    );
  }
```