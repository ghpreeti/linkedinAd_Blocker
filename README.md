
# LinkedIn AdBlocker

LinkedIn AdBlocker is a Chrome extension that removes ads from LinkedIn.

## Features

- Blocks ads on LinkedIn.
- Simple and lightweight.
- Easy to install and use.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/LinkedInAdBlocker.git
    cd LinkedInAdBlocker
    ```

2. Open Chrome and go to `chrome://extensions/`.

3. Enable "Developer mode" using the toggle in the top-right corner.

4. Click "Load unpacked" and select your extension's directory.

## Usage

Click the extension icon in the Chrome toolbar to open the popup. Click the "Remove Ads" button to block ads on LinkedIn.

## Files

- `manifest.json`: Contains metadata about the extension and specifies the background script and content scripts.
- `extensive.js`: Listens for navigation changes and injects the ad-blocking script into LinkedIn.
- `linkedin.js`: The script that removes ads from LinkedIn.
- `popup.html`: The HTML file for the extension's popup.
- `popup.js`: The script that handles the popup's functionality.
- `noAdd.png`: The icon for the extension.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements.


