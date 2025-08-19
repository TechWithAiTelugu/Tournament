
# Tournament Manager

A comprehensive tournament management system with admin and user interfaces for creating, managing, and participating in gaming tournaments.

🎥 [Watch on YouTube](https://youtu.be/FM_e1K6ejz0?si=F490eqcDby-PG9mP)

## Features

### Admin Panel
- **Dashboard**: Overview of tournaments, users, and participants with real-time statistics
- **Tournament Management**: Create, edit, and delete tournaments with detailed information
- **User Management**: View and manage all registered users with search functionality
- **Settings**: Admin preferences including password change, notifications, and theme selection
- **Full-Screen Mode**: Toggle between normal and full-screen views for focused work
- **Remember Me**: Persistent login sessions to avoid repeated authentication
- **Activity Tracking**: Monitor recent system activities and changes

### User Interface
- **Authentication**: Secure login and registration system with Game ID integration
- **Tournament Browsing**: Filter tournaments by game, type, and date
- **Tournament Details**: View comprehensive tournament information
- **Registration**: Join tournaments with team and Game ID information
- **User Profile**: Manage personal account settings and preferences
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Screenshots

### Admin Dashboard
![Admin Dashboard](https://techwithaitelugu.github.io/Tournament/images/Screenshot%20(196).png)
- Real-time statistics cards
- Recent activity feed
- Quick navigation to all features

### Tournament Management
![Tournament Management](https://techwithaitelugu.github.io/Tournament/images/Screenshot%20(198).png)
- Create new tournaments with detailed information
- View all tournaments with participant lists
- Edit or delete existing tournaments

### User Interface
![User Interface](https://techwithaitelugu.github.io/Tournament/images/Screenshot%20(197).png)
- Browse available tournaments
- Filter by game, type, and date
- Join tournaments with registration form

## Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Firebase account (for database services)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/TechWithAiTelugu/Tournament.git
   cd tournament-manager
   ```

2. Set up Firebase:
   - Create a new project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Realtime Database
   - Copy your Firebase configuration

3. Configure Firebase:
   - Open `admin.html` and `user.html`
   - Replace the Firebase configuration object with your own:
     ```javascript
     const firebaseConfig = {
         apiKey: "YOUR_API_KEY",
         authDomain: "YOUR_AUTH_DOMAIN",
         projectId: "YOUR_PROJECT_ID",
         storageBucket: "YOUR_STORAGE_BUCKET",
         messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
         appId: "YOUR_APP_ID"
     };
     ```

4. Deploy to web hosting:
   - Use Firebase Hosting, GitHub Pages, or any static web hosting service
   - Ensure both admin and user interfaces are accessible

## Usage

### Admin Panel
1. Access the admin interface at your deployed URL
2. Log in with admin credentials (default: username: `techwithai`, password: `telugu`)
3. Use the sidebar to navigate between different sections
4. Create tournaments by filling out the form with all required details
5. Monitor user registrations and tournament participation
6. Toggle full-screen mode using the button in the bottom-right corner

### User Interface
1. Access the user interface at your deployed URL
2. Register a new account with your email, password, and Game ID
3. Browse available tournaments using the filter options
4. Click "View & Join" on any tournament to see details and register
5. Manage your profile through the settings menu

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Custom CSS with Font Awesome icons
- **Database**: Firebase Realtime Database
- **Authentication**: Custom implementation with Firebase
- **Design**: Responsive design with mobile optimization
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Poppins)

## Project Structure

```
tournament-manager/
├── admin.html           # Admin interface
├── user.html            # User interface
├── README.md            # This file
├── images/         # Images and icons
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [@techwithai](https://youtube.com/@techwitai1?si=nbFi4SpBRd-RiOuf)

Project Link: [https://github.com/yourusername/tournament-manager](https://github.com/TechWithAiTelugu/Tournament)

## Acknowledgements

- [Font Awesome](https://fontawesome.com/) for the amazing icons
- [Google Fonts](https://fonts.google.com/) for the Poppins font
- [Firebase](https://firebase.google.com/) for the backend services
