# resources

- css
1. lib 폴더 : 라이브러리 관련 파일
2. fonts.css : 웹폰트 (추가가능)
3. reset.css : reset css (추가 및 변경 금지)
4. variable.css : 추가 가능 (추가된 속성은 변경 금지)<br/>
               font size 속성은 기본적으로 variable.css 에서 관리 (추후 사용된 폰트 사이즈 관리용도)<br/>
               color 속성은 기본적으로 variable.css 에서 관리 (추후 사용된 색상 관리용도)
5. layout.css : 레이아웃 관련 css 
6. common.css : 공통으로 사용되는 css
7. 1dep명.css : 1dep 기준 css 관리 (1dep 하위 페이지들은 모두 1dep.css 파일에서 관리함)

- images
1. common : icon, btn, visual등 공통으로 사용되는 이미지
2. mb : 모바일 화면에서 사용되는 개별 이미지
3. wb : 웹 화면에서 사용되는 개별 이미지
4. temp : 테스트용 이미지

- font
1. 웹폰트 파일 폴더

- js
1. lib 폴더 : 라이브러리 관련 파일
2. script.js : 기본 스크립트 파일

# _common

1. common.html : 공통으로 사용되는 태그
  - 서브페이지 공통 영역 (Before & After 부터 하단 전체) 
    *Before & After 위 padding 값은 공통 영역에서 제어하지 않음
2. layout.html : layout 태그
3. popup.html : popup 태그

# 퍼블리싱 가이드
1. 공유된 "퍼블리싱 사이트맵 작업내역 공유 파일"을 참고하여 페이지별 고유 부모 클래스 적용
   예시) 자려한코 성형 > url : nose/natural_fancy.html 
   <div id="wrap" class="natural_fancy"> 클래스명은 파일명 기준으로 한다.
2. 폰트 사이즈와 모든 컬러는 variable.css 파일에 등록해서 사용
3. 이미지명은 "파일명_부모컨텐츠 or class_용도" 형태로 작성 *파일명이 제일 첫번째로 오도록 작성
4. C-클래스명이 들어간 요소는 공통요소 css속성은 common.css 에서 관리


# 퍼블리싱 사이트맵 작업내역 공유 파일
https://docs.google.com/spreadsheets/d/1XnFNQrlXyQoYEJ0sGso_JK2-38b8X4IMSlFsTQYHpRk/edit?usp=sharing
