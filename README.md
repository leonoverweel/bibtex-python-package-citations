# BibTeX Citations for Python Package

If you're writing a paper, it's important to [acknowledge the software engineers who make your scientific contributions possible](https://colah.github.io/posts/2019-05-Collaboration/).
For software and packages, I've found it much harder to find BibTeX citations I can simply copy-paste into my `references.bib` than it is for papers.
Hopefully this repository will be the first step towards making that easier.

I'm using this page to collect **the most official citations I can find for common (machine learning) Python packages.**
If you spot a mistake or know of another citation that you think should be on this page, please open an issue or PR!

# Python

Bit of discussion around this online (see [this StackOverflow thread](https://academia.stackexchange.com/questions/5482/how-do-i-reference-the-python-programming-language-in-a-thesis-or-a-paper)).
The following is based on [this email by Steven D'Aprano](https://mail.python.org/pipermail/tutor/2016-March/108473.html).

```bibtex
@manual{python,
    title = {{Python: A dynamic, open source programming language}},
    author = {{Python Core Team}},
    organization = {{Python Software Foundation}},
    year = {2019},
    url = {https://www.python.org/},
}
```

It may also be a good idea to add the specific version of Python, for example for 3.7:

```bibtex
@manual{python37,
    title = {{Python: A dynamic, open source programming language}},
    author = {{Python Core Team}},
    organization = {{Python Software Foundation}},
    year = {2019},
    url = {https://www.python.org/},
    note = {Python version 3.7}
}
```
