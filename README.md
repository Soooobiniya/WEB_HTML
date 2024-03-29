# WEB_HTML

### 2023.03.29 ~ 2023.03.30
***
* HTML 장점
1. 쉬움
2. 웹페이지 언어 -> 중요

* 웹은 저작권 없는 public  domain, 따라서 특정 기업 독점 없음
***
첫번째 실습
1. 프로젝트명.html -> 확장자명은 약속!
2. 반드시 save 해주기(동그라미 표시 있으면 안됨!) or ctrl+s
3. ctrl+o or 파일을 url 창에 드래그하면 해당 프로젝트(html 파일) 결과 확인 가능
***
두번째 실습
1. 단순히 수업을 따라가는 것이 아닌, 내가 하고싶은 or 나의 정보를 담으면서 웹페이지 만들기
2. <태그명:strong>굵은글씨<태그명:/strong>
3. <태그명:u>밑줄<태그명:/u>
***
세번째 실습
1. 어떤 웹페이지의 소스 코드를 보고 싶다면, 오른쪽 마우스 클릭 후 페이지 소스 보기 -> html 코드 확인 가능
2. <태그명:h1>h1부터 h6까지 제목을 나타내는 태그<태그명:/h1>
3. <태그명:h1>~<태그명:h6>으로 갈수록 글씨 크기 작아짐, 일반적인 글씨보다 굵음, 자동 줄바꿈
4. <태그명:h7>은 없다
***
* 오늘날 웹페이지는 태그가 평균 25~26개 사용됨
***
네번째 실습
1. <태그명:br>단순 줄바꿈 -> 닫히는 태그 없음!!
2. <태그명:p>"br태그"와 달리 어디서부터 어디까지 한 단락인지 표현 가능, 정해진 여백 크기, 닫히는 태그 있음<태그명:/p>
=> "p태그"를 쓰는 것이 웹페이지를 정보로서 좀 더 가치 있게 만듦. 의미론적으로 단락 표현해줌.
***
* html을 의미에 맞게, 정확하게 사용하는 것은 비즈니스적 측면에서 매우 중요 (예쁘게 꾸미는 것보다 중요할 수 있다)
* 접근성이 중요(예쁘게 꾸미는 것만 집중하다 보면 접근성 매우 떨어질 수도..)
***
다섯번째 실습
1. <태그명:img src="이미지 주소" width="원하는 크기(450 or 100% 등..)">이미지를 웹페이지에 포함시킬 때 사용
2. "img태그"처럼 뒤에 속성들이 붙는 태그 존재, 속성들의 순서 상관 없음
* unsplash.com => 퀄리티 좋은 이미지 저작권 구애 없이 사용 가능
***
여섯번째 실습
* <태그명:parent> <태그명:child><태그명:/child> <태그명:/parent>
1. <태그명:li>리스트<태그명:/li>
2. <태그명:ul>연관된 리스트들을 묶음<태그명:/ul>
=> "li태그"는 반드시 부모 태그를 갖고, "ul태그"는 반드시 자식 태그를 갖는다
* vscode에서 드래그 후 탭 => 들여쓰기
3. "li태그"의 부모 태그를 <태그명:ol>리스트 숫자 자동 넘버링<태그명:/ol>로 변경하면 넘버링 가능
4. ol: ordered list & ul: unordered
5. <태그명:table>표 작성 시 <태그명:tr>1행 <태그명:td>1열<태그명:/td><태그명:td>2열<태그명:/td>... <태그명:/tr> <태그명:tr>... <태그명:/tr> <태그명:/table>
***
일곱번째 실습
1. <태그명:title>웹페이지 제목<태그명:/title>
2. <태그명:meta charset="utf-8"> utf-8로 문서를 읽어라
3. 웹페이지는 본문설명 - 본문으로 구성, <태그명:head>1&2가 본문설명<태그명:/head> <태그명:body>본문<태그명:/body>
=> "head태그"로 본문설명을, "body태그"로 본문을 묶기로 한 것은 약속! 필수!
4. <태그명:!doctype html>
<태그명:html>
<태그명:head>
<태그명:/head>
<태그명:body>
<태그명:/body>
<태그명:/html>
=> html 문서의 관용적 표현, 처음 쓸 때 무조건 이렇게 시작!
***
여덟번째 실습
1. <태그명:a href="연결할 링크" target="해당 링크 탭 띄우는 방식(새 탭 or 기존 탭 등..)" title="링크 설명">링크를 걸고싶은 텍스트<태그명:/a>
***
아홉번째 실습
1. 기본 웹페이지 완성!
***
* 인터넷 안에 웹이 존재
* 1990년대 웹을 만나면서 인터넷 대중화
* 웹서버를 사용한다는 것은 '내 컴퓨터에 있는 문서를 전세계에 있는 누구나, 인터넷이 연결되어 있는 컴퓨터에 웹브라우저를 깔면 가져다가 볼 수 있도록 할 수 있다'는 것이다.
***
* 깃허브 내장 기능 중에 'github page'는 깃허브 안에 보관된 코드를 이용해 웹사이트를 만들 수 있는 기능 제공
=> Settings-Pages-Branch에서 main으로 설정-Save-완료-url 클릭 (진행과정 보고싶으면 Actions)
* 코드파일 수정 후 깃허브 업로드하려면 다시 upload file하면 자동갱신됨
***
* live server 이용하면 웹페이지 띄운 후, 실시간 편집 가능
***
* 웹사이트를 아름답게 -> (WEB2) CSS
* 사용자와 상호작용 -> (WEB2) JavaScript
***
<부록>
1. 동영상 넣는 방법: 소스코드 복사+붙여넣기 (ex: 유튜브-공유-퍼가기-소스코드 복사)
=> <태그명:iframe 속성1 속성2 ...><태그명:/iframe>
2. 댓글 기능 넣는 방법: DISQUS or LiveRe 서비스 이용
DISQUS 이용 방법: 내 사이트에 disqus 설치-웹사이트 이름, 카테고리 입력-universal code-복붙
※ DISQUS 로드 불가(웹서버를 통하지 않아서, 보안 상의 이유로 안열림) => 웹서버(ex: Live Server) 있어야 함! 주소를 "localhost/파일명" or "127.0.0.1/파일명"으로 변경
3. 채팅 기능 넣는 방법: tawk 서비스 이용
관리자 화면-코드 복붙
※ 웹서버를 통해야 함! localhost/~ 주소 변경
※ tawk 대시보드 보면 상대의 채팅 확인, 답장 가능
※ 상대가 채팅 종료 누르면 채팅 끝
4. 웹사이트 방문자 분석기: Google Analytics 서비스 이용
