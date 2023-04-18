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
![IMG-20230411-WA0021](https://user-images.githubusercontent.com/110459633/232764143-c0d72ad4-36f6-4858-b17e-9339d2ef43e2.jpg)
![IMG-20230411-WA0022](https://user-images.githubusercontent.com/110459633/232764183-fed774e1-8de4-4ad2-96a4-82ee7d8427fd.jpg)
![IMG-20230411-WA0014](https://user-images.githubusercontent.com/110459633/232764197-1f164814-d4f6-4d4d-beb3-b086b2eabad1.jpg)
![IMG-20230411-WA0016](https://user-images.githubusercontent.com/110459633/232764230-4fe95c11-9d97-42f4-a203-fcd7bf922fd7.jpg)
![IMG-20230411-WA0017](https://user-images.githubusercontent.com/110459633/232764240-44a7283e-9d92-42f0-9b11-f15615cd579a.jpg)
![IMG-20230411-WA0019](https://user-images.githubusercontent.com/110459633/232764266-2dbc494a-f844-453a-83d5-bedf769c43f6.jpg)
![IMG-20230411-WA0020](https://user-images.githubusercontent.com/110459633/232764274-598903f3-8610-4de5-ac7b-0c0789d6dfd9.jpg)
![IMG-20230411-WA0018](https://user-images.githubusercontent.com/110459633/232764283-8d6809a4-fb48-469a-bbdc-06621cb175dd.jpg)


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
