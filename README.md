# Custom Theme
Extended from OutsystemsUI

## How to install
1 - Download the dart-sass package for you operating system at https://github.com/sass/dart-sass/releases/tag/1.58.3\
2 - Extract to wanted location (ex C:\dart-sass)\
3 - Add this path to your PATH environment variable\
    3.1 - Go to "system environment variables" on windows\
    3.2 - Click "Environment Variables"\
    3.3 - Under system varibles find the PATH variable, select it, and click "Edit"\
    3.4 - If there is no PATH variable, click "New" and write here PATH\
    3.5 - Go your dard-sass folder and copy directory (C:\dart-sass based on the example given on step 2)\
    3.6 - Add the directory to the PATH variable list\
    3.7 - Open "Command Prompt"\
    3.8 - Write here "sass --version" and click enter to be sure it installed correctly\
    3.9 - Use 'sass --watch src/theme.scss dist/theme.css' on the project directory\
4 - Run npm install on the project root directory to install other dependencies\
5 - Enable format on save with prettier on VSCode: https://www.alphr.com/auto-format-vs-code/\

# Recommended 

## 7-1 Architecture
Our SCSS folder follows the 7-1 Architecture pattern
Checkit at https://sass-guidelin.es/#the-7-1-pattern
