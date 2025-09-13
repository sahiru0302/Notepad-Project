 ✨ Notepad Mini — Java Swing Text Editor



> 🖋️ A lightweight **Notepad-style text editor** built with pure **Java Swing**.  
> Developed as a coursework project to demonstrate GUI programming, file I/O, and user-friendly design.



 📌 About

**Notepad Mini** is a minimal desktop text editor designed in Java Swing.  
It provides the core features of Windows Notepad, plus extras like font customization, text color, and a modern look.

👨‍💻 Author:Praveen  
🆔 Student ID: 2022s19243  



## ✨ Features

- 📂 **File Menu** — New, Open, Save, Save As, Exit  
- ✂️ **Edit Menu** — Cut, Copy, Paste, Select All  
- 🎨 **Format Menu** — Font chooser dialog, Text color picker  
- ℹ️ **Help Menu** — About dialog (shows author details)  
- 💾 **File Handling** — Reads/writes files with UTF-8 encoding  
- ⚡ **Keyboard Shortcuts** — Standard Notepad-style (Ctrl+N, Ctrl+O, Ctrl+S, etc.)  
- 🎭 **Cross-Platform** — Works on Windows, macOS, and Linux  



## ⚙️ Setup Instructions

### 1. Requirements
- **Java 8 or later** (tested with Java 17 & Java 21)  
- Any Java IDE (IntelliJ, Eclipse, VS Code) OR JDK command-line tools  

### 2. Running the Program

#### Option A — Run with an IDE
1. Open your IDE.  
2. Create a new Java project.  
3. Add the file `NotepadMini.java` to your `src/` folder.  
4. Run the `main` method inside the `NotepadMini` class.  

 Option B — Run from Command Line
```bash
# Compile
javac NotepadMini.java

# Run
java NotepadMini
```

 Option C — Build a Runnable JAR (Optional)
```bash
# Compile
javac NotepadMini.java

# Create manifest file
echo "Main-Class: NotepadMini" > manifest.mf

# Package into JAR
jar cfm NotepadMini.jar manifest.mf NotepadMini.class

# Run the JAR
java -jar NotepadMini.jar
```



 📝 Assumptions & Notes
- Text files are read and written using **UTF-8 encoding**.  
- If no extension is given when saving, `.txt` will be added automatically.  
- Font dialog lets you select **family, style, and size**.  
- About dialog contains **your name and student ID**.  
- The app uses the **system look and feel** for a native appearance.  
- No external libraries are required — this is **pure Java SE**.  




 📂 Project Structure

```
/ (repository root)
├─ NotepadMini.java   # Complete Java Swing source code
└─ README.md          # This documentation
```



 ✅ Technical Requirements

- **Java Version:** Java 8 or later  
- **Dependencies:** None (uses only standard Java Swing & AWT)  
- **Platforms:** Windows, macOS, Linux  




 🎉 Credits

- Built with ❤️ using **Java Swing**  
- Inspired by Windows Notepad, but extended with customization features  
- Developed as part of coursework submission  



 ✨ *“Great things are done by a series of small things brought together.” — Vincent van Gogh*  
