# latex-exam-template
LaTeX template for St Andrews School of Computer Science take-home exams.

A `.bib` file is not included, as School of Computer Science exams do not expect references. In the case where a reference may be required, footnotes should be used. 

Subsections and subsubsections have been defined to match the question numbering style of School of Computer Science exam papers.

PDF files have been added to the `.gitignore`, but you may wish to remove this.

## Usage

1. Rename `{module}-exam-{matriculation}.tex` with the relevant module code and your matriculation number. 
2. Insert the module code and your matriculation number in the marked sections in `{module}-exam-{matriculation}.tex`
3. Add additional questions in the `questions/` directory in the form `questions/questions-{x}.tex`. Question 1 is already added to highlight how to use the subsections and subsubsections.
4. Use `\code{}` if you need to display code (i.e. function names, variables, etc) inline. 
5. Use `\verbatim` for larger code blocks.

## Suggestions

If you have any suggestions, please feel free to create an issue.