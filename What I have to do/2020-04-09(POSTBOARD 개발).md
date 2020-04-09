# POSTBOARD 개발

* 폴더 구성 ([postboard](https://github.com/taehyundev/postboard_web_page))

```
.
├─models
├─public
│  ├─css
│  └─image
├─router
│  ├─board
│  ├─join
│  ├─login
│  ├─logout
│  ├─main
│  └─myhome
└─views
```



* models(db 연결 분리)



* public (정적인 파일이 위치한곳)
  * css
  * image



* router (app.js 에서 get 이나 post 요청을 받으면 router 에서 처리를 해줌)

  * board (게시물에 관련한 페이지 라우팅)

  * join (가입페이지 라우팅)

  * login (로그인페이지 라우팅)

  * logout (로그아웃페이지 라우팅)

  * main (메인페이지 라우팅)

  * myhome (마이페이지 라우팅)

    

* views (ejs 파일이 위치하고 get요청을 통해서 받아온 값을 보여준다.)
  * 실질적으로 보여지는 내용을 담은 파일이 있음



