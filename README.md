# stegjs-demo

Demo of steganography using JavaScript in a simple image

## Overview
This project demonstrates how to use steganography to hide a text message within an image using JavaScript. The Least Significant Bit (LSB) method is used to encode the message into the pixel data of the image, ensuring minimal visual distortion. The message length is also embedded into the image to facilitate decoding.

## Key Concepts

### Steganography
Steganography is the practice of hiding secret data within an ordinary, non-secret file or message to avoid detection. In this project, we hide a text message inside an image.

### Least Significant Bit (LSB) Method
The LSB method is a common technique in steganography where the least significant bit of each pixel's color channels (Red, Green, and Blue) is modified to encode the secret message. Since the LSB represents a very small portion of the overall color value, changes to this bit typically result in minimal visual distortion.
