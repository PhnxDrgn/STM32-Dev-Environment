# STM32 Development Environment
## Description
This template serves as an STM32 development environment base. The goal is to start a container detatched that can be attached to for development. The firmware directory is mounted so all code that is placed in there will be in `/workspace` inside of the container. There is also a `.bashrc` that is mounted so the user can edit their preferences for bash.

## How to Use
Running `start_dev_container.sh` will start a detatched Alpine container with all the tools necessary for building and debugging STM32 code.

You should be able to use VSCode to attach to that running container developing code, regardless of host machine OS.