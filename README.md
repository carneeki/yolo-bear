yolo-bear
=========

It's backup. With swag. For Linux.

yolo-bear uses an application called rsync to perform the actual backups, and
will by default allow you to have a week's worth of files (assuming you backup
daily!) taking up only little more than the total amount of data you use.

It works by storing only what has changed, but, using github, you're probably
already used to that.


Instructions
============

Simply download, configure (look in the top couple of lines of the file), and
run every day.

yolo-bear is a completely self contained backup script that uses only a small
handful of binaries which are called by variable names (yes, on some systems you
might be forced to change them, but that's

1. rare (and)

2. better than accidentally calling the wrong binary because some nincompoop has
spoiled things in your $PATH variable.

Name
====

The name came from github's autosuggestertron. I figure, you do only live once,
so why spend all that time worrying about backups?
