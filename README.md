# Assignment Template

This is a template for math and CS assignments that I have developed, intended
to contain every addition that I frequently make to LaTeX documents. I love
writing any assignment I can in LaTeX, I think it adds a level of polish that
puts you in the assignment grader's good graces.

Features a lot of code lifted from various places on the internet in addition to
my own.

## Template Features

- Stylized, small header (update the variables at the top of
  [main.tex](main.tex)).
- Each equestion / answer is contained in a separate file, automatically added
  into the document (see [questions/q1.tex](questions/q1.tex)).
- A nice looking separator for questions/answers `midsep`
- a standard environment for solutions (with a nice QED square at the end)
  `solution`.
- A standard environment for multi-part questions with alphabetic part names
  `alpQ`.
- A convenient way of splitting the page into two vertical, side-by-side spaces
  via `\lsplit`
- Hyperref set up to make a clickable table of contents if you uncomment it.
  Overkill for almost every assignment, but a table of contents really makes
  anything feel like a great accomplishment, so I can't resist.
- Storage for reusable constants, via `\sv{}` and `\gv`, inside of the .tex
  files. For example: `\sv{x = \frac{3}{4}}`, and then later in the document:
  `\gv{x}`, which will show up as simply `\frac{3}{4}`. I find this more
  convenient than using macros, often a singular answer will require something
  be repeated a lot and so I want to be able to store and reuse it without
  heading over to the preamble.
- The functions `br{}`, `sbr{}`, and `cbr{}` for automatically sizing brackets,
  square brackets, and curly braces respectively. Consequently, you never have
  to use `\left(`and`\right)` again.
- A `\todo{}` command that creates a bright red box around the text, useful
  for TODO notes to ensure you don't forget to do something before submitting
  the assignment.
- Various formatting niceties (eg. margins, page breaks in math mode, etc).

See [main.pdf](main.pdf) for an example.
