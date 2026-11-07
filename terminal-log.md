Exercise 1 : Basic Navigation
pwd- Showed the current working directory path.
ls - Listed files and directories in the current folder.
cd ~/Documents - Navigated to the Documents directory.
cd .. - Moved up one directory level.
cd ~ - Returned to the home directory.
cd ~/terminal-practice - Navigated into the terminal practice directory.

Exercise 2 : Create Project Structure
mkdir my-project - Created the main project folder.
cd my-project- Navigated into the my-project directory.
mkdir -p src/css src/js src/images docs tests - Created nested subdirectories for source assets,docs, and tests.
touch README.md- Created an empty README.md file inside my-project.
ls -R- Listed all files and subdirectories to verify the structure.

Working with Directories
cp -r src/ src-backup/ - Copied the src directory to src-backup.
mv src-backup/ archive/ - Renamed the src-backup directory to archive.
rmdir archive/ - Attempted to remove archive failed because the directory was not empty.
rm -r archive/ - Removed the non-empty archive directory and its contents.

Portfolio Reorganization
mkdir portfolio-v2 - Created anew folder for the re-organized project version 2 structure.
mv src/ portfolio-v2/ - Moved the src folder into portfolio-v2.
mv README.md portfolio-v2 - Moved the README file into portfolio-v2.
ls -R portfolio-v2 - Listed the contents of portfolio-v2 to verify the final reorganized structure.

Useful Terminal Commands
Search and Find
find portfolio-v2 -name "*.html"
grep -rn "contact" portfolio-v2/
grep -r "button" ./src/
wc -1 portfolio-v2/src/css/*.css
history 
