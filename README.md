# gluPaste

[![PRs & Issues Welcome](https://img.shields.io/badge/PRs%20&%20Issues-welcome-brightgreen.svg?style=flat-square)](https://github.com/Nithmr/gluPaste/issues)

## Introduction
gluPaste is a nighthack by GLUG-NITH that provides programmers a platform to share code with their peers. You can view the working behind this pastebin and are also welcomed for any pull requests.

## Usage

## Contributing
Refer [CONTRIBUTING.md](https://github.com/Nithmr/gluPaste/blob/master/CONTRIBUTING.md)

## Installation

### Requirements

1. PHP
2. MySql
3. Apache/Nginx

### Running locally
1. clone the project using the command<br>
``git clone git@github.com:Nithmr/gluPaste.git
``
<br>OR <br>
Download it by clicking [here](https://github.com/Nithmr/gluPaste/archive/master.zip)
2. Then navigate to project directory and run the project as<br>
``php -S localhost:4000 index.php
``
3. Now visit [http://localhost:4000](http://localhost:4000)

### Configuration
The project is currently configured for be run by a webserver such as Apache or Nginx, and a MySql database should be already available. The project needs to be placed in a folder with this specific path `/var/www/html/glupaste` and the webserver configuration should be pointing to that folder. 

The MySql database should be available and the connection parameters have to be updated in the following files `index.php`, `index1.php`,`insert.php`,`search.php`. 

## Found a bug?
[Submit an issue](https://github.com/Nithmr/gluPaste/issues) to the gluPaste Github. And, of course, feel free to submit pull requests with bug fixes or changes.

## Maintainers
We will be happy to respond to any type of queries you have. Just ping us at [http://glug.nith.ac.in/gluapps/gluask](http://glug.nith.ac.in/gluapps/gluask)

## License
This Project is licensed under License - [MIT](https://github.com/Nithmr/gluPaste/blob/master/LICENSE.md)
