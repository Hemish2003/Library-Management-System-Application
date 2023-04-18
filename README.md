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

![optimized-image (7)](https://user-images.githubusercontent.com/110459633/232771754-e91465b2-63b0-4677-ba30-9ad9e09a8b3b.jpeg)
![optimized-image (6)](https://user-images.githubusercontent.com/110459633/232771763-f42af247-39cb-4fb4-8671-70de2fe1c43a.jpeg)
![optimized-image (5)](https://user-images.githubusercontent.com/110459633/232771766-c757335d-de03-47a5-a12c-013365bd03b0.jpeg)
![optimized-image (9)](https://user-images.githubusercontent.com/110459633/232771769-80d033a6-a21a-45da-90ff-67362c6b2260.jpeg)
![optimized-image (8)](https://user-images.githubusercontent.com/110459633/232771774-b9e9ff0c-f543-47f8-9b89-ef12ff660485.jpeg
![optimized-image](https://user-images.githubusercontent.com/110459633/232772427-c860fca6-fb09-4b30-ae57-aca9f5ad5a83.jpeg)
![optimized-image (2)](https://user-images.githubusercontent.com/110459633/232772435-b196af97-f3d2-4f45-a5f6-a9ffd98eed0f.jpeg)
![optimized-image (1)](https://user-images.githubusercontent.com/110459633/232772439-0ddcc9b3-86fa-4d4e-8552-ccaf74f79636.jpeg)
)


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
