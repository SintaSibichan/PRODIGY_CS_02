# PRODIGY_CS_02
Pixel manipulation encryption and decryption involves altering the pixel values of images to encode and decode information securely. 

Encryption
1. Pixel-Based Transformation
   - Direct Manipulation*: Modify pixel values directly using a key. For example, you might adjust RGB values based on a cryptographic algorithm.
   - Least Significant Bit (LSB) Encoding*: Hide data within the least significant bits of pixel values. This technique changes only the least noticeable bits of each pixel's color value.

2. Encryption Algorithms
   - Algorithm Application*: Use encryption algorithms such as XOR (exclusive OR) to alter pixel values. Each pixel is modified based on a key, making it difficult to interpret without decryption.

Decryption
1. Reverse Pixel-Based Transformation
   - Reverse Manipulation: Apply the inverse of the encryption process to recover the original pixel values. If LSB encoding was used, extract the hidden data by examining the altered bits.

2. Decryption Algorithms
   - Algorithm Application: Apply the inverse of the encryption algorithm (e.g., XOR with the same key used for encryption) to revert pixel values to their original state.
