Ejudge
---

For programming tasks (homeworks), the [Ejudge](https://ejudge.ru) contest system is used.
It helps automate the process of checking homeworks and other programming assignments.

This document contains instructions on how to configure and maintain Ejudge.

# Installation

Ejudge is installed from source code.
The official instruction in Russian is
[here](https://ejudge.ru/wiki/index.php/Инсталляция_из_исходных_текстов).
The challenge is to install in in Ubuntu 20, while the official instruction is for Ubuntu 16.

Also, [here](https://zharaskhan.com/ru/posts/ejudge-installation) is the link
to the instructions on how to install in in Ubuntu 18.

## Required libraries

The list of required libraries is [here](https://ejudge.ru/download/ubuntu-16-install-packages-x86_64).
This list is for Ubuntu 16. Some of library versions might be irrelevant.
So, we need to try to find the library names, which are relevant.
Another way is to try compile the sources of Ejudge and install packages based on error messages.

## Installation folders

Please read [here](https://ejudge.ru/wiki/index.php/Инсталляционные_каталоги)
about installation folders. Please note that they must be consistent
(though the official manual might use different user names and user folder paths in different chapters).

## Configure options

Options for `configure` are [here](https://ejudge.ru/wiki/index.php/Рекомендуемые_опции_configure). 

# Downloading and installing.

The download URL for the latest Ejudge version 3.8.0 is this:

http://ejudge.ru/download/ejudge-3.8.0.tgz

The official instruction is [here](https://ejudge.ru/wiki/index.php/Инсталляция_системы_ejudge).
Please pay attention to the user, under which the system will be installed.
He must a have a superuser rights. The manual suggests creating a special user / group (`ejudges`). 

# Running

```bash
cd /home/ejudge/ejudge
su ejudge
./ejudge-control start
exit
```

# Logging In As Admin

Server:
http://158.160.144.239/cgi-bin/serve-control

__TODO__

# Changing passwords

__TODO__

# Adding users

Users can be added from a CSV table in a special format (see [example](222.csv)).

# Creating contests

__TODO__

# Checking results

__TODO__
