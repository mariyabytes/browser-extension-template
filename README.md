# Browser Extension Template

This is a template repository for hosting a cross-browser browser extension. It also has build scripts.

## Installation

### From public stores 

- [Firefox](https://addons.mozilla.org/en-US/firefox/)
- [Chrome/Chrome derivatives](https://chromewebstore.google.com/)

### Download and install
The extension is not yet published on the Firefox Add-on store or the Chrome Web store.
You can download the latest release (for your browser) from the [releases](/mariyabytes/releases) section.

To install the extension from the downloaded folder locally, follow the steps here:
- [Mozilla Firefox](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/)
- [Google Chrome/Chromium derivatives](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked)


### Build locally
To generate the extension zips/folders, run the script `generate_plugins.sh`.\
This will generate two versions of the extension (one for manifest v2 and one for v3).

```sh
# For Mozilla Firefox
build/firefox/v2

# For Google Chrome/Microsoft Edge/Chromium derivatives
build/chrome/v3
```

