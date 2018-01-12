# Notes so far:
- Nothing
- My merge request 1




``` bash
# optional i think
git add origin git@github.com:collinscole/nimbus.git

# To create a branch and checkout it
git checkout -b MY_COOL_BRANCH_NAME
# Just to checkout it
git checkout MY_COOL_BRANCN_NAME
# Check what branch your on
git branch
# Add the file to the stash
git add FILENAME
# Commit it to be changed
git commit -m "my cool message"
# Push your branch to github
git push origin MY_COOL_BRANCH_NAME

# checkout master
git checkout master
# Set the upstream path
git remote add upstream git@github.com:SilexOne/nimbus.git
# git info from branches
git fetch upstream
# git the info
git pull --rebase upstream master
```
