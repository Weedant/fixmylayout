FixMyLayout

> A Flutter-based tool that lets you place widgets in portrait mode and lock their position across device orientation changes.

Problem

Mobile and tablet layouts often break or shift when devices are rotated. FixMyLayout provides a drag-and-drop interface to place widgets and ensures consistent positioning in both portrait and landscape modes.

Features (MVP)

- Detect device orientation changes (portrait/landscape)
- Drag-and-drop widgets onto a layout canvas
- Lock widget positions relative to screen size
- Save & restore layouts locally
- Live preview across orientations

 Tech Stack

- Flutter – Cross-platform framework
- Dart – Programming language
- `MediaQuery`, `Stack`, `Positioned`, `OrientationBuilder` – Layout tools
- `SharedPreferences` – Local layout storage

Getting Started

```bash
flutter pub get
flutter run
