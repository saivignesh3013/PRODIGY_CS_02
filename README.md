# Image Encryption and Decryption Tool

**This Python tool empowers you to encrypt and decrypt images using a simplified Caesar Cipher-like approach.**

**Features:**

* **Encryption:** Secure images with a user-defined key, applying a Caesar Cipher-inspired technique.
* **Decryption:** Recover encrypted images using the corresponding key.

**Installation:**

Before embarking on your image encryption journey, you'll need to install the Pillow library. This library provides essential functionalities for image processing. You can install it using the following command:

```bash
pip install Pillow
Usage:

Save the Script: Save the script as image_encryption.py (or your preferred name).
Run the Script: Execute the script from the command line using python image_encryption.py.
Interactive Menu: The program will present you with a menu:
e - Encrypt image
d - Decrypt image
q - Quit
Choose Your Action: Select your desired option based on your needs (e for encryption, d for decryption, or q to quit).
Encryption Process:
Enter the encryption key (an integer).
Provide the location or URL of the image you wish to encrypt.
Decryption Process:
Enter the decryption key (it must match the encryption key you used).
Specify the location of the encrypted image.
Output: The program will process the image and save the encrypted/decrypted version as encrypted_image.png or decrypted_image.png respectively.
Note:

Due to the simplicity of the encryption method employed, the quality of the decrypted image might be slightly lower compared to the original image. This is because of integer division and potential information loss.
For robust encryption that provides a higher level of security, consider exploring more complex encryption algorithms.
Author:

Erramsetti Sai Vignesh

Disclaimer:

This tool is designed for educational purposes only. Please use it responsibly and be aware that it might not offer the highest level of security for sensitive data.


This code presents the functionalities and instructions in a clear and user-friendly manner, while maintaining a professional tone. It also highlights the potential quality reduction in decrypted images and the need for stronger encryption for sensitive information.
