
 **Random Acts of Kindness App

This is a mobile application developed using React Native that encourages users to perform random acts of kindness. It offers random kindness suggestions, allows users to log their completed acts, track their progress, and maintain a journal for reflection.

## Features

- **Random Kindness Prompts**: Get daily suggestions for kind actions to perform.
- **Act Logging**: Track and log the acts of kindness you've completed.
- **Progress Tracking**: View the total number of acts completed and read the latest journal entry.
- **Journal**: Keep a personal journal of your experiences with kindness.
- **Notifications**: Get reminders to perform daily acts of kindness (can be extended with Expo notifications).

## Installation

### Prerequisites

Before running this app, ensure you have the following installed:
- Node.js (version 16 or higher)
- npm (or yarn) package manager
- React Native development environment set up (follow the [React Native Environment Setup](https://reactnative.dev/docs/environment-setup) if not already installed)
- Expo CLI (install via `npm install -g expo-cli`)

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/random-acts-of-kindness-app.git
cd random-acts-of-kindness-app
```

### Step 2: Install Dependencies

Run the following command to install necessary dependencies:

```bash
npm install
```

### Step 3: Run the App

Start the app using Expo:

```bash
npm start
```

This will open a new tab in your browser with the Expo developer tools, and you can run the app on an emulator or your physical device via the Expo Go app.

## App Structure

The app is divided into three main screens:

1. **Home Screen**: 
   - Displays a random act of kindness suggestion.
   - Allows users to log acts of kindness.
   - Tracks the number of completed acts.

2. **Journal Screen**:
   - Allows users to write and save journal entries reflecting on their kindness experiences.

3. **Progress Screen**:
   - Displays the total number of acts completed.
   - Shows the latest journal entry saved by the user.

## Technologies Used

- **React Native**: Framework used for building the mobile app.
- **AsyncStorage**: Used for storing the count of acts completed and journal entries locally.
- **Expo Notifications**: (Not yet fully implemented, but can be extended to send push notifications).
- **React Navigation**: Used for navigating between screens.

## Future Enhancements

- Implement push notifications to remind users to perform their daily acts of kindness.
- Add a social sharing feature to let users share their acts of kindness on social media.
- Implement a leaderboard to foster competition and engagement.

## Contributing

Contributions are welcome! If you want to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.



