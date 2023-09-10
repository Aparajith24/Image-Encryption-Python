# Chaotic Map Encryption on Compressed Images

### Chaotic Map

Chaotic maps are mathematical functions characterized by their sensitivity to initial conditions and their chaotic behavior. They are used in image encryption to generate pseudo-random sequences for encryption keys, enhancing image security.

### Arnold Cat Map

The Arnold cat map is a two-dimensional chaotic map used in image processing and cryptography. It shuffles pixel positions in an image, increasing diffusion and making it challenging to decipher the original content without decryption.

### Deflate Compression Algorithm

Deflate compression, used in formats like PNG and ZIP, reduces data redundancy. It employs LZ77 and Huffman coding to replace repeated patterns with shorter codes, achieving efficient data compression.

## Objective

The primary goal of this project is to implement an efficient encryption and compression algorithm for images. It involves:

1. Encrypting the image using Arnold cat map.
2. Compressing the encrypted image using the Deflate Algorithm (combining LZ77 and Huffman coding).

### Deflate-based Compression Technique

The Deflate algorithm is used to compress images. It involves LZ77 for finding repeated patterns and Huffman coding for efficient coding. The compression process is reversible during decompression.

### Chaotic Map-based Encryption Method on Compressed Images

This method combines the Arnold cat map for confusion and the Henon map for diffusion of the image. Arnold cat map rearranges pixel positions, while the Henon map generates pseudo-random sequences to scramble the image.

### Inflate-based Decompression Technique

Inflate-based decompression reverses the Deflate compression process. It sequentially processes compressed blocks using Huffman coding and LZ77-based sliding window techniques, reconstructing the original image data.

### Chaotic Map-based Decryption Method on Images

Decrypting images involves applying inverse transformations of both the Arnold cat map and Henon map in reverse order. This restores the original image data.

## Results and Discussions

- Simulation results comparing image sizes before and after compression.
- Visual comparisons of images before compression, after compression, after encryption, and after decryption and decompression.
- Histogram analysis results.

## Conclusion

In conclusion, the implementation of Chaotic Map-based encryption on compressed images shows promise for enhancing data security while preserving data integrity. Further research is needed to evaluate its robustness against various attacks and optimize computational complexity. Chaotic Map-based encryption holds potential for securing compressed image data across diverse applications.
