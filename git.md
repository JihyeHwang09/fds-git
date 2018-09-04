


Windows에서는 /c밑에 gitbash가 존재.
cmd에서는 backslash(\)로 나타냄.

## 상대 경로 VS 절대 경로
현재 있는 위치와 가까운 경로로 가려고 할 때 -> 상대 경로
먼 경로로 이동하려고 할 때 -> 절대 경로 

ls -a 숨김파일까지 표시(all)
ls -l 부가정보들을 표시
ls -al 숨김파일 표시하면서& 부가정보들까지 표시하고 싶다. 
-> 이 의미가 중요한 게 X
명령어 -
오타나면 Ctrl+c-> 로 지울 수 있음


에러메시지를 꼭 해석해야 함. (첫번째 문장이라도)


어떤 폴더에 있더라도 cd만 치면 홈디렉터리로 이동

cp 복사할 파일 이름     복사해서 저장할 파일 이름
cp ./hello ~/hello

파일 이름 변경할 때도 mv를 사용함
mv 파일을 바꿀 파일명 새로 바꿔줄 파일명

mv, rm은 자주 사용하는 편(정말 조심히 써야함)
rm -rf  특히 자주 씀. 리커시브?? 그 밑에 있는 거까지 다 지우겠다. 강제로.
(뜻까지 외울 필요는 없음)(rm -rf 검색해보기)
	ex) rm -rf fds

nano는 기억해두기!(텍스트편집기 같은 거임)
nano 파일명.확장자명


vim- 명령모드, 편집모드 2가지가 있음.
간혹 쓸 일이 있음. 

개발용 프로그램을 켜고, 삭제하고 등등을 터미널을 이용해서 많이 할 것임. 


오늘 배운 것 중에 rm -rf가 가장 중요함. 

실무에서는 WebStorm을 많이 씀 (프론트엔드 개발자를 위한 통합 개발 환경)




code . 현재 폴더를 여는 명령
ctrl + , Visual Code Studio 설정창
html 파일을 연 후에 하단에 있는 Go Live를 누름. (새로고침할 필요 X. 수정사항 반영됨)
MarkDown: ‘.md’ 

*이탤릭체*
**볼드체**
_밑줄_
~~취소선~~
`고정폭`
> 인용문


코드를 마크다운 문서 안에 넣을 때는 백틱(``)로 감싸서 넣을 것
고정폭을 지원하는 사이트 

git add . 현재 폴더에 있는 파일 전부 다 스테이징 영역에  올리겠다. 
git log 어떤 commit들이 이루어졌는지(커밋을 누가, 언제했는지, 일련번호가 나옴)
가장 중요한 건 staging area:

git은 파일만 관리함. 폴더는 관리하지 X.  -> 빈폴더를 올리면 아무 변화 X. 
삭제라는 변경사항도 스테이징 영역에 올려야함. 
git checkout  일련번호:  일련번호에 해당하는 변경사항으로 돌아가기 가능함. 
git remote add origin(별명) https://github.com/JihyeHwang09/fds-git.git(주소)


## commit VS push 
commit은 내 로컬 저장소에만 저장되는 것임.
push는 이제까지 한 commit을 원격저장소에 저장하는 것임. (로컬 저장소의 변경사항 -> 원격 저장소)

## pull
pull (원격 저장소의 변경사항 -> 로컬 저장소)로 당겨오는 것


## Visual Studio Code에서 git 사용하기  
Visual Studio Code에서도 git 사용할 수 있음.
ctrl+shift+p -> push 누르면 push 가능 (pull은 없음)
git은 처음에는 command line을 이용하는게 좋음. (개념 잡기에 좋음)(명령어에 뜻이 담겨있으므로)

Visual Studio Code 내장 기능에서는 git의 모든 기능을 사용할 수 X. 단순한 기능만 들어있음.

## SSH 에러
Sourcetree에서 
SSH에러가 날 경우, 
도구 -> 옵션 -> SSH 클라이언트 설정 -> SSH 클라이언트: OpenSSH로 설정

## git에 올리지 않고 싶은 파일이 있을 때
git ignore 키워드로 검색

## Pull Request
: 협업할 때 많이 사용. 사용자가 소유자의 허락을 받아야만 push를 할 수 있는 절차. 


