# status
A bash script to track progress of linux file commands. As of now, only `cp` command stats are implemented

Table of Contents
=================
* [Setup](#Setup)

# Setup

Download script with the following command:

`curl -O https://raw.githubusercontent.com/KostasEreksonas/status/main/status`

Enable execution of `status` script by setting the executable bit on:

`chmod +x status`

# Usage

Usage `./status -c <command> -p parameters -f <file-to-copy/(re)move> -t <target-directory>`
