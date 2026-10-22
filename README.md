# Inled Pulsar OS F-Droid Repository

Official F-Droid repository for [Pulsar OS](https://github.com/Inled-Pulsar-OS) and [InledGroup](https://github.com/InledGroup) Android applications, featuring **Sayri Mobile**.

## Adding this Repository

### 1. Direct F-Droid Link
If you are on an Android device with F-Droid, Droid-ify, or Neo Store installed, click:
- [Add Repository in F-Droid](fdroidrepos://inledgroup.github.io/fdroid-repo/repo)

### 2. Manual URL Entry
1. Open **F-Droid**, **Droid-ify**, or **Neo Store**.
2. Go to **Settings** > **Repositories** > **Add Repository (+)**.
3. Paste:
   ```text
   https://inledgroup.github.io/fdroid-repo/repo
   ```
4. Tap **Add** and update your repositories.

## Included Applications

| Application | Package | Description |
|---|---|---|
| **Sayri Mobile** | `es.inled.sayri` | AI Operating System Copilot synchronized with Pulsar OS (System Orchestration, App Functions, App Intents, Spatial OCR, Dicio STT) |

## Automated Deployment
This repository is automatically updated and deployed via GitHub Actions:
- Checks daily for new APK releases in `Inled-Pulsar-OS/sayri-android`.
- Builds and signs the F-Droid repository index (`index-v1.jar`, `index-v1.json`, `index.xml`).
- Deploys the repository and landing page to Cloudflare Pages & GitHub Pages.
