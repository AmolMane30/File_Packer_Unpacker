# 🗂️ File Packer & Unpacker

**Technology:** Java Programming
**Interface Type:** Command Line User Interface (CUI)

---

## 📘 Project Overview

The **File Packer & Unpacker** is a Java-based file utility tool designed to simplify file management operations.
It allows users to **pack multiple files** into a single archive and later **unpack** them back into their original form — with all metadata preserved (such as filename, size, and timestamp).

To ensure **data security**, the packed archive can be **encrypted**, making sure that only authorized users can decrypt and extract the content.

---

## 🚀 Features

### 🧩 File Packing

* Combines multiple files into a single archive file.
* Stores essential metadata:

  * File Name
  * File Size
  * Last Modified Timestamp
* Ensures file integrity and structure preservation.

### 📂 File Unpacking

* Extracts individual files from the packed archive.
* Restores all original metadata and file hierarchy.
* Detects and handles errors gracefully during extraction.

### 🖥️ Command Line Interface

* Simple, intuitive console-based interaction.
* Allows easy selection between **packing** and **unpacking** modes.
* Cross-platform — works on any OS with **Java Runtime Environment (JRE)** installed.

---

## 🧠 Learning Outcomes

This project helps in gaining practical exposure to:

* Java **File Handling** and **I/O Streams**
* **Metadata management** in file systems
* Concepts behind **archiving and compression utilities** (similar to ZIP or TAR)
* Command-line application development in Java
* Implementing **secure file operations** using Java APIs

---

## ⚙️ Requirements

* **Java Development Kit (JDK)** 8 or later
* **Operating System:** Windows / Linux / macOS
* **IDE (optional):** IntelliJ IDEA, Eclipse, or VS Code

---

## 🪜 How to Run

### 1️⃣ Compile

```bash
javac File_Packer.java
javac File_Unpacker.java
```

### 2️⃣ Execute

#### For Packing:

```bash
java File_Packer
```

#### For Unpacking:

```bash
java File_Unpacker
```

---

## 💡 Example Usage (Console Flow)

**Packing Phase:**

```
Enter Directory Name: DemoFiles
Enter Packed File Name: PackedData.txt
Packing in progress...
File1.txt Packed
File2.txt Packed
Packing Completed Successfully!
```

**Unpacking Phase:**

```
Enter Packed File Name: PackedData.txt
Unpacking in progress...
File1.txt Extracted
File2.txt Extracted
Unpacking Completed Successfully!
```

---

## 📁 Project Structure

```
├── File_Packer.java
├── File_Unpacker.java
└── README.md
```

---

## 🧰 GitHub Repository

[File Packer & Unpacker](https://github.com/AmolMane30/File_Packer_Unpacker)

---

## 👨‍💻 Author

**Amol Mane**
💻 *Aspiring Software Developer | Java, C, C++, Data Structures & OS Internals*
📫 [GitHub Profile](https://github.com/AmolMane30)

