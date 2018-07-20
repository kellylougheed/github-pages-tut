# How to Put Your Project Online!
#### Cloud9 & GitHub Pages

1. Create a new repository in your GitHub account. Go to your profile, then to "Respositories", and click the green "New" button to create a new repo. Name it after your project and press "Create Repository." After you create it, you should be taken to a new page with git commands on it.
2. Navigate to your project directory in Cloud9 using `cd`.
3. In your Cloud9 terminal, run the command `git init`.
4. Run `git status`.
5. Run `git add .` to stage all your files to be added to the repo.
6. Run `git commit -m "Initial commit"` to commit your files.
7. Run `git remote add origin YOUR_REPO_URL_HERE` to tell Cloud9 where to push the files. You can get your repo URL by referring the git commands given to you on the GitHub page you were taken in step one. The URL should end in `.git`.
8. Run `git push -u origin master` in Cloud9.
9. Go back to GitHub and refresh your repo page. You should now see your code in the repo! Navigate to "Settings" in the top menu bar.
10. In Settings, scroll down until you see "GitHub Pages." Add "master branch" as a source and then hit save.
11. Make another change to your project repo in Cloud9.
12. Run `git status` to see your change, and `git add .` to add the change to your next git commit.
13. Run `git commit -m "Your message here"` with a message describing your change.
14. Run `git push origin master` to push the change to your GitHub repo.
15. Go to the GitHub Pages URL that appeared in your settings. You should now be able to see your live site!

## GitHub Workflow
##### Terminal Commands

1. `git status`
2. `git add .`
3. `git commit -m "Message describing changes"`
4. `git push origin master`

## Common Gotchas
1. Did you `git init` the repository?
2. Did you `cd` in your project directory on Cloud9?