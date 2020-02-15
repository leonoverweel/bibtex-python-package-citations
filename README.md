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
@article{caffe,
  Author={Jia, Yangqing and Shelhamer, Evan and Donahue, Jeff and Karayev, Sergey and Long, Jonathan and Girshick, Ross and Guadarrama, Sergio and Darrell, Trevor},
  Journal={arXiv preprint arXiv:1408.5093},
  Title={Caffe: Convolutional Architecture for Fast Feature Embedding},
  Year={2014}
}
```

([source](https://caffe.berkeleyvision.org/))

### CoreNLP BibTeX citation

```bibtex
@InProceedings{corenlp,
  author={Manning, Christopher D. and  Surdeanu, Mihai  and  Bauer, John  and  Finkel, Jenny  and  Bethard, Steven J. and  McClosky, David},
  title={The {Stanford} {CoreNLP} Natural Language Processing Toolkit},
  booktitle={Association for Computational Linguistics (ACL) System Demonstrations},
  year={2014},
  pages={55--60},
  url={http://www.aclweb.org/anthology/P/P14/P14-5010}
}
```

([source](https://stanfordnlp.github.io/CoreNLP/citing.html))

### fastai BibTeX citation

```
@misc{fastai,
  author={
    Howard, Jeremy
    and Gugger, Sylvain
  },
  title={fastai: A layered API for deep learning},
  journal={Information (Special Issue)}
  url={fast.ai},
  year={2019}
}
```
([source](https://www.mdpi.com/journal/information/special_issues/ML_Python))

### gensim BibTeX citation

```bibtex
@inproceedings{rehurek_lrec,
  title={{Software Framework for Topic Modelling with Large Corpora}},
  author={Radim {\v R}eh{\r u}{\v r}ek and Petr Sojka},
  booktitle={{Proceedings of the LREC 2010 Workshop on New Challenges for NLP Frameworks}},
  pages={45--50},
  year=2010,
  month=May,
  day=22,
  publisher={ELRA},
  address={Valletta, Malta},
  note={\url{http://is.muni.cz/publication/884893/en}},
  language={English}
}
```
([source](https://radimrehurek.com/gensim/about.html))

### Keras BibTeX citation

```bibtex
@misc{keras,
  title={Keras},
  author={Chollet, Fran\c{c}ois and others},
  year={2015},
  howpublished={\url{https://keras.io}},
}
```

([source](https://keras.io/getting-started/faq/))

### Larq BibTeX citation

```bibtex
@article{larq,
  doi={10.21105/joss.01746},
  url={https://doi.org/10.21105/joss.01746},
  year={2020},
  month=jan,
  publisher={The Open Journal},
  volume={5},
  number={45},
  pages={1746},
  author={Lukas Geiger and Plumerai Team},
  title={Larq: An Open-Source Library for Training Binarized Neural Networks},
  journal={Journal of Open Source Software}
}
```

([Source](https://larq.dev/faq/#how-can-i-cite-larq))

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

See also: ([DOIs per version of Matplotlib](https://matplotlib.org/3.1.0/citing.html))

### MLxtend BibTeX citation

```bibtex
@article{mlxtend,
  author={Sebastian Raschka},
  title={MLxtend: Providing machine learning and data science utilities and extensions to Python’s scientific computing stack},
  journal={The Journal of Open Source Software},
  volume={3},
  number={24},
  month=apr,
  year=2018,
  publisher={The Open Journal},
  doi={10.21105/joss.00638},
  url={http://joss.theoj.org/papers/10.21105/joss.00638}
}
```

([source](http://rasbt.github.io/mlxtend/))

### NLTK BibTeX citation

```bibtex
@book{nltk,
  title={Natural Language Processing with Python},
  author={Bird, Steven, Edward Loper and Ewan Klein},
  year={2009},
  publisher={O'Reilly Media Inc.}
}
```

([source](https://www.nltk.org/))

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
@article{opencv,
  author={Bradski, G.},
  citeulike-article-id={2236121},
  journal={Dr. Dobb's Journal of Software Tools},
  keywords={bibtex-import},
  posted-at={2008-01-15 19:21:54},
  priority={4},
  title={{The OpenCV Library}},
  year={2000}
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

([source](https://pandas.pydata.org/talks.html))

### PyTorch BibTeX citation

```bibtex
@inproceedings{pytorch,
  title={Automatic Differentiation in {PyTorch}},
  author={Paszke, Adam and Gross, Sam and Chintala, Soumith and Chanan, Gregory and Yang, Edward and DeVito, Zachary and Lin, Zeming and Desmaison, Alban and Antiga, Luca and Lerer, Adam},
  booktitle={NIPS Autodiff Workshop},
  year={2017}
}
```

([source](https://github.com/pytorch/pytorch/blob/master/CITATION))

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
@article{scipy,
  author={
    {Virtanen}, Pauli and
    {Gommers}, Ralf and
    {Oliphant}, Travis E. and
    {Haberland}, Matt and
    {Reddy}, Tyler and
    {Cournapeau}, David and
    {Burovski}, Evgeni and
    {Peterson}, Pearu and
    {Weckesser}, Warren and
    {Bright}, Jonathan and
    {van der Walt}, St{\'e}fan J. and
    {Brett}, Matthew and
    {Wilson}, Joshua and
    {Jarrod Millman}, K. and
    {Mayorov}, Nikolay and
    {Nelson}, Andrew R.~J. and
    {Jones}, Eric and
    {Kern}, Robert and
    {Larson}, Eric and
    {Carey}, CJ and
    {Polat}, {\.I}lhan and
    {Feng}, Yu and
    {Moore}, Eric W. and
    {VanderPlas}, Jake and
    {Laxalde}, Denis and
    {Perktold}, Josef and
    {Cimrman}, Robert and
    {Henriksen}, Ian and
    {Quintero}, E.~A. and
    {Harris}, Charles R and
    {Archibald}, Anne M. and
    {Ribeiro}, Ant{\^o}nio H. and
    {Pedregosa}, Fabian and
    {van Mulbregt}, Paul and
    {Contributors}, SciPy 1.0
  },
  title="{SciPy 1.0: Fundamental Algorithms for Scientific Computing in Python}",
  journal={Nature Methods},
  year="2020",
  adsurl={https://rdcu.be/b08Wh},
  doi={https://doi.org/10.1038/s41592-019-0686-2},
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

([source](https://www.tensorflow.org/about/bib))

### Theano BibTeX citation

```bibtex
@article{theano,
  author={{Theano Development Team}},
  title="{Theano: A {Python} framework for fast computation of mathematical expressions}",
  journal={arXiv e-prints},
  volume={abs/1605.02688},
  primaryClass="cs.SC",
  keywords={Computer Science - Symbolic Computation, Computer Science - Learning, Computer Science - Mathematical Software},
  year=2016,
  month=may,
  url={http://arxiv.org/abs/1605.02688},
}
```

([source](http://deeplearning.net/software/theano/citation.html))

### Torchbearer BibTeX citation

```bibtex
@article{torchbearer,
  author={Ethan Harris and Matthew Painter and Jonathon Hare},
  title={Torchbearer: A Model Fitting Library for PyTorch},
  journal={arXiv preprint arXiv:1809.03363},
  year={2018}
}
```

([source](https://github.com/leonoverweel/bibtex-python-package-citations/issues/1))


# Acknowledgements

Many citations come from the [SciPy citing guide](https://www.scipy.org/citing.html) (which doesn't have BibTeX entries for most citations). Thanks to [Lynn (Tristan) Pepin](https://github.com/tpepin96/) for adding lots of citations to this page!

If this resource was useful to you, please consider checking the following as well:
* [Dynamically Typed](https://dynamicallytyped.com/): My thoughts and links on productized artificial intelligence, machine learning technology, and the tech/startup industry. Delivered to your inbox every second Sunday.
* [Machine Learning Resources](https://www.notion.so/adab36fecaea4306880898f41dcb9cb3): Machine learning resources featured in the Quick ML Resource Links section of Dynamically Typed. Updated with new resources every second Sunday!

(Random additional tip: to find the documentation PDF of any LaTeX package, go to texdoc.net/pkg/{package-name}.)
