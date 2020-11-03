### 학습목표(아래)

- 반응형 웹사이트 만들기
- 파이어폭스 개발자도구의 스타일 탭사용
- 기존 PC용 > 태블릿용 > 모바일용 CSS작업순서를 [모바일용 > 태블릿용 > PC용] 으로 변경작업

#### 20201103(화)
-유효성검사: 예전에는 자바스크립트 처리
            html5 속성으로 처리.(required)
-<form>태그 속성 2가지 중요
    action 속성 : 데이터 전송 위치
    method 속성 : 데이터 전송 방법(아래)
        get(비보안-데이터 노출), post(보안-데이터 숨김)
        GET(기본) : 검색방식
        POST(지정) : 등록폼에서 사용.
- 게시판 리스트: 모바일용 작업
- 모바일용 -> 태블릿용 - > PC용
- 부트스트랩 
#### 20201102(월)
- 
- 람다식(코드생략:애로우함수): ->(자바) , =>(자바스크립트)
    자바7(X),자바8(O),안드로이드 스튜디오
- 자바스크립트 버전(아래)
- es5(엑마스크립트 2015-네이티브 자바스크립트),
    es7(엑마스크립트 2017 - 람다함수수식추가 - 코드축소 구현)

#### 20201030(금)
- background-size: cover 속성은 영역보다 이미지가 작을때 작동.
- initial : 초기화(extends)
- inherit : 상속 (extends)
- @media all => screen + print +... 
- 대괄호 [배열], 중괄호 {구현 내용}, 소괄호 (매개변수)
- @미디어쿼리
    @애노테이션 = 지시어
- 웹프로그램 : 기본은 게시판 (아래)
    CRUD : Creat (Insert - 자료입력)
           Read (Select - 자료조회)
           Updata (자료수정)
           Delete(자료삭제)

#### 20201029(목)
- bbs(pc통신부터 게시판약자 bbs) board system.
- img는 가로크기를 지정하면, 세로크기는 자동으로 조정.
- j쿼리 : 네이티브 자바스크립트 단축키워드로 사용.
- j쿼리 코어를 가져와서 사용.
- 자바스크립트 콜백함수 : (아래)
    이름이 없는 함수
    기본함수는 이름을 호출해야지 실행이 되지만, 콜백함수는 호출없이 실행됨.
- nav태그 : html5 추가된 태그.
- ul(unorder list)태그 > li(list)태그
- 네이밍규칙 : 카멜표기법(낙타등)
- 사각형 영역 크기 : box-sizing : border-box; 
- 웹접근성 : 시각장애인들을 위한 코딩 추가
- 스크린리더 프로그램용 코딩 예) text-indent : -9999px ;
- 햄버거메뉴 : .openMOgnb -> gnb(global navigation)         
    글로벌 네비게이션(전체메뉴)
    ps. page navigation (페이징 링크 처리)

#### 20201028(수)
- Z-index : 화면에는 레이어라는 개념 , 0부터 시작
- CSS 스타일 적용하는 3가지 방법
    - 1.인라인 스타일 : 태그 안쪽에 style 속성 사용
     예)sytle='padding:10px'
    - 2.파일안에 style 태그사용 (아래) 
     예)<style>내부 스타일 주기</style>
    - 3.외부 CSS파일 지정하기 (아래)
     예) <link href="CSS파일위치"/>
- 깃허브 README.md(마크다운 언어)
- meta 데이터 : 데이터의 데이터,(콘텐츠를 설명하는 데이터).
- 메타태그중 viewport는 반응형 사이트에서 필수.
    initial-scale=1, minimum-scale=1, maximum-scale=1

- 반응형사이트 화면설계서_학생용 구글ppt 다운받기(아래 구글링크):
- https://drive.google.com/file/d/17jXgf7R2BawMt3K9eoxfnnO_8X9yClLZ/view?usp=sharing
- 반응형사이트 기획서_학생용 구글xlsx 다운받기(아래 구글링크):
- https://drive.google.com/file/d/1dC2RMqDqNeEFtr-r-dvcsKk0YwPjk0Xy/view?usp=sharing

#### 20201022(목)

- 소스내용 교육용으로 정리
- 깃 사용시 토큰인증헤제: [윈도우 자격증명관리]에 personal access token 을 삭제 후 커밋
- 강사블로그 http://blog.daum.net/web_design 에서 익스텐션으로 검색 vscode 사용법 참조.
- 비주얼스튜디오코드 익스텐션 파일 구글드라이브 다운로드(아래):
- https://drive.google.com/file/d/1NkZ0qfr2P0tDsRKyP9qHQ3tPkafeKiPv/view?usp=sharing

#### 20201019(월)

- 반응형사이트 화면설계서_교사용 구글ppt 다운받기(아래 구글링크):
- https://drive.google.com/file/d/1GqBK_sKPFpfhTDd4whbLK3ZLXP1g3_Kw/view?usp=sharing
- 반응형사이트 기획서_교사용 구글xlsx 다운받기(아래 구글링크):
- https://drive.google.com/file/d/1Wjuov4TCQjqBtCu5EbUc3SNns8PaxHSX/view?usp=sharing
