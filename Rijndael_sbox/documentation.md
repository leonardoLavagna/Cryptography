## Rijndael S-Box

The goal of this project is to gain a better understanding of the arithmetic in Rijndael's finite field (underlying the [AES blockcipher](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)). We will write a program able to perform the basic operations in Rijndael's finite field, using the extended Euclidean algorithm for computing the multiplicative inverse of a polynomial. Next, we will use that program to re-generate the [AES S-Boxes](https://en.wikipedia.org/wiki/Rijndael_S-box) (for both encryption and decryption).

### What's in here?
- The Jupyter Notebook of the project with all the code and comments `Rijndael_S_Box.ipynb`
- The script `s_box.py` with all the assambled code to generate an S-Box (the relevant code is also present, but scattered, in the notebook)

