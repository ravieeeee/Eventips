# Eventips
이벤트를 등록하고 사용자가 이 이벤트에 참가 신청을 할 수 있는 EventBrite와 유사한 웹사이트

## Requirements
**사용자**

1. 사용자는 본인이 이벤트를 생성할 수도 있고, 참가할 수도 있다.
2. 회원가입, 로그인
3. 관리자는 관리 페이지에서 사용자 목록을 관리(조회,삭제,수정)할 수 있다.
4. (Option) 회원 탈퇴: 탈퇴 시 회원의 개인 정보는 삭제하고 로그인 할 수 없도록 처리함.
5. (Option) 비밀번호 암호화
6. (Option) Facebook 로그인
7. (Option) 카카오톡 로그인
8. (Option) 비밀번호 수정, 회원 정보 수정
9. (Option) 비밀번호 재설정 이메일 전송 기능


**이벤트 생성**

1. 필수 정보를 입력할 수 있다: 이벤트의 이름, 장소, 시작시간, 종료시간, 상세 설명, 등록 조직 이름, 등록 조직 설명
2. 이벤트의 종류와 분야를 선택할 수 있다.
3. 무료 행사인지, 유료 행사인지를 결정하여 유료 행사의 경우 티켓 가격을 입력받는다.
4. (option) 이벤트 관련 사진을 여러장 입력할 수 있다.
5. (option) 상세 설명을 WYSIWYG에디터를 이용하여 입력받는다. (TinyMCE 등 활용 가능)
6. (option) 장소를 맵을 이용하여 입력받을 수 있다.
7. (option) 최대 참가 인원을 설정할 수 있다.
8. (option) 참여인원에게 간단한 설문 (소속, 참여 이유 등)을 진행할 수 있다.


**이벤트 조회**

1. 이벤트의 목록을 조회할 수 있다.
2. 이벤트의 상세 정보를 조회할 수 있다.
3. 이벤트에 참여 신청을 할 수 있다. 
4. (Option) 키워드, 지역, 분야를 통한 이벤트 검색
5. (Option) 지도에서 이벤트 보여주기
6. (Option) 캘린더에서 이벤트 보여주기

**이벤트 관리**

1. 등록자는 이벤트 정보를 수정/삭제 할 수 있다.
2. 등록자는 이벤트 참여 신청자 목록을 확인할 수 있다.

**기타 기능**

1. 반드시 nodejs, express, mongodb를 사용해야 함.
2. 모든 최신 브라우져(IE, Safari, Chrome, Firefox)에서 무리 없이 사용할 수 있어야 함.
3. 과제의 결과물을 웹에서 확인 가능해야 함.
4. (Option) 후기 기능. 사용자는 이벤트에 대한 후기/질의를 남길 수 있고 등록자는 후기에 답변을 달 수 있다.
5. (Option) 이벤트 추천보기: 이벤트 후기, 참여자 수, 지역, 등에 의한 추천기능
6. (Option) Favorite 기능: 이벤트를 Favorite에 추가. 자신의 Favorite 목록 확인 가능
7. (Option) Responsive Design
8. (Option) Ajax 기술, 혹은 WebSocket 기술을 활용
