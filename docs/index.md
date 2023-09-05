# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


You can write code in a file index.md in MkDocs by using the fenced code block syntax. The fenced code block syntax starts with three or more backticks () and ends with the same number of backticks. For example, the following code would write a Python code block in a fileindex.md`:

Python
def factorial(n):
  """
  Calculate the factorial of a number.

  Args:
    n: The number to calculate the factorial of.

  Returns:
    The factorial of the number.
  """
  if n == 0:
    return 1
  else:
    return n * factorial(n - 1)

Use code with caution. Learn more
The fenced code block syntax can be used to write code in any programming language. You can also specify the language of the code block by adding a language identifier after the first set of backticks. For example, the following code would write a Python code block in a file index.md and specify that the language of the code block is Python:

```
def factorial(n):
  """
  Calculate the factorial of a number.

  Args:
    n: The number to calculate the factorial of.

  Returns:
    The factorial of the number.
  """
  if n == 0:
    return 1
  else:
    return n * factorial(n - 1) 
```