# Image Steganography in Java

## Overview

**Image Steganography in Java** is a desktop application that allows users to securely embed and extract secret messages within images using steganography techniques. This project provides a simple, cross-platform GUI (built with Java Swing) for safe and private communication.

> **Steganography** is the practice of hiding messages or information within other non-secret text or data. In this project, you can hide text messages inside image files.

## Table of Contents

- [Features](#features)
- [Technology Used](#technology-used)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Encrypt and Decrypt Messages:** Hide and retrieve secret messages inside images.
- **Passcode Protection:** Secure your data with a passcode for extra privacy.
- **GUI Interface:** User-friendly interface built with Java Swing.
- **Cross-Platform Support:** Runs on Windows, macOS, and Linux.
- **Image File Support:** Works with standard image formats like JPG (and optionally PNG).
- **Real-Time Status Updates:** Shows progress during encryption and decryption.

## Technology Used

- **Programming Language:** Java (JDK 8+)
- **Libraries/Frameworks:**
  - Java Swing (for GUI)
  - Java AWT (for image handling/UI layout)
  - Java ImageIO (for image read/write)
  - Java File Handling
- **Development Environment:** Eclipse, IntelliJ IDEA, NetBeans, or any Java IDE

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Akhil200324/Steganography-Java.git
   cd Steganography-Java
   ```

2. **Open the project** in your favorite Java IDE (Eclipse, IntelliJ IDEA, etc.).

3. **Ensure Java JDK 8 or later is installed** on your system.

4. **Build and run** the project from your IDE.

## Usage

### Encrypt a Message

1. Launch the application.
2. Click the **Select Image** button and choose a cover image.
3. Enter your secret message and a passcode.
4. Click **Encrypt** to embed the message.
5. Save the newly created steganographic image.

### Decrypt a Message

1. Launch the application.
2. Select the image that contains a hidden message.
3. Enter the passcode used during encryption.
4. Click **Decrypt** to reveal the hidden message.

## Troubleshooting

- **Image not loading?**  
  Ensure the image is in a supported format (JPG, optionally PNG/BMP).
- **Wrong passcode?**  
  The correct passcode is required to decrypt and reveal the message.
- **Application won't start?**  
  Verify that you have Java JDK 8 or newer installed and properly set up in your system’s PATH.

## Contributing

Contributions are welcome!  
To contribute, please fork the repository, create a new branch, and submit a pull request.  
For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).  
<!-- If you want to use a different license, specify here and add the file accordingly. -->

## Acknowledgments

- Java official documentation
- Open-source steganography research
