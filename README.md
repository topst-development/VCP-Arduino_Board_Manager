# TOPST VCP-G Arduino Board Manager

This repository hosts the Arduino Board Manager for TOPST VCP-G. This board manager allows users to easily add support for TOPST VCP-G boards to the Arduino IDE, enabling them to write and upload programs using familiar tools.

## Features

- Easy installation of board definitions for TOPST VCP-G.
- Compatible with Arduino IDE.
- Supports all major TOPST VCP-G board models.

## Installation

To install the TOPST VCP-G board manager in the Arduino IDE, follow these steps:

1. Open the Arduino IDE.
2. Go to `File > Preferences`.
3. In the "Additional Board Manager URLs" field, add the following URL:
   ```
   https://raw.githubusercontent.com/topst-development/VCP-Arduino_Board_Manager/main/package_topst_vcp_index.json
   ```
   If you already have other URLs in this field, separate them with commas.

4. Click "OK" to save the preferences.
5. Go to `Tools > Board > Boards Manager...`.
6. Search for "TOPST VCP-G" in the Boards Manager.
7. Click "Install" next to the entry for TOPST VCP-G.

## Usage

After installation, you can select your TOPST VCP-G board from `Tools > Board` menu in the Arduino IDE. Select the board that corresponds to your hardware, and then proceed to write and upload your sketches as usual.

## Support

For support, troubleshooting, and to report any issues, please visit the GitHub Issues page for this repository.

## Contributing

Contributions to the board manager are welcome. Please read the CONTRIBUTING.md file for guidelines on how to contribute effectively.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

