# EZ-Talk

EZ-Talk is a modern, Java-based chat application that brings together real-time messaging, ephemeral stories, contact management, and group conversations in an intuitive interface. Inspired by popular messaging platforms, EZ-Talk aims to provide a seamless and secure communication experience.

## 🚀 Features

- **Private & Group Chats**: Engage in one-on-one conversations or create group chats with multiple users.
- **Message Management**: Reply to messages, star important ones, and track read receipts.
- **Ephemeral Stories**: Share temporary updates with text and images that disappear after 24 hours.
- **Contact System**: Add and manage contacts with mutual connection detection.
- **User Profiles**: Customize your profile with a bio, photos, and privacy settings.
- **Search Functionality**: Easily find messages and contacts with a powerful search feature.
- **Security**: Secure authentication and user management to protect your data.

## 🧱 Project Structure

The application follows the MVC (Model-View-Controller) architecture pattern:

- **Models**
  - `User`: Represents application users, including their information, contacts, and preferences.
  - `ChatRoom`: Manages conversations, supporting both one-to-one and group chat types.
  - `Message`: Handles message content, timestamps, sender information, and read status.

- **Views**
  - JavaFX-based UI components for chat windows, contact lists, story displays, and profile management.

- **Controllers**
  - Handle user interactions, update models, and refresh views accordingly.

## 🛠️ Installation

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- JavaFX SDK 23 or higher

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/gedokhattab/EZ-Talk.git
   cd EZ-Talk
