# Installation

If you use Python 3 and `pyenv`, do following.


```bash
export PYTHON2_VERSION='2.7.16'  # the version of Python you　want to use 
cd ${pymot_dir}  # pymot_dir is the root directory
pyenv versions
pyenv local ${PYTHON2_VERSION}
pip2 install virtualenv
python2 -m virtualenv python2
source python2/bin/activate
python -V
which python
```

Add dependency

```bash
pip2 install munkres
```