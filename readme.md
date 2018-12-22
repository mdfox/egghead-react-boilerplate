# React Boilerplate

## Steps to start a new React project using this boilerplate:

1. Copy the clone link from GitHub
2. In terminal, navigate to the folder that your new React project's folder will reside
3. Run the following command:  
   `git clone --depth=1 <clone link from step 1> <folder name for your new React project>`
4. `cd` to the new folder
5. If you are using VS Code: `code -r .`
6. Remove from source control (since your new project is still pointing at this project):  
   `rm -rf .git`
7. Initialize a new git repository:  
   `git init`
8. Add all files to repo:  
   `git add .`
9. Commit:  
   `git commit -m "Initial commit"`
10. Create a new repo here on GitHub
11. Follow the instructions to push an existing repository from the command line
12. Edit `package.json`

- remove:  
  -repository  
  -bugs  
  -homepage
- edit:  
  -name  
  -description

13. Edit `readme.md`
14. Run `npm init -y` to add new origin information to package.json
15. Run `npm install` to install package dependencies
