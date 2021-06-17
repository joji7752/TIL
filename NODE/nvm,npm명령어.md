# node nvm(노드버전관리) 주요 명령어 
   nvm 버전확인 : nvm -v
   현재 NODE FRAMEWORK 버전 목록 : nvm ls
   특정버전 노드 활성화 :  nvm use 버전명
   특정 버전 노드 설치 : nvm install 버전명
   특정 버전 노드 삭제 : nvm uninstall 버전명

* 주의 : nvm은 윈도우에서 한글 유니코드 지원 안해서 컴퓨터 명이나 계정명등이 한글일 경우 인식을 못해서 설치 안 될 수 있음.

* 설치/삭제가 안될경우 : C:\Users\사용자이름\AppData\Roaming\nvm (보기에서 숨김항목 체크하면 AppData폴더 보임), 경로에서 직접 삭제 후 설치.

# node npm(node pakage manager) 주요 명령어
   npm init (초기 환경 package.json 설치)
   npm install ejs
   npm i moment
   npm i : package.json dependencies에 있는 패키지 설치, i는 isntall 약자
   npm i -g 컴퓨터 전역공간에 설치
   ...

express myfirstproject --view=pug (마지막부분 공백있음 안됨)
view engine = 서버상의 view(html)을 조작하는 기술
express view engine = pug(별도의 html을 만드는 별도 pug문법) / ejs(이미 작성된 html 코드 안에 뷰스크립트 코드로 html 제어), 요즘은 별도의 문법을 사용할 필요 없는 ejs를 자주 씀 

   package.json은 설치된 패키지들의 정보와 버전 관리
   package-lock.json 은 설치된 패키지들 간의 종속성을 나타내는 파일
