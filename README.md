# PROJECT FARM - Google Home Integration

A smart home control system integrated with Google Home, built with React and Firebase.

## Overview

This project provides a web interface for managing smart home devices with full Google Home integration. Users can control devices, manage notifications, and sync their devices with Google Assistant.

## Features

- 🏠 **Device Management**: Add, edit, and control smart home devices
- 🔔 **Real-time Notifications**: Toast notification system with color-coded alerts
- 🔐 **OAuth 2.0 Authentication**: Secure Google Home integration
- 🔄 **Device Sync**: Automatic synchronization with Google Home
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile
- 🔥 **Firebase Backend**: Real-time database and authentication

## Tech Stack

- **Frontend**: React, React Router, Vite
- **Backend**: Firebase (Firestore, Authentication, Cloud Functions)
- **Deployment**: Vercel
- **APIs**: Google Smart Home API, OAuth 2.0

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- Firebase account
- Google Cloud Platform project with Smart Home Actions enabled

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Lx-flexy/PROJECT_FARM.git
cd PROJECT_FARM_WEB
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
   - Copy `.env.example` to `.env.local`
   - Fill in your Firebase and OAuth credentials

4. Run the development server:
```bash
npm run dev
```

### Environment Variables

See [ENV_CHECKLIST.md](docs/ENV_CHECKLIST.md) for detailed environment configuration.

## Deployment

For deployment instructions, see [DEPLOYMENT_INSTRUCTIONS.md](docs/DEPLOYMENT_INSTRUCTIONS.md) and [DEPLOYMENT_CHECKLIST.md](docs/DEPLOYMENT_CHECKLIST.md).

## Documentation

All project documentation is available in the [`docs`](./docs) folder:

### Setup & Configuration
- [Firebase Admin Setup](docs/FIREBASE_ADMIN_SETUP.md)
- [Environment Variables Checklist](docs/ENV_CHECKLIST.md)
- [Deployment Instructions](docs/DEPLOYMENT_INSTRUCTIONS.md)
- [Deployment Checklist](docs/DEPLOYMENT_CHECKLIST.md)

### Google Home Integration
- [Google Home API Documentation](docs/GOOGLE_HOME_API_DOCUMENTATION.md)
- [Google Home Verification Report](docs/GOOGLE_HOME_VERIFICATION_REPORT.md)

### OAuth & Authentication
- [OAuth Fix Summary](docs/OAUTH_FIX_SUMMARY.md)
- [OAuth Client ID Diagnostic](docs/OAUTH_CLIENT_ID_DIAGNOSTIC.md)
- [OAuth POST 400 Fix](docs/OAUTH_POST_400_FIX.md)
- [Client ID Mismatch Fix](docs/CLIENT_ID_MISMATCH_FIX.md)
- [Safe OAuth Diagnostic](docs/SAFE_OAUTH_DIAGNOSTIC.md)

### Notification System
- [Notification System](docs/NOTIFICATION_SYSTEM.md)
- [Notification Architecture](docs/NOTIFICATION_ARCHITECTURE.md)
- [Toast Notification System](docs/TOAST_NOTIFICATION_SYSTEM.md)
- [Notification Quick Reference](docs/NOTIFICATION_QUICK_REFERENCE.md)
- [Toast Quick Reference](docs/TOAST_QUICK_REFERENCE.md)
- [Notification Summary](docs/NOTIFICATION_SUMMARY.md)
- [Complete Notification Summary](docs/COMPLETE_NOTIFICATION_SUMMARY.md)
- [Notification Delete Implementation](docs/NOTIFICATION_DELETE_IMPLEMENTATION.md)

### Color & UI System
- [Color Matched Architecture](docs/COLOR_MATCHED_ARCHITECTURE.md)
- [Color Matched Notifications](docs/COLOR_MATCHED_NOTIFICATIONS.md)
- [Color Matched Notifications Complete](docs/COLOR_MATCHED_NOTIFICATIONS_COMPLETE.md)
- [Color Matched Notifications Fix](docs/COLOR_MATCHED_NOTIFICATIONS_FIX.md)
- [Color Matched Notifications Summary](docs/COLOR_MATCHED_NOTIFICATIONS_SUMMARY.md)
- [Color Matched Notifications Verification](docs/COLOR_MATCHED_NOTIFICATIONS_VERIFICATION.md)
- [Color Matched Notifications Quick Reference](docs/COLOR_MATCHED_NOTIFICATIONS_QUICK_REFERENCE.md)
- [Color Fix Final](docs/COLOR_FIX_FINAL.md)
- [Debug Color Flow](docs/DEBUG_COLOR_FLOW.md)

### Dark Mode
- [Dark Mode Fixes](docs/DARK_MODE_FIXES.md)
- [Dark Mode Before After](docs/DARK_MODE_BEFORE_AFTER.md)
- [Dark Mode Removal Summary](docs/DARK_MODE_REMOVAL_SUMMARY.md)

### Bug Fixes & Features
- [Device Edit Fix](docs/DEVICE_EDIT_FIX.md)
- [Vercel Fix Report](docs/VERCEL_FIX_REPORT.md)

### Testing & Validation
- [Final Code Review](docs/FINAL_CODE_REVIEW.md)
- [Final Test Report](docs/FINAL_TEST_REPORT.md)
- [Final Validation Report](docs/FINAL_VALIDATION_REPORT.md)
- [Production Test Report](docs/PRODUCTION_TEST_REPORT.md)
- [Responsive Test Report](docs/RESPONSIVE_TEST_REPORT.md)
- [Runtime Test Report](docs/RUNTIME_TEST_REPORT.md)

## Project Structure

```
PROJECT_FARM_WEB/
├── api/                    # Serverless API endpoints
│   ├── oauth/             # OAuth endpoints
│   ├── lib/               # Shared libraries
│   └── fulfillment.js     # Google Home fulfillment
├── docs/                  # Documentation
├── src/                   # React source code
├── public/                # Static assets
└── .env.local            # Environment variables
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Support

For issues and questions, please open an issue on GitHub.

## Acknowledgments

- Google Smart Home API
- Firebase Platform
- React Community
