# library_app

<!-- A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference. -->
<!-- # Book Library -->

Book Library application where u can make simple CRUD operations (create, read, update, delete).
This application has a dark theme, the state is managed by the `ThemeNotifier` class and injected by the `Provider` package.
This simple application demonstrates the use of the `Provider` package in specific the `ChangeNotifierProvider`.
I make use of a simple model, together with a `Notifier` class which extends from `ChangeNotifier`.

## Showcase
### Phone
Light Theme        |  Dark Theme
:-------------------------:|:-------------------------:
![Showcase](showcase/showcase.gif)  | ![Showcase dark theme](showcase/showcase_dark.gif)

### Tablet
This project contains adaptive widgets, to display both on a phone and a tablet.

![Showcase Tablet](showcase/showcase_tablet.gif)

## Project
This project is mainly focused for Flutter users who would like to use the `Provider` package suggested by the Flutter team.
So in short this project contains following use cases:
* Use of a `extends ChangeNotifier` class
* Provide the `ChangeNotifier` class with `ChangeNotifierProvider` from the `Provider` package 
* Simple widget tests
* Dark and light theme, with the possibilty to switch at runtime
* Adaptive widgets to display on both a phone and tablet (master and details view)
* Use of assets
* Use of external fonts
* Logo generations by `flutter_launcher_icons` package
* Flutter version: `1.7.8+hotfix.3`

The Project is designed by Hemish,Jeel,Hemil.

### Tests

This Flutter app contains some simple widget tests to demonstrate the way you should handle widget tests in your Flutter app. These tests should be run every time you commit a change, if needed update the tests.
This will ensure the quality of your application.

#Output
![optimized-image](https://user-images.githubusercontent.com/110459633/232765480-186d007e-9c0e-4a4d-af44-91d4fb398edb.jpeg)
![optimized-image (4)](https://user-images.githubusercontent.com/110459633/232765486-7f1ed327-faa7-4e2b-b33f-e3c388cb8c98.jpeg)
![optimized-image (3)](https://user-images.githubusercontent.com/110459633/232765492-cbe7ee97-2ea6-4279-94fa-815fe4f27814.jpeg)
![optimized-image (2)](https://user-images.githubusercontent.com/110459633/232765495-e00397a1-5a24-4ce3-864b-673fc9a4e7fa.jpeg)
![optimized-image (1)](https://user-images.githubusercontent.com/110459633/232765497-617a58e0-159a-4d8e-87a3-5ebd910ee43b.jpeg)



## Getting Started

Clone this repo and look into the source code
```
git clone https://github.com/devrnt/book-library-flutter.git
```

### Application
```
flutter run 
```

### Tests

```
flutter test
```

## Packages
* [Provider](https://pub.dev/packages/provider)
* [smooth_star_rating](https://pub.dev/packages/smooth_star_rating)
* [image_test_utils](https://pub.dev/packages/image_test_utils)
* [smooth_star_rating](https://pub.dev/packages/smooth_star_rating)
* [flutter_speed_dial](https://pub.dev/packages/flutter_speed_dial)
* [flutter_launcher_icons](https://pub.dev/packages/flutter_launcher_icons)
