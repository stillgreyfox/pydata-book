# Python for Data Analysis, 3rd Edition

Materials and IPython notebooks for "Python for Data Analysis, 3rd
Edition" by Wes McKinney, published by O'Reilly Media. Book content
including updates and errata fixes can be [found for free on my
website][1].

[Buy the book on Amazon][2]

Follow Wes on Twitter: [![Twitter Follow](https://img.shields.io/twitter/follow/wesmckinn.svg?style=social&label=Follow)](https://twitter.com/wesmckinn)

## IPython Notebooks

### All links set to open from stillgreyfox fork, in Google Colab

* [Chapter 2: Python Language Basics, IPython, and Jupyter Notebooks](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch02.ipynb)
* [Chapter 3: Built-in Data Structures, Functions, and Files](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch03.ipynb)
* [Chapter 4: NumPy Basics: Arrays and Vectorized Computation](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch04.ipynb)
* [Chapter 5: Getting Started with pandas](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch05.ipynb)
* [Chapter 6: Data Loading, Storage, and File Formats](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch06.ipynb)
* [Chapter 7: Data Cleaning and Preparation](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch07.ipynb)
* [Chapter 8: Data Wrangling: Join, Combine, and Reshape](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch08.ipynb)
* [Chapter 9: Plotting and Visualization](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch09.ipynb)
* [Chapter 10: Data Aggregation and Group Operations](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch10.ipynb)
* [Chapter 11: Time Series](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch11.ipynb)
* [Chapter 12: Introduction to Modeling Libraries in Python](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch12.ipynb)
* [Chapter 13: Data Analysis Examples](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/ch13.ipynb)
* [Appendix A: Advanced NumPy](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/appa.ipynb)
* [Appendix B: More on the IPython System](https://colab.research.google.com/github/stillgreyfox/pydata-book/blob/3rd-edition/appb.ipynb)

## License

### Code

The code in this repository, including all code samples in the notebooks listed
above, is released under the [MIT license](LICENSE-CODE). Read more at the
[Open Source Initiative](https://opensource.org/licenses/MIT).

[1]: https://wesmckinney.com/book/
[2]: https://amzn.to/3DyLaJc

## Notes

The original notebooks had all these distracting '#! ipython' things.
I cleaned them up using bash:

```bash
for i in {2..9}; do sed -i '/#! ipython/d' "ch0$i.ipynb"; done
for i in {10..13}; do sed -i '/#! ipython/d' "ch$i.ipynb"; done
for i in {a..b}; do sed -i '/#! ipython/d' "app$i.ipynb"; done
```
