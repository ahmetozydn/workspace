| command                            | explanation                                                                                        |
|------------------------------------|----------------------------------------------------------------------------------------------------|
| git cherry-pick <commit-hash> -m 1 |                                                                                                    |
| git remote -v                      |                                                                                                    |
| git reset --hard                   | localdeki değişiklikleri kaldır.                                                                   |
| git reset --hard 64128185          | HEAD ilgili commit’e ilerler                                                                       |
| git revert 64128185                | commit’e ait değişiklikleri geri al, cherry-pick tersi.                                            |
| git fetch                          | fetches the changes from the remote repository but doesn't merge them into your working directory. |
| git commit --amend                 | convenient way to modify the most recent commit.                                                   |
| local > global > system            |                                                                                                    |
| git push origin —delete feature    | remove remote branch                                                                               |
| git merge --abort                  | cherry-pick abort                                                                                  |
| git log --diff-filter=D --summary  | geçmişteki delete olan dosyaları bul                                                               |
| git reset —hard origin/master      |                                                                                                    |


`git log`

---

- --reverse
- --author="ahmet”
- qa..dev
- -- <file-name>
- shortlog -sn (group by commit count and username)
- —format="%H | %an | %s"
- origin/qa..qa
- -1

`git config`

---

- —list
- user.name
- --local user.email
- --local user.email "name[@gmail.com](mailto:ahmetozaydn944@gmail.com)"
- — global user.name

`git branch`

---

- --merged
- --no-merged
- --no-merged master
- --contains 36a3c72
- -al
- -v