# Introduction
- [Introduction](#introduction)
  - [Install the python enviroment](#install-the-python-enviroment)
## Install the python enviroment
- Install the pyenv
  - Install the package
    ```
    git clone https://github.com/yyuu/pyenv.git ~/.pyenv
    echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
    echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
    echo 'eval "$(pyenv init -)"' >> ~/.bash_profile

    source ~/.bash_profile
    ```
- Install the python 3.9.7
  - ```
    sudo apt install zlib-devel bzip2 bzip2-devel readline-devel sqlite sqlite-devel openssl-devel
    sudo apt install zlib1g zlib1g-dev
    ```
  - ```pyenv install 3.9.7```
  - ```pyenv global 3.9.7```

