# 🧠 Operating Systems Lab – OSL

**Savitribai Phule Pune University | TE IT (2019 Course)**  
**GitHub Repo – Practical Assignments (Unix/Linux + C)**

---

## 📁 Repository Structure

Each folder corresponds to one assignment (and sub-parts if any).  
Inside each assignment folder:
- Sub-parts are named `A`, `B`, etc.  
- Source/programs are stored as `.txt` files.

```

📂 Assignment 1
├── A → Linux Commands.txt
└── B → Address Book.txt

📂 Assignment 2
├── A → Zombie.txt, Orphan.txt
└── B → EXECVE.txt

📂 Assignment 3
├── SJF.txt
└── Round Robin.txt

📂 Assignment 4
├── A → Producer Consumer.txt
└── B → Reader Writer.txt

📂 Assignment 5
└── Banker's Algo.txt

📂 Assignment 6
├── FIFO PageReplace.txt
├── LRU PageReplace.txt
└── Optimal.txt

📂 Assignment 7
├── A → FIFO Pipeline.txt
└── B → Client Server.txt

📂 Assignment 8
├── SSTF.txt
├── SCAN.txt
└── C-LOOK.txt

````

---

## 📌 Assignment Details 

> All programs target **Linux**. Use `gcc` & **POSIX APIs** (pthreads, semaphores, System V IPC).  
> Example commands assume you are inside the respective folder.

### 1A — Basic Linux Commands
* **File**: `Linux Commands.txt`
* **Contents**: demo snippets for `echo`, `ls`, `cat`, `touch`, `grep`, `sed`, loops, etc.

---

### 1B — Address Book (Menu Driven)
* **File**: `Address Book.txt`
* **Features**: create, view, insert, delete, modify records.

---

### 2A — Process Control: fork(), wait(), Zombie & Orphan
* **Files**:  
  - `Zombie.txt` → zombie process demo  
  - `Orphan.txt` → orphan process demo  

---

### 2B — execve(): Parent Sort → Child Reverse
* **File**: `EXECVE.txt`
* **Flow**: Parent sorts array → passes to child via `execve()` → child prints reverse.

---

### 3 — CPU Scheduling
* **Files**:  
  - `SJF.txt` → Preemptive Shortest Job First  
  - `Round Robin.txt` → Round Robin Scheduling  

---

### 4A — Producer–Consumer
* **File**: `Producer Consumer.txt`
* **Concepts**: Counting semaphores + mutex.

---

### 4B — Readers–Writers
* **File**: `Reader Writer.txt`
* **Concepts**: Reader priority with mutex + condition variables.

---

### 5 — Banker's Algorithm
* **File**: `Banker's Algo.txt`
* **Concepts**: Deadlock avoidance, safe sequence.

---

### 6 — Page Replacement
* **Files**:  
  - `FIFO PageReplace.txt`  
  - `LRU PageReplace.txt`  
  - `Optimal.txt`  

---

### 7A — IPC via FIFOs
* **File**: `FIFO Pipeline.txt`
* **Design**: Full duplex communication using two named pipes.

---

### 7B — IPC via Client–Server (Shared Memory)
* **File**: `Client Server.txt`
* **Design**: System V shared memory communication.

---

### 8 — Disk Scheduling
* **Files**:  
  - `SSTF.txt`  
  - `SCAN.txt`  
  - `C-LOOK.txt`  

---

## 🔧 Tech Stack
* **Language**: C , CPP (GCC)  
* **OS**: Linux  
* **APIs**: POSIX (pthreads, semaphores), System V IPC, `fork/execve/wait`, file I/O  

---

## 🚀 Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/os-lab-practicals.git
   cd os-lab-practicals
  
2. Open any `.txt` file, copy the code, and compile:

   ```bash
   gcc program.c -o program
   ./program
   ```

---

## 🙌 Author

**Aaryan Bairagi**
TE IT | Savitribai Phule Pune University
GitHub: [@AaryanBairagi](https://github.com/AaryanBairagi)

---

## 📌 License

This project is for academic learning only.
© 2025 Aaryan Bairagi – All rights reserved.

---
