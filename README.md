# EZ-Talk


A modern Java-based chat application with features similar to popular messaging platforms. EZ Talk provides real-time messaging, user stories, contact management, and group conversations in an intuitive interface.

**Features**
  Private & Group Chats: One-to-one private conversations and multi-user group chats.
  Message Management: Reply to messages, star important messages, and track seen status.
  Ephemeral Stories: Share temporary updates with text and images that expire after 24 hours.
  Contact System: Add and manage contacts with mutual connection detection.
  User Profiles: Customize your profile with bio, photos, and privacy settings.
  Search: Find messages and contacts with powerful search functionality.
  Security: Secure authentication and user management.

**Project Structure**
The application follows the MVC (Model-View-Controller) architecture pattern:

**Models**
  User: Represents application users with their information, contacts, and preferences.
  ChatRoom: Manages conversations with features for ONE_TO_ONE and GROUP chat types.
  Message: Encapsulates sent messages with metadata and tracking information.
  Story: Implements ephemeral stories with view tracking and expiration.
  UserProfile: Handles user's profile data including bio, images, and visibility settings.
**Controllers**
  ChatController: Main interface controller managing chat rooms, messages, and contacts.
  LoginCon: Handles user authentication and registration processes.
  StoryCon: Controls the story viewing and creation interface.
**Utilities**
  Authenticator: Manages login and registration processes.
  FilesUtil: Handles persistent storage of application data.
  Generator: Creates unique identifiers for application objects.
  Global: Maintains application state and shared data structures.
  
Technical Requirements
Java: JDK 11 or higher
JavaFX: For the user interface components
File System Access: Read/write permissions for storing user data and media files

Open the project in your preferred Java IDE (Eclipse, IntelliJ IDEA, etc.)
Build the project with dependencies
Run the main application class to start EZ Talk
Usage
Registration and Login
New users can register with their mobile number, name, and profile picture. Returning users can login with their mobile number and password.

**Messaging**
Start a private chat by selecting a contact, Create a group chat by selecting multiple contacts, Send messages with the text input field and send button, Reply to messages by selecting the reply option, Star important messages for quick reference
**Stories**
View stories from contacts in the stories section, Create your own stories with text and optional images, See who has viewed your stories, Stories automatically expire after 24 hours
**Contacts**
Add new contacts by mobile number, View your contact list, Search for specific contacts
