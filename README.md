# learning_cli_from_codex

### Navigation

01. Beginning...
02. Filesystem
03. Moving Day
04. House Tour
05. Clean Slate
06. Scavenger Hunt

### Manipulation

07. Recipes
08. Cuisine Type
09. Grilled Cheese
10. Move Around
11. Copy That
12. Music Playlists

# Navigation
## Command	--- Description
echo --- output-here	Print what is typed next to this command.<br>
pwd	--- Print the current working directory.<br>
cat file-name.extension ---	Print the contents of a file.<br>
ls ---	List the contents of the current directory.<br>
cd directory-name ---	Change into an existing directory.<br>
cd ..	--- Change backward into an existing directory.<br>
cd directory-name/sub-directory-name	--- Change forward on multiple directories.<br>
cd ../..	--- Change backward on multiple directories.<br>
clear	--- Clear the command line screen.<br>

# Manipulation
## Command ---	Description
mkdir ---	Create a new directory from the current directory.<br>
touch	--- Create and save a new file.<br>
echo "text" > file ---	Overwrite existing content in file with "text".<br>
echo "this text" >> file ---	Write "this text" to existing content in file.<br>
cat file-a > file-b ---	Overwrite content of file-b with content of file-a.<br>
cat file-a >> file-b ---	Add content of file-a to content of file-b.<br>
mv source-file target-file ---	Move/rename the source-file into the target-file.<br>
mv source-directory target-directory ---	Move/rename the source-directory into the target-directory.<br>
rm file	--- Delete a file.<br>
rm -r --- directory	Delete a non-empty directory.<br>
rmdir --- directory	Delete an empty directory.<br>
cp file-a > file-b	--- Copy content of file-a into a file-b (overwriting anything already inside).<br>
cp -r directory-a directory-b ---	Copy content of directory-a into a directory-b (overwriting anything already inside).<br>

# Operators
## " Operator " ---	Description ---	Example
" > "	--- Overwrite the contents of a file with the results of a command. ---	echo "Hello, World" > file.txt<br>
" >> "	--- Add the result of a command to the end of a file. ---	echo "Hello, World" >> file.txt<br>
" ; "	--- Run multiple commands in a row, one after another. ---	echo "Howdy there!" ; cat file.xt<br>
" || "	--- Logical OR: Runs an alternative command if the first one fails. ---	mkdir work || echo "Directory creation failed. Does it already exist?"<br>
" && "	--- Logical AND: Runs the next command if the first one succeeds. ---	mkdir video-games && cd video-games<br>
