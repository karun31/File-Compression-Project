# File-Compression-Project

## Introduction
The project is to design compression and decompression programs using Huffman Coding. The idea is to assign variable length codes to input characters based on their frequencies. The more the frequency of the character the shorter the code assigned to it.

## Implementation
### Compression:
Provide the input.  
Note the frequency of all the characters in the input.  
Construct a min priority queue with respect to the frequencies of the characters.  
Construct Huffman Tree from the priority queue.  
Encode the file, store the encoding table and compress the input based on the encoding table.  

***The codes are stored as bits and each character is provided a prefix code which is a string of bits.***

### Decompression:
Open the file and reconstruct the Huffman Tree based on the Encoded table.  
Decode the file and store it to the desired file.  
