1. **alias name="value"** Creates an alias of *name* for the *value* command<br>
2. **echo hello $USER** Prints hello and the current Linux user<br>
3. **export PATH=$PATH:/folder** Adds *folder* to _PATH_ and makes it the last directory in _PATH_ <br>
4. **ls $PATH | wc -l** Counts the number of directories in the _PATH_ <br>
5. **printenv** Lists global/environmental variables<br>
6. **set** Lists all local variables as well as global/environmental variables<br>
7. **VARNAME="value"** Creates a new local variable _VARNAME_ <br>
8. **export VARNAME="value"** Creates an global/environment variable<br>
9. **echo $((1 + $VARNAME))** Prints the result of the addition of 1 to the value stored in the _VARNAME_ variable<br>
10. **echo $(($VARNAME / $DIV))** Prints the result of _VARNAME_ divided by _DIV_ <br>
