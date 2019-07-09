# BibTeX Citations for Python Package

If you're writing a paper, it's important to [acknowledge the software engineers who make your scientific contributions possible](https://colah.github.io/posts/2019-05-Collaboration/).
For software and packages, I've found it much harder to find BibTeX citations I can simply copy-paste into my `references.bib` than it is for papers.
Hopefully this repository will be the first step towards making that easier.

I'm using this page to collect **the most official citations I can find for common (machine learning) Python packages.**
If you spot a mistake or know of another citation that you think should be on this page, please open an issue or PR!

# Citations

## Python

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

## Packages

Packages are listed alphabetically. If this list grows too long, maybe we can add categories.

### Matplotlib

```bibtex
@article{matplotlib,
  title={Matplotlib: A 2D graphics environment},
  author={Hunter, John D},
  journal={Computing in science \& engineering},
  volume={9},
  number={3},
  pages={90},
  year={2007},
  publisher={IEEE Computer Society}
}
```

([source](https://www.scipy.org/citing.html))

### NumPy

```bibtex
@misc{numpy,
  author = {Travis Oliphant},
  title = {{NumPy}: A guide to {NumPy}},
  year = {2006--},
  howpublished = {USA: Trelgol Publishing},
  url = "http://www.numpy.org/",
  note = {[Online; accessed <today>]}
}
```

([source](https://www.scipy.org/citing.html))

### Pandas

```bibtex
@inproceedings{pandas,
  author = {Wes McKinney},
  title= {Data Structures for Statistical Computing in Python},
  booktitle = {Proceedings of the 9th Python in Science Conference},
  pages = {51 - 56},
  year = {2010},
  editor = {St\'efan van der Walt and Jarrod Millman}
}
```

([source](https://github.com/pandas-dev/pandas/issues/24036))

### PyTorch

```bibtex
@inproceedings{pytorch,
  title={Automatic differentiation in PyTorch},
  author={Paszke, Adam and Gross, Sam and Chintala, Soumith and Chanan, Gregory and Yang, Edward and DeVito, Zachary and Lin, Zeming and Desmaison, Alban and Antiga, Luca and Lerer, Adam},
  booktitle={NIPS-W},
  year={2017}
}
```

([source](https://github.com/pytorch/pytorch/issues/4126))

### SciPy

```bibtex
@misc{scipy,
  author = {Eric Jones and Travis Oliphant and Pearu Peterson and others},
  title = {{SciPy}: Open source scientific tools for {Python}},
  year = {2001--},
  url = "http://www.scipy.org/",
  note = {[Online; accessed <today>]}
}
```

([source](https://www.scipy.org/citing.html))

# Credits

Many citations come from the [SciPy citing guide](https://www.scipy.org/citing.html) (which doesn't have BibTeX entries for most citations).
