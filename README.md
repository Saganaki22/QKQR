# QKQR - Quick QR Code Generator

QKQR is a fast, user-friendly QR code generator web application that allows users to create customizable QR codes for various purposes such as URLs, text, contact information, Wi-Fi credentials, and geographical locations.

![image](https://github.com/user-attachments/assets/141c4c8f-36a7-4744-a7fe-4978955adc9b)


## Features

- **Multiple QR Code Types**: Generate QR codes for URLs, plain text, contact information (vCard), Wi-Fi network credentials, and geographical locations
- **Customization Options**: Customize QR code colors, size, error correction level, and add logos
- **Export Options**: Download QR codes as PNG images or SVG vector files
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Modern UI**: Clean, intuitive interface with 8-bit retro styling elements
- **No Server Dependency**: Entirely client-side implementation for privacy and performance
- **Share Feature**: Share QR codes directly using the Web Share API (where supported)

## Architecture

QKQR is built using a client-side only architecture with the following technologies:

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **JavaScript**: Core functionality and interactivity
- **Canvas API**: For rendering and exporting QR codes as PNG images
- **WebGL**: Used for background shader effects on the 404 page
- **Web Share API**: For sharing QR codes (on supported browsers)

## Libraries and APIs

QKQR uses the following libraries and APIs:

- **QRCode.js** (v1.0.0): Primary QR code generation library
- **QRCode-SVG** (v1.1.0): For generating vector-based QR codes
- **Phosphor Icons**: For UI icons
- **Google Fonts API**: For typography (Inter and Press Start 2P fonts)
- **Google Maps Search API**: For location QR codes

## Getting Started

Open the `index.html` file in a modern web browser to generate QR codes. No installation, server setup, or build process is required.
Everything is client side, no data is collected or stored anywhere, ever!

## Browser Compatibility

QKQR works best in modern browsers including:
- Google Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for enhancements, bug fixes, or feature requests.

## License

This project is licensed under the Apache License 2.0 - see below for details:

```
Copyright 2023 QKQR

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
![og-image](https://github.com/user-attachments/assets/348d00c2-3c0a-45fd-8e1e-1ef939933517)

