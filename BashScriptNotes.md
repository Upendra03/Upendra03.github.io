# Bashscript notes

- which bash -> to know the bash directory
- #! -> shebang, informs the kernel name of the interpreter to execute the script
- chmod 755 first -> set 755 to make the executable by all, 700 for only owners
- do not use .sh as extension in the name of the file
- /bin -> default directory where scripts are looked up
- echo $PATH -> prints all directory where scripts are searched
- by default linux looks up for 'bin' folder in user home directory. create a 'bin' folder and move the bash script in there.
- the below code adds the bin folder to the $PATH
> export PATH=~/bin:"$PATH"
- either close and re-open the terminal for change to take effect or run . .bashrc

