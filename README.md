# FolderLab

**Learn files & directories by doing.**

An interactive study website on the *File System Interface* (Operating Systems, Module 4). Every section is something you can try.

## What's inside

| Section | What you can do |
|---|---|
| **The file concept** | Type any file name to split it into name and extension and see its file type. Watch an "open file" request travel through the file-system layers. |
| **Access methods** | Compare sequential, direct and index-sequential access, and see how many records each one reads to find a record. |
| **Directory structures** | A working mini file system with a terminal (`ls`, `cd`, `mkdir`, `touch`, `rm`, `ln`, `gc`) and a live diagram. Switch between single-level, two-level, tree, acyclic-graph and general-graph structures, and each one enforces its own rules. |
| **Sharing & protection** | Set read/write/execute permissions and test whether the owner, a group member or a guest can access a file. |
| **AI file organiser** | Paste a messy list of files and let AI group them into a directory tree, then explore it in the mini file system. |
| **AI tutor** | Ask questions in the chat, or type `ask …` in the terminal. |

## Running it

It's a single self-contained file: open `index.html` in any browser. No install or build step.

## About the AI features

The AI features run through Claude when the site is opened as a Claude artifact. Anywhere else (GitHub Pages or a local file), they switch to offline mode automatically: the chat answers from the course notes, and the organiser groups files by extension. Everything else works the same.

## Tech

Plain HTML, CSS and JavaScript in one file. Diagrams are drawn as SVG by code, and all simulations run live in the browser.

---

Based on OS Module 4 lecture notes. Made for educational use.
