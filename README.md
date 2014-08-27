hdfs-completion
===============

Bash completion for hdfs-cli, written with help from http://www.debian-administration.org/article/316.

Usage:
> Run hdfs-completion-update
> hdfs dfs -ls /your/path[TAB]

Installation:

> Put hdfs in /etc/bash-completion.d/
> Put hdfs-completion-update in /usr/local/bin

Notes:

> Make sure hdfs-completion-update is runnable (e.g 777)
> Modify DATA_LOC in hdfs if you don't like the current path, but make sure it matches with the path in hdfs-completion-update
> You might need to modify hdfs-completion-update to suite your needs depending on how you use hdfs
