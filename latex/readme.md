# LaTeX

LaTeX is a document preparation system. I write the content and formatting instructions in a `.tex` file, then compile it to create the final document. At first, working with commands felt different from using a regular word processor, but it gave me more control over the layout.

## Setting up a document

A LaTeX document has two main parts:

- The **preamble**, where I choose the document class and load packages.
- The **document body**, between `\begin{document}` and `\end{document}`, where the actual content goes.

In the exercises, I used the `article` class and practised adding titles, sections and subsections.

## Organising content

I practised three list environments:

- `itemize` for bullet points.
- `enumerate` for numbered lists.
- `description` for terms with explanations.

Using sections and lists made it easier to divide information into smaller, readable parts.

## Tables and colours

The exercises gave me practice with the `tabular` environment, where column specifiers such as `l`, `c` and `r` control alignment. I also used fixed-width columns with `p{...}`.

Packages including `xcolor`, `colortbl`, `array`, `multirow` and `booktabs` helped me add colours, adjust columns, merge cells and improve the appearance of tables.

## Images and figures

I used the `graphicx` package and `\includegraphics` to add images. I also practised adjusting image width, cropping with `trim` and `clip`, and placing images in a `figure` environment with captions and labels. The `minipage` environment was useful for putting two images side by side.

## Beamer presentations

I also explored Beamer, a LaTeX document class for presentations. The work introduced creating slides, adding titles and lists, and using a theme to keep the slides consistent.

## What I learned

The main thing I took away is that LaTeX separates the content from the formatting instructions. It takes some time to get comfortable with the syntax, but once a document is structured properly, formatting can be reused consistently.

## Practical files

The ZIP files in this folder contain the `.tex` exercises and their supporting images. They are the practical examples behind the topics described above.
