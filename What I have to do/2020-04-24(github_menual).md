### 기본적인 명령어

#

```
git init
git add . 
git commit -m "올린 파일 주제"
```
* 가입한거 기준 (컴퓨터에서 한번만 쳐주면 나머지떄는 생략 가능)
```
git config --global user.name "NickName"
git config --global user.name "Email"
```
* 내가 올릴 위치에 대한 주소 (일반적으로 github.com/닉네임/레파지토리주소 의 형태를 띄고 있음)
```
git remote add origin 레파지토리 주소
```
* 파일 올리기
```
git push -u origin master
```

