# Image Cryptography

The encryption and decryption of the image for secure communication, both X-OR and AES algorithm are used.

<div align="center" >
<h2><a href="https://github.com/sripesh/imageCryptography/blob/main/imageCryptography_xor.ipynb">X-OR Algorithm</a></h2>
</div>

**X-OR** is the most basic way of cryptography which can crack by *brute force*, so it is not used in communication now-a-days. But to understand the way of encryption and decryption one can start with this method.
> No installation of package is required.

<div align="center" >
<h2><a href="https://github.com/sripesh/imageCryptography/blob/main/imageCryptography_AES.ipynb">AES Algorithm</a></h2>
</div>

**AES** is widely used toady as it is much stronger than DES and triple DES despite being harder to implement.
In this, points to remember
- AES is a block cipher, i.e. AES performs operations on bytes of data rather than in bits.
- The key size can be 128/192/256 bits, in this program 128 bits is used.
- Encrypts data in blocks of 128 bits each.

### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Crypto.

```bash
pip install crypto
```
```bash
pip install base64
```

## Usage

The program can be used for cryptography of any format of file. <br>
[![Test_Image](https://github.com/sripesh/imageCryptography/blob/main/image.jpg)](https://github.com/sripesh/imageCryptography/blob/main/image.jpg)
> This image is used for the cryptography.
<br>

One is only needed to change the `file_path` to the path of file that needs to be encrypt/decrypt.


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.