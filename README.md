# 🚀 File Compression Software  

A powerful and efficient file compression tool that allows you to **Zip** and **Unzip** files using two advanced algorithms:  

1. **Huffman Coding** – Ideal for compressing data with high redundancy.  
2. **Lempel-Ziv-Welch (LZW) Algorithm** – Optimized for faster compression without extra dictionary storage.  



## 📌 Compression Algorithms  

### 🔹 Huffman Coding  
Huffman’s algorithm replaces each byte of the input file with a unique bit sequence. It generates a one-to-one mapping of bytes and binary sequences, stored in a dictionary. While effective, it requires extra space for storing the encoding scheme.  

### 🔹 Lempel-Ziv-Welch (LZW)  
LZW compression eliminates the need for an external dictionary by dynamically building a mapping of **multiple-byte sequences** to binary codes during compression. This method is efficient for compressing repetitive patterns and structured data.  



## 🚀 How to Run  

Run the software using the following command:  
```bash
java -jar FileCompression.jar
```  

![File Compression GUI](/git_resource/outlook.png?raw=true "File Compression GUI")  


## 📂 How to Use  

### 🔹 Compress (Zip) a File  
1. **Go to:** `File > Open`  
2. **Click:** `Zip`  
3. The compressed file will be saved in the **same folder** as the original.  

### 🔹 Decompress (Unzip) a File  
1. **Go to:** `File > Open`  
2. **Click:** `Unzip`  
3. The extracted file will be saved in the **same folder** as the compressed file.  


## 🖥️ Tested Environments  

This software has been tested and verified to work on:  
✅ **Linux Mint**  
✅ **macOS El Capitan (10.11.6)**  



⚡ **Fast, efficient, and easy to use—compress your files with ease!** ⚡  

 
