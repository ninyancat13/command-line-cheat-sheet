# command-line-cheat-sheet

## ZSH Style Guide
https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/
I use the dracula theme https://draculatheme.com/iterm

## Deleting files
Credit: https://linuxize.com/post/how-to-remove-files-and-directories-using-linux-command-line/?fbclid=IwAR3tb1kUy2EDQz4rQ6FeY0hRo2usX5E0y7x-Hkh0TAfABCfrl6foLJkHq4g

To delete a single file, use the rm or unlink command followed by the file name:
```
rm filename
```
To delete multiple files at once, use the rm command followed by the file names separated by space.
```
rm filename1 filename2 filename3
```
You can also use a wildcard (*) and regular expansions to match multiple files. For example, to remove all .pdf files in the current directory, use the following command:
```
rm *.pdf
```
Use the rm with the -i option to confirm each file before deleting it:
```
rm -i filename(s)
```
To remove files without prompting, even if the files are write-protected, pass the -f (force) option to the rm command:
```
rm -f filename(s)
```
You can also combine rm options. For example, to remove all .txt files in the current directory without a prompt in verbose mode, use the following command:
```
rm -fv *.txt
```
How to Remove Directories (Folders)
```
rmdir dirname
```
To remove non-empty directories and all the files within them, use the rm command with the-r (recursive) option:
```
rm -r dirname
```
If a directory or a file within the directory is write-protected, you will be prompted to confirm the deletion.
To remove non-empty directories and all the files without being prompted, use rm with the -r (recursive) and -f options:
```
rm -rf dirname
```
To remove multiple directories at once, use the rm -r command followed by the directory names separated by space.
```
rm -r dirname1 dirname2 dirname3
```

## Cloning
In order to clone, copy the URL of the relevant repository and put inside this command
```
git clone URL
```
