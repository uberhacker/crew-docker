# crew-docker
Bash script to launch ChromeOS with Chromebrew in Docker

## Prerequisite
[Docker](https://docs.docker.com/engine/install/)

## Installation
```bash
$ git clone https://github.com/uberhacker/crew-docker.git
$ sudo cp crew-docker/crew-docker /usr/local/bin
$ rm -rf crew-docker
$ cd /path/to/projects
$ git clone https://github.com/chromebrew/chromebrew.git
$ mkdir pkg_cache
```

## Usage
```bash
$ cd /path/to/projects (the parent directory where chromebrew was cloned)
$ crew-docker armv7l|i686|x86_64 [chipset milestone]
```

## Examples
```bash
$ crew-docker armv7l (installs fievel m91)
$ crew-docker arm strongbad m120
$ crew-docker x86_64 (installs nocturne m90)
$ crew-docker x64 nocturne m120
$ crew-docker x86 (installs alex m58)
```

## Troubleshooting
TBD
