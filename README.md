# sewing-kit

Sewing-kit is a collection of programs designed to make day-to-day tasks for StepsAway developers easier.

### Prerequisites

__Disclaimer:__ _sewing-kit only works on OS X and Linux._

* Unix-based operating system (OS X or Linux)
* [Bash] should be installed (v3.2 or more recent).
* `curl` or `wget` should be installed
* `git` should be installed

### Basic Installation

sewing-kit is installed by running one of the following commands in your terminal. These commands will download the whole 
sewing-kit projects, so it is recommended that you run the command from your projects directory. 
You can install this via the command-line with either `curl` or `wget`. During the install you will be prompted to add 
sewing-kit to your PATH, it is highly recommended that you do. Not only will you be able to run the sewing-kit commands 
from anywhere, but sewing-kit will also periodically check for updates.

#### via curl

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/stepsaway/sewing-kit/master/install.sh)"
```

#### via wget

```shell
sh -c "$(wget https://raw.githubusercontent.com/stepsaway/sewing-kit/master/install.sh -O -)"
```

### List of commands
* composeify - wrapper for docker-compose. RUn composeify -f for help.
* configs-copy - copies configs from configs directory to the project directory. Run configs-copy -h for help.
* docker-clean - cleans exited containers, dangling images and dangling volumes. Run docker-clean -h for help.
* docker-commit - creates and pushes images based on a running container. Run docker-commit -h for help.
* docker-list - list all images within a docker repo. Run docker-list -h for help.
* docker-log - list all messages associated with an image. Run docker-log -f for help.
* docker-ship - takes image name, image tag and vcs branch name and ships the proper images to docker hub. Run ship-image -h for help.
* upgrade-swk - manually upgrade sewing-kit.

## License

sewing-kit is released under the [MIT license](LICENSE.txt).