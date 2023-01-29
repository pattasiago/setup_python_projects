# Basic Setup For Python Projects:

Using:

- Poetry;
- Black Formatter;
- isort;
- Prospector;
- Pytest

To use it with pyenv, config poetry to respect the current folder python version:

    poetry config virtualenvs.prefer-active-python true

Settings for VSCode were provided in settings.json to automate the usage of black formatter, isort and prospector. Also, you have to configure the python enviroment in your vscode.

- CTRL + SHIFT + P;
- Search for 'Python: Select Interpreter';
- Select the virtualenv created by Poetry;
