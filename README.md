
# File Compresser(Huffman Coding)

Huffman coding implemtation in C++ for Compressing any text file by reducing space requirement of repeating character by changing ASCII 

Using data structure like priority Queue(min) , HashMap, Binary Tree.




## Run Locally

Clone the project

```bash
  git clone https://github.com/piyush4for/HuffmanCoding_Cpp
```

Go to the project directory

```bash
  cd piyush_FileCompresser
```

Compile Encryting File

```bash
  g++ encode.cpp huffman.cpp -o encoder
```

Start the Encrytion

```bash
  encoder.exe inputFile.txt compressedFile.huf 
```

For decryption

```bash
  g++ decode.cpp huffman.cpp -o decoder
```

Start the decryption

```bash
  decoder.exe compressedFile.huf outputFile.txt 
```


## Explanation

![HandWritten_Explanation](https://github.com/piyush4for/HuffmanCoding_Cpp/blob/main/piyushHandWritten.jpg)

