# Annsetu

Annsetu is an AI-powered digital platform designed to connect surplus food sources (restaurants, grocery stores, hotels, and caterers) with NGOs and community kitchens for real-time food redistribution. The goal is to reduce food waste and help address hunger efficiently.

## Team

This app is developed by a team of four students passionate about leveraging technology for social good.

## Features

- **Real-time food donation matching**: Connects food donors with NGOs instantly.
- **AI-powered chatbot**: Assists users in navigating the platform and answering queries.
- **User roles**:
  - **Donors**: Restaurants, grocery stores, hotels, caterers.
  - **Receivers**: NGOs, community kitchens, food banks.
- **Location-based matching**: Ensures efficient redistribution within nearby areas.
- **Notification system**: Alerts donors and receivers about available food.
- **Data analytics dashboard**: Tracks donations, food saved, and impact.

## Tech Stack

- **Frontend**: Flutter (for cross-platform mobile app development)
- **Backend**: Firebase / MySQL with Node.js (TBD)
- **AI Chatbot**: NLP model for query handling (Dataset TBD)
- **Cloud Storage**: Firebase Storage / AWS S3
- **Authentication**: Firebase Auth / OAuth
- **Database**: Firestore / MySQL

## Installation & Setup

### Prerequisites

- Flutter SDK installed
- Node.js and npm installed
- Firebase project set up (if using Firebase backend)

### Steps

1. Clone the repository:
   ```bash
   git clone (https://github.com/iiinnn-source/Annsetu_Tech.git)
   cd annsetu
   ```
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Configure Firebase (if applicable):
   - Add `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) to the respective directories.
4. Run the app:
   ```bash
   flutter run
   ```

## Future Enhancements

- AI-based demand prediction for food donations
- Integration with logistics services for pickup and delivery
- Multi-language support for accessibility

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request.