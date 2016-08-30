1. switch to previous working directory

> cd -

2. create directory and intermediate directories

> mkdir -p /one/two/

3. recursive listing

> ls -R

> tree -d -C

4. change permissions

> chmod u+x test.txt

> chmod g-w test.txt

> chmod o=r test.txt

> chmod a=rwx test.txt

> chmod u=rwx,g+w,o= test.txt

5. view files

> head -10 file.txt

> tail -100 file.txt

> tail -f file.log

> less file.log then type F

6. IO

- send the standard output of one command as the standard input to another command
> cat test.txt | sort

- use the contents of a file as standard input
> sort < test.txt

- redirect the output of a command to a file
> sort test.txt > sorted.txt

- append output to a file
> sort test.txt >> sorted.txt

- redirect standard error
> ls no-such-file 2> error.txt

- combine standard output and standard error
> ls text.txt no-such-file > combined.txt 2>&1

7. alias

> alias ll 'ls -l'

> unalias ll

> unalias -a

8. Personal Initialization Files

- reads and executes the commands from the given file in the current shell
> source ~/.bashrc

> . ~/.bashrc