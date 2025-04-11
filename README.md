PS E:\2nd Sem Programs\NewsHive> git pull origin main
remote: Enumerating objects: 55, done.
remote: Counting objects: 100% (46/46), done.
remote: Compressing objects: 100% (27/27), done.
remote: Total 55 (delta 26), reused 33 (delta 19), pack-reused 9 (from 1)
Unpacking objects: 100% (55/55), 16.59 KiB | 73.00 KiB/s, done.
From https://github.com/AdityaPrmr/NewsHive
 * branch            main       -> FETCH_HEAD
   eb92e1a..5c7d205  main       -> origin/main
Updating eb92e1a..5c7d205
error: Your local changes to the following files would be overwritten by merge:
        package-lock.json
Please commit your changes or stash them before you merge.
Aborting
PS E:\2nd Sem Programs\NewsHive> git reset --hard
>> git pull origin main
>>
HEAD is now at eb92e1a modified
From https://github.com/AdityaPrmr/NewsHive
 * branch            main       -> FETCH_HEAD
Updating eb92e1a..5c7d205
Fast-forward
 README.md                          |  59 ++++++++++++--
 package-lock.json                  | 137 +++++++++++++++++++++++++++++++
 package.json                       |   1 +
 src/App.jsx                        |   6 ++
 src/Pages/Home.jsx                 |   2 +-
 src/dashboard/Featured/Dis.jsx     | 157 +++++++++++++++++++++++++++++++++++
 src/dashboard/Featured/Live.jsx    | 162 +++++++++++++++++++++++++++++++++++++
 src/dashboard/layout/SideBar.jsx   |   4 +-
 src/dashboard/pages/AdminIndex.jsx |  29 ++++++-
 src/dashboard/pages/Login.jsx      |   2 +-
 src/dashboard/pages/Profile.jsx    |  27 +++++++
 11 files changed, 574 insertions(+), 12 deletions(-)
 create mode 100644 src/dashboard/Featured/Dis.jsx
 create mode 100644 src/dashboard/Featured/Live.jsx
 create mode 100644 src/dashboard/pages/Profile.jsx
PS E:\2nd Sem Programs\NewsHive> git add .
>> git commit -m "Made some updates"
>> git push origin main
>>
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
Everything up-to-date
