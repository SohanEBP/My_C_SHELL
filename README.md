# C-Shell — Custom Unix Shell in C

A fully functional Unix-inspired command-line shell engineered in C with support for process management, piping, I/O redirection, signal handling, background execution, and custom shell utilities.

This project demonstrates practical systems programming, Linux internals, process control, and operating system concepts through the implementation of a modular shell environment supporting both standard Unix behaviors and custom-built commands.

---

# 🚀 Key Highlights

- Custom Unix shell implementation in C
- Foreground & background process execution
- Multi-stage piping and I/O redirection
- Signal handling (`SIGINT`, `SIGTSTP`)
- Process monitoring and activity tracking
- Custom shell commands and aliases
- HTTP-based online manpage retrieval
- Linux process inspection utilities
- `.myshrc` support for shell customization

---

# ✨ Features

## ⚙️ Command Execution

- Supports execution of system and custom shell commands
- Handles multiple commands separated by `;` and `&`
- Implements foreground and background process execution
- Tracks long-running foreground processes dynamically

---

## 📁 Directory Navigation (`hop`)

Custom implementation of Unix-like `cd` functionality with support for:
- Relative and absolute paths
- `~` home directory resolution
- Previous directory tracking using `-`
- Intelligent path handling logic

---

## 📂 File & Directory Listing (`reveal`)

Custom implementation inspired by `ls`:
- Displays files, directories, and executables
- Hidden file support
- Detailed permission formatting
- Lexicographically sorted output

---

## 🧠 Process Inspection (`proclore`)

Linux process analysis utility supporting:
- PID inspection
- Process state monitoring
- Memory usage details
- Shell process introspection

---

## 🔍 Recursive File Search (`seek`)

Filesystem traversal utility supporting:
- File discovery
- Executable detection
- Directory filtering
- Recursive path searching

---

## 📝 Command Logging System (`log`)

- Stores recent shell history
- Prevents redundant duplicate logging
- Supports history viewing and clearing
- Optimized command tracking logic

---

## 🔗 Unix Piping & Redirection

Supports:
- Multi-stage pipelines using `|`
- Input redirection `<`
- Output redirection `>`
- Append mode `>>`
- Combined piping and redirection workflows

---

## 🛡️ Signal Handling

Implements Linux signal management:
- `SIGINT` (`Ctrl+C`)
- `SIGTSTP` (`Ctrl+Z`)
- Child process signal isolation
- Foreground process control

---

## 🌐 iMan — Internet Manual Pages

Custom HTTP-based online manpage fetcher:
- Sends GET requests to remote manpage servers
- Parses HTTP responses
- Removes HTML tags dynamically
- Displays clean terminal-friendly documentation

---

## ⚡ Activities Tracker

Tracks:
- Background jobs
- Foreground jobs
- Process execution states
- Active process metadata

---

## 🧬 Neonate

Custom Linux utility for:
- Monitoring newly spawned child processes
- Periodic PID tracking
- Interactive keyboard-based termination

---

# 🏗️ Systems Programming Concepts Demonstrated

This project demonstrates practical understanding of:

- Linux Systems Programming
- Process Management
- Fork/Exec System Calls
- Signal Handling
- File Descriptor Manipulation
- Inter-Process Communication (IPC)
- Unix Shell Architecture
- TCP Socket Programming
- Command Parsing
- Operating System Internals
- Concurrent Process Execution

---

# ⚙️ Build & Run

## Compile

```bash
make
```

## Run Shell

```bash
./a.out
```

or

```bash
./myshell
```

---

# 🖥️ Environment

- Linux / Unix-based systems
- GCC Compiler
- Makefile Support

---

# 👨‍💻 Author

### Sohan Saha

Computer Science Engineering (IoT & Cybersecurity)  
Heritage Institute of Technology

- GitHub: https://github.com/SohanEBP
- LinkedIn: https://linkedin.com/in/sohan-saha

---

# ⭐ Project Goal

This project was developed to strengthen practical understanding of:

- Operating Systems
- Linux Internals
- Systems Programming
- Process Scheduling
- Shell Architecture
- Unix Command Execution

while implementing a production-style command-line shell environment from scratch in C.

---

# 📄 License

MIT License — Free to use for educational and portfolio purposes.
