# Zyron 2.0

"Math Punch" is a modern, high-performance web-based proxy application that provides a seamless "Virtual Browser" experience. Built on the **Shader Proxy Engine** and **BareMux** transport, it allows for secure, tab-based web navigation through a robust Service Worker architecture.

## Features

- **Tab-Based Browsing**: Manage multiple browsing sessions within a single page.
- **Service Worker Proxy**: Efficiently intercept and proxy network requests.
- **Alpine.js UI**: Lightweight and reactive user interface.
- **Customizable Bookmarks**: Save and manage your favorite web apps.
- **Math Theme**: A clean, math-inspired aesthetic.

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/shuttlenetwork/math-punch.git
   cd math-punch
   ```

2. Serve the directory using any static file server:
   ```bash
   npx serve .
   ```

3. Open your browser to `http://localhost:3000`.

## Architecture

- `index.html`: Main UI and application logic.
- `shader-canvas.js`: High-level controller for managing multiple browsing surfaces.
- `shader-client.js`: Core client logic for each tab.
- `compute.js`: The Service Worker that handles request proxying.
- `shader.config.mjs`: Configuration for the proxy engine.

## License

This project is licensed under the MIT License.
