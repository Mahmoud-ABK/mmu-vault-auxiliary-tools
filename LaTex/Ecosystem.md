_An overview of the ecosystem, terminology, and fundamental ideas._

# WYSIWG approach and the need for alternatives 

You might know **WYSIWYG** ,it stands for **What You See Is What You Get**.

You can think of programs like Microsoft Office, Google Docs, or LibreOffice.

Well, you might say that they do a good job? Wait until you move an image by **1cm** and watch your **whole document collapse**.

This is why we need things like **markup languages** to make documenting less painful.

Thus, the need for **TeX/LaTeX**. 
# Tex and other Engines
### TeX as a Typesetting Program
- TeX is a **typesetting system** created by Donald Knuth.
- Its purpose: to produce **high-quality documents**, especially for scientific and mathematical formulae.

## Tex as an engine
- **Engine**: The software that interprets TeX code and produces a formatted document (usually PDF or DVI in legacy workflows).
- The TeX engine reads `.tex` files and compiles them into output.
## other Tex Engines
- **pdfTeX** – Generates PDF directly from TeX.
- **XeTeX** – Unicode and modern font support.
- **LuaTeX** – Extends TeX with the Lua scripting language.
# What is LaTeX? 
## what is a macro ? 
- A **macro**: a set of instructions or commands grouped under a name, to automate repetitive tasks.
- **Example in C**: `#define PI 3.14159` here PI is a macro  
## LaTex : a Tex macro
- LaTeX is a **macro package built on top of TeX**.
- Provides predefined commands, document structures, and formatting rules.
- Makes TeX more user-friendly by abstracting complex formatting.

>[!what will be learning in this vault?]
>we will be learning Latex not Tex as raw Tex is much more "low level" 
# LaTeX Distributions 
- **Distribution**: A bundle containing the TeX engine(s), LaTeX macro packages, and additional tools for compiling documents.
- Examples:
    - **TeX Live** (cross-platform)
    - **MiKTeX** (Windows)
    - **MacTeX** (macOS, based on TeX Live)
# Editors and IDEs
- **Editor**: Basic text editor with syntax highlighting (e.g., TeXworks, TeXmaker).
- **IDE**: Full environment with build tools, project management, and live preview (e.g., TeXstudio, Overleaf).

> Basically, most modern editors and IDEs support Tex/LaTex like VS code / Vim etc..  you just need some configuration 

# Compilation Process 
- Write a `.tex` source file.
- Run it through a TeX engine (e.g., `pdflatex`, `xelatex`).
- Auxiliary files (`.aux`, `.log`) are generated during processing.
- Final output: `.pdf` or `.dvi`.

here is a more detailed workflow using **pdfTex** as an engine

![https://texample.net/files/tex-workflow.png](https://texample.net/files/tex-workflow.png)
# Packages and Extensions
popular packages and extensions 
- Extend LaTeX functionality.
- Popular examples:
    - **geometry** – Page layout customization.
    - **amsmath** – Advanced math formatting.
    - **graphicx** – Image inclusion.
    - **hyperref** – Hyperlinks and bookmarks.


[[Latex summary |Summary Page]]

---
# Sources:
- The Not So Short Introduction to LATEX : [link](https://tobi.oetiker.ch/lshort/lshort.pdf)·
- TeXample : [link](https://texample.net/tex-workflow/)
- Tex wikipedia page : [link](https://en.wikipedia.org/wiki/TeX#Pronunciation_and_spelling)
 