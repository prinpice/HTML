# WEB1 - HTML & Internet

1. 수업소개
   
   - 상상력, 공감력 필요
   
2. 프로젝트의 동기

   - 생활코딩을 시작할 당시의 제작자 이야기
   
3. 기획

   - 무엇인가 만들기 위한 사전준비(=기획)
     - 미리 상상하기
     - 계획해보기
   - 기획자가 되어 웹사이트 기획하기
     1. 제일 위쪽에 수업의 전체 제목 작성
     2. 왼쪽에는 수업의 목차 작성
        - 목차에 링크 걸어 링크에 해당하는 콘텐츠가 오른쪽에 표시됨
     3. 오른쪽 상단에 제목 표시
     4. 본문에는제목에 대한 자세한 설명 표시
   
4. 코딩과 HTML

   - 코딩 : 원인인 코드를 통해서 결과를 만듬

   - 사람이 하는 일과 기계가 하는 일을 비교해보기
     - 사람이 하는 일(원인을 부름) : Code, Source, Language
     - 기계가 하는 일(결과를 부름) : Application, App, Program, Webpage(웹에서 결과), Website(웹페이지가 모여있음)
   - HTML(HyperText Markup Language)
     - 웹 페이지를 만드는 코드(언어)
     - 가장 쉬운 언어
     - 중요한 언어
     - Public Domain(저작권 X)
   
5. HTML 코딩 실습 환경 준비

   1. 웹브라우저
   2. 에디터(Editor) : 컴퓨터와 사람이 모두 이해할 수 있도록 컴퓨터 언어 코드 작성 프로그램
      - 윈도우 - 메모장
      - 맥 - 텍스트 편집기
      - 리눅스 - gedit, nano, vim
      - github - atom : 코드를 작성하는 전문적 도구
   3. atom 사용하기
      1. 파일 생성
         - 메뉴 ->  File -> Add project folder
         - 확장자. html
      2. 웹 브라우저로 웹페이지 열어보기
         - 윈도우 : Ctrl + O
         - 맥 : Cmd + O
      3. 에디터 화면에 작성하기
         -  'hello web' 입력 후 저장(윈도우 : Ctrl + s, 맥 : Cmd + s)
      4. 웹브라우저 리로드하기
         - 웹페이지 화면에서 에디터에 작성된 내용 출력됨
   
6. 기본문법 - 태그
   - \<\> : 열린 태그 , \</\> : 닫힌 태그
   - 웹을 지배하는 중요한 문법
   - \<strong\>태그\<strong\>\</strong\>
     - 강조하고 싶은 부분의 글자를 진하게 작성하기
   - \<u\> 태그\<u\>\</u\>
     - 밑줄을 작성하여 강조하기
   
7. 혁명적인 변화
   - 처음에 배우는 것(태그)
     - 가장 쉽지만 가장 중요함
     - 가장 자주 사용하는 결합
   - 20년 전에는 궁금한 것을 알기 위해 시간과 돈이 많이 들었지만 지금은 1분안에 찾을 수 있음
   - 기초만 알아도 많은것을 할 수 있는 시대
   - 웹페이지의 오른쪽 클릭 -> 페이지 소스보기 를 통해 웹페이지 소스보기 가능
   - \<h1\> 태그\<h1\>\</h1\>
     - HTML headings(h1 ~ h6)
     - 가장 큰 제목 태그
     - 글자가 두꺼워짐
     - h 뒤에 붙는 숫자가 커질수록 글씨가 작아짐
   
8. 통계에 기반한 학습
   - 150이상의 태그가 존재
   - https://www.advancedwebranking.com/html
     - 중요한 통계를 기반으로 정리한 사이트
     - 전세계의 웹페이지 들이 몇개의 태그로 이루어져 있는지 통계로 보여줌
     - 웹페이지에서 사용되는 태그의 rank를 보여줌
     - 25개정도의 태그로 이루어져있는 웹페이지가 가장 많음
   
9. 줄바꿈 : br vs p
   - 검색창에 html new line tag 검색하기
   - \<br\>태그 : 줄바꿈\<br\>
     - 원하는 만큼의 여백을 만들 수 있음
   - 검색창에 html paragraph tag 검색하기
   - \<p\>태그 : 단락구분태그 \<p\>\</p\>
     - 정해져 있는 여백만큼 떨어짐
   - 참고 css
     - 태그안에 style속성 적용
     - \<p style="margin-top:40px;"\>\</p\>
       - <\p\>태그 위의 여백을 40px로 지정
   
