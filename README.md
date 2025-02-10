# 📍NearbyApp

## 🚀 About the Project
The NearbyApp is a powerful and user-friendly iOS application designed to assist users in discovering nearby locations, such as restaurants, gas stations, stores, and other points of interest. Developed with SwiftUI, the app leverages CoreLocation to provide real-time location tracking and MapKit to display locations interactively on a map.

- Real-Time Location Tracking: The app continuously updates the user’s position using CoreLocation, ensuring precise and accurate location detection.
- Interactive Map Display: Leveraging MapKit, NearbyApp presents locations dynamically, allowing users to navigate effortlessly with an intuitive map interface.
- Smart Search & Categorization: Users can quickly search for specific locations using predefined categories such as restaurants, gas stations, and shopping centers, improving efficiency in finding relevant places.
- Seamless UI/UX Experience: The interface is designed with SwiftUI, ensuring a visually appealing and responsive user experience with support for Dark Mode.
- Integration with External APIs: Supports services like Google Places API for an enhanced and up-to-date location database.
- Custom Map Annotations: Personalized pins for different categories of locations enhance the visual distinction between various types of establishments.
- Performance Optimization: The app implements background location updates and optimized API calls, ensuring smooth performance without unnecessary battery consumption.

The primary goal of NearbyApp is to provide a seamless, fast, and efficient tool for users who need quick access to relevant locations nearby. Whether you’re searching for a gas station during a road trip, a nearby café to work in, or an emergency service, the app ensures an effortless and streamlined experience.

## 🛠 Technologies Used
- Language: Swift
- Frameworks: SwiftUI, CoreLocation, MapKit
- External APIs: Google Places API (if configured)
- UI & Design: SwiftUI with Dark Mode support
- Dependency Management: Swift Package Manager (SPM)
- Database: Firebase (if applicable)

## 📋 Requirements
- Platform: iOS 15+
- Tools: Xcode 14+ (recommended)
- Internet Connection: Required for accessing external APIs
- Apple Developer Account: Required for testing on physical devices

## 📥 Installation and Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/NearbyApp.git
   ```
2. Open the project in Xcode:
   ```sh
   cd NearbyApp
   open NearbyApp.xcodeproj
   ```
3. Install dependencies (if needed):
   - In Xcode, go to File > Swift Packages > Update to Latest Package Versions
4. Run the app on the simulator or a physical device:
   - Select the target device in Xcode
   - Press Run (Cmd + R)

## 📂 Project Structure
```
NearbyApp/
├── 📁 Resources/
│   ├── Assets.xcassets/  # Icons and project images
│   ├── Localizable.strings  # Translation and localization files
├── 📁 Models/               # Application data models
├── 📁 Views/                # UI components and main screens
├── 📁 ViewModels/           # Business logic and data handling
├── 📁 Controllers/          # Controllers bridging View and Model
├── 📁 Services/             # Auxiliary services (e.g., API requests)
└── 📁 NearbyApp.xcodeproj   # Main Xcode project file
```

## 🎯 Learning Objectives
During the development of NearbyApp, several technical and conceptual skills were enhanced, including:
- Geolocation Implementation: Using CoreLocation to capture and manage the user's position.
- Integration with MapKit: Displaying and handling interactive maps in SwiftUI.
- Usage of External APIs: Integrating services like Google Places API for location search.
- Development with SwiftUI: Building modern, responsive, and Dark Mode-compatible interfaces.
- State Management: Implementing the MVVM (Model-View-ViewModel) pattern for responsibility separation.
- Connectivity and Performance: Implementing asynchronous calls to improve user experience.

Developed to enhance your navigation and discovery of new places!



