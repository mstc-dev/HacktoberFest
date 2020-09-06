# Hacktoberfest_firstPR
This repository aims at providing guidance & simplifying the way beginners make their first contribution. If you are looking forward to make your first contribution, follow the steps below.
If you don't have git installed on your machine then, [install it]( https://help.github.com/articles/set-up-git/).

## Step 1 : Fork this repo
Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your github account.

## Step 2 : Clone the repository
Now clone the forked repository to your device. Click on the clone button and copy to your clipboard.
Open terminal and write command "git clone {url you just copied}"

e.g. if you copied url "https://github.com/mstc/mstc.git" then command will look like this
```
git clone https://github.com/mstc/mstc.git
```

## Step 3 : Create a branch
go to directory where you clonned the repo if you aren't already.
Create branch using git checkout command
```
git checkout -b add-dhyey
```
(we recommend you to name branch add-{your name} for making logical name)

## Step 4 : Make necessary changes
In contributers.md file add your name, github profile link (optional: do tell us why you are excited about open source)

## Step 5 : Stage changes and make commit
write "git status" command for checking status.
to stage your changes 
```
git add contributers.md
```
to commit these changes
```
git commit -m "add dhyey to Contributors list"
```
(use your name in commit message)

## Step 6: Push changes to github
write this command to push changes but use name of your branch
```
git push origin add-dhyey
```
for example if name of your branch is add-vrushti then write "git push origin add-vrushti"

## Step 7: Submit changes for review and make PR
If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.
Submit pull request with proper title and comments if you wanna add

Congratulations you created your first PR successfully.
We will merger your PR with repo and that would be all for 1st PR.
 
# Don't stop here.
This is beginning there is lot to explore do connect with us if you have any queries.

<a href="https://mstc.now.sh/" style="display:inline;"><img src="data:image/png;base64,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" alt="MSTC" height="50px"></a>&nbsp; &nbsp;
<a href="mailto:microsoftclub@daiict.ac.in" style="display:inline;"><img src="https://ssl.gstatic.com/ui/v1/icons/mail/rfr/logo_gmail_lockup_default_1x.png" alt="Gmail" height="30px"></a>

