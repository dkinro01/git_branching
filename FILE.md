# git_branching

## Visualization of 15 commits:
https://github.com/dkinro01/git_branching/network
<br>
![](13.png)
<br>
## Terminal commands to get the network graph above:
01 git init<br>
02 git add README.md<br>
03 git commit -m "Initial commit"<br>
04 git checkout -b bug-fix<br>
05 git checkout main<br>
06 git commit -a -m "1"<br>
07 git commit -a -m "2"<br>
08 git checkout bug-fix<br>
09 git commit -a -m "3"<br>
10 git commit -a -m "4"<br>
11 git checkout -b bug-fix-experimental<br>
12 git checkout bug-fix<br>
13 git merge main<br>
14 git mergetool<br>
15 git commit -a -m "Merge branch 'main' into bug-fix"<br>
16 git checkout bug-fix<br>
17 git commit -a -m "6"<br>
18 git checkout bug-fix-experimental<br>
19 git commit -a -m "7"<br>
20 git commit -a -m "8"<br>
21 git commit -a -m "9"<br>
22 git checkout main<br>
23 git commit -a -m "10"<br>
24 git checkout bug-fix<br>
25 git merge bug-fix-experimental<br>
26 git mergetool<br>
27 git commit -a -m "Merge branch 'bug-fix-experimental' into bug-fix"<br>
28 git checkout bug-fix<br>
29 git commit -a -m "12”<br>
30 git checkout main<br>
31 git merge bug-fix<br>
32 git mergetool<br>
33 git commit -a -m "Merge branch 'bug-fix'"<br>
## Note to marker:
In a few practice runs, I was getting merges wrong when I used numbers, so I have expressly written out what I wanted to do instead of using numbers for commits 5, 11, and 13.
