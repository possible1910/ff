# STAYPAID

A native iOS WebView application that opens **https://github.com** with Face ID authentication, Dark Mode support, pull-to-refresh, and a native navigation interface.

## Features

- 🔒 Face ID / Touch ID authentication
- 🌙 Automatic Dark Mode
- 🌐 Opens https://github.com
- 🔄 Pull to Refresh
- ⬅️ Back & Forward Navigation
- 🏠 Home Button
- 📤 File Upload Support
- 📥 File Download Support
- 📷 Camera Access
- 🎤 Microphone Access
- 📶 Offline Detection
- ⚡ WKWebView Performance
- 📱 Optimized for iPhone 14

---

## Requirements

- macOS
- Xcode 16 or later
- iOS 16+
- Apple ID
- Apple Developer Account (required for App Store distribution)

---

## Project Structure

```
STAYPAID/
│
├── STAYPAID.xcodeproj
├── STAYPAID/
│   ├── App.swift
│   ├── ContentView.swift
│   ├── WebView.swift
│   ├── FaceIDManager.swift
│   ├── NavigationBar.swift
│   ├── Info.plist
│   ├── Assets.xcassets
│   └── LaunchScreen.storyboard
│
└── README.md
```

---

## Configuration

Website URL

```
https://github.com
```

App Name

```
STAYPAID
```

Bundle Identifier

```
com.staypaid.app
```

Minimum iOS

```
16.0
```

Deployment Target

```
iPhone
```

---

## Building

1. Clone the repository.

```
git clone https://github.com/USERNAME/STAYPAID.git
```

2. Open

```
STAYPAID.xcodeproj
```

3. Select your Apple Developer Team.

4. Set your Bundle Identifier.

5. Build the project.

6. Run on an iPhone or Simulator.

---

## Using GitHub Actions

A sample workflow can be placed in

```
.github/workflows/ios-build.yml
```

to automate building on every push.

---

## App Permissions

Camera

```
NSCameraUsageDescription
```

Microphone

```
NSMicrophoneUsageDescription
```

Photo Library

```
NSPhotoLibraryUsageDescription
```

Face ID

```
NSFaceIDUsageDescription
```

---

## Customization

Replace the contents of

```
Assets.xcassets/AppIcon.appiconset
```

with your own icon.

Current branding:

**STAYPAID MUST SHINE**

---

## License

MIT License

---

## Disclaimer

GitHub is a trademark of GitHub, Inc.

This application simply displays the GitHub website inside an iOS WebView and is not affiliated with or endorsed by GitHub.
