## GreenhouseSystemProject
# PlantPlus

A modern plant care and monitoring app built with React Native and Expo.

## 📋 Project Overview

PlantPlus is a user-friendly mobile application designed to help plant enthusiasts track and care for their plants. The app provides an intuitive interface for managing plant collections, receiving care reminders, and accessing plant care information.

## ✨ Key Features

- **Plant Gallery**: Browse your collection of plants
- **Plant Details**: Access specific information for each plant
- **Care Reminders**: Get notified about watering, fertilizing, and other care tasks
- **Add Plants**: Easily add new plants to your collection
- **Light/Dark Mode**: Toggle between light and dark themes for comfortable viewing
- **Bottom Navigation**: Intuitive navigation between main screens
- **Responsive Design**: Optimized for various mobile device sizes

## 🛠️ Technologies & Tools

- **React Native**: For cross-platform mobile development
- **Expo**: Development platform and tools for React Native
- **React Navigation**: For screen navigation (Bottom Tabs Navigator)
- **AsyncStorage**: For local data persistence
- **Vector Icons**: Using Expo's integrated icon sets
- **Custom Components**: Reusable UI components for consistent design

## 📱 Screens & Components

The application includes:

- **Home Screen**: Overview of your plant collection
- **Plant Detail Screen**: Detailed view of individual plants
- **Add Plant Screen**: Interface for adding new plants
- **Profile Screen**: User settings and preferences
- **Custom Components**:
  - Plant Cards
  - Navigation Bar
  - Header Components
  - Custom Buttons
  - Input Fields

## 🎨 UI/UX Design

- Clean, minimalist interface with plant-themed elements
- Consistent color scheme throughout the app
- Intuitive navigation with custom tab bar
- Smooth transitions between screens
- Responsive layout adapting to different device sizes

## 🚀 Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm or yarn
- Expo CLI
- iOS Simulator, Android Emulator, or physical device for testing

### Installation

1. Clone the repository
```bash
git clone https://github.com/dhyeyfarasram/PlantPlus.git
cd PlantPlus
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
expo start
# or
npm start
```

4. Open the app on your device/simulator
   - Scan the QR code with the Expo Go app (Android) or Camera app (iOS)
   - Press 'i' for iOS simulator or 'a' for Android emulator in the terminal

## 📂 Project Structure

```
PlantPlus/
├── .expo/              # Expo configuration files
├── assets/             # Static assets including images and fonts
│   ├── fonts/          # Custom fonts
│   └── images/         # App images and icons
├── components/         # Reusable UI components
│   ├── CustomButton.js # Custom button component
│   ├── PlantCard.js    # Plant card display component
│   └── ...             # Other components
├── navigation/         # Navigation configuration
│   └── tabs.js         # Bottom tab navigator setup
├── screens/            # Application screens
│   ├── AddPlant.js     # Add plant screen
│   ├── Home.js         # Home/gallery screen
│   ├── PlantDetail.js  # Plant detail screen
│   ├── Profile.js      # User profile screen
│   └── ...             # Other screens
├── .gitignore          # Git ignore file
├── App.js              # Main application component
├── app.json            # Expo configuration
├── babel.config.js     # Babel configuration
└── package.json        # Project dependencies and scripts
```

## 🔮 Future Enhancements

- Plant recognition via camera
- Community features for plant enthusiasts
- Integration with plant care APIs for detailed information
- Advanced care scheduling and statistics
- Plant health diagnostics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

Dhyey Farasram - [GitHub](https://github.com/dhyeyfarasram)

Project Link: [https://github.com/dhyeyfarasram/PlantPlus](https://github.com/dhyeyfarasram/PlantPlus)
