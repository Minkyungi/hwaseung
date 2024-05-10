1. git 로컬 저장소 관리할 관리자 정보 세팅
- 이름 : git config --global user.name'황민경
- 이메일 : git config --global user.email'이메일'
- 브랜치명 변경 : git config --global init.defaultBranch'main'

2. 원하는 작업 폴더를 열어서
- 로컬 저장소 세팅: git init
- 저장소에 추가: git add .
- 버전에 설명(라벨링) : git commit -m"남겨놓고 싶은 말"
- 현재 상태 확인 : git status 
- 로그 확인 : git log
- 원격 저장소 세팅 : github.com


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
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 (이걸로 해)
- 토큰을 컴퓨터에 저장
::자격 증명 관리자 열기
::일반 자격 증명 추가

- 원격 저장소 생성 : create repository
- 원격 저장소 연결 : git remote add origin 원격저장소 주소
- 확인 : git remote
- 원격 저장소에 업로드 : push
:: git push -u origin main


* Vscode 탐색기에 표시되는 git 정보
- U : Untracked : 새로 추가되거나 수정된 것들인데 아직 git에 추가 되지 않은 상태
- A : Added : 관리가 되게끔 저장소에 추가됨
- M : Modified : 수정된 것들
 
* 반복적으로 해야 할 작업
gid add .
git commit -m '남겨놓을 메시지'
git push -u origin main


* 집에서 git 설치하고 관리자 정보를 입력한 후
* (1회만) 원격 저장소 복제 : github.com 저장소로 이동 후 초록색 code 버튼을 클릭해서 저장소 주소 복사
원하는 곳에서 마우스 오른쪽 클릭 후 git bash 실행
- git clone 저장소 주소

* 집에서 추가 작업 진행 후 
- github.com에 업데이트
gid add .
git commit -m '남겨놓을 메시지'
git push -u origin main

* 학원에서 github.com의 최신 정보를 받아오자 : pull
git pull
