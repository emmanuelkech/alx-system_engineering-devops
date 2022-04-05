1. **alias name="value"** Creates an alias of *name* for the *value* command<br>
2. **echo hello $USER** Prints hello and the current Linux user<br>
3. **export PATH=$PATH:/folder** Adds *folder* to _PATH_ and makes it the last directory in _PATH_ <br>
4. **echo $PATH | tr -s ":" "\n" | wc -l** Counts the number of directories in the _PATH_ <br>
5. **printenv** Lists global/environmental variables<br>
6. **set** Lists all local variables as well as global/environmental variables<br>
7. **VARNAME="value"** Creates a new local variable _VARNAME_ <br>
8. **export VARNAME="value"** Creates an global/environment variable<br>
9. **echo $((1 + $VARNAME))** Prints the result of the addition of 1 to the value stored in the _VARNAME_ variable<br>
10. **echo $(($VARNAME / $DIV))** Prints the result of _VARNAME_ divided by _DIV_ <br>
11. **echo $(($BREATH ** $LOVE))** Prints the result of _BREATH_ to the power _LOVE_ <br>
12. **echo $((2#$BINARY))** Prints the result of the conversion of _BINARY_ to decimal (base 10) <br>
13. **echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"** Prints all possible combinations of two lower case letters, except _oo_, one combination per line and alpha ordered<br>
14. **printf "%.2f\n" $NUM** Prints a number stored in _NUM_ with two decimal places and adds a new line<br>
15. **printf '%x\n' $DECIMAL** Prints the result of the conversion of _DECIMAL_ (base 10) to base 16 <br>
16. **tr '[A-Za-z]' '[N-ZA-Mn-za-m]'** Encodes and decodes text using the rot13 encryption. Assume ASCII <br>
17. **paste - - | cut -f 1** Prints every other line from the input, starting with the first line <br>
18. **printf "%o\n" $((5#$(echo $WATER | tr 'water' '01234') + 5#$(echo $STIR | tr 'stir.' '01234'))) | tr '01234567' 'behlnort'** Adds two numbers stored in thr environment variable _WATER_ and _STIR_ and prints the result. _WATER_ is in base _water_, _STIR_ is in base _stir._, and the result is in base _bestchol_
