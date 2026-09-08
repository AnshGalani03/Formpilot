# FormPilot — Installation Guide

FormPilot is a Chrome extension that detects contact forms on websites and fills them from your saved profiles. Because it is not yet published on the Chrome Web Store, it is installed as an **unpacked extension**.

## What you need

- A Chromium-based browser: Chrome, Edge, Brave, Arc, or Opera
- The `formpilot.zip` file from this project

## Download the extension

1. Go to the project download page.
2. Click **Download for Chrome**.
3. Save `formpilot.zip` to your computer.

## Install the extension

### Step 1 — Unzip the file

- On **Windows**: right-click `formpilot.zip` → **Extract All…** → choose a folder.
- On **Mac**: double-click `formpilot.zip` to extract it.
- On **Linux**: right-click → **Extract Here**.

Keep the extracted folder somewhere safe. You will point Chrome to this folder.

### Step 2 — Open the Extensions page

Open your browser and go to:

```
chrome://extensions
```

### Step 3 — Turn on Developer mode

Look for the **Developer mode** toggle at the top-right of the page and turn it on.

### Step 4 — Load the unpacked extension

1. Click the **Load unpacked** button.
2. Select the extracted `formpilot` folder (the one that contains `manifest.json`).
3. Click **Select Folder**.

FormPilot will now appear in your list of extensions.

### Step 5 — Pin the extension

1. Click the extensions icon in your browser toolbar (it looks like a puzzle piece).
2. Find **FormPilot** and click the pin icon next to it.

FormPilot is now ready to use.

## Set up your profile

1. Click the FormPilot icon in your toolbar.
2. Click **Open settings**.
3. Go to the **Profiles** tab.
4. Fill in your details: name, email, phone, company, address, website, and message.
5. Click **Save profile**.

The extension will use only the information you save here. It never makes up or guesses data.

## How FormPilot works

- **Automatic fill and submit**: By default, when you open a page with a contact form, FormPilot finds the form, fills it from your active profile, and submits it.
- **Fill only**: You can change the mode so it fills the form but does not submit.
- **Confirm before submit**: A review panel appears first so you can check the fields before sending.

You can change the mode in the popup or on the **Settings** tab.

## Fill multiple websites automatically

1. Open FormPilot settings.
2. Go to the **Websites** tab.
3. Paste one or more website links, each on a new line.
4. Click **Add to list**.
5. Click **Start filling all**.

FormPilot will open each website in a new tab, fill the form from your saved profile, submit it, and close the tab. It processes one website at a time.

## Keep the extension up to date

When a new version is released:

1. Download the new `formpilot.zip`.
2. Delete the old extracted folder and unzip the new one.
3. Go to `chrome://extensions`.
4. Find FormPilot and click the refresh icon, or click **Remove** and load the new folder again.

## Troubleshooting

| Problem | What to do |
| --- | --- |
| FormPilot does not fill anything | Make sure you saved a profile and that the page has a contact form. |
| Some fields are not filled | Check that your profile has the matching information. The extension only fills fields it is confident about. |
| The form is filled but not submitted | Make sure the mode is set to **Fill and send automatically** or the site is added to trusted sites. |
| A site is opened but nothing happens | The site may be blocked, or the form may appear after the page loads. Try adding the site again or increasing wait time. |
| The extension disappeared after restarting Chrome | You may be in a guest or incognito window. Extensions usually stay installed; reload `chrome://extensions` and make sure it is enabled. |

## Privacy note

Your profiles, website list, and fill history are stored only in your browser's local extension storage. Nothing is sent to any server.
