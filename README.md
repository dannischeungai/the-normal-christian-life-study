# The Normal Christian Life Study Companion

A static study app for understanding and memorising the themes of *The Normal Christian Life*.

Open `index.html` in a browser to use it. No install or build step is required.

## Mobile App

The project is also a Progressive Web App. To install it on a phone, serve this folder from a local or hosted URL, open that URL on the phone, then use the browser's Add to Home Screen or Install action.

Service-worker offline support requires `http://localhost`, a local-network `http://` address, or `https://`; it will not run from a `file://` URL.

## Native Mobile App

This project is ready to be wrapped with Capacitor as a real Android/iOS app.

1. Install Node.js with npm.
2. From this folder, run `npm install`.
3. Build the web bundle with `npm run build`.
4. Add native platforms:
   - Android: `npm run cap:add:android`
   - iOS: `npm run cap:add:ios`
5. Open the native project:
   - Android: `npm run android`
   - iOS: `npm run ios`

Android builds require Android Studio. iOS builds require Xcode on macOS.

## Features

- Chapter-by-chapter study guide
- Plain-language summaries and key concepts
- Memory cards for review
- Quick chapter quizzes
- Verse anchors for deeper reading
- Personal notes saved in the browser
- Progress tracking with localStorage
- Focus mode for distraction-light reading
- Installable mobile app metadata
- Offline cache when served from a supported URL

The app uses paraphrased study material rather than reproducing the full book text.
