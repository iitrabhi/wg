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

