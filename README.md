# PawnVersation

PawnVersation is an innovative chess game designed for inclusivity, enabling players to move chess pieces using voice commands in addition to existing traditional methods (drag-n-drop and touch). By leveraging modern web technologies, we aim to make chess accessible to everyone, including individuals with physical disabilities. Currently, chess lacks representation from groups such as the blind or those without means to physically interact with chess, and this project seeks to bridge that gap.

We're using Groq to power our speech to text conversion, which in turn results in automated movement of chess pieces. Pair this with a serene UI and highly portable software, we present the chess for everyone (literally!!).

## Project info

**URL**: [PawnVersation](https://pawnversation.vercel.app/)

## Features

1. **Voice Control**: Make chess moves naturally using voice commands. Just say the move, and the platform will process it instantly.
2. **Smart AI**: Challenge yourself against an intelligent AI opponent that knows whats the best next move.
3. **Beautiful Design**: Enjoy a clean, user-friendly, and visually appealing chess interface.

---

## Pages Overview

### **1. Home Page**

The home page introduces the PawnVersation platform with key features. It includes:
  - Voice Control: Describes the natural voice command functionality.
  - Smart AI: Promotes the advanced AI opponent.
  - Beautiful Design: Focuses on the sleek and modern user experience.
- A prominent "Start Playing" button that navigates users to the chessboard.
- A "Share Game" button that presents a QR code, waiting to be scanned by you.

### **2. Chess Game Page**

The chess game page provides the main functionality of the platform. Key elements:

- **Interactive Chessboard**: A standard chessboard for gameplay, featuring white and black pieces.
- **Captured Pieces Display**: Two sections showing pieces captured by White and Black.
- **Voice Input Icon**: Allows players to make moves via voice commands.
- **Navigation Options**:
  - Back to Home: A button to return to the home page.
  - Share Game: A QR code option for sharing the game with others.


## How to Use

1. Visit the **Home Page** and click "Start Playing" to begin.
2. On the **Chess Game Page**, use voice commands or manual input to make moves.
3. Monitor the captured pieces and strategize your gameplay.
4. Share your game session using the QR code feature.

---

## Future Enhancements

- Multiplayer functionality for real-time matches.
- Enhanced AI difficulty levels.
- Support for additional languages in voice commands.

---

Enjoy the ultimate chess experience with PawnVersation!

## How can I edit this code?

There are several ways of editing your application.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Groq API for voice recognition
