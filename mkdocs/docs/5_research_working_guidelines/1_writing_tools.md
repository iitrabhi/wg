![](attachments/Pasted%20image%2020240208221851.png)
## About LaTeX
We follow the LaTex in our lab, so we have 
LaTeX is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation. LaTeX is the de facto standard for the communication and publication of scientific documents. It is available as free software and is used for a wide range of documents, from simple letters to complete books. LaTeX uses TeX as its formatting engine. This system is particularly powerful for complex documents that include references and footnotes. 
There are many software to write in LaTex, but we follow overleaf. The detailed procedure to login and use overleaf is explained below: 
## Overleaf Sign-In and Initial Setup Guide

### 1. Navigating to Overleaf

- Open your web browser and go to [Overleaf](https://www.overleaf.com/). Overleaf is a cloud-based LaTeX editor that supports real-time collaboration.

### 2. Creating an Account or Signing In

- **New Users**: Click on `Register` to create a new account. Provide an email address, create a password, and complete the registration.
- **Existing Users**: Click on `Login` and enter your email and password.

### 3. Overview of Overleaf Interface

- The dashboard allows access to existing projects, creation of new ones, and finding templates for various documents.

### Creating and Managing Projects

1. **Creating a New Project**:
    
    - On your dashboard, click on "New Project" to start a new LaTeX document. You can choose to start from a blank project, upload an existing project, or select from a variety of templates.
    - Give your project a meaningful name that reflects its content or purpose.
2. **Working on the Project**:
    
    - The Overleaf editor is split into three main sections: the source code editor, the PDF preview, and the file tree/settings. You can write your LaTeX code in the source editor, and the PDF preview will update in real-time.
    - Use the file tree to organize your document's components, such as chapters, images, and bibliography files.
3. **Compiling Your Document**: 

	- Use the "Recompile" button to compile your LaTeX code into a PDF document. Overleaf automatically detects errors and warnings displayed above the PDF preview.
    

### Sharing Overleaf Projects

1. **Collaborating on a Project**:
    
    - Open the project you wish to share, and click on the "Share" button located at the top right of the page.
    - You can invite collaborators by entering their email addresses and selecting their permission level (can edit or can view).
    - Collaborators will receive an invitation to join the project. Once they accept, you can work on the document simultaneously.
2. **Link Sharing**:
    
    - For easier access, you can also share a project using a link. Choose the link-sharing option under the "Share" menu and select the appropriate access level. Copy and share the link with your peers.
## LaTeX Cheat Sheet

### Document Structure
```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
\begin{document}
Hello, World!
\end{document}
```

### Sections and Subsections
```latex
\section{Section Title}
\subsection{Subsection Title}
\subsubsection{Subsubsection Title}
```

### Text Formatting
- **Bold**: `\textbf{bold text}`
- **Italic**: `\textit{italic text}`
- **Underline**: `\underline{underlined text}`

### Lists
- **Unordered List**:
  ```latex
  \begin{itemize}
    \item First item
    \item Second item
  \end{itemize}
  ```
- **Ordered List**:
  ```latex
  \begin{enumerate}
    \item First item
    \item Second item
  \end{enumerate}
  ```

### Figures and Tables
- **Inserting a Figure**:
  ```latex
  \begin{figure}
    \includegraphics[width=\linewidth]{filename.jpg}
    \caption{Caption here.}
    \label{fig:label}
  \end{figure}
  ```
- **Creating a Table**:
  ```latex
  \begin{table}
    \begin{tabular}{l|c|r}
      Left & Center & Right \\
      \hline
      A & B & C \\
    \end{tabular}
    \caption{Table caption.}
    \label{tab:label}
  \end{table}
  ```

### Mathematical Formulas
- **Inline Math Mode**: `$...$` or `\( ... \)`
- **Displayed Math Mode**: `\[ ... \]` or `$$...$$`
- **Subscripts and Superscripts**: `_` for subscripts, `^` for superscripts
  ```latex
  E = mc^2
  ```
- **Fractions**:
  ```latex
  \frac{numerator}{denominator}
  ```
- **Square Roots**:
  ```latex
  \sqrt{x}
  ```

### Referencing
- **Labeling and Referencing**:
  Use `\label{}` to mark an element and `\ref{}` to reference it.
  ```latex
  \label{sec:mySection} % Labeling a section
  See Section~\ref{sec:mySection} for details.
  ```

This cheat sheet covers the basics to get started with LaTeX. For more detailed information and advanced features, consider referring to comprehensive LaTeX guides or the [Overleaf Documentation](https://www.overleaf.com/learn).

Here's a Markdown-friendly LaTeX cheat sheet focusing on mathematical commands, covering the essentials like addition, square roots, powers, subscripts, fractions, and more. This guide is designed to be both comprehensive and easy to reference.

## LaTeX Mathematical Commands Cheat Sheet

### Basic Operations
- **Addition/Subtraction**: `a + b`, `a - b`
- **Multiplication (Dot)**: `a \cdot b`
- **Division (Fraction)**: `\frac{a}{b}`
- **Square Root**: `\sqrt{x}`
- **Nth Root**: `\sqrt[n]{x}`

### Powers and Indices
- **Power (Superscript)**: `a^{b}`
- **Subscript**: `a_{b}`

### Fractions
- **Simple Fraction**: `\frac{a}{b}`

### Text in Equations
- **Text Within Equations**: `\text{your text here}`

### Integration
- **Definite Integral**: `\int_{a}^{b} f(x) \, dx`
- **Indefinite Integral**: `\int f(x) \, dx`

### Summation
- **Summation**: `\sum_{i=1}^{n} a_i`

### Brackets and Delimiters
- **Parentheses**: `\left( a + b \right)`
- **Brackets**: `\left[ a + b \right]`
- **Curly Braces**: `\left\{ a + b \right\}`
- **Big Brackets**: `\bigl( \bigr)`, `\Bigl( \Bigr)`, `\biggl( \biggr)`, `\Biggl( \Biggr)`

### Norms
- **Norm**: `\|x\|`, `\left\| x \right\|`

### Dot and Cross Product
- **Dot Product**: `a \cdot b`
- **Cross Product**: `a \times b`

### Gradient, Nabla, and Divergence
- **Nabla (Gradient)**: `\nabla f`
- **Gradient**: `\nabla f`
- **Divergence**: `\nabla \cdot \mathbf{F}`

### Hessian
- **Hessian Matrix**: `H(f)(\mathbf{x})`, typically defined explicitly in the context of a function.

### Underbrace
- **Underbrace**: `\underbrace{a + b + \cdots + z}_{\text{sum}}`

### Additional Commands
- **Cross Product**: `a \times b` (repeated for emphasis)
- **Underbraces**: `\underbrace{expression}_{text}`

### Examples
Here are some examples to illustrate how to use these commands in LaTeX:

```latex
% Powers and indices
E = mc^{2}
x_{1}

% Fractions
\frac{1}{2}

% Square root
\sqrt{x}, \sqrt[n]{x}

% Text in equations
F = ma \text{ where } m \text{ is mass}

% Integration
\int_{0}^{\infty} e^{-x} \, dx

% Summation
\sum_{i=1}^{n} i^2

% Brackets and Norms
\left( \frac{a}{b} \right)
\|x\|

% Dot and Cross Product
a \cdot b, a \times b

% Gradient and Divergence
\nabla \cdot \mathbf{F}, \nabla f

% Underbrace
\underbrace{1 + 2 + \cdots + 100}_{\text{first 100 natural numbers}}
```

This cheat sheet covers fundamental mathematical commands used in LaTeX for various types of expressions and operations. It's a handy reference for quickly recalling how to format mathematical content within your LaTeX documents.
## We use LaTex OCR for equation automation.
Link - [Link to OCR git](https://github.com/lukas-blecher/LaTeX-OCR)

To run the model you need Python 3.7+

If you don't have PyTorch installed. Follow their instructions [here](https://pytorch.org/get-started/locally/).

Install the package `pix2tex`:

```
pip install "pix2tex[gui]"
```

Model checkpoints will be downloaded automatically.

There are three ways to get a prediction from an image.

1. You can use the command line tool by calling `pix2tex`. Here you can parse already existing images from the disk and images in your clipboard.
    
2. Thanks to [@katie-lim](https://github.com/katie-lim), you can use a nice user interface as a quick way to get the model prediction. Just call the GUI with `latexocr`. From here, you can take a screenshot, and the predicted latex code is rendered using [MathJax](https://www.mathjax.org/) and copied to your clipboard.
    