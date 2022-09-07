# Challenges for the CEO Web Development Class #

## Current Challenge: ##
### Day 9d, Daily Challenge - Tuesday (09/06/2022) ###
1. Navigate to tonight's repo on GitHub: [day09d](https://github.com/zeromile/day09d)
2. "Fork" the repo
    - Click on the button that says "Fork" in the upper right hand corner
3. Choose the owner (you) from the drop-down and leave the repo name as `day09d`
4. Click the green "Create fork" button
5. Copy the SSH “code” for the new repo: (this will be used when we clone the repo on our local computer)
    - Click the green button that says code
    - Select SSH, not HTTPS
    - Click on the double-page icon to copy the repo code to your clipboard
5. Now, on your local machine, launch Git Bash
6. Navigate to the `ceo-web-dev` folder:
    - In Bash: `cd ~/Desktop/ceo-web-dev/` (if your computer is using One Drive you will need to go to the `OneDrive` folder first)
5. Clone the `day09d` repo:
    1. In Bash: `git clone` + PASTE (right-click->paste) YOUR REPO CODE FROM STEP 5 ABOVE
6. In VSCode navigate to the `day09d` folder and:
    1. Create an `index.html` file 
    2. Create an `img` folder
    3. Create a `css` folder
    4. Create a `fonts` folder
7. Inside the `day09d/css` folder: 
    1. Create a `styles.css` file
    2. Create a `nav.css` file
8. Open the `day09d/index.html` file and create an HTML template with `!` + `TAB`
9. `<link>` Both the `styles.css` and `nav.css` files (remember that they are in the `css` folder)
10. In Bash, inside the `Desktop/ceo-web-dev/day09d` folder, do the git "add, commit, and push":
    1. `git add .` to add all the new files and folders to the staging area (remember the space between 'add' and the '.')
    2. `git commit -m "new files"` to commit the staged files to the local repo
    3. `git push origin main` to push the local repo to GitHub
11. In your browser, refresh your day09d repo page to see your files

## Past Challenges: ##
- [Day 09c - Tuesday(08/30/2022)](https://github.com/zeromile/ceo-challenges/tree/day09c)
- [Day 09b - Tuesday(08/30/2022)](https://github.com/zeromile/ceo-challenges/tree/day09b)
- [Day 09 - Thursday(08/25/2022)](https://github.com/zeromile/ceo-challenges/tree/day09)
