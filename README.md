<center>
  <h1 align="center">Volume Manager</h1>
  <h3 align="center">A simple Chrome extension to control any tab's volume separately.</h3>
</center><br>

# Introduction

* Click on the extension icon and drag the slider to adjust the volume of the active tab
* You can reduce its volume down to 0% and boost it up to 600%
* The current volume is displayed as a badge next to the icon

There are several similar extensions. However, they're either filled with telemetry and analytics, or their UI sucks.

# Installation
<a href="https://chrome.google.com/webstore/detail/volume-manager/imhcgcnjkibjikdbdgnhclihigkooeaf"><img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_128x128.png" width="48" /></a>

# Local install
1. Clone this repository
2. Run `npm install && npm run build`
3. Go to `chrome://extensions/`, enable developer mode and load `dist` folder as an unpacked extension
