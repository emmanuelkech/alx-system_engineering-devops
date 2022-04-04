**echo "Hello"** Prints *Hello* to the standard output<br>
**cat file** Displays the content of the *file* file<br>
**cat file1 file2** Displays the content of *file1* and *file2* files<br>
**tail -n 10 file** Displays the last 10 lines in the *file* file<br>
**head -10 file** Displays the first 10 lines in the *file* file<br>
**head -3 file | tail -1** Displays only the third line in the *file* file<br>
**ls -la > file** Writes into the *file* file, the result of the command *ls -la*<br>
**tail -1 file >> file** Duplicates the last line of the *file* file into the same *file* file<br>
**find . -name "*.js" -type f -delete** Removes all the files with .js extensions in the current directory<br>
**ls -t | head -10** Displays the 10 newest files in the current directory sorted from newest to oldest<br>
**sort | uniq -u** Takes a list of words as input and prints only words that appear exactly once<br>
**grep 'word' file** Displays lines containing *word* in the *file* file<br>
**grep -c 'word' file** Counts and displays the number of lines containing *word* in the *file* file<br>
**grep -A 3 'word' file** Displays lines containing *word* and 3 lines after them in the *file* file<br>
**grep -v 'word' file** Displays all other lines apart from the lines containing *word* in the *file* file<br>
**grep '^[[:alpha:]]' file** Displays all lines of the *file* filstarting with a letter<br>
**rev** Reverses an input<br>
**tr a b | tr A B** Replaces all character occurence of *a* and *A* with *b* and *B* in an input<br>
**tr -d 'Aa'** Removes every occurence of *A* and *a* from an input<br>
**cut -d : -f 1,6 psswdfile | sort** Displays the component of *psswdfile* in a sorted format based on username(1) and user home directory(6)<br>
