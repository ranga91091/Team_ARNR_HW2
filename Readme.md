
This is readme.md file.

Third Edit.
Fourth Edit.
First Edit.
Second Edit.
Ninth Edit
Fifth Edit.
Sixth Edit.
Seventh Edit.
Eigth Edit.
Tenth Edit.Eleventh Edit.

---
![image](/Users/prabhushankar/Desktop/Screen Shot 2016-09-15 at 2.36.17 AM.png)

---
#Commands

git init

vi Readme.md 
git add Readme.md
git commit -m"Initial Commit"
vi Readme.md 
git add Readme.md
git commit -m"First Commit"
vi Readme.md 
git add Readme.md
git commit -m"Third Commit"
git checkout da728ee294d5848315e71217d286372699bb9262
git checkout -b bug-fix
vi Readme.md 
git add Readme.md
git commit -m"Fourth Commit"
vi Readme.md 
git add Readme.md
git commit -m"Fifth Commit"
vi Readme.md 
git add Readme.md
git log
git merge master

***CONFLICT (content): Merge conflict in Readme.mdAutomatic merge failed; fix conflicts and then commit the result.***
vi Readme.md 
git add Readme.md
git commit -m"Conflicts Resolved and this is a Sixth Commit"
vi Readme.md 
git add Readme.md
git commit -m"Seventh Commit"
git checkout 6c6305167019ce8cab8d7b71bbb206f281a7dd45
git checkout -b bug-fix-experimental
vi Readme.md 
git add Readme.md
git commit -m"Eight Commit"
vi Readme.md 
git add Readme.md
git commit -m"Ninth Commit"
vi Readme.md 
git add Readme.md
git commit -m"Tenth Commit"
git checkout master
git checkout 5c5786205a58543b541094b330ef9a7e3e418c9cvi Readme.md 
git add Readme.md
git commit -m"Eleventh Commit"
git checkout bug-fix
***Warning: you are leaving 1 commit behind, not connected toany of your branches:134a144 Eleventh Commit***git checkout mastergit cherry-pick 134a144vi Readme.md 
git checkout bug-fix
Switched to branch 'bug-fix'
git merge bug-fix-experimental 
***Auto-merging Readme.mdCONFLICT (content): Merge conflict in Readme.mdAutomatic merge failed; fix conflicts and then commit the result.***
vi Readme.md 
git add Readme.md
git commit -m"Twelfth Commit"
git checkout bug-fix
Switched to branch 'bug-fix'
vi Readme.md 
git add Readme.md
git commit -m"Thirteenth Commit"
git checkout master 
git merge bug-fix
Auto-merging Readme.md
***CONFLICT (content): Merge conflict in Readme.mdAutomatic merge failed; fix conflicts and then commit the result.***
vi Readme.md 
git add Readme.md
git commit -m"Fourteenth Commit"
vi Readme.md 
git add Readme.md
git commit -m"Fifteenth Edit"-uu-:**-F1  COMMIT_EDITMSG   All L12    (Fundamental)----------------------------------