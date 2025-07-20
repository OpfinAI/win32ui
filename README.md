# Win32UI

Win32UI is a Windows desktop UI project written in pure C, featuring custom-drawn window controls and bitmap graphics. It includes utilities for embedding and processing bitmap and font resources, and demonstrates custom UI rendering using raw pixel data.

## Features

- **Custom-drawn window controls**: All window buttons (close, maximize, minimize, restore) are rendered from embedded bitmap arrays.
- **Bitmap and font embedding**: Tools in `compiled_graphics/` convert BMP and TTF files into C arrays for direct inclusion in the application.

## Building

To build the main application and utilities, use a C compiler (e.g., MSVC or MinGW) on Windows.

## License

MIT License
