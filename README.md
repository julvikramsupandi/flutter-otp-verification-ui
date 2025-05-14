# Flutter OTP Verification UI

A beautiful and modern Flutter UI implementation for OTP (One-Time Password) verification flow. This project showcases a clean and user-friendly interface for mobile number registration and OTP verification.

![OTP Verification UI](https://user-images.githubusercontent.com/37796466/120930941-a7e75e80-c719-11eb-9d4a-845eeed8497b.png)

## Features

- Clean and modern UI design
- Smooth navigation between screens
- Welcome screen with registration and login options
- Phone number input with country code
- 4-digit OTP verification with auto-focus
- Resend OTP functionality
- Custom illustrations for each screen
- Responsive layout
- Material Design components

## Screens

1. **Welcome Screen**
   - Initial landing page
   - Options to create account or login
   - Welcoming illustration

2. **Registration Screen**
   - Phone number input with country code (+62)
   - Input validation
   - Circular illustration

3. **OTP Verification Screen**
   - 4-digit OTP input boxes
   - Auto-focus on next input
   - Resend code option
   - Verification illustration

## Getting Started

### Prerequisites

- Flutter SDK (>=2.7.0 <3.0.0)
- Dart SDK
- Android Studio / VS Code

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/flutter-otp-verification-ui.git
   ```

2. Navigate to project directory
   ```bash
   cd flutter-otp-verification-ui
   ```

3. Install dependencies
   ```bash
   flutter pub get
   ```

4. Run the app
   ```bash
   flutter run
   ```

## Dependencies

- flutter_sdk
- cupertino_icons: ^1.0.2

## Project Structure

```
lib/
├── main.dart          # App entry point
├── welcome.dart       # Welcome screen
├── register.dart      # Registration screen
└── otp.dart          # OTP verification screen

assets/
└── images/           # Contains illustrations
```

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
