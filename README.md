remote repository of git_tutorial

git config --list :git config 확인
git config --global user.name "사용자이름"
git config --global user.email "이메일"
git config --unset user.name
git config --unset user.email
git config --unset --global user.name
git config --unset --global user.email

cd /d       :d드라이브 이동
mkdir folder
cd folder
git init
git status  :저장소 상태 확인
파일 생성
git add 파일명
git commit
git commit -m "커밋 메시지"

git branch :branch확인
git branch 브랜치이름 :branch만들기
git checkout 브랜치이름 :branch이동
git checkout -b 브랜치이름 :branch만들고 checkout
git commit -a :변경된 파일 모두 commit

(다른 branch에서 파일 수정)
git checkout master
git merge 브랜치이름 :현재 작업중인 브랜치에 브랜치이름을 가져와 병합
