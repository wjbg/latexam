# LaTeX Exam Template

[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A simple LaTeX template for written exams, based on the excellent
[template](https://ctan.org/pkg/anufinalexam?lang=en) from the
Australian National University.

The template features:
1. A title page with:
   * University and faculty information
   * An image, could be a logo
   * The course name and the course code
   * Available time
   * Materials permitted during the exam
   * Optional fields for student name and student number
2. A page with generic guidelines for the exam.
3. A command and an environment for the questions and answers:
   * `\question` for auto-numbered questions; this allows easy
     reshuffling of questions without messing up the numbering order...
   * `\begin{answer} ... \end{answer}` for the answers, which will be
     printed in a yellowish box.

The answers can be shown or hidden using a boolean:

```latex
% ==============================================================================
% Show answers?
%
\showanswerstrue
% \showanswersfalse

```

Optionally, the form provides space for the student name and number on
the front page, and adds a statement that the question form should be
returned after the exam. This option can be turned on or off using the
following boolean.

```latex
% ==============================================================================
% Return form?
%
% \returnformtrue
\returnformfalse

```

Check the [pdf](latex_exam_template.pdf) for an impression.

## License

Free as defined in the [GNU General Public
License v3](https://www.gnu.org/licenses/gpl-3.0.en.html).
