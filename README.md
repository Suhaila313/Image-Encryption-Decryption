# 🔐 Image Encryption and Decryption

This project demonstrates a simple approach to image encryption and decryption using Python. It shows how an image can be transformed using encryption techniques and later decrypted to retrieve the original visual content.

## 📌 Project Overview

- Encrypts an image using basic image manipulation techniques.
- Decrypts the encrypted image to retrieve the original version.
- Displays side-by-side comparison of original, encrypted, and decrypted images.

## 📷 Preview

| Original Image | Encrypted Image | Decrypted Image |
|----------------|------------------|------------------|
| ![original](images/original.png) | ![encrypted](images/encrypted.png) | ![decrypted](images/decrypted.png) |

> *(Add your actual image paths in the repo)*

## 🛠️ Technologies Used

- Python
- OpenCV (`cv2`)
- NumPy
- Jupyter Notebook / Python Script

## 🚀 How It Works

1. **Encryption:**
   - Each pixel's value is modified using a simple algorithm (e.g., bitwise NOT, XOR with a key, or color inversion).
2. **Decryption:**
   - The encryption process is reversed to get back the original image.

## 📁 Folder Structure

