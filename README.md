Via homebrew instalar
brew install gfortran (para o numpy)
brew install pkg-config (para o matplotlib)
brew install freetype  (para o matplotlib)
brew install libpng (para o matplotlib)
brew install ffmpeg (para o matplotlib)
brew install zeromq (para o ipython notebook)

Via pip (em requirements.txt):

pip install pandas
pip install ipython
pip install mpmath
pip install numpy
pip install scipy
pip install statsmodels
pip install matplotlib
pip install patsy
pip install pyzmq
pip install Tornado
pip install jinja2

Usar iPython
In [1]: from IPython.external.mathjax import install_mathjax
In [2]: install_mathjax()

Finalmente, rodar
$ ipython notebook --pylab inline

baseado em http://www.tapir.caltech.edu/~dtsang/python.html