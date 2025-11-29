#  Image Encryption Tool (Tkinter GUI)

A simple Python GUI application for encrypting and decrypting images using **XOR** and **reversible pixel swap** methods. Built with **Tkinter**, **Pillow**, and **NumPy**, this project demonstrates basic cryptography concepts in a visual and interactive way.

---

##  Features
- Encrypt and decrypt images with:
  - **XOR method** (symmetric, requires a numeric key)
  - **Swap method** (reversible pixel swapping)
- Supports common formats: `.jpg`, `.png`, `.bmp`
- Easy-to-use Tkinter interface:
  - Browse and select an image
  - Choose encryption method
  - Enter a key (for XOR)
  - Save encrypted/decrypted images automatically

---

##  Requirements
Make sure you have Python 3 installed. Then install dependencies:

```bash
sudo apt update
sudo apt install -y python3 python3-tk python3-pil python3-numpy
python3 -m pip install --upgrade pillow numpy
 Usage
- Clone or download this repository.
- Save the script as image_encryptor.py.
- Run the program:
python3 image_encryptor.py


- Use the GUI:
- Browse to select an image.
- Choose XOR or Swap method.
- Enter a key (only for XOR).
- Click Encrypt or Decrypt.
- Output images are saved in the same folder as the original, with suffix:
- _encrypt.png
- _decrypt.png
