# Gym plan

An offline workout app for your phone.

## Put it online (GitHub Pages, free)

1. Create a new **public** repository on GitHub, for example `gym-plan`.
2. Upload everything in this folder to the repository root, keeping the `fonts` and `icons` folders.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute your app is live at `https://<your-username>.github.io/gym-plan/`.

## Install on iPhone

1. Open that address in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Open it once from the home screen while online. After that it works with no signal.

## Glute plan

A second app lives in `glutes/`, at `https://<your-username>.github.io/gym-plan/glutes/`.
It has three days (A, B, C) for training 1 to 3 times a week: it opens on the next day in the rotation and clears last session's ticks.
Install it the same way. It has its own `sw.js`, so bump `glute-plan-v1` when you change anything in `glutes/`.

## Changing it later

Edit the files, then raise the version in `sw.js` (`gym-plan-v1` → `gym-plan-v2`).
Open the app twice while online and the new version takes over.

Your ticked sets are stored on the phone and stay through updates.
