# PRODIGY_CS_02
Image Encryption and Decryption

This Python script provides a simple method for encrypting and decrypting images using a basic XOR operation. It allows you to secure image files by altering their pixel values based on a user-provided encryption key.

How It Works:

Encryption: Each pixel's RGB values are modified using an XOR operation with a specified key (an integer between 0 and 255).

Decryption: The same XOR operation is applied to the encrypted image using the same key, restoring the original image.

Usage:

Enter the encryption key: A number between 0 and 255 that will be used to alter pixel values.

Select mode: Choose 'encrypt' to secure the image or 'decrypt' to restore it.

Provide image paths: Specify the file paths for the input image and the output location where the result will be saved.

Requirements:


PIL (Python Imaging Library): Install using pip install Pillow.

This script is useful for basic image encryption tasks but is not intended for secure applications due to the simplicity of the XOR encryption method.
