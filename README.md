git init : 깃에 올라갈 후보
git add : 깃에 올라가기 위해 대기
git commit : 깃에 올라감

git bash에서
폴더 이동 : cd
git init : 나 여기를 깃폴더로 쓸거야 선언
확인 : ls -al (숨겨진 .git 확인)

$ git config --global user.name "Yerim lee"
$ git config --global user.email yelim527@naver.com

vsd 에서 git 연동 폴더 열어서 파일 2개 만들기
git에 추가
>> git 확인 : ls

$ git add README.md(추가할 파일)
$ git commit -m "프로젝트 설명파일 추가" > 커밋메세지
$ git log


git clone 주소 : clone

git push origin master : push
git pull origin master : pull

git에서의 커밋이란??
변경사항모음이 아닌 하나의 최종 코드 모음
다만, 기존의 커밋과 비교해서 변경된 파일이 아니면 변경되지 않았다고만 저장 >> 용량이 무겁지 않음 ! 

git
untracked : 추적 안됨
tracked : 수정없음 수정함 스테이지됨

평행세계 만들기 - branch
디폴트 브랜치 : master
git branch cat -- 새 브랜치를 현재 시점에 만들거야! (master가 있는 시점)
git chechout cat --cat 브랜치로 이동해라 ! (master에 있던 head가 cat으로 옮겨짐)

코딩 깃 공부 조아용


