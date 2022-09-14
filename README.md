# Challenges for the CEO Web Development Class #

## Daily Challenge: ##
1. Sign in to your GitHub account
2. Click the green `New` button top create a repo
    - Choose the owner (you) from the drop-down and name the repo `day11`
    - Make sure you check the box next to "Add a README.md file"
3. Copy the SSH “code” for the new repo: (this will be used when we clone the repo on our local computer)
    - Click the green button that says code
    - Select SSH, not HTTPS
    - Click on the double-page icon to copy the repo code to your clipboard
4. Now, on your local machine, launch Git Bash
5. Navigate to the `ceo-web-dev` folder:
    - In Bash: `cd ~/Desktop/ceo-web-dev/` (if your computer is using One Drive you will need to go to the `OneDrive` folder first)
6. Clone the `day11` repo:
    - In Bash: `git clone` + PASTE (right-click->paste) YOUR REPO CODE FROM STEP 3 ABOVE
7. In VSCode navigate to the `day11` folder and:
    - Create an `index.html` file 
    - Create an `img` folder
    - Create a `css` folder
        - Inside the `day11/css` folder: 
            - Create a `styles.css` file
            - Create a `nav.css` file
            - Create a `fonts` folder
8. Open the `day11/index.html` file and create an HTML template with `!` + `TAB`
9. `<link>` Both the `styles.css` and `nav.css` files (remember that they are in the `css` folder)
10. Back in Bash, inside the `Desktop/ceo-web-dev/day11` folder, do the git "add, commit, and push":
    - `git add .` to add all the new files and folders to the staging area (remember the space between 'add' and the '.')
    - `git commit -m "new files"` to commit the staged files to the local repo
    - `git push origin main` to push the local repo to GitHub
11. In your browser, refresh your day11 GithHub repo page to see your files
