# pycontest

A collection of exercises for [Pycon 2019](https://us.pycon.org/2019/) 
tutorial [To trust or to test?: Automated testing of scientific projects with pytest](https://us.pycon.org/2019/schedule/presentation/82/)

- You can find the presentation [here](https://djarecka.github.io/pycontest/presentation/#1)

Dependencies:
-------------

Tutorial requires Python 3.6, Matplotlib 3.0, Scipy, Numpy, Pytest and Hypothesis.
To create example animations you may need ffmpeg or mencoder packages. 

Troubleshooting:
----------------
- to install the tutorial example code:
  ```
  $ pip install .
  ```

- to run the tutorial example code without installation:
  ```
  $ python -m pycontest.simulation
  ```

- in case you have more than one python distribution you may need to specify python version to pytest:
  ```
  $ python3 -m pytest tests                      
  ```