10. HTML이 중요한 이유
    - 일반인과 지식인이 작성한 내용에 대한 코드가 다름
    - 오늘날 정보의 세계에서 검색엔진의 검색결과에서 노출되는 것이 중요
    - 웹
      - 핵심적인 철학은 접근성(accessibility)
      - 모든 운영체제에서 동작
      - 웹페이지의 소스코드는 누구나 볼 수 있음
      - 저작권이 없는 순수한 공공재
    - 웹페이지를 꾸미기 위해 이미지로 만들면 시각 장애가 있는 분들에게 암흑과도 같은 상태가 됨
      - HTML로 만드는 경우 스크린리더(screen reader)와 같은 프로그램을 이용해서 정보를 청각화해서 접하게 됨
    
11. 최후의 문법 속성(attribute) & img
    - \<img\>태그\<img\>
      - 이미지를 넣는 태그
      - 속성
        - 위치는 상관없음
        - src="" 따옴표 안에 넣을 이미지의 주소 삽입
        - width="100%" 이미지의 width를  페이지 크기에 맞게 사이즈 변경
      - cf) unsplash.com : 저작권에 구애받지 않고 사용가능한 이미지 사이트
    
12. 부모 자식과 목록
    - 부모태그 : 포함하고 있는 태그
    - 자식태그 : 포함된 태그
    - 목차
      - \<li\>태그 \<li\>\</li\>
        - 순서없는 목록형태로 구성됨
      - \<ul\>태그\<ul\>\</ul\>
        - \<li\>태그의 부모 태그
        - \<ul\>태그 안의 내용을 한 목록으로 구성하여 구분시켜줌
      - \<ol\>태그\<ol\>\</ol\>
        - \<li\>태그의 부모 태그
        - 순서있는(넘버링) 목록형태로 구성됨
    - 표
      - \<td\>태그\<td\>\</td\>
        - 표의 열을 구성함
      - \<tr\>태그\<tr\>\</tr\>
        - \<td\>의 부모 태그
        - 표의 행을 구성함
      - \<table\>태그\<table\>\</table\>
        - \<tr\>의 부모 태그
        - 표의 전체 틀을 구성함
    - cf) window - ctrl/mac-cmd를 누르고 원하는 줄을 클릭하면 여러줄을 한번에 작성 가능
    
13. 문서의 구조와 슈퍼스타들
    - \<title\>태그\<title\>\</title\>
      - 웹페이지의 (본문의) 제목
      - 웹페이지의 제목을 사용자에게 명시적으로 알려줌
      - 검색엔진에서 책표지와 같은 정보로 사용함
    - \<meta\>태그
      - 본문이 저장된 형식
      - 한글을 UTF-8로 저장하기 때문에 웹페이지를 열 때도 UTF-8로 열어야 함
        - \<meta charset="utf-8"\>
          - utf-8로 문서를 읽어라
    - \<body\>태그\<body\>\</body\>
      - 본문을 구성하는 태그
    - \<head\>태그\<head\>\</head\>
      - body(본문)를 설명하는 태그
    - \<html\>태그\<html\>\</html\>
      - 문서의 전체를 감싸는 최고위층 태그
    - \<!doctype html\>
      - 관용적으로 작성
      - 이 문서가 html이라는 것을 명시
      - \<html\>태그 위에/문서 맨 처음에 작성
    
14. HTML 태그의 제왕
    - \<a\>태그\<a\>\</a\>
      - anchor의 첫글자 사용
      - 링크를 거는 태그
      - 속성(attribute)
        - href="" 따옴표 안에 링크주소를 삽입함
        - target="_blank" 새 탭을 열기
        - title="" 링크가 클릭전에 무엇인지 알려주고싶을때 알려주고자하는 내용을 따옴표 안에 작성함
    - cf) html specification
      - html을 만드는 w3c에서 만든 공식사용설명서
    
15. 웹사이트 완성

    - 링크를 걸어 해당 링크 페이지로 넘거가도록 만듬

16. 원시웹

    - Internet vs Web
      - Internet : 도시, 도로, 운영체제
      - Web : 도시 위의 건물 하나, 도로위의 자동차 하나, 운영체제 위의 프로그램 하나
    - 역사적 사건
      - 1960년 Internet 등장
        - 당시 중앙집중통신시스템이었음
        - 핵공격에도 견딜 수 있는 강인한 통신 시스템의 필요성에 의해 탄생
      - 30년동안 Internet 확산됨, 그러나 사람들은 인터넷이 세상에 있다는 것을 잘 모름. 당시 기관들에서 사용했음
      - 1990년 Web 등장
        - Swiss에서 탄생
        - 제네바유럽입자물리연구소(CERN)에 Internet이 들어옴
        - 팀 버너스리가 80년도부터 10년동안 했던 과제(Web에 전신이 됨)에 Internet을 합성함
        - 1990년 10월 웹페이지 만드는 편집기 만듬
        - 1990년 11월 World Wide Web 프로그램 만듬
        - 1990년 12월 웹서버 프로그램 만들고 info.cern.ch 주소를 부여함(primitive web)
        - Web과 Internet은 폭발성장함

17. 인터넷을 여는 열쇠 : 서버와 클라이언트

    - 인터넷을 하기 위해 두 대의 컴퓨터가 필요함

      - Internet으로 연결되어 있음

        C1 : 설치된 프로그램-Web Browser

        C2 : 설치된 프로그램-Web Server, 주소-http://info.cern.ch, 하드디스크의 한 디렉토리에 index.html이 저장되어 있음

      - C1에서 http://info.cern.ch/index.html입력하면 Internet을 통해 C2에 전기적 신호를 보냄(request)

      - C2 에서 설치된 Web Server 프로그램이 index.html파일을 찾아서 전기적 신호로 변환하여 C1에 보냄(response)

      - 역할에 따라 이름부여 : C1-client, C2-server

18. 웹호스팅(github pages)

    - web hosting 업체 : 웹 서버 운영을 대신 해주는 회사
    - github
      - web hosting 업체 중 하나
      - 프로그래머들의 성지
      - 홈페이지를 운영할 수 있는 web server를 무료로 제공함
      - 웹서버로 사용하기 위한 설정 
        - repository : settings -> GitHub Pages  -> Source : master branch
      - static web hosting
        - html만으로 구성된 서버
    - 검색창에 (free) (static)web hosting 입력하여 검색
    - ex) https://www.bitballoon.com/, http://neocities.org/, Amazon S3, Google Cloud Storage, Azure Blob
    
19. 웹서버 운영하기

    - 내 컴퓨터에 웹서버 설치
    - 웹 서버 제품 : Apache(오픈소스, 무료), IIs, Nginx 등등
      - 검색창에 how to install apache http server 운영체제 검색하여 설치방법 보기

20. 웹서버 운영 : 윈도우

    - 윈도우에 웹서버 설치
      - 검색창에 bitnami wamp stack 검색하여 홈페이지 들어가기
      - Local INSTALL의 최신버전 다운로드
      - 설치 중에 비밀번호 설정시 반드시 기억해야 함
      - 설치 완료 후 Go to application버튼 클릭
      - bitnami를 설치한 디렉토리 안에 manager-windows 프로그램을 실행시키면 manager 프로그램(web server의 on/off 제어) 켜짐 - 초록색인경우 켜져있음 
    - 웹서버와 http
      - http://127.0.0.1/index.html : local host와 같은 화면 나옴
        - 127.0.0.1 : 특정 컴퓨터 IP주소(Internet Protocol Address)
      - html 파일 위치 : bitnami directory -> wampstack -> htdocs(웹페이지가 저장된 곳)
      - file://
        - 파일에 있는 것을 직접 여는 것으로 Web Server가 관여하지 않음
      - http://
        - Hyper(Web page) Text Transfer(통신) Protocol(규약)
        - Web Browser와 Web Server가 서로 통신할 때 사용하는 통신 규약을 이용하여 데이터를 가져옴
        - Web Browser와 Web Server가 서로다른 컴퓨터에 있을 때 반드시 이를 통해 통신해야 함
    - 웹브라우저와 웹서버의 통신
      - Web Browser가 Web Server에 요청을 할 때 Web Server의 IP Address가 필요함
      - 컴퓨터가 2대 필요함
        - 스마트폰을 Web Browser로 사용할 수 있음
      - 화면 오른쪽 하단의 Window바에서 컴퓨터모양/와이파이모양 우클릭 -> Open Network and Sharing Center/네트워크 및 인터넷 설정 열기 -> Ethernet/Wifi -> Details.. -> IPv4 Address확인(현재 컴퓨터의 IP주소)
        - 127.0.0.1 : 현재 사용하고있는 컴퓨터( 자기 자신)(약속)
      - 두 대의 컴퓨터가 연결되기 위해서는 같은 네트워크에 접속되어 있어야 함 => 다른 네트워크에서는 접속 불가능

