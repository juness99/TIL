# SSAFY-2019-01-02

## 목차

### 1.깃에 추가하기

```
student@DESKTOP MINGW64 ~
$ cd TIL-junwon

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git add .

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git commit -m "D01| 190102 | startcamp"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git commit -m "D01 | 190102 | startcamp"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
        deleted:    python/J STUDY 2018.12.21.md

Untracked files:
        startcamp/

no changes added to commit

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ ^C

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ ^C

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git commit -m "D01 | 190102 | startcamp"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
        deleted:    python/J STUDY 2018.12.21.md

Untracked files:
        python/2018.12.27.md
        startcamp/

no changes added to commit

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git add .

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git commit -m "D01 | 190102 | startcamp"
[master ed20a60] D01 | 190102 | startcamp
 3 files changed, 395 insertions(+), 145 deletions(-)
 create mode 100644 python/2018.12.27.md
 delete mode 100644 python/J STUDY 2018.12.21.md
 create mode 100644 startcamp/SSAFY-DAY1.md

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git push
To https://github.com/juness99/TIL.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/juness99/TIL.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

student@DESKTOP MINGW64 ~/TIL-junwon (master)
$ git pull\
>

```

깃허브에 create 사용 하지말것 로컬 충돌 일어날수있음

만약 오류난다면 git pull 명령어를 쓰면됨 



### 2.깃허브 ignore 설정

### 깃허브에 올릴때 쓸데없는 파일을 못올리게 설정하기

1.python gitignore 들어가기

[gitignore/Python.gitignore at master · github/gitignore · GitHub](https://github.com/github/gitignore/blob/master/Python.gitignore)

2.내용전체 복사한뒤 git bash에 touch .gitignore쓴다

![1546389914926](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1546389914926.png)

3.그후에 code . 을 치면 커맨드창이 열린다. (ls -a 를 치면 폴더가생성됬는지 확인가능하다.)

![1546389938062](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1546389938062.png)

![1546389954410](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1546389954410.png)

4.gitignore에 내용 복사후 저장

5.이후에 git bash에 커밋해준다.

![1546390096340](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1546390096340.png)

6.그리고 git push를 해준다.

![1546390133994](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1546390133994.png)