# PNG Recolor Live-Tool

An interactive browser-based utility for live recoloring of PNG images. Drag and drop up to 25 PNGs into the drop zone, pick a new color, and download the processed images individually.

## Features

* **Drag & Drop**: Seamless drag-and-drop support for up to 25 PNG files.
* **Color Shift**: Real-time hue replacement while preserving brightness, saturation, and transparency.
* **Eyedropper Mode**: Automatically picks the dominant center color of the first image or lets you select any pixel.
* **High Fidelity**: Maintains image details and contrasts without artifacts.
* **Individual Download**: Save each recolored PNG in its original resolution.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/RiseVDevelopment/Simple-Bulk-Image-Colorshifting-Tool.git
   ```
2. **Navigate into the folder**

   ```bash
   cd Simple-Bulk-Image-Colorshifting-Tool
   ```
3. **Open in browser**

   * Double-click `index.html` or serve it with a static server.

## Usage

1. Open `index.html` in a modern browser (Chrome, Firefox, Edge).
2. Drag and drop your PNG files into the drop zone (max. 25 files).
3. The tool auto-selects the center color of the first image.
4. Click the **Eyedropper** button to manually pick any pixel’s color.
5. Adjust the target hue via the color picker or by entering HEX/RGB/HSL values.
6. Hit **Download All** to export each recolored PNG.

## Code Highlights

* **HTML5 Canvas**: Direct pixel manipulation in JavaScript.
* **Color Math**: HSL conversions to shift hue accurately.
* **FileSaver.js**: Enables download of raw PNG blobs.

## Contributing

Contributions are welcome! Please submit issues or pull requests on GitHub.

## License

MIT License © RiseV Development
