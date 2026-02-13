# asics
* 1주전 과제이어서 → HTML 작성하고 gitHub업로드하기
## 26/02/04 
1. 사이트이름으로 project 하위폴더로 폴더 생성하기 → project/naver/
2. 나머지 중요폴더와 파일등을 생성하여 준비 
3. main까지 html 완료
## 26/02/06
* footer까지 html 완료
## 26/02/11
* 2월 9일에 선생님 피드백(1) 받고, `index.html` 수정중
* 슬라이드, id, class 수정
## 26/02/12
* 2월 11일에 선생님 피드백(2) 받고, contents6 까지 이름, 슬라이드 구조 수정
### feedback(2)
* `top_bnr`에서  `slide`, `a(닫기 버튼)`에 이름태그 추가
* `FAB(a)`에 이름태그 추가
* `header` 시멘틱 태그가 있기 때문에, 주석에는 `h_left`, `h_right`로 줄여써도 됨.
* `gnb` 안에 배너이미지 추가해야함.
    * `div` -> `ul + div`(선택되는 배너라면 div대신에 a)
    * 배너가 선택 되므로 `a`로 작성했음.
* `form`에 이름태그 달기, div 묶음 풀기
* `button`에 class -> `id`로 변경
* `hero_bnr`에서 `a`에 이름태그 주기, div 묶음 풀기
* `contens1`로 이름 주지 말고, 알아볼 수있는 이름으로 만들어주기(길어져도 됨), 순서가 바뀔 수있음으로, 숫자 붙이지 않기.
    * 이름은 콘텐츠내용에서 발췌해서 직역하기.
* `prev`와 `next`를 뷰포트랑 형제관계로 수정
* `ul`의 이름을 구체적으로 변경하면 `li`에서 이름을 빼도 됨.
* `span 고객 상담실`이 강조 내용이므로 `em`으로 변경
* `dl`에 이름주기
    * dl-dt-dd를 쓸 수 있지만보통은 `a + div`로 준다.
* `fnb`에서 `fnb1, fnb2, fnb3`으로 단을 나누지 않기.
    * div 없애고 ul 만 남기기
* footer 안의 `sns_icon`에서 `ul -> div, a`로 수정, 이름에 icon 빼기

## 26/02/13 오전
* footer까지 이름, 슬라이드 구조 수정
* 2월 13일 오전 선생님 피드백(3) 받고 `index.html` 수정
### feedback(3)
* top_bnr에서 `a 닫기`는 `slide_container`랑 형제로 빼기
* `class="Chatbot"`으로 대문자 적혀있는 것 수정
* gnb의 li에 depth1 이름 준 것 빼기
* gnb_bnr에 배너 이름 men -> right로 변경
* depth2와 a(gnb_bnr)묶는 div추가
* `form`에 name 빼기
* page를 progress bar로 수정 `div 안에 span`으로 수정
* style 빼고 css로 넣을 `bg` 주석 달기
* 가격은 span 말고 `class`주기
    * span을 가격에 쓰는 경우는 부분적으로 디자인을 다르게 할 때
    * ex) 가격이 크고, 원이 작을 때
* li에 slide 오타 그만~
* `p - em`으로 묶인 것 중, 강조 내용이 없는 경우, em 말고 P에 class를 주기
## 26/02/13 오후
* 선생님 피드백(4) 받고 `index. html` 남은 수정부분 적용하고, `index.css - header`작성 시작
* 피드백(5), css 끝까지 작성하고 header까지만 스타일적용 해보기
### feedback(4)
* 상태바 `span`에도 이름을 줘야함.
    * 모든 태그에 class, id 가능, span도 이름태그 가능
    * `div class="bar", span class="progrees"`
* 개별 slide에 class 추가
    * `class="slide(공통) slide1(개별)"`
* new 안에 span 태그 추가
    * p (class="badge") 안에서 span(clsss=new) span(class=members) 넣어서 추가 뱃지 생길 것 고려
* add_bnr에 바로가기에 이름 추가
### feedback(5)
* 개발자도구(f12)로 css 선택자 잘 적혔는지 확인하기
* h_left, h_right h1ml과 css 선택자 통일
* search 오타
* progress bar 수정 빠진 것 확인