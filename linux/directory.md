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