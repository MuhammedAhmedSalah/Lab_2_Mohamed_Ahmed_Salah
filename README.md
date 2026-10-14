Test
git init //intiliazed repo locally
git add Lab_2.txt // added first File
git commit -m "First Commit With Txt file" // commited first file
{
    git remote add origin git@github.com:MuhammedAhmedSalah/Lab_2_Mohamed_Ahmed_Salah.git
    git branch -M main
    git push origin main
} //pushed to remote repo(github)
git branch // lists out branches and states what branch you are on
git branch dev // created dev branch
git add .// added created files/changes to dev branch
git commit // commited changes to dev branch
git checkout main // checked out to main
git branch test // created test branch
git checkout test// swtiched to test
git add Branch_2_TestFile.txt // added file to test branch  
git commit -m "Fourth Commit (First Commit on the Second branch (Test)) " // commited changes to second branch

git checkout dev / swtiched to dev
git merge test / merged test and dev
git checkout main // switched to main
git merge dev// merged dev and main

git push --set-upstream origin main // pushed main branch after merges

git branch testBranch // crated a branch named testBranch
git branch -d testBranch // deleted the testBranch locally
git branch testBranch_2// created branch named testBranch 2

git push origin testBranch_2// pushed the branch

git push origin :testBranch_2 // deleted remotely

git branch testBranch_3 //created a new branch
git checkout testBranch_3 // swtiched
git add Branch_3_Testing_Stash.txt // added changes
git stash / stashed changes
git checkout main // swtiched to main
git checkout testBranch_3 // swtiched back to the branch with stashed changes
git stash list // lists stashes
git stash pop // brought back changes from stash
 git tag -a v1.7 -m "Testing annotated tag" // created annotaed tag named : v1.7
 git tag -a v1.8 -m "Testing deleting local tag 2" // created another annotated tag named v1.8

git tag -d v1.8 // deleted the tag named v1.8 locally

git tag -a v1.9 -m "testing deleting remote tag 2" // created a third tag named v1.9
git push origin v1.9 // pushed the third tag
git push origin --delete v1.9 // deleted the third tag remotely 
git add Testing_Img.png README.md // added image to readme file
git commit -m "Image Added To ReadME File " // commited the added image
