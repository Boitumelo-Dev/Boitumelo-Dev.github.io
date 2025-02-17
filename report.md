- Created a github repo called "Boitumelo-Dev.github.io" for GitHub Pages purposes.
- Configured git via the CLI to input my username and email
- I cloned my repo into a local folder
- Created the required files with the index.html file having all the required code and the <h1> tag.
- Commit these changes and used the Special Commit Message then pushed this changes.
- Created a branch called feature/student-details
- Inserted all the information as required into each file in the brief under the student-details branch
- Committed and pushed these changes under the commit message "added required information in files"
- Since these changes are under the feature/student-details branch, I merged the two branches into main
- Committed and pushed the changes then the GitHub Pages site was accessible

Commands used:

git config --global user.email "Boitumelo-Dev"
git config --global user.email "2559819@students.wits.ac.za"
git clone https://github.com/Boitumelo-Dev/Boitumelo-Dev.github.io.git

**created files and input html code into index.html

git add .
git commit -m "feat: Initial commit with student files"
git push origin main

git checkout -b feature/student-details

**edited and added information into report.md and student-details.txt

git commit -m "added required information in files"
git push origin feature/student-details

Then merged the two branches after making an additional edit in report.md

git commit -m "merged main with feature/student-details"