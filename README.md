📷 Flutter OCR App

This Flutter app demonstrates Optical Character Recognition (OCR) using the camera (live scanning) and by selecting an image from the gallery. It leverages:

flutter_scalable_ocr
 for real-time camera text recognition.

google_mlkit_text_recognition
 for image-based text recognition.

image_picker
 to select images from the gallery.

🚀 Features

🔦 Live Camera OCR with torch toggle, lock camera, and switch between front/rear cameras.

🖼️ Pick image from gallery and extract text using ML Kit.

📄 Result Screen shows the selected image with recognized text displayed below.

✅ Clean architecture: separate functions for image picking and text recognition.

📸 Screenshots

(Add your app screenshots here – one with live camera OCR and one with gallery image + text result.)

🛠️ Getting Started
1. Clone the repository
git clone https://github.com/your-username/flutter-ocr-app.git
cd flutter-ocr-app

2. Install dependencies
flutter pub get

3. Update pubspec.yaml (already included)
dependencies:
  flutter:
    sdk: flutter
  flutter_scalable_ocr: ^2.0.1
  image_picker: ^1.1.2
  google_mlkit_text_recognition: ^0.13.0

4. Run the app
flutter run

📂 Project Structure
lib/
 ├── main.dart          # Entry point, OCR logic, and UI
 ├── result_screen.dart # Displays image + recognized text

📱 Usage

Launch the app.

Use the camera OCR to detect text live.

Or tap Pick Image from Gallery → select an image.

The app navigates to a new screen showing:

The selected image.

The recognized text below.

⚡ Requirements

Flutter SDK (3.x recommended)

Android Studio / VS Code

Device/emulator with a camera (for live OCR)
