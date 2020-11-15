Git Repository Test
# 현재 저장소의 사용자 이름과 이메일을 등록한다. (없으면 commit 이 안됨)
```
git config --global user.name "Youngju Lee"
git config --global user.email "posforyou@chollian.net"
git config --list
```
```
git init
```
# commit 하기 위해 staging 한다
```
git add .
```
# git commit -m "<메시지>"
```
git commit -m "first commit"
git log
git status
git branch
```
# 새로운 branch <name> 을 만든다
```
git branch <name>
```
# branch <name> 으로 이동한다
```
git checkout <name>
```
# 새로운 branch <name> 을 만들고 이동한다
```
git checkout -b <name>
git branch -M posforyou
```
# git remote add origin (remote repository github URL)
# origin 은 remote repository 의 이름이며, 다른 이름으로 설정해도 무방합니다.
```
git remote add origin https://github.com/posforyou/git-helloworld.git
```
# origin 이라는 원격 저장소의 posforyou Branch 에 Push 합니다.
```
git push -u origin posforyou
git push --set-upstream origin posforyou
```
