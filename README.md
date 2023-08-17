# Huffman Coding Text File Compression in C

This repository contains an implementation of text file compression using the Huffman coding algorithm in the C programming language. Huffman coding is a popular algorithm used for lossless data compression, especially for text files. It works by assigning variable-length codes to different characters in the input text, with more frequent characters having shorter codes, resulting in efficient compression.

## Features

- Efficient Huffman coding algorithm implementation.
- Command-line interface for easy compression and decompression of text files.
- Detailed comments for better understanding of the code logic.
- Simple and straightforward file I/O operations in C.

## How it Works

1. The input text is read from a text file.
2. The frequency of each character in the text is calculated to build a frequency table.
3. A priority queue (min-heap) is used to create a Huffman tree based on the character frequencies.
4. The Huffman tree is traversed to generate the Huffman codes for each character.
5. The input text is then encoded using the generated Huffman codes.
6. The encoded text is written into an output binary file, along with the necessary information to reconstruct the Huffman tree during decompression.
