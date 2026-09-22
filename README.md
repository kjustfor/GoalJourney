# GoalJourney — Phone-Only Web App

This is a mobile-first version of GoalJourney designed to work from an iPhone without Xcode or a Mac.

## Features
- First-time goal setup
- Persistent local storage with browser localStorage
- Goal progress and percentage
- Remaining amount
- Deadline and days remaining
- Weekly pace
- Contribution history
- Contribution streak
- 10%, 25%, 50%, 75%, and 100% milestones
- Journal with mood
- Goal "Why"
- Settings
- Home-screen/PWA metadata

## How to use on iPhone
1. Put these files on a web host that serves HTTPS.
2. Open the site's index.html in Safari.
3. Tap Share -> Add to Home Screen.
4. Launch GoalJourney from the Home Screen.

Important: The app stores data locally in the browser on that device. Clearing Safari website data can erase it. This version does not sync across devices.

## Important limitation
A browser cannot turn these files into a signed native iOS .ipa by itself. This version is intentionally designed so the user can use it without a Mac.
