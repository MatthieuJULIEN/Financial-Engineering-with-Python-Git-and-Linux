# TD 1

## Exercise 1 : Move around
1. Go to the root directory
``` 
cd /
```

2.  Display the content of the current (root) directory

``` 
ls
```

3. Check your current location
``` 
pwd
```

4. Try to create a directory named test
``` 
mkdir test
```
5. Go to the general home directory (should contain folders named after
each user)
``` 
cd /home
```
6. Go to your home directory
``` 
cd $HOME
```
7. Go back to the general home directory (located "just above")
``` 
cd ..
```
8. Go again "just above", you should be back to the root directory
``` 
cd ..
```
9. Go directly to your home directory (named after you). It should be a
very simple command, which take no name as parameter of the path
``` 
cd ~
```
10. Try to create a directory named test
``` 
mkdir test
```
11. Go into this new directory
``` 
cd test
```
12. Check your current location
``` 
pwd
```

## Exercice 2 : Create, Rename, copy, delete

1. Go to your home directory (should be named after you, you might be
there by default)
``` 
cd ~
```
2. Check your current location
``` 
pwd
```
3. Create a folder linux_ex_1
``` 
mkdir linux_ex_1
```
4. Go into this folder
``` 
cd linux_ex_1
```
5. Create an empty text file named [first_name]_[last_name].txt (e.g. alexis_bogroff.txt)
``` 
touch [first_name]_[last_name].txt
```
6. Create a folder notes
``` 
mkdir notes
```
7. Move your text file into this folder
``` 
mv [first_name]_[last_name].txt notes/
```
8. Rename the text file by appending the current year [first_name]_[last_name]_[current_year].txt
``` 
mv notes/[first_name][last_name].txt notes/[first_name][last_name]_[current_year].txt
```
9. Make a copy of this folder, name it notes_2022
``` 
cp -r notes notes_2022
```
10. Delete the first folder (notes) using the verbose option
``` 
rm -rv notes/
```

## Exercice 3 : Create and run a script

1. Create a script script_1.sh in the folder linux_ex_1
``` 
touch script_1.sh
```
2. In the script, write the commands that would output the following :
Script running please wait ...
Done.
``` 
echo "echo 'Script running please wait ...'; echo 'Done.'" > script_1.sh
```
3. Quit editing and save the script
``` 

```
4. Display the content of the script (using a command, not from an editor)
``` 
cat script_1.sh
```
5. Run the script
``` 
bash script_1.sh
```
