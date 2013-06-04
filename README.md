# domainadd.sh

Easily add a domain into your /etc/hosts file, nice for development with vhosts. All credit goes to artheus for his answer on [Ubuntu forums](http://ubuntuforums.org/showthread.php?t=1419032).

## Installation

1. Clone the repo somewhere
2. Add that directory to your path
3. Make the script executable: ````chmod +x domainadd````

## Usage

1. Execute ````sudo domainadd server.dev```` from anywhere
2. Optional: add an alias to your ````.bashrc```` or ````.zshrc```` for automatic sudo: ````alias domainadd='sudo domainadd'````

