# android-movie-ticket

## 페어프로그래밍 규칙
* 교대는 기능 단위로 커밋 2번으로 한다.
* 서로를 존중하며 의견을 공유한다.
* 토론은 주저하지 않는다.


## 기능 목록

#### 영화 목록
- [x] 영화 데이터는 제목, 썸네일, 상영일, 러닝타임, 소개글로 이뤄져 있다.
- [x] 사용자는 영화 목록 중 하나의 예매 화면으로 이동할 수 있다.


#### 영화 예매
- [x] 사용자는 예매 화면에서 선택한 영화의 상세 데이터를 확인할 수 있다.
- [x] 영화 상영일은 각자의 범위를 갖는다(예: 2024.4.1 ~ 2024.4.28).
- [x] 영화 상영 시간 범위는 오전 9시부터 자정까지다.
  - 주말에는 오전 9시부터 두 시간 간격으로 상영한다.
  - 평일에는 오전 10시부터 두 시간 간격으로 상영한다.
- [x] 사용자는 선택한 영화의 날짜와 시간을 설정할 수 있다.
  - 날짜와 시간은 기본값으로 초기화되어있다.
- [ ] 사용자가 설정한 정보들은 화면이 회전되어도 유지되어야 한다.
- [x] 사용자는 예약할 인원을 선택할 수 있다.
- [x] 사용자는 좌석 선택 버튼을 통해 좌석 선택 화면으로 이동할 수 있다.
- [x] 사용자는 예매 화면에서 뒤로 가기 버튼을 통해 영화 목록 화면으로 돌아갈 수 있다.


#### 좌석 선택
- [x] 좌석은 총 5행 4열로 구성 되어 있다.
  - [x] 좌석은 행별로 등급이 나뉜다.
  - [x] 각 행은 알파벳, 열은 숫자로 표현한다.
  - [x] 좌석은 등급별로 가격과 글자색이 다르다.
- [x] 사용자는 원하는 좌석을 선택할 수 있다.
  - [ ] 원하는 위치를 선택하면, 배경색이 변경된다.
- [x] 사용자는 선택했던 좌석을 취소할 수 있다.
  - [ ] 선택된 좌석을 재선택하면 배경색이 변경되며 선택이 해제된다.
- [ ] 사용자가 원하는 좌석을 선택하면, 하단에 최종 가격이 표시된다.
- [ ] 확인 버튼을 누르면 최종 예매를 확인하는 다이얼로그가 표시된다.
  - 배경을 터치해도 사라지지 않아야 한다.


#### 예매 완료
- [x] 사용자는 완료 화면에서 예매 정보를 확인할 수 있다.
  - [x] 사용자는 인원수와 그에 따른 총 티켓 가격을 확인할 수 있다.
- [x] 사용자는 완료 화면에서 뒤로 가기 버튼을 통해 영화 목록 화면으로 돌아갈 수 있다.
