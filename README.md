# Image Encryption and Decryption Tool

This Python tool allows you to encrypt and decrypt images using a simple Caesar Cipher-like approach.

**Features:**

* Encrypts images using a user-provided key.
* Decrypts encrypted images using the same key.

**Installation:**

Before using this tool, you need to install the Pillow library, which provides image processing functionalities. You can install it using the following command:

```bash
pip install Pillow

Usage:
Run the script: python image_encryption.py (replace image_encryption.py with your actual script name)
The program will display a menu:
e - Encrypt image
d - Decrypt image
q - Quit
Choose your desired option (e for encryption, d for decryption, or q to quit).
If you select encryption (e):
Enter the encryption key (an integer).
Enter the location or URL of the image you want to encrypt.
If you select decryption (d):
Enter the decryption key (must match the encryption key you used).
Enter the location of the encrypted image.
The program will process the image and save the encrypted/decrypted version as encrypted_image.png or decrypted_image.png respectively.

Note:
Due to the simplicity of the encryption method used, the quality of the decrypted image might be slightly lower compared to the original image. This is because of integer division and potential information loss.
For stronger encryption, consider exploring more complex encryption algorithms.

Author:
Erramsetti Sai Vignesh

Disclaimer:
This tool is for educational purposes only. Please use it responsibly and be aware that it might not provide a high level of security for sensitive data.
