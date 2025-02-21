

# Secure Data Hiding in Image Using Steganography

# Introduction

This project implements image-based steganography to securely hide messages within images. The hidden messages can only be retrieved using a password, ensuring confidentiality and security.

# Features

Secret message embedding within an image.

Password-protected decryption to ensure authorized access.

Minimal image distortion, making detection difficult.

Supports different image formats.

# Technology Used

Programming Language: Python

Platform: VS Code

Libraries: OpenCV, OS, String Handling

Concepts: Steganography, Image Processing, Cryptography Basics

# Clone the repository:

git clone https://github.com/premkumarmistry/Secure-Data-Hiding-in-Image-Using-Steganography.git

Navigate to the project directory:

cd secure-data-steganography

Install required dependencies:

pip install opencv-python

# Usage

Encryption (Hiding Message)

# Run the script:

python encrypt.py

Enter the secret message and passcode.

The encrypted image will be saved as encryptedImage.jpg.

Decryption (Retrieving Message)

Run the script:

python decrypt.py

Enter the correct passcode.

The hidden message will be displayed.

# Example

Input Image: Prem.jpg

Secret Message: Hello, this is a secret!

Output Image: encryptedImage.jpg (Appears unchanged but contains the hidden message)

# Future Enhancements

Implement AES encryption for an additional security layer.

Extend to video-based steganography.

Develop a GUI-based application for ease of use.

Optimize storage algorithm to increase capacity while maintaining image quality.

# Contribution

Feel free to fork this repository, make improvements, and submit a pull request.

# License

This project is open-source and available under the MIT License.



[Provide Your GitHub Repository Link Here]

