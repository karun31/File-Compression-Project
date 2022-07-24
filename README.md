# File-Compression-Project

## Introduction
The project is to design compression and decompression programs using Huffman Coding. The idea is to assign variable length codes to input characters based on their frequencies. The more the frequency of the character the shorter the code assigned to it.

## Implementation
The program has been implemented in C++ language. The idea is to reduce the weighted expected storage by means of assigning shorter codes to frequently occurring characters.
### Compression:
Provide the input.  
Note the frequency of all the characters in the input.  
Construct a min priority queue with respect to the frequencies of the characters.  
Construct Huffman Tree from the priority queue.  
Encode the file, store the encoding table and compress the input based on the encoding table.  

***The codes are stored as bits and each character is provided a prefix code which is a string of bits.***
![Encode func](https://user-images.githubusercontent.com/107580357/180644597-bc0c5873-f681-4285-8ab5-feb8fb3f8206.jpg)



### Decompression:
Open the file and reconstruct the Huffman Tree based on the Encoded table.  
Decode the file and store it to the desired file.  

![decode func](https://user-images.githubusercontent.com/107580357/180644617-449e5894-9868-4c04-abef-306b886ba94b.jpg)

### Compression Rate:
A compression varying from 6-7% of the initial input file is achived.

![Compression Rate](https://user-images.githubusercontent.com/107580357/180644767-f6551498-9211-4843-b200-81006cc26311.jpg)

### Output:
![Output](https://user-images.githubusercontent.com/107580357/180644774-e35d7353-7f13-45ff-a3b9-48c85bdeef03.jpg)

