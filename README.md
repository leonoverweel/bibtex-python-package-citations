# BibTeX Citations for Python Packages

If you're writing a paper, it's important to [acknowledge the software engineers who make your scientific contributions possible](https://colah.github.io/posts/2019-05-Collaboration/).
For software and packages, I've found it much harder to find BibTeX citations I can simply copy-paste into my `references.bib` than it is for papers.
Hopefully this repository will be the first step towards making that easier.

I'm using this page to collect **the most official citations I can find for common (machine learning) Python packages.**
If you spot a mistake or know of another citation that you think should be on this page, please open an issue or PR!

# Citations

## Python BibTeX citation

Bit of discussion around this online (see [this StackOverflow thread](https://academia.stackexchange.com/questions/5482/how-do-i-reference-the-python-programming-language-in-a-thesis-or-a-paper)).
The following is based on [this email by Steven D'Aprano](https://mail.python.org/pipermail/tutor/2016-March/108473.html).

```bibtex
@manual{python,
  title={{Python: A dynamic, open source programming language}},
  author={{Python Core Team}},
  organization={{Python Software Foundation}},
  year={2019},
  url={https://www.python.org/},
}
```

It may also be a good idea to add the specific version of Python, for example for 3.7:

```bibtex
@manual{python37,
  title={{Python: A dynamic, open source programming language}},
  author={{Python Core Team}},
  organization={{Python Software Foundation}},
  year={2019},
  url={https://www.python.org/},
  note={Python version 3.7}
}
```

## Packages

Packages are listed alphabetically. If this list grows too long, maybe we can add categories.

### Caffe BibTeX citation

```bibtex
@inproceedings{jia2014caffe,
  title={Caffe: Convolutional architecture for fast feature embedding},
  author={Jia, Yangqing and Shelhamer, Evan and Donahue, Jeff and Karayev, Sergey and Long, Jonathan and Girshick, Ross and Guadarrama, Sergio and Darrell, Trevor},
  booktitle={Proceedings of the 22nd ACM international conference on Multimedia},
  pages={675--678},
  year={2014},
  organization={ACM}
}
```

### CoreNLP BibTeX citation

```bibtex
@InProceedings{manning-EtAl:2014:P14-5,
  author    = {Manning, Christopher D. and  Surdeanu, Mihai  and  Bauer, John  and  Finkel, Jenny  and  Bethard, Steven J. and  McClosky, David},
  title     = {The {Stanford} {CoreNLP} Natural Language Processing Toolkit},
  booktitle = {Association for Computational Linguistics (ACL) System Demonstrations},
  year      = {2014},
  pages     = {55--60},
  url       = {http://www.aclweb.org/anthology/P/P14/P14-5010}
}
```

### Keras BibTeX citation

```bibtex
@misc{chollet2015keras,
  title={Keras},
  author={Chollet, Fran{\c{c}}ois and others},
  year={2015}
}
```

### Matplotlib BibTeX citation

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

### NLTK BibTeX citation

```bibtex
@inprocedings{nltk,
    author={Edward Loper and Steven Bird},
    title={NLTK: The Natural Language Toolkit},
    booktitle={In Proceedings of the ACL Workshop on Effective Tools and Methodologies for Teaching Natural Language Processing and Computational Linguistics. Philadelphia: Association for Computational Linguistics},
    year={2002}
}
```

([source](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.4.585))

### NumPy BibTeX citation

```bibtex
@misc{numpy,
  author={Travis Oliphant},
  title={{NumPy}: A guide to {NumPy}},
  year={2006--},
  howpublished={USA: Trelgol Publishing},
  url="http://www.numpy.org/",
  note={[Online; accessed <today>]}
}
```

([source](https://www.scipy.org/citing.html))

### OpenCV BibTeX citation

```bibtex
@article{opencv_library,
  author = {Bradski, G.},
  citeulike-article-id = {2236121},
  journal = {Dr. Dobb's Journal of Software Tools},
  keywords = {bibtex-import},
  posted-at = {2008-01-15 19:21:54},
  priority = {4},
  title = {{The OpenCV Library}},
  year = {2000}
}
```

([source](https://github.com/opencv/opencv/wiki/CiteOpenCV))

### Pandas BibTeX citation

```bibtex
@inproceedings{pandas,
  author={Wes McKinney},
  title= {Data Structures for Statistical Computing in Python},
  booktitle={Proceedings of the 9th Python in Science Conference},
  pages={51 - 56},
  year={2010},
  editor={St\'efan van der Walt and Jarrod Millman}
}
```

([source](https://github.com/pandas-dev/pandas/issues/24036))

### PyTorch BibTeX citation

```bibtex
@inproceedings{pytorch,
  title={Automatic differentiation in PyTorch},
  author={Paszke, Adam and Gross, Sam and Chintala, Soumith and Chanan, Gregory and Yang, Edward and DeVito, Zachary and Lin, Zeming and Desmaison, Alban and Antiga, Luca and Lerer, Adam},
  booktitle={NIPS-W},
  year={2017}
}
```

([source](https://github.com/pytorch/pytorch/issues/4126))

### scikit-learn BibTeX citation

```bibtex
@article{scikit-learn,
  title={{Scikit-learn: Machine Learning in Python}},
  author={
    Pedregosa, F. and
    Varoquaux, G. and
    Gramfort, A. and
    Michel, V. and
    Thirion, B. and
    Grisel, O. and
    Blondel, M. and
    Prettenhofer, P. and
    Weiss, R. and
    Dubourg, V. and
    Vanderplas, J. and
    Passos, A. and
    Cournapeau, D. and
    Brucher, M. and
    Perrot, M. and
    Duchesnay, E.
  },
  journal={Journal of Machine Learning Research},
  volume={12},
  pages={2825--2830},
  year={2011}
}
```

([source](https://scikit-learn.org/stable/about.html))

### SciPy BibTeX citation

```bibtex
@misc{scipy,
  author={Eric Jones and Travis Oliphant and Pearu Peterson and others},
  title={{SciPy}: Open source scientific tools for {Python}},
  year={2001--},
  url="http://www.scipy.org/",
  note={[Online; accessed <today>]}
}
```

([source](https://www.scipy.org/citing.html))

### TensorFlow BibTeX citation

```bibtex
@misc{tensorflow,
  title={ {TensorFlow}: Large-Scale Machine Learning on Heterogeneous Systems},
  url={https://www.tensorflow.org/},
  note={Software available from tensorflow.org},
  author={
    Mart\'{\i}n~Abadi and
    Ashish~Agarwal and
    Paul~Barham and
    Eugene~Brevdo and
    Zhifeng~Chen and
    Craig~Citro and
    Greg~S.~Corrado and
    Andy~Davis and
    Jeffrey~Dean and
    Matthieu~Devin and
    Sanjay~Ghemawat and
    Ian~Goodfellow and
    Andrew~Harp and
    Geoffrey~Irving and
    Michael~Isard and
    Yangqing Jia and
    Rafal~Jozefowicz and
    Lukasz~Kaiser and
    Manjunath~Kudlur and
    Josh~Levenberg and
    Dandelion~Man\'{e} and
    Rajat~Monga and
    Sherry~Moore and
    Derek~Murray and
    Chris~Olah and
    Mike~Schuster and
    Jonathon~Shlens and
    Benoit~Steiner and
    Ilya~Sutskever and
    Kunal~Talwar and
    Paul~Tucker and
    Vincent~Vanhoucke and
    Vijay~Vasudevan and
    Fernanda~Vi\'{e}gas and
    Oriol~Vinyals and
    Pete~Warden and
    Martin~Wattenberg and
    Martin~Wicke and
    Yuan~Yu and
    Xiaoqiang~Zheng
  },
  year={2015},
}
```

### Theano BibTeX citation

```bibtex
@inproceedings{bergstra2010theano,
  title={Theano: a CPU and GPU math expression compiler},
  author={Bergstra, James and Breuleux, Olivier and Bastien, Fr{\'e}d{\'e}ric and Lamblin, Pascal and Pascanu, Razvan and Desjardins, Guillaume and Turian, Joseph and Warde-Farley, David and Bengio, Yoshua},
  booktitle={Proceedings of the Python for scientific computing conference (SciPy)},
  volume={4},
  number={3},
  year={2010},
  organization={Austin, TX}
}
```

([source](https://www.tensorflow.org/about/bib))

# Credits

Many citations come from the [SciPy citing guide](https://www.scipy.org/citing.html) (which doesn't have BibTeX entries for most citations).
