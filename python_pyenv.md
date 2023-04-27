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

## install the python3 
- ```sudo apt install python3-pip```
- ```python3 -mvenv workspace --without-pip```
- ```. workspace/bin/activate```

- ```pip install --upgrade pip```

--------------------OR------------------------
Linux and Mac
- ```python3 -m venv .venv```
- ```source .venv/bin/activate```

windows
- ```python3 -m venv .venv```
- ```.\.venv\Scripts\activate```

install python3.8 aws
- amazon-linux-extrasパッケージがインストールされていない場合はyumでインストール
- ```sudo yum install -y amazon-linux-extras```

python3.8をインストール
- ```sudo amazon-linux-extras install -y python3.8```

- ``` python3.8 -m venv .venv```
- ```source .venv/bin/activate```
