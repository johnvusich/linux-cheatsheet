# Linux Commands Cheat Sheet

This markdown document is adapted from [guru99's Linux Commands Cheat Sheet](https://www.guru99.com/linux-commands-cheat-sheet.html) by Emily Carter.

---

## Table of Contents

* [Basic Linux Commands](#basic-linux-commands)
* [File Permission Commands](#file-permission-commands)
* [Environment Variables](#environment-variables)
* [User Management](#user-management)
* [File Commands](#file-commands)
* [Process Related Commands](#process-related-commands)
* [Networking Commands](#networking-commands)
* [Compression Commands](#compression-commands)
* [Disk Usage Commands](#disk-usage-commands)
* [SSH Commands](#ssh-commands)
* [Package Management (Debian/Ubuntu)](#package-management-debianubuntu)
* [Package Management (Red Hat/CentOS)](#package-management-red-hatcentos)
* [VI Editing Commands](#vi-editing-commands)

---

## Basic Linux Commands

| Command           | Description                            |
| ----------------- | -------------------------------------- |
| `pwd`             | Displays the present working directory |
| `ls`              | Lists files and directories            |
| `cd`              | Changes the directory                  |
| `cd ~`            | Navigate to HOME directory             |
| `cd ..`           | Move one level up                      |
| `cd /`            | Move to the root directory             |
| `mkdir`           | Creates a new directory                |
| `rmdir`           | Removes an empty directory             |
| `touch file_name` | Creates a new file                     |
| `cat file_name`   | Displays the content of a file         |

---

## File Permission Commands

| Command | Description                  |
| ------- | ---------------------------- |
| `chmod` | Changes the file permissions |
| `chown` | Changes the file owner       |
| `chgrp` | Changes the group ownership  |
| `umask` | Sets default permissions     |

---

## Environment Variables

| Command            | Description                        |
| ------------------ | ---------------------------------- |
| `printenv`         | Displays all environment variables |
| `export VAR=value` | Sets an environment variable       |
| `echo $VAR`        | Displays value of a variable       |

---

## User Management

| Command   | Description           |
| --------- | --------------------- |
| `adduser` | Adds a new user       |
| `passwd`  | Changes user password |
| `userdel` | Deletes a user        |
| `usermod` | Modifies a user       |

---

## File Commands

| Command | Description                                 |
| ------- | ------------------------------------------- |
| `cp`    | Copies files and directories                |
| `mv`    | Moves or renames files/directories          |
| `rm`    | Removes files or directories                |
| `find`  | Searches for files in a directory hierarchy |

---

## Process Related Commands

| Command    | Description                        |
| ---------- | ---------------------------------- |
| `ps`       | Displays current running processes |
| `top`      | Displays active processes          |
| `kill PID` | Kills a process by PID             |
| `killall`  | Kills all processes by name        |

---

## Networking Commands

| Command           | Description                   |
| ----------------- | ----------------------------- |
| `ping`            | Checks connectivity to a host |
| `ifconfig` / `ip` | Displays network interfaces   |
| `netstat`         | Displays network connections  |
| `wget`            | Downloads files from the web  |

---

## Compression Commands

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `tar`           | Archives files                       |
| `gzip`          | Compresses files                     |
| `gunzip`        | Decompresses gzip files              |
| `zip` / `unzip` | Compresses or decompresses zip files |

---

## Disk Usage Commands

| Command  | Description                              |
| -------- | ---------------------------------------- |
| `quota`  | Displays space quota for all file spaces |
| `df`     | Displays disk space usage                |
| `du`     | Displays file space usage                |
| `mount`  | Mounts a file system                     |
| `umount` | Unmounts a file system                   |

---

## SSH Commands

| Command               | Description                            |
| --------------------- | -------------------------------------- |
| `ssh user@host`       | Connects to a host via SSH             |
| `scp file user@host:` | Securely copies files between machines |

---

## Package Management (Debian/Ubuntu)

| Command           | Description           |
| ----------------- | --------------------- |
| `apt-get update`  | Updates package list  |
| `apt-get upgrade` | Upgrades all packages |
| `apt-get install` | Installs new package  |
| `apt-get remove`  | Removes a package     |

---

## Package Management (Red Hat/CentOS)

| Command       | Description                 |
| ------------- | --------------------------- |
| `yum update`  | Updates all packages        |
| `yum install` | Installs new package        |
| `yum remove`  | Removes a package           |
| `rpm -i`      | Installs a package manually |

---

## VI Editing Commands

| Command    | Description              |
| ---------- | ------------------------ |
| `i`        | Switches to insert mode  |
| `Esc`      | Switches to command mode |
| `:w`       | Saves the file           |
| `:q`       | Quits VI                 |
| `:wq`      | Saves and quits          |
| `/pattern` | Searches for a pattern   |
| `dd`       | Deletes a line           |

---

