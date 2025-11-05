# 📞 Phone Book Management System in C

This is a console-based **Phone Book Management System** developed in **C language** using **Code::Blocks**.  
It allows users to **store, search, modify, list, and delete** contact information easily from a simple terminal interface.  
All contact data is saved permanently in a text file.

---

## 🚀 Features

- Add new contact (name, address, gender, email, phone number)
- Search existing contact by name
- View all saved contacts
- Modify contact details
- Delete a contact
- File-based data storage for persistence
- Console-based UI using `gotoxy()` and ASCII design

---

## 🛠️ Technologies Used

- **Language:** C  
- **IDE:** Code::Blocks  
- **File Handling:** Used for storing and retrieving contact data  
- **Libraries Used:**  
  `stdio.h`, `conio.h`, `windows.h`, `dos.h`, `string.h`

---

## 💻 How to Run the Program

1. Open the project in **Code::Blocks** or any C compiler (Windows recommended).  
2. Make sure the source file (e.g., `phonebook.c`) is saved in your project folder.  
3. Click **Build and Run** (or press `F9`).  
4. Follow on-screen menu options:
   - `1` → Add New Contact  
   - `2` → Search Contact  
   - `3` → List All Contacts  
   - `4` → Modify Contact  
   - `5` → Delete Contact  
   - `6` → Exit  

---

## 📂 File Used

- `phoneBook.txt` → Stores all contact information  
- `temp.txt` → Used for modifying and deleting records  

---

## 🧠 Concepts Used

- File Handling (`fopen`, `fprintf`, `fscanf`)
- String Manipulation (`strcmp`, `gets`, `scanf`)
- Console Cursor Control (`gotoxy()`)
- Menu-driven program design
- Basic data persistence

---

## 📜 Sample Output (CLI)

