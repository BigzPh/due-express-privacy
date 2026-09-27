# Due Express - Privacy Policy & Terms of Use (GitHub Pages)

This repository contains the official, App Store-compliant **Privacy Policy** and **Terms of Use** website for **Due Express - Deadline Timer**, ready to be hosted on **GitHub Pages**.

---

## 🌐 Expected Live URLs

Once deployed with your GitHub username (`BigzPh`):

| Page | URL Format |
| :--- | :--- |
| **Privacy Policy (App Store URL)** | `https://bigzph.github.io/<repository-name>/` |
| **Direct Policy Path** | `https://bigzph.github.io/<repository-name>/index.html` |
| **Terms of Use** | `https://bigzph.github.io/<repository-name>/terms.html` |

> **Recommended Repository Name:** `due-express-privacy`  
> In that case, your App Store Privacy Policy URL will be:  
> **`https://bigzph.github.io/due-express-privacy/`**

---

## 🚀 How to Deploy to GitHub Pages (2 Steps)

### Step 1: Push This Code to GitHub

If you haven't created a GitHub repository yet:
1. Go to [GitHub - Create New Repository](https://github.com/new).
2. Set the repository name to `due-express-privacy` (or your preferred name).
3. Keep it **Public** (required for free GitHub Pages).
4. Do **not** initialize with README or license (we already have all files here).
5. In your terminal, run:

```bash
# Rename branch to main (recommended)
git branch -M main

# Add all files
git add .
git commit -m "Add Privacy Policy and Terms for Due Express"

# Add your GitHub remote (replace with your repo URL)
git remote add origin https://github.com/BigzPh/due-express-privacy.git

# Push to GitHub
git push -u origin main
```

---

### Step 2: Enable GitHub Pages

1. In your GitHub repository, click on **Settings** (top navigation bar).
2. In the left sidebar, click on **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` (or `master`) and folder `/(root)`.
4. Click **Save**.
5. Wait 1–2 minutes. GitHub will show a banner at the top:
   > *"Your site is live at https://bigzph.github.io/due-express-privacy/"*

---

## 🍎 How to Add to App Store Connect

1. Go to [App Store Connect](https://appstoreconnect.apple.com/).
2. Select your app: **Due Express - Deadline Timer**.
3. In the left sidebar, under **General**, click **App Information**.
4. Scroll down to the **Privacy Policy URL** field.
5. Paste your GitHub Pages URL:
   ```text
   https://bigzph.github.io/due-express-privacy/
   ```
6. Click **Save** in the top right.

---

## 📋 App Store Privacy Questionnaire Cheat Sheet

When filling out **App Privacy** in App Store Connect:

- **Do you or your third-party partners collect data from this app?**  
  👉 **No, we do not collect data from this app.**

Due Express is an offline-first app where all deadlines and countdowns are stored locally on the user's device. No account is required and no analytics or ad SDKs are included.

---

## 📁 Repository Structure

```text
├── index.html        # Privacy Policy webpage (App Store compliant)
├── terms.html        # Terms of Use / EULA webpage
├── styles.css        # Modern, responsive light & dark mode stylesheet
├── 404.html          # Custom error page redirecting to privacy policy
├── .nojekyll         # Disables Jekyll processing for instant static hosting
└── README.md         # Deployment and App Store submission guide
```
