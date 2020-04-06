make sure you are in the right directory in your terminal 


.../2-Boostrap/Nucamp Site


git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/dianaramirez16/Nucamp-Bootstrap.git
git push -u origin master


some warning messages you might see:

warning: would you like to add node_modules to 
gitignore? 

solution: select YES 


warning: LF will be replaced by CRLF in readme.txt.
The file will have its original line endings in your working directory.   

solution : enter this command in your terminal: 

git config core.autocrlf true

(more info: https://stackoverflow.com/questions/5834014/lf-will-be-replaced-by-crlf-in-git-what-is-that-and-is-it-important)

	