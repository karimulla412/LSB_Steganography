# LSB Steganography with MLEA Encryption

This project hides encrypted messages inside images using **Least Significant Bit (LSB)** steganography combined with a **magic square embedding pattern** and **MLEA encryption**.

---

## Features

- Secure message encryption with MLEA algorithm.
- Embeds encrypted message bits into the blue channel of an image using a magic square pattern.
- Extracts and decrypts the hidden message from the stego image.
- Calculates image quality metrics: Mean Squared Error (MSE) and Peak Signal-to-Noise Ratio (PSNR).
- Visual side-by-side comparison of original and stego images.

---

## How to Use

1. Place your input image (e.g., `lion.png`) inside the project folder.
2. Run the Python script or Jupyter notebook.
3. When prompted, enter the secret message you want to hide.
4. The program will generate a random encryption key, embed the encrypted message into the image, and save the stego image as `stego_image.png`.
5. The program will then extract and decrypt the message from the stego image and verify it matches the original.
6. Image quality metrics (MSE and PSNR) will be calculated and displayed.

---

## Requirements

Make sure you have Python 3.x installed along with the following packages:

- OpenCV (`cv2`)
- NumPy
- Pillow (`PIL`)
- Matplotlib
- IPython (for displaying images in notebooks)



## Contact

If you have any questions, feedback, or would like to collaborate, feel free to reach out!

You can contact me by email at **kasmur8096@gmail.com** or connect with me on:

I would love to hear from you!
