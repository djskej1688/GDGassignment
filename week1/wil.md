오늘은 github 와 git, VScode, Vercel을 설치/회원가입 하고 웹사이트를 배포하는 법을 배웠습니다. 
컴퓨터 바탕화면에 새 폴더 하나를 만들어 git 의 repository 와 연동합니다.
그 후 VScode 로 이 폴더의 index.html 파일을 열어 웹사이트에 들어갈 기본적인 정보를 입력하였습니다.
입력은 html 형식으로 진행하였습니다.
먼제, <body><\body> 사이에 들어갈 내용을 입력합니다.
제목의 경우 <h><\h> 를 써놓고 그 사이에 입력을 하면 됩니다.
세부 내용은 <p><\p> 사이에 입력하면 됩니다.
각각 h = heading , p = paragraph 입니다.
입력이 완료되었다면 git bash 를 엽니다.
cd Desktop/파일명 을 입력하여 접근한 후, 
git status
git add <file> 혹은 git add . 
git commit -m "<message>"
git push 
순으로 진행하여 깃허브에 업로드 하면 됩니다.

참고로, 이미지를 추가하고 싶다면, 
index.html 이 있는 위치에 이미지를 저장할 폴더를 생성한 후 업로드할 이미지를 넣어줍니다.
그 후 <body><\body> 사이에 <img src="img/1.jpg"> 를 입력하면 됩니다.
저 같은 경우, 사진을 여러장 올렸는데 사이즈가 달라 코드를 덧붙였습니다. 

<img src="img/1.jpg" alt="내 사진" class="profile">
<img src="img/2.jpg" alt="내 사진" class="profile">
<img src="img/3.jpg" alt="내 사진" class="profile">

<style>
    .profile{
        width: 200px;
    }
</style>

라고 하였는데, 지피티의 도움을 받았습니다.

마지막으로, Vercel 에 들어가 깃허브의 레포지토리를 import 한 후  Deploy 하면 웹사이트가 배포됩니다.
감사합니다.
