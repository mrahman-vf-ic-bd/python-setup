# python-setup

### pyenv with pipenv which has all kinds of compatibility

#### Install Pyenv

1. Installing Pyenv is typically done via running the following script:
```
curl https://pyenv.run | bash
```

2. Shell Setup

Pyenv requires you to run the following code in the shell prior to usage. This can be run via the .bashrc file at the initialization of the shell.
```
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

#### Using pyenv to install python
Next, we will run the install argument with a version, this will install on the system of Python version we requested.
Show available list of python version to install:
```
pyenv install -l
```
Insall a specific version:
```
pyenv install 3.9.2
```
To see all the installed versions, just run:
```
pyenv versions
```
Set as the global python version running:
```
pyenv global 3.8.8
```
Check your global version, just run:
```
python -V
```
To set a local version, go to the project folder in the terminal:
```
cd ~/path/to/the/project/folder
```
And set the local version, for example, 3.9.1:
```
pyenv local 3.9.1
```
To uninstall an already installed Python version.
```
pyenv uninstall <Python version>
```

For using pipevn follow this link: https://www.singlestoneconsulting.com/blog/setting-up-your-python-environment


Reference:
1. https://www.rootstrap.com/blog/how-to-manage-your-python-projects-with-pipenv-pyenv
