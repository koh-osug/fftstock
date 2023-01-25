# Summary

Stock analysis with FFT.

# Build

~~~shell
sudo pip3 install virtualenv 
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
# Follow instructions on https://github.com/pyenv/pyenv
pyenv install 3.9.15
virtualenv --python=$HOME/.pyenv/versions/3.9.15/bin/python3.9 venv
source venv/bin/activate
python -m pip install -U pip
pip install -r requirements.txt
~~~

# Run

~~~shell
source venv/bin/activate
python fftstock.py
~~~
