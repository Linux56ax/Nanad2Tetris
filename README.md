# Nand2Tetris Projects

> *"From Nand to Tetris: Building a Modern Computer From First Principles"*

Welcome to the **Nand2Tetris** implementation repository by [Linux56ax](https://github.com/Linux56ax). This repo contains completed projects from the renowned Nand2Tetris course, which guides you through building a modern computer system from the ground up — starting with NAND gates and ending with a working Tetris game!

---

## 📚 About Nand2Tetris

[Nand2Tetris](https://www.nand2tetris.org/) is a hands-on educational course created by Noam Nisan and Shimon Schocken. It walks you through 12 projects that progressively build a complete computer system:

- Hardware: Logic gates → CPU → Memory → Computer architecture
- Software: Assembler → VM → Compiler → OS → High-level application (Tetris!)

This repository contains the author’s completed work for each project in the course.

---

## 📁 Repository Structure

All projects are located under the [`projects/`](https://github.com/Linux56ax/Nanad2Tetris/tree/main/projects) directory:

```
projects/
├── 01/    # Boolean Logic & Basic Gates
├── 02/    # Boolean Arithmetic & ALU
├── 03/    # Sequential Logic & Memory
├── 04/    # Machine Language & CPU
├── 05/    # Computer Architecture
├── 06/    # Assembler
├── 07/    # Virtual Machine I (Stack Arithmetic)
├── 08/    # Virtual Machine II (Program Control)
├── 09/    # High-Level Language & Compiler I
├── 10/    # Compiler II (Syntax Analysis)
├── 11/    # Compiler III (Code Generation)
└── 12/    # Operating System & Tetris
```

Each folder contains:
- HDL (Hardware Description Language) files for hardware projects
- Source code (Jack, VM, ASM) for software projects
- Test scripts and comparison outputs
- Documentation or notes (if available)

---

## 🛠️ Tools Used

- **Hardware Simulator** — for testing HDL chip designs
- **Assembler** — converts assembly (.asm) to machine code (.hack)
- **CPU Emulator** — runs compiled machine code
- **VM Translator** — translates VM code to assembly
- **Jack Compiler** — compiles Jack (OOP language) to VM
- **Text Editor / IDE** — for writing HDL, ASM, VM, and Jack code

> All tools are available for free from the [Nand2Tetris Software Suite](https://www.nand2tetris.org/software).

---

## ✅ How to Use This Repo

1. **Clone the repo:**
   ```bash
   git clone https://github.com/Linux56ax/Nanad2Tetris.git
   cd Nanad2Tetris/projects
   ```

2. **Navigate to a project folder** (e.g., `cd 06` for the Assembler project).

3. **Load the `.hdl`, `.asm`, `.vm`, or `.jack` files** into the appropriate Nand2Tetris tool.

4. **Run the supplied test scripts** (`.tst`) to verify correctness.

5. **Compare your output** with the provided `.cmp` (compare) files.

---

## 🎓 Learning Outcomes

By completing these projects, you will understand:

✅ How logic gates form the foundation of computation  
✅ How memory, ALU, and CPU work together  
✅ How machine language is assembled from human-readable code  
✅ How a stack-based virtual machine operates  
✅ How a compiler translates high-level OOP code to low-level instructions  
✅ How an operating system supports applications like Tetris

---

## 🧑‍💻 About the Author

**Linux56ax** — A passionate learner and builder of systems from the ground up. This repo is a personal milestone in understanding computer architecture and systems programming.

> “If you want to *really* understand how computers work — build one yourself.”

---

## 📜 License

This project is for educational purposes. All code is original work completed as part of the Nand2Tetris curriculum.

The Nand2Tetris course materials are copyrighted by Noam Nisan and Shimon Schocken. Redistribution of original course files (`.tst`, `.cmp`, etc.) must comply with their [course license](https://www.nand2tetris.org/course).

---

## 🙌 Acknowledgements

- Noam Nisan & Shimon Schocken — creators of Nand2Tetris
- Coursera / The Hebrew University of Jerusalem — for hosting the course
- The Nand2Tetris community — for support, inspiration, and shared knowledge

---

## 💬 Feedback & Contributions

Found a bug? Have a suggestion? Want to compare solutions?

👉 Open an [Issue](https://github.com/Linux56ax/Nanad2Tetris/issues) or reach out!

*(Note: This repo is a personal educational record — PRs may not be accepted, but discussions are welcome!)*

---

## 🚀 Ready to Build a Computer?

Start from Project 01 — and build your way up to Tetris!

```text
NAND → Gates → ALU → RAM → CPU → Assembler → VM → Compiler → OS → Tetris
```

You’ve got this. 💪

---

> “Computer science is no more about computers than astronomy is about telescopes.” — Edsger Dijkstra  
> But sometimes, you gotta build the telescope to see the stars. 🌌

--- 

🔗 **Course Website**: https://www.nand2tetris.org/  
🔗 **Author’s GitHub**: https://github.com/Linux56ax  
📅 Completed: [Add Completion Date if Known]

---

⭐ *If you found this helpful, consider giving the repo a star!* ⭐
