# Hajime-Skin

## 0. Fetch the latest version

```bash
git fetch upstream
git merge upstream/main
```

## 1. 📝 Rewrite meta data

### ⚙️ **Update the `manifests.json`**

- [ ] **Rename** the extension.
- [ ] Update the **version number**.
  - `manifest.json`
  - `manifest v3.json`

## 2. 🎨 Overwrite Images

## 3. 🛠️ Build

### 🧩 Chrome

Create another `.zip` file with the following contents:

```plaintext
icons, images, manifest v3.json, mrbeasify.js
```

### 🦊 Firefox

Create a `.zip` file with the following contents:

```plaintext
icons, images, manifest.json, mrbeasify.js
```

This is your Firefox add-on.

> **⚠️ CAUTION**
> Rename `manifest v3.json` to `manifest.json`.

This is your Chrome extension.

## 4. ☁️ Upload

### 🧩 Chrome

Go to the [Chrome Web Store](https://chrome.google.com/webstore/devconsole/3930a7e0-bab7-49ab-ad9c-e8f834f32649).

### 🦊 Firefox

Go to the [Firefox developer hub](https://addons.mozilla.org/developers/addons).
