# 우아한테크코스 8기 학습 기록

**카야 · 최서영 · Backend**  
페어와 함께 구현하고, 코드 리뷰로 돌아보고, 다음 미션에서 다시 시도한 기록을 모았습니다.

[GitHub 프로필](https://github.com/choiyoung69) · [미션 PR 모아보기](https://github.com/pulls?q=is%3Apr+author%3Achoiyoung69+org%3Awoowacourse) · [LMS+](https://techcourse-lms-plus-web.woowahan.com/crew/missions)

## 목차

- [Java와 객체지향](#java와-객체지향)
- [Spring과 웹 애플리케이션](#spring과-웹-애플리케이션)
- [프레임워크 내부 구현](#프레임워크-내부-구현)
- [페어프로그래밍과 코드 리뷰](#페어프로그래밍과-코드-리뷰)
- [프로젝트와 글쓰기](#프로젝트와-글쓰기)
- [프리코스](#프리코스)

## Java와 객체지향

| 미션 | 코드 | 단계별 제출 · 리뷰 |
| --- | --- | --- |
| 블랙잭 | [java-blackjack](https://github.com/choiyoung69/java-blackjack) | [사이클 1 · 게임 실행](https://github.com/woowacourse/java-blackjack/pull/993) / [사이클 2 · 베팅](https://github.com/woowacourse/java-blackjack/pull/1121) |
| 장기 | [java-janggi](https://github.com/choiyoung69/java-janggi) | [사이클 1 · 보드 초기화와 기물 이동](https://github.com/woowacourse/java-janggi/pull/185) / [사이클 2 · 기물 확장과 DB 적용](https://github.com/woowacourse/java-janggi/pull/354) |
| Today I Learn 페이지 | [web-today-i-learn](https://github.com/choiyoung69/web-today-i-learn) | [미션 제출](https://github.com/woowacourse/web-today-i-learn/pull/110) |
| Gemini 웹앱 출시 | [gemini-canvas-mission](https://github.com/choiyoung69/gemini-canvas-mission) | [사용자가 있는 웹앱 출시하기](https://github.com/woowacourse/gemini-canvas-mission/pull/124) |

## Spring과 웹 애플리케이션

방탈출 예약 서비스를 단계적으로 확장한 기록입니다.

| 미션 | 코드 | 단계별 제출 · 리뷰 |
| --- | --- | --- |
| 방탈출 예약 관리 | [spring-roomescape-admin](https://github.com/choiyoung69/spring-roomescape-admin) | [예약 관리](https://github.com/woowacourse/spring-roomescape-admin/pull/399) |
| 방탈출 사용자 예약 | [spring-roomescape-member](https://github.com/choiyoung69/spring-roomescape-member) | [사이클 1 · 테마와 사용자 예약](https://github.com/woowacourse/spring-roomescape-member/pull/398) / [사이클 2 · 예약 변경·취소와 에러 처리](https://github.com/woowacourse/spring-roomescape-member/pull/505) |
| 방탈출 인증과 인가 | [spring-roomescape-auth](https://github.com/choiyoung69/spring-roomescape-auth) | [선택 미션 제출](https://github.com/woowacourse/spring-roomescape-auth/pull/32) |
| 방탈출 예약 대기 | [spring-roomescape-waiting](https://github.com/choiyoung69/spring-roomescape-waiting) | [사이클 1 · 예약 대기](https://github.com/woowacourse/spring-roomescape-waiting/pull/372) / [사이클 2 · 예약 대기 승인](https://github.com/woowacourse/spring-roomescape-waiting/pull/496) |
| 방탈출 예약 외부 API 연동 | [spring-third-party-api](https://github.com/choiyoung69/spring-third-party-api) · [제출 저장소](https://github.com/choiyoung69/spring-roomescape-waiting) | [1단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/644) / [2단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/646) / [3단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/655) |

> 외부 API 연동 PR은 실제 제출된 spring-roomescape-waiting 저장소로 연결했습니다.

## 프레임워크 내부 구현

| 미션 | 코드 | 단계별 제출 · 리뷰 |
| --- | --- | --- |
| HTTP 서버 | [java-http](https://github.com/choiyoung69/java-http) | [1 · HTTP 서버 구현](https://github.com/woowacourse/java-http/pull/1197) / [2 · 로그인 구현](https://github.com/woowacourse/java-http/pull/1339) / [3 · 리팩터링](https://github.com/woowacourse/java-http/pull/1440) / [4 · 동시성 확장](https://github.com/woowacourse/java-http/pull/1455) |
| MVC 프레임워크 | [java-mvc](https://github.com/choiyoung69/java-mvc) | [1 · @MVC 프레임워크 구현](https://github.com/woowacourse/java-mvc/pull/1275) / [2 · 점진적인 리팩터링](https://github.com/woowacourse/java-mvc/pull/1330) / [3 · JSON View 구현](https://github.com/woowacourse/java-mvc/pull/1340) |
| JDBC 라이브러리 | [java-jdbc](https://github.com/choiyoung69/java-jdbc) | [1 · JDBC 라이브러리 구현](https://github.com/woowacourse/java-jdbc/pull/1527) / [2 · 리팩터링](https://github.com/woowacourse/java-jdbc/pull/1581) / [3 · Transaction 적용](https://github.com/woowacourse/java-jdbc/pull/1583) / [4 · Transaction synchronization 적용](https://github.com/woowacourse/java-jdbc/pull/1584) |

## 페어프로그래밍과 코드 리뷰

LMS+의 **사전학습 → 토론 활동 → 피드백 활동** 흐름을 참고해, 구현 결과와 그 과정에서 나눈 고민을 함께 찾아볼 수 있도록 정리합니다. 각 미션의 PR에서 제출 당시의 질문, 리뷰 대화, 수정 내역을 확인할 수 있습니다.

### 블랙잭 · TDD와 테스트 가능한 설계

[사이클 1 PR](https://github.com/woowacourse/java-blackjack/pull/993)에 남긴 페어 경험을 요약했습니다.

- 페어와 TDD를 활용해 작은 단위의 기능을 검증하는 경험에 집중했습니다.
- 랜덤 요소가 있는 카드 덱과 객체 간 협력 구조에서 테스트 작성의 어려움을 경험하고, 테스트를 위해 설계를 수정했습니다.
- 현재 구조가 테스트하기 쉬운지, TDD를 위한 설계 방향은 무엇인지, 테스트에서 놓친 부분은 없는지 리뷰를 요청했습니다.

페어별 이름·활동 기간과 개별 회고는 확인된 기록을 바탕으로 추가할 예정입니다.

### 기록을 추가할 때

| 항목 | 남길 내용 |
| --- | --- |
| 미션과 단계 | 미션명, 사이클 또는 단계, PR 링크 |
| 페어 활동 | 페어의 공개 프로필, 함께 작업한 범위 |
| 사전학습 | 구현 전에 정리한 개념과 질문 |
| 토론과 구현 | 비교한 선택지, 결정 이유, 역할 교대 경험 |
| 피드백 | 리뷰에서 발견한 문제와 반영한 변경 |
| 회고 | 배운 점과 다음 미션에서 시도할 행동 |

## 프로젝트와 글쓰기

| 활동 | 기록 |
| --- | --- |
| DAYNOMY 팀 프로젝트 | [팀 저장소](https://github.com/woowacourse-teams/2026-DAYNOMY) · [개인 fork](https://github.com/choiyoung69/2026-DAYNOMY) |
| DAYNOMY 소개 | [daynomy-showcase](https://github.com/choiyoung69/daynomy-showcase) |
| 투자 서비스 프로토타입 | [woowa-prototype-investment](https://github.com/choiyoung69/woowa-prototype-investment) |
| 테크니컬 라이팅 | [woowa-writing](https://github.com/choiyoung69/woowa-writing) · [제출 및 피드백 PR](https://github.com/woowacourse/woowa-writing/pull/1111) |

## 프리코스

| 미션 | 코드 |
| --- | --- |
| 문자열 덧셈 계산기 | [java-calculator-8](https://github.com/choiyoung69/java-calculator-8) |
| 자동차 경주 | [java-racingcar-8](https://github.com/choiyoung69/java-racingcar-8) |
| 로또 | [java-lotto-8](https://github.com/choiyoung69/java-lotto-8) |
| Yacht | [java-yacht-8](https://github.com/choiyoung69/java-yacht-8) |
| Planet Lotto | [java-planetlotto-8](https://github.com/choiyoung69/java-planetlotto-8) |

---

2026-11-23 기준 공개 저장소와 본인 작성 PR 27개를 확인해 정리했습니다. PR의 Open/Merged 상태는 각 링크에서 확인할 수 있습니다. LMS+는 로그인이 필요할 수 있으며, 수강 상태를 구현 완료 여부로 사용하지 않습니다. 미션 코드와 리뷰 원문은 각 원본 저장소에서 관리합니다.
