# A Generative Spider Web System

## Description

Created an L-System-based generative art system created in Python
using ColabTurtle.

The project explores how simple rule-based systems can generate
different spider web structures.

The system contains three main patterns:

1. Orb Web
2. Corner Web
3. Damaged Web

The project combines L-System rewriting with procedural geometry to
create the support and connecting structures of spider webs.

## L-System Rules

### Orb Web

X → F+X

### Corner Web

X → F+FX

### Damaged Web

X → F[+X][-X]

## How to Run

The project was created using Google Colab.

1. Open `spider_web_generator.ipynb` in Google Colab.
2. Run the installation/import cell.
3. Run the L-System setup cell.
4. Run any of the three pattern cells.
5. Change the adjustable parameters at the beginning of a pattern
   cell to generate variations.
6. Run the cell again to view the new output.

## Adjustable Parameters

Depending on the pattern, adjustable parameters include:

- iterations
- spokes
- rings
- size
- web color
- line width
- random seed
- angle variation
- thread variation

## Requirements

- Python
- Google Colab
- ColabTurtle

## Author

Hong Anh Hoang
