# Smart Collector - Ultimate File Organizer

A powerful and beautiful file collection tool built with C++, ImGui, and GLFW. This application safely scans user folders (Downloads, Desktop, Documents, Pictures, Videos, Music) and organizes files into categorized folders based on extensions.

## Features

- **🎯 Multi-threaded File Collection**: Collect images, videos, archives, and ISO files with progress tracking.
- **📊 Real-time Progress**: Visual progress bars with detailed statistics.
- **🚫 Cancellation Support**: Cancel tasks at any time.
- **📈 Overall Statistics**: Track total files scanned, copied, and success rates.
- **📜 Activity Log**: Detailed logging with export functionality.
- **⚙️ Customizable Settings**: Adjust worker threads and manage logs.
- **🎨 Epic UI**: Modern dark theme with vibrant colors and smooth animations.
- **🖼️ Embedded Icon**: Custom application icon embedded in the executable.

## Supported File Types

- **Images**: jpg, jpeg, png, gif, bmp, tif, tiff, webp, heic, raw
- **Videos**: mp4, mkv, avi, mov, wmv, flv, webm, mpeg, mpg
- **Archives**: zip, rar, 7z, tar, gz, bz2, xz, tgz, tbz, tbz2, txz, cab, zipx
- **ISO**: iso
- **Custom**: Any extensions you specify

## Building

### Prerequisites
- CMake 3.20+
- C++17 compiler (MSVC, GCC, Clang)
- Windows (for native APIs)

### Build Steps
1. Clone or download the project.
2. Navigate to the project directory.
3. Run CMake:
   ```bash
   mkdir build
   cd build
   cmake ..
   cmake --build . --config Release
   ```
4. The executable will be in `build/Release/SmartCollector.exe`.

## Usage

1. Run `SmartCollector.exe`.
2. Select a destination folder.
3. Choose collection tasks (Images, Videos, etc.).
4. Monitor progress in the Tasks tab.
5. View logs and statistics.

## Project Structure

- `main.cpp`: Main application code.
- `SmartCollector.rc`: Resource file for the icon.
- `icon.ico`: Application icon.
- `CMakeLists.txt`: Build configuration.
- `external/`: Dependencies (ImGui, GLFW).

## Dependencies

- [ImGui](https://github.com/ocornut/imgui): GUI framework.
- [GLFW](https://www.glfw.org/): Window and input handling.
- Windows APIs: For file dialogs and shell operations.

## License

This project includes code from ImGui and GLFW, which have their own licenses. The main application code is provided as-is.

## Contributing

Feel free to fork and contribute improvements!

## Screenshots

[Add screenshots here if available]

---

Built with ❤️ using C++, ImGui, and GLFW.
