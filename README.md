## 우아한 테크코스 7기 BE LV2 최종 미션
### By mimi

# 맛집 예약 서비스
## 필수 기능
- [X] 사용자는 특정 맛집을 예약할 수 있다.
  - [X] 오늘이나 이전 날짜에 대한 예약 시 예외가 발생한다.
  - [X] 존재하지 않는 사용자이면 예외가 발생한다.
  - [X] 기존에 예약이 존재하면 예외가 발생한다.
  - [X] 등록되지 않은 일정일 경우 예외가 발생한다.
  - [X] 공휴일이면 예외가 발생한다.
- [X] 모든 사용자는 예약 현황을 확인할 수 있다.
- [X] 사용자 본인은 자신이 한 예약의 상세 정보까지 확인할 수 있다.
  - [X] 사용자 본인이 아닐 경우 예외가 발생한다.
  - [X] 예약이 존재하지 않을 경우 예외가 발생한다.
- [X] 사용자는 본인의 예약만 수정/삭제할 수 있다.
  - [X] 사용자 본인이 아닐 경우 예외가 발생한다.
  - [X] 오늘이나 이전 날짜에 대한 예약 수정 시 예외가 발생한다.
  - [X] 예약 수정 시, 예약이 존재하지 않을 경우 예외가 발생한다.
  - [X] 예약 수정 시, 기존에 예약이 존재하면 예외가 발생한다.
  - [X] 예약 수정 시, 등록되지 않은 일정일 경우 예외가 발생한다.
  - [X] 예약 수정 시, 공휴일이면 예외가 발생한다.

## 프로그래밍 요구사항
- [X] h2를 이용하여 데이터를 관리한다.
- [X] 테스트 코드를 통해 애플리케이션이 의도대로 동작하는지 검증한다.
  - [X] 도메인 객체에 대한 단위 테스트를 진행한다.
  - [X] 서비스 계층에 대한 기능 정상/예외 테스트를 진행한다.
  - [X] RestAssured를 사용해 중요한 비즈니스 로직에 대한 통합 테스트를 진행한다.
- [X] 공휴일 정보 조회 외부 API를 연동한다.
  - [X] 공휴일 확인 로직에 사용한다.

## ToDo
- [X] 시스템 시간에 종속적이지 않도록 수정한다.
- [X] DTO에 대한 유효성 검증 로직을 작성한다.
- [ ] 예약에 알맞는 사용자를 구분하기 위해 별도의 로직을 작성한다.
