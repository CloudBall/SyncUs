# NexusSync - Google Play Store Publishing Guide

Follow these steps to publish your NexusSync app on the Google Play Store as an official mobile application:

### Step 1: Host Your App Online
1. Upload all repository files (`index.html`, `manifest.json`, `sw.js`, and `icon-512.png`) to a GitHub repository.
2. Enable **GitHub Pages** in your repository settings under **Settings -> Pages**, pointing to the `main` branch.
3. Copy your live GitHub Pages URL (e.g. `https://yourusername.github.io/your-repo/`).

### Step 2: Package with PWABuilder
1. Go to [PWABuilder.com](https://www.pwabuilder.com/).
2. Paste your live URL and click **Start**.
3. Once analyzed, click **Package For Stores** under Android.
4. Fill in your package details (App Name, Package ID like `com.squad.nexussync`).
5. Download your signed Android App Bundle (`.aab`) file.

### Step 3: Publish on Google Play Console
1. Register a developer account on the [Google Play Console](https://play.google.com/console/) ($25 USD one-time registration fee).
2. Create a new application, fill out your store listing details, screenshots, and privacy policy.
3. Go to **Production -> Create New Release**, and upload your `.aab` file.
4. Submit for review!
