# MASA QR Matrix Studio

Dual-mode QR matrix generator and image-based barcode/QR decoder application

## Technical Architecture

The application is architected with modular separation of concerns adhering to modern clean code standards:

- **Component Layering**: Isolated view layouts, state managers, and service controllers.
- **Defensive Engineering**: Robust input sanitization and exception management.
- **Modern Design Standards**: High-contrast dark-mode interface styled for optimal usability and visual polish.

## Preview

![Application Interface](screenshots/app_interface.png)

## Features

- High-density QR code synthesis with customizable error correction levels.
- Local image decoding extracting URLs, text, and binary payload strings.
- PNG export facility with automatic clipboard sync.
- Modern tabbed architecture separating encoder and decoder workflows.

## Prerequisites

- Python 3.10 or higher
- Required packages:

```bash
pip install customtkinter pillow requests
```

## Execution

Launch the application via Python:

```bash
python "QR Code Reader & Generator App in Python/main.py"
```

## Project Structure

```
.
├── QR Code Reader & Generator App in Python
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
