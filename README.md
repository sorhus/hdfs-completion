hdfs-completion
===============

Bash completion for hdfs-cli,
<h5>Usage</h5>
* `hdfs-completion-update [/path/of/interest] [grep filter]`
* `hdfs dfs -ls /path/of/interest/[TAB]`
* e.g.`hdfs-completion-update /user ^d` will list all the content of /user, filtering out files

<h5>Setup</h5>
* Put `source /path/to/hdfs` in `.bashrc`
* Put `export HDFS_COMPLETION_TMP=/tmp/hdfs-completion` in `.bashrc`
* Put `hdfs-completion-update` in `/usr/local/bin/`

<h5>Notes</h5>
* Make sure `hdfs-completion-update` is runnable
* Written with help from http://www.debian-administration.org/article/316
