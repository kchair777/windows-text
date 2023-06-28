# NodeJS 
1. nvm-setup(windows)설치후 버전확인 nvm --version 1.11.11
   1.  nvm ls 실행후 리스트확인 18.16.1 짝수는안정적버전,
   1.  nvm use 12.14.1 실행시 사용버전로딩
   1.  nvm install 12.14.7 추가버전 인스톨시
   1.  nvm uninstall 12.14.5 삭제시 
1. NodeJs시
   1.  node --version   v18.16.1
   1.  node use 18.16.0 다른버전사용시 
   1.  모듈설치 lodash, GSAP & Scroll, Swipper, ScrolMagic
1. Project 화일 생성후 
   1. npm inin -y  후 package.json화일생성됨 
   1. npm install parcel-bundler -D 후 node_modules, package-lock.json생성됨
   1. npm install lodash 생성됨  "dependencies": {
    "lodash": "^4.17.21" }
   1. node_modules 삭제 재설치 npm i , npm install 
   1. index.html생성후 script main.js연결, h1 입력후 
   1. parcel index.html실행 후 
   1. package.json에scripts "dev": "parcel index.html"수정 
   1. npm run dev 실행  build in 568ms
   1. 검사기능에서 main.js작성한 console.log 내용이 출력됨 
   1. import _ from 'lodash';로 패켓연결
   1. "build":"parcel build index.html" 추가 scripts { 에 }
   1. npm run build 실행하면 사용자 보는용도로 전환됨. 
      1. dist\main.b63...js.map 
      1. dist\main.b53..js
      1. dist\index.html 추가로 .cache , dist화일생성됨 

1.  git version관리
    1. .gitignore화일추가 
    1. git init 시작 U 표시됨 버전할것만 U 표시 
    1. git status 변경사항이 추적되지않는 내용이 빨강색으로 
    1. git add . 버전추적시작하면 
    1. git status
    1. git commit -m '프로젝트 버전관리'
    1. git log 확인시 (HEAD-> master) 프로젝트 생성 
    1.github열어서 repositories 생성후  주소카
    1. git remote add origin https://github.com/kchair777/windows-text.git 원격저장소 연결 
    1. git push origin master [new branch](master -> master)
    1.git log시 변경된 내용  (HEAD->master, origin/master)
