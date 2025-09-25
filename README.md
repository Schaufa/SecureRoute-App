SecureRoute 
A privacy-focused Android navigation app that encrypts location data and empowers users to travel securely.

Project Outline
- Description: SecureRoute provides encrypted route planning and GPS tracking.
- Problem Addressed: Reduces exposure to location tracking and data harvesting.
- Platform: Android (API 26+), Android Studio
- Front-End: Kotlin, Jetpack Compose, Material Design
- Back-End: SQLite, Android Keystore, optional Firebase
- Functionality: Offline maps, VPN toggle, encrypted history
- Design: Wireframes include Home, Messages, Settings, Permissions

GitHub Wiki
Visit the [Wiki](https://github.com/Schaufa/SecureRoute-App/wiki) for detailed module breakdowns and wireframes.

Resources
- [GitHub Training Lab](https://lab.github.com/githubtraining/introduction-to-github)
- [Hello World Guide](https://guides.github.com/activities/hello-world)

 Week 4 Update – Version 1.3

Technical Enhancements
- Refactored `SQLiteOpenHelper` into a modular class for better version control and maintainability.
- Implemented forensic logging to track permission changes and message access events.
- Improved database schema to support encrypted message storage and audit trails.

 Wireframe Adjustments
- Updated Permissions screen wireframe to include a forensic log viewer.
- Added visual indicators for encrypted vs. unencrypted messages in the Messages screen.

Documentation & Wiki
- Published updated project outline and changelog to GitHub Wiki.
- Added forensic logging module explanation to README.
- Linked SQLite schema and usage instructions in the Wiki.

 Ethical Considerations
- Reinforced privacy-first design by encrypting sensitive data at rest.
- Ensured forensic logs are stored securely and access-controlled.

Commit Summary
bash
Commit Message: Week 4 Update: SQLite refactor + forensic logging
