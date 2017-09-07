## Cloning Your Repository
1. Go to github.com and access your project0 folder. This should be in CS1520 organization with the name <USERNAME PREFIX>-project0.
  * Note: I am assuming that your pitt username and git username for this class are the same.
2. Click clone or download and copy the git link
3. Open terminal, command line, etc.
4. Clone your github repo by typing/pasting 
  * git clone &ltclone with HTTPS link&gt 
  * Example link: https://github.com/PittCS1520/PITTID-project0.git

Note: if you get an error that says the repo is not found, at may be the case that your global config is not set. An alternative to setting your global config is to include your git username in git clone.
git clone https://<GIT USERNAME>@github.com/PittCS1501/<USERNAME PREFIX>-project0.git


## Add/Modifying Your Files
Follow Dr. Farnan’s specifications written in the README.md
Additional Information:
* Examine git status and git diff to see how this changes as you modify/add/commit files
* To add files to be committed you can 
  * Individually add files: git add <FILE>
  * Add all files: git add . 
* Modifying/Creating files in the command line can be done with nano (for example, nano file.txt). There are other command line editors.
* Commit files by git commit -m “<COMMIT MESSAGE>”
* Push the staged commit: git push
