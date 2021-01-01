# tutorials

Basic flutter app using dark theme.

## Getting Started

This is basic flutter app with dark theme in flutter.
I created this app for YouTube tutorial.
```dart
bool _isDark = false;
  ThemeData _light = ThemeData.light().copyWith(
    primaryColor: Colors.green,
  );
  ThemeData _dark = ThemeData.dark().copyWith(
    primaryColor: Colors.blueGrey,
  );
```
```dart
MaterialApp(
    darkTheme: _dark,
    theme: _light,
    themeMode: _isDark ? ThemeMode.dark : ThemeMode.light,
    title: 'Flutter Theme',
    home:Scaffold()
  )
```
A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
