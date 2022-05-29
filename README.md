## Properly Installing Python

#### There’s a good chance that you already have Python on your operating system. If so, you do not need to install or configure anything else to use Python. 
#### Having said that, I would strongly recommend that you install the tools and libraries described in the guides below before you start building Python applications for real-world use. 
#### In particular, you should always install Setuptools, Pip, and Virtualenv — they make it much easier for you to use other third-party Python libraries. 
<br />

### Installing Python 3 on Linux

#### To see which version of Python 3 you have installed, open a command prompt and run

```
python3 --version
```

#### If you are using Ubuntu 22.04 or newer, then you can easily install Python 3.10 with the following commands:

```
sudo apt-get update
sudo apt-get install python3.10
```

#### If you’re using another version of Ubuntu (e.g. the latest LTS release) or you want to use a more current Python, we recommend using the deadsnakes PPA to install Python 3.8:

```
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.8
```

#### Working with Python 3
```
$ python3
```

#### This will always launch the Python 3 interpreter.
<br />

### Setuptools & Pip
#### The two most crucial third-party Python packages are setuptools and pip.

#### Once installed, you can download, install and uninstall any compliant Python software product with a single command. It also enables you to add this network installation capability to your own Python software with very little work.

#### To see if pip is installed, open a command prompt and run

```
command -v pip
```
#### To install pip, follow the official pip installation guide - this will automatically install the latest version of setuptools.

##### Note that on some Linux distributions including Ubuntu and Fedora the pip command is meant for Python 2, while the pip3 command is meant for Python 3.

```
command -v pip3
```
However, when using virtual environments (described below), you don’t need to care about that. 
<br />
 
 
 ## Pipenv & Virtual Environments

 ### ☤ Make sure you’ve got Python & pip

#### Before you go any further, make sure you have Python and that it’s available from your command line. You can check this by simply running:

```python3 --version```

#### You should get some output like 3.6.2. If you do not have Python, please install the latest 3.x version from python.org or refer to the Installing Python section of The Hitchhiker’s Guide to Python.
