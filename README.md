# Flutter Simple Calculator

A basic calculator application built using Flutter that performs arithmetic operations like addition, subtraction, multiplication, and division on two user-input numbers.

---

## Features

*  Input two numbers using TextFields
*  Addition
*  Subtraction
*  Multiplication
*  Division
*  Displays result instantly
* Clean and user-friendly UI

---

##  Technologies Used

* Flutter
* Dart

---

##  Project Structure

```id="h2k8sl"
lib/
 └── main.dart
```

---

##  Getting Started

Follow these steps to run the project locally:

### Prerequisites

* Install Flutter SDK
* Install Android Studio or VS Code
* Set up an emulator or connect a physical device

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-simple-calculator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-simple-calculator
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

---

##  How It Works

* Two `TextField` widgets are used to accept numeric input from the user
* Input values are parsed into numbers
* Buttons trigger arithmetic operations:

  * Addition (`+`)
  * Subtraction (`-`)
  * Multiplication (`×`)
  * Division (`÷`)
* The result is displayed using a `Text` widget
* `setState()` updates the UI dynamically

---

## Notes

* Ensure valid numeric input to avoid errors
* Handle division by zero to prevent crashes

---

##  Future Improvements

* Add input validation and error messages
* Improve UI with grid-style calculator layout
* Add more operations (%, square root, etc.)
* Add history of calculations
* Support dark mode

---

##  Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

##  Author

Riya Patani

---
