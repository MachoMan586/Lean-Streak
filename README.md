# Lean Streak: put it on your iPhone

Lean Streak is a web app you add to your home screen. Once it's there it has its own icon, opens full screen like a normal app, and works with no internet. Everything you log stays on your phone.

You need to put these files online once (free), then add the app to your home screen.

## What's in this folder

| File | What it is |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | The app's name, colors and icon |
| `sw.js` | Lets the app work offline |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | The app icon in each size the phone needs |

## Step 1: Put it online with GitHub Pages (free, about 10 minutes)

GitHub accounts are for ages 13 and up. Ask a parent to help if you need it.

1. Go to github.com and sign up for a free account.
2. Click the **+** in the top right, then **New repository**.
3. Name it `lean-streak`, set it to **Public**, and click **Create repository**.
4. On the next page, click **uploading an existing file**.
5. Select **all 8 files in this folder** (click one, then press Ctrl+A) and drag them in together. Then click **Commit changes**.
6. Go to **Settings**, then **Pages** in the left menu.
7. Under **Branch**, pick **main** and **/ (root)**, then click **Save**.
8. Wait a minute and refresh. The page shows your app's address, like `https://YOUR-NAME.github.io/lean-streak/`.

## Step 2: Add it to your home screen

1. On your iPhone, open **Safari** (it has to be Safari) and go to your app's address.
2. Tap the **Share** button (the square with an arrow).
3. Scroll down and tap **Add to Home Screen**, then **Add**.
4. Open Lean Streak from the new icon. The coach starts the first time.

## Step 3 (optional): Show your streak on the icon

iPhone doesn't allow widgets for web apps, but the icon can show your streak as a red number badge.

1. Open Lean Streak from the home screen icon (not from Safari).
2. Go to the **Streak** tab (the flame button) and tap **Turn on icon badge**.
3. Tap **Allow** when your iPhone asks about notifications. Badges need that permission. The app doesn't send you notifications.

This needs iOS 16.4 or newer.

## Keep your data safe

Your streak, food log and check-ins are saved only on your phone. If you delete the app from your home screen, the data goes with it.

On the **Progress** tab, tap **Copy backup** every few weeks and paste it into the Notes app. To restore, paste it back into the backup box and tap **Restore from backup** twice.

## Updating the app later

1. Upload the changed files to your GitHub repository the same way (they replace the old ones).
2. Open `sw.js` and bump the version at the top (for example `lean-streak-v2` to `lean-streak-v3`), and upload that too. This tells phones to grab the new version.
3. Close and reopen the app on your phone. You may need to do it twice.

## About the coach

The coach is built into the app. It asks 7 questions in a set order and understands answers in different formats, like `5'2`, `157 cm`, `63 kg` or "basketball twice a week". It isn't a full AI that can chat about anything, and it doesn't send your answers anywhere. Your calories never go under 1,800 a day if you're under 18. Show your plan to a parent or doctor.
