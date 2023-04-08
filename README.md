# Fitch

Command line system information display utility for Linux systems built with .NET (F#).

![Fitch CLI Tool](./images/fitch-display.png)

[![Generic badge](https://img.shields.io/badge/Made%20with-FSharp-rgb(1,143,204).svg)](https://shields.io/)

**NOTE: This application should work on most Linux systems. However, it's only been tested on Arch-based distributions like Manjaro and Debian-based distributions like Ubuntu**

## Dependencies

- [Spectre.Console](https://spectreconsole.net/)

## Build from source

### Prerequisites

- [.NET 7 SDK](https://dotnet.microsoft.com/download/dotnet/7.0) 

### Instructions

1. Clone [fitch repo](http://www.luisquintanilla.me/github/fitch) in your Linux machine

    ```
    git clone http://www.luisquintanilla.me/github/fitch
    ```



1. Nagivate to the project directory and run the script Setup.sh

    ```bash
    cd fitch
    ```

    ```bash
    ./Setup.sh
    ```

    ![Setup.sh](./images/setup.gif)

    Running this script will generate an executable called `fitch` in the *bin/Release/net7.0/linux-x64/publish* directory and copy it to the */usr/bin/* directory.


## Run application

1. Run the `fitch` command in your terminal

    ```bash
    fitch
    ```

1. (Optional) Add the `fitch` command to your shell config file to start when your shell starts. 

## To-Dos

- [ ] Enable customization through config file
- [ ] Publish to NuGet as dotnet global tool

## Acknowledgements

This project was inspired by [Nitch](https://github.com/unxsh/nitch) and [Neofetch](https://github.com/dylanaraps/neofetch)