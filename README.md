hist
====

A shell history utility for bash.

I use this utility instead of the *history* builtin in bash. It allows me to some things that are not possible with the standard builtin as well as some things that are not otherwise easy or straightforward:

1. retain my history forever
1. immediately see commands that were executed in other terminal sessions.
1. retain with each history entry information including: shell PID, exit code, and pwd at the time of execution.
1. query my entire history efficiently using `hist -ag $REGEXP`, where $REGEXP can include the datetime, shell id, directory of execution or any part of the command

