# doc4sh

This a collection of scripts that could be a Ghist each.

## `get_comments`

During my _Unix_ course, this is one of the exercice I ask my students in
order to start playing with learned concepts and commands: 
1. "Write a script that will extract comment from a shell script. But make 
it fail when the script is called with no argument, and also when the script
file cannot be found or read, or doesn't contain shebang. Try to use only
grep and keep your script the smallest possible."
2. "Same script, but display some error message, when possible, with the
parameter expansion. Also change the check to allow any good name from 
/usr/ and /usr/local. Then, the script can work with: PERL, PHP, Python,
Ruby, Tcl, etc."
3. "Now, let user add the comment characters. it should be optional, and
still default to the hashtag. By the same way, the script should work on
non-shell scripts too, and test with an unstrurtured BASIC file for example
Be aware that delimiter lenght may change... (`'[0-9]* REM '` vs `'# '` ...)
Finally, completely relax the check, so that it can accept something like
`#!/bin/env somename` and others."
4. "Finally, let user indicate, optionally, the beginning and the ending of
comments. So the script may extract bloc comments from PHP and others."
5. "Let's reload the script using `sed` anywhere possible. Now, observe that
it works for Ruby and Python multi-lines comments. Yeah. But less good on C."

