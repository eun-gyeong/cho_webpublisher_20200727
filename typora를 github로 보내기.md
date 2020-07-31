# typora를 github로 보내기

Administrator@G501-06 MINGW64 /c/work
$ pwd
/c/work

Administrator@G501-06 MINGW64 /c/work
$ git clone https://github.com/eun-gyeong/cho_webpublisher_20200727.git
Cloning into 'cho_webpublisher_20200727'...
warning: You appear to have cloned an empty repository.

Administrator@G501-06 MINGW64 /c/work
$ cd cho_webpublisher_20200727

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ touch README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ cat README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ cat README.md
# 웹퍼블리셔과정

# 2020.07.27~2020.12.18




Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git config username
error: key does not contain a section: username

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git config --global user.name "eun_gyeong"

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git config --global user.email "dmsrud2420@gmail.com"

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git config user.name
eun_gyeong

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git config user.email
dmsrud2420@gmail.com

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git add README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git commit -m "생성을위한첫파일"
[master (root-commit) 99737c3] ?앹꽦?꾩쐞?쒖껀?뚯씪
 1 file changed, 6 insertions(+)
 create mode 100644 README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 288 bytes | 288.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/eun-gyeong/cho_webpublisher_20200727.git
 * [new branch]      master -> master

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git push
Everything up-to-date

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git add README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git commit -m "생성을위한첫파일2"
[master 72a887d] ?앹꽦?꾩쐞?쒖껀?뚯씪2
 1 file changed, 33 insertions(+), 6 deletions(-)
 rewrite README.md (92%)

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 705 bytes | 705.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/eun-gyeong/cho_webpublisher_20200727.git
   99737c3..72a887d  master -> master

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git add README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$  git add README.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$  git commit -m "git userble_01"
[master 0599dc9] git userble_01
 1 file changed, 4 insertions(+)

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/eun-gyeong/cho_webpublisher_20200727.git
   72a887d..0599dc9  master -> master

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ cat README.md
# 웹퍼블리셔과정20200727~20201218

# git 계정 생성하기



1. github 가입

2. new repository 생성

3. git 자료를 복제

   1. 내 컴퓨터에서 git clone 생성한 repository

4. README.md 파일을 생성 및 내용 작성

5. 계정을 연결

   1. 자료를 올리는 사람의 이름과 이메일주소
   2.
   3. 계정 id/pw

6. github로 push처리하여 보내기

7. github의 자료를 pull 처리하여 가져오기

   ---

   # 택배보내는순서

   1. 물건을 포장한다
   2. 상자에 담는다
   3. 우체국에 간다
   4. 송장을 작성한다 (주소, 이름, 연락처, 우편번호, 물건의 내용)
   5. 돈내고 보낸다


Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ touch eun_gyeong

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ rm -f eun_gyeong

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ touch eun_gyeong.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git add eun_gyeong.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   eun_gyeong.md


Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git commit "eun_gyeong"
error: pathspec 'eun_gyeong' did not match any file(s) known to git

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git commit "eun"
error: pathspec 'eun' did not match any file(s) known to git

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git commit "eun_gyeong.md"
hint: Waiting for your editor to close the file...       1 [sig] bash 2048! sigpacket::process: Suppressing signal 18 to win32 process (pid 3976)
1603276 [sig] bash 2048! sigpacket::process: Suppressing signal 18 to win32 process (pid 3976)
Aborting commit due to empty commit message.

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git commit -m "eun_gyeong.md"
[master 77f3c13] eun_gyeong.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 eun_gyeong.md

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 276 bytes | 276.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/eun-gyeong/cho_webpublisher_20200727.git
   0599dc9..77f3c13  master -> master

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Administrator@G501-06 MINGW64 /c/work/cho_webpublisher_20200727 (master)
$