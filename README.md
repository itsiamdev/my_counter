# My Counter App

A simple yet modern Flutter application that implements an interactive counter using Material 3 and declarative widgets.

## Features

- **Material 3 UI**: Modern design featuring a color scheme based on `Colors.cyan`.
- **Interactive Counter**: Real-time counter increments using a floating action button (`FloatingActionButton`).
- **Widget Tests**: Integrated automated tests verifying the initial state and correct increment behavior.

## Screenshot

![My Counter App](assets/screenshots/my_counter_app.png)

## Project Structure

- `lib/main.dart`: Entry point of the application (`MyApp` and `MaterialApp` theme configuration).
- `lib/counter_page.dart`: Main screen (`CounterPage`) handling the counter state and Material 3 layout.
- `test/widget_test.dart`: Automated widget tests for counter functionality.

## How to Run the App

1. Ensure you have installed the [Flutter SDK](https://flutter.dev/docs/get-started/install).
2. Connect a physical device or start an emulator.
3. Run the following command in your terminal:
   ```bash
   flutter run
   ```

## Running Tests

To run the automated tests:
```bash
flutter test
```