21. 웹서버 운영하기 : 맥

    - Apache가 기본적으로 깔려있음(이 강의에서는 사용X)
    - 맥에 웹서버 설치하기
      - 검색엔진에 bitnami mamp stack 검색하기
      - MAMP : Mac Apache MySQL PHP -> 3개의 프로그램이 동시에 설치됨
      - LOCAL INSTALL 에서 최신버전 다운로드 -> 더블클릭 설치 -> 체크박스 해제 후 설치
      - 설치 중에 비밀번호 설정시 반드시 기억해야함 
      - Management Console
        - 설치 완료 후 실행되는 프로그램
        - Apache Web Server를 관리하는 프로그램
        - Spotlight Search에서 manager-osx검색 또는 Application폴더에서 mampstack-x.x.x-> manager-osx를 클릭하여 프로그램 실행
    - 웹서버와 http
      - Application(응용프로그램) 폴더 -> mampstack directory -> apache2 directory -> htdocs(웹페이지가 저장된 곳)
      - http://127.0.0.1:8080/index.html
        - 8080
          - PORT
          - Mac에는 Web Server가 이미 깔려있음
          - Web Server가 2개 이상일 경우 구별하기 위해 나중에 설치된 Web Server에 PORT를 부여함
    - 웹브라우저와 웹서버의 통신
      - cmd + o : 웹페이지 열기
      - System Preference(제어판) -> Network -> 고급 -> TCPIP -> IPv4 address : 해당 컴퓨터의 IP주소
      - 통신을 하려는 두 대의 컴퓨터가 동일 네트워크에 접속하고 있어야 함

22. 웹서버 운영 : 리눅스

    - 검색엔진에 apache install ubuntu 검색
    - console에서 $ sudo apt-get update
      - sudo : 관리자 권한으로 실행
      - apt-get : ubuntu와 같은 몇몇 운영체제에서의 앱스토어
      - update : 설치한 프로그램을 최신 버전으로 업데이트 함
    - console에서 $ sudo apt-get install apache2
      - install [프로그램명] : 특정 프로그램을 설치함
      - 설치할껀지 yes/no가 뜨면 y입력
    - IP Address 찾기(console에서)
      - $ hostname -I
        - host : 인터넷에 연결되어있는 컴퓨터 한대 한대를 이름
        - hostname : 컴퓨터의 인터넷 상의 이름
        - -I : 해당 컴퓨터의 IP Address
    - 두 대의 컴퓨터가 동일네트워크에 접속하고 있어야 제대로 동작함
    - 화면에 표시된 웹페이지의 위치(console 창에서)
      - $ cd /var/www/html
        - cd : change directory
      - $ ls -al
        - 현재 디렉토리에 있는 파일 목록
      - $ sudo mv [이름을 바꾸려는 파일명(전)] [바꾸고자 하는 파일명(후)]
        - mv : rename
      - $ sudo cp * [이동하고자 하는 폴더명]
        - cp : 특정 파일을 특정 폴더로 이동
        - \* : 해당 폴더의 모든 파일
    
23. 수업을 마치며 1

    - 기술 : 본질(essence) / 혁신(innovation)
    - 학습 : 교양(hobby) / 직업(professional)
    - 

24. 수업을 마치며 2

    - 복잡함
      - 공부한 것을 사용하려 할 때 막막하게 함
      - ex) \<input type="checkbox"\>를 통해 체크박스 생성
        - 체크박스 1개일 때 테스트 : 2번
        - 체크박스 2개일 때 테스트 : 4번
        - 체크박스 3개일 때 테스트 : 8번
        - ...
        - 체크박스 50개일 때 테스트 : 2^50^ = 1,125,899,906,842,624번(1천조)
      - 세상은 쉽게 복잡해짐
      - 스스로 좌절할 필요 없음

25. 수업을 마치며 3

    - 공부의 방향 선택
      - CSS : 웹페이지 꾸미기
        - web publisher
        - web designer
      - JavaScript : 사용자와 상호작용하는 웹페이지
        - web front end engineer
        - web interactive designer
      - backend기술
        - 하나의 파일을 변경하면 일억개의 페이지가 동시에 바뀜
        - PHP, JSP, Node.js의 express, python의 django, ruby의 ruby on rails, asp.net
        - backend engineer
    
26. 부록 : 코드의 힘 - 동영상 삽입

    - youtube동영상
      - share -> embed(source, 퍼가기) -> code를 copy하여 삽입하고자 하는 위치에 삽입하기
    - \<iframe\>태그\<iframe\>\</iframe\>
      - 동영상 삽입하는 태그

