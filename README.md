# File Compressor

## Demo (Github Pages)
https://adriraj2000.github.io/File-Compression-Utility/


# About
A web app built for users to compress their text files. The user has a choice to compress his/her file using Huffman
or LZW (Lempel-Ziv-Welc) algorithm. The input is a .txt file, while the the encoded output file is a .huff file when Huffman compression is selected and .lzw file for the LZW case. These files cannot be read and accessed by users. The website also displays the compression ratio acheived while performing the compression.The user can also decode their encoded file and acheive their original text file.


# Underlying algorithm

## Huffman Algorithm
It is a lossless compression algorithm and an entropy encoding system, in which characters are converted into variable length codes. Most frequent characters are converted to shortest bit-strings while least frequent are assigned the longest. This algorithm works upon the huffman tree generated using the heap (min-heap) data structure.
The decoding is done by traversing the huffman tree and obtaining the original text.

## LZW Algorithm
It is also a lossless compression algorithm which succeeds the LZ family of compression, specifically LZ-78 which used to return both index and character and based on the sliding window technique. This algorithm makes use of the repetition of more longer words, which increase the compression ratio.A dictionary table is maintained for all characters (0-255) and new words being encountered are added to the table from 256 onwards.


# Built with
<li>CSS</li>
<li>JS</li>
<li>HTML</li>

---
**NOTE**
<ol>
  <li>For most of the text files tested,LZW algorithm is working more efficiently than Huffman</li>
  <li>For eg a text file of 69kb:
  <ul>
  <li>Using Huffman 56kb</li>
  <li>Using LZW 37kb</li>
  </li>

---






