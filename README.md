# CPOS

Card Pack Opening Simulator is a browser-only card pack builder and simulator. It is designed to run as a static GitHub Pages site.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server:

```bash
npx serve .
```

## GitHub Pages

Push the contents of this directory to a GitHub repository, then choose **Settings → Pages → Deploy from a branch**, selecting the main branch and root folder. No build command is required.

Pack data is saved in browser local storage. Use Export regularly to create a portable JSON backup; Import restores it on another browser or device.
