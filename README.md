# git 사용법
## README 작성법
### 마크 다운 문법
1. '#' :  제목
2. '##' : 부제목
3. '###' : 소제목
4. 번호가 없는 리스트 : '* 목록','- 다른 목록', '+ 다른목록'
5. 번호가 있는 리스트  : '1 첫번째'
6. 기울임꼴 : '*텍스트* or _텍스트_ : ' *텍스트* or _텍스트_
7. 굵은 글씨 : '**텍스트** OR  __텍스트__ : '**텍스트** OR  __텍스트__
8. '> 텍스트' : 인용
9. 코드추가 : 띄어쓰기 4개(tab)
10. 폴더 구조 작성 <br>
+-- _config.yml
+-- _drafts
|   +-- begin-with-the-crazy-ideas.textile
|   +-- on-simplicity-in-technology.markdown
+-- _includes
|   +-- footer.html
|   +-- header.html
+-- _layouts
|   +-- default.html
|   +-- post.html
+-- _posts
|   +-- 2007-10-29-why-every-programmer-should-play-nethack.textile
|   +-- 2009-04-26-barcamp-boston-4-roundup.textile
+-- _data
|   +-- members.yml
+-- _site
+-- index.html
- 참고 url <br>
 [링크] [https://happybono.wordpress.com/2018/01/03/tip-markdown-%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-readme-%EB%AC%B8%EC%84%9C-%EC%9E%91%EC%84%B1%EB%B2%95/]

### 필수 정보
1. 프로젝트 명
2. 프로젝트 정보

## git 문법
### 자주쓰는 문법
1. 원격 연결 <br>
 > git remote add origin 깃허브 주소  

### 헷갈리는 문법
1. git rebase i HEAD~3
커밋 목록 합치기  
> error: invalid line 1: S BBE5056 remove will commit
  error: cannot 'squash' without a previous commit
  You can fix this with 'git rebase --edit-todo' and then run 'git rebase --continue'.
  Or you can abort the rebase with 'git rebase --abort'.  

HEAD~3 : 해드 기준 3번째 전 커밋 까지 불러오는것 인데 커밋목록중 첫번째 커밋도 squash 하니 에로 발생