


======================================== to add all files to the repository
git add .
======================================== to add a file: "assets/babel.js" to the repository
git add "assets/babel.js"
======================================== show all files in repository
git status
======================================== send sync data to git (LOCAL)
git commit -m "first commit react test"
======================================== after editting to sync with git (LOCAL)
git add .
git commit -m "test2"
======================================== to return to a commit
git log

-------
PS D:\WEB-IT\05 Learning-Drills\React\tests\test-react18-git> git log
commit a7205a7ab2901d0f2587f3f33d878956847b5224 (HEAD -> master)
Author: musaMosafer <ardalan2002@gmail.com>
Date:   Sun Sep 22 15:47:15 2024 +0330

    test2

commit ab39659273d4118dc34291100bde1bee9e02b1a5
Author: musaMosafer <ardalan2002@gmail.com>
Date:   Sun Sep 22 14:55:30 2024 +0330

    first commit react test
PS D:\WEB-IT\05 Learning-Drills\React\tests\test-react18-git> 
-------

git reset ab39659273d4118dc34291100bde1bee9e02b1a5
======================================== add local git to github
--- create a repository in github "my-first-repository"
--- …or push an existing repository from the command line
git remote add origin https://github.com/musaMosafer/my-first-repository.git
git push -u origin master







