# KVRouite to Shotcut MLT Converter

A fast, lightweight, and 100% client-side web application that converts **KVRouite** project files (`.KVRouiteproj`) into **Shotcut** project files (`.mlt`).

🔗 **Live Tool:** [https://mcsanady.github.io/kvrouite-to-shotcut/](https://mcsanady.github.io/kvrouite-to-shotcut/)

## Features
- **100% Client-Side & Private:** All conversion logic runs directly in your web browser. No project data or filenames ever leave your machine.
- **Accurate Transitions:** Faithfully translates cut intervals, symmetrical crossfades (`lumaMix`), and multi-chapter GoPro sequences across continuous files.
- **Path Remapping:** Easily replace drive/folder paths if transferring projects across different computers or operating systems (e.g. Linux to Windows).
- **Zero Install:** Works instantly in any modern browser without installing Python or dependencies.

## Usage
1. Open the [web app](https://mcsanady.github.io/kvrouite-to-shotcut/).
2. Drag and drop your `.KVRouiteproj` file onto the drop zone.
3. (Optional) Adjust target resolution, frame rate, or path remapping.
4. Click **Generate & Download Shotcut (.mlt)** and open the downloaded project directly in Shotcut!

## License
MIT
