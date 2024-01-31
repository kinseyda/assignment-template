# Assignment Template

This is a template for math and CS assignments that I have developed, intended to contain every addition that I frequently make to LaTeX documents. The goal is to never have to touch the preamble when writing an assignment.

Features a lot of code lifted from various places on the internet in addition to my own.

## Template Features

- Stylized, small header (update variables per assignment inside [main.tex](main.tex)).
- Questions and answers contained in separate files, automatically added into the document (see [questions/q1.tex](questions/q1.tex)).
- A nice looking separator for questions/answers and a standard environment for solutions (with a nice QED square at the end).
- A standard environment for multi-part questions with alphabetic part names `alpQ`.
- A convenient way of splitting the page into two vertical, side-by-side spaces via `\lsplit`
- A clickable table of contents. Overkill for almost every assignment, but a table of contents really makes anything feel like a great accomplishment so I can't resist.
- "Variable" storage, via `\sv{}` and `\gv`. For example: `\sv{x = \frac{3}{4}}`, and then later in the document: `\gv{x}`, which will show up as simply `\frac{3}{4}`.
- Various formatting niceties (eg. margins, nested brackets that grow automatically, page breaks in math mode, etc).

See [main.pdf](main.pdf) for an example.
