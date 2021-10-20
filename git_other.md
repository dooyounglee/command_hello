# 깃허브1`#깃허브1`
## 깃허브1`## 깃허브1`
### 깃허브1`### 깃허브1`
#### 깃허브1`#### 깃허브1`
##### 깃허브1`##### 깃허브1`
###### 깃허브1`###### 깃허브1`

# 깃허브

엔터두번 쳐야 줄바꿈

---
└`---`
---------
└`---------`
- - -
└`- - -`
***
└`***`
***********
└`***********`
* * *
└`* * *`

1. 1번 이라 적음
3. 3번 이라 적음
2. 2번 이라 적음

23. 23번 이라 적음
22. 22번 이라 적음
21. 21번 이라 적음

- 가
- 나
- 다

- 가
  - 가갸
  - 거겨
- 나
  - 나냐
  - 너녀

'+,-,* 구별하지 않고'
+ 가
  - 가갸
  - 거겨
  + 고교
    * 구규
    * 그기
- 나
  - 나냐
  - 너녀

**굵음** __굵음__
*기울임체* _기울임체_
***굵은 기울임체*** ___굵음 기울임체___

> 인용1
>> 인용2

소스 삽입은 `function game(a,b){ return a+b;}` 사이에 쓰면 됌
여러줄 소스 삽입은
```
<script>
function game(a,b){
  return a+b;
}
</script>
```
3개 사이에 쓰면 됌

뾰족괄호 사이 <www.naver.com>
대괄호 사이 클릭하면 소괄호 사이 링크 이동 [이 사이가 보여지고](www.naver.com)
대괄호 사이 클릭하면 소괄호 주소, 부가설명 [이게 보여지고](www.naver.com,"여기가 설명")

맨앞에 느낌표, 대괄호 사이 대체텍스트, 소괄호 사이 이미지 주소 ![이게 대체 텍스트](http://이미지링크.jpg)
현재 repository에 image 업로드 하고 경로를 `./폴더/파일.jpg` 이렇게 적으면 

---
# 블로그 만들기
## 홈페이지 파일이 있을 때
1. 깃허브에 로그인
2. 플러스(+) 누르고 New repository 선택
3. Repository name 필드에 '계정.github.io'라고 입력
4. Initialize this repository with a README 체크
5. Create repository 클릭
6. Upload Files 클릭
7. 파일 올리고 Commit changes 클릭
8. Settings 클릭
9. GitHub Pages 항목에 'Your site is published at https://gostbaducking1.github.io/' 확인
10. https://gostbaducking1.github.io/ 접속


## 홈페이지 파일이 없을 때
1. 검색창에 jekyll을 적고 All GitHub 클릭
2. 검색결과 중 맘에 드는거 클릭(걍 아무 유저가 만들고 이름에 jekyll을 포함해서 쓰는거라 테마가 아닐 수 있음)
3. 보통 demo 사이트가 있을 꺼임. 눌러 보고 맘에 드는거 고름
4. jekyll themes(jekyllthemes.org)이용해도 됌. 다운로드 가능.

### Fork해서 사용 하는 방법
5. jekyll 테마 소스 저장소를 Fork 클릭
6. 내 계정에 복사 됌.
7. Settings
8. Repository name 항목에 '계정.github.io' 입력
9. Rename 클릭
10. 이전에 만든 '계정.github.io'인 repository가 있으면 먼저 삭제
11. '_config.yml' 파일 클릭
12. 수정
13. name, description, footer links의 url부분은 꼭 수정. 주석으로 설명이 있을 꺼임
14. Commit
15. 변경 내용이 GitHub Pages에 적용되려면 몇초~10분여 걸림.

#### 포스트 작성
16. _posts 디렉터리 이동
17. post파일 얘제가 있을 꺼임
18. --- 사이는 모든 포스트에 꼭 들어가야 할 내용
19. `layout:post`는 수정안됌
20. --- 사이 복사
21. _posts로 이동
22. Create new file 클릭
23. 파일이름은 'yyyy-mm-dd-문자열.md'입력
24. 내용 맨 위에 복사한거 붙여넣기
25. title 수정
26. 내용 작성
27. commit new file 클릭
28. 1~2분 기다렸다가 확인
29. 'READ MORE' 누르면 내용 전체 확인

#### 이미지 삽입
30. images 디렉터리 만들기
31. 이미지 업로드 하고 commit
32. 포스트 작성 or 수정
33. `![대체 텍스트](/images/파일이름)`
34. Preview changes에서 확인
35. Commit changes 클릭

