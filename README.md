# ⭐️ 우아한테크코스 5기 모바일 안드로이드 환노의 학습 과정 ⭐️

## 레벨1 - 코틀린 미션
|미션명|레포지토리|PR 1|PR 2|
|---|---|---|---|
|자동차 경주|[레포지토리](https://github.com/hwannow/kotlin-racingcar/tree/hwannow)|[1단계 PR](https://github.com/woowacourse/kotlin-racingcar/pull/141)|[2단계 PR](https://github.com/woowacourse/kotlin-racingcar/pull/157)|
|로또|[레포지토리](https://github.com/hwannow/kotlin-lotto/tree/hwannow)|[1단계 PR](https://github.com/woowacourse/kotlin-lotto/pull/113)|[2단계 PR](https://github.com/woowacourse/kotlin-lotto/pull/132)|
|블랙잭|[레포지토리](https://github.com/hwannow/kotlin-blackjack/tree/hwannow)|[1단계 PR](https://github.com/woowacourse/kotlin-blackjack/pull/110)|[2단계 PR](https://github.com/woowacourse/kotlin-blackjack/pull/132)|
|오목|[레포지토리](https://github.com/hwannow/kotlin-omok/tree/hwannow)|[1,2단계 PR](https://github.com/woowacourse/kotlin-omok/pull/105)|[3,4단계 PR](https://github.com/woowacourse/kotlin-omok/pull/128)|

### 📍 레벨 1에서 배운 것
1. Kotlin 다운 코드를 고민했어요.
2. 페어프로그래밍을 경험했어요.
3. 책임의 주인을 찾는 연습을 했어요.
4. 테스트 하기 쉬운 구조를 고민했어요.
5. 확장에 열린 설계를 시도했어요.
6. Android를 처음 다뤄 봤어요.
7. 리뷰어와 처음 코드로 소통해 봤어요.
> PR마다 고민을 질문으로 남기고, 생각이 다를 땐 근거를 들어 의견을 나눴어요.

## 레벨2 - 안드로이드 미션
|미션명|레포지토리|PR 1|PR 2|
|---|---|---|---|
|영화 티켓 예매|[레포지토리](https://github.com/hwannow/android-movie-ticket/tree/hwannow)|[1,2단계 PR](https://github.com/woowacourse/android-movie-ticket/pull/107)|[3,4단계 PR](https://github.com/woowacourse/android-movie-ticket/pull/128)|
|영화 극장 선택|[레포지토리](https://github.com/hwannow/android-movie-theater/tree/hwannow)|[1,2단계 PR](https://github.com/woowacourse/android-movie-theater/pull/100)|[3,4단계 PR](https://github.com/woowacourse/android-movie-theater/pull/127)|
|쇼핑 장바구니|[레포지토리](https://github.com/hwannow/android-shopping-cart/tree/hwannow)|[1,2단계 PR](https://github.com/woowacourse/android-shopping-cart/pull/95)|[3,4단계 PR](https://github.com/woowacourse/android-shopping-cart/pull/123)|
|쇼핑 주문|[레포지토리](https://github.com/hwannow/android-shopping-order/tree/hwannow)|[1,2단계 PR](https://github.com/woowacourse/android-shopping-order/pull/108)|[3,4단계 PR](https://github.com/woowacourse/android-shopping-order/pull/130)|

### 📍 레벨 2에서 배운 것
1. MVP에서 MVVM으로 넘어가 봤어요.
2. 데이터 바인딩으로 View 코드를 줄였어요.
3. RecyclerView를 제대로 다뤄 봤어요.
4. 로컬 DB와 서버 통신을 붙였어요.
5. 콜백에서 코루틴으로 비동기를 바꿨어요.
6. Repository로 데이터 계층을 분리했어요.
7. Android 컴포넌트를 폭넓게 써 봤어요.
> AlarmManager로 상영 30분 전 알림을 보내고, Fragment와 바텀 내비게이션으로 화면을 구성했어요.
8. ViewModel까지 테스트했어요.
> MockK로 Presenter와 ViewModel을, Awaitility로 비동기 콜백을 테스트했어요.
9. 처음으로 페어의 코드 위에서 작업해 봤어요.
> 영화 극장 선택 미션에서 처음으로 페어의 코드를 이어받아 리팩터링하며 기능을 확장했어요.

## 레벨3 - 팀 프로젝트 '물깜'
[팀 프로젝트 레포지토리](https://github.com/woowacourse-teams/2025-mul-kkam)

## 레벨4 - DI/뷰 심화 미션, 레벨3 프로젝트 유지보수
|미션명|레포지토리|PR 1|PR 2|PR 3|PR 4|
|---|---|---|---|---|---|
|Compose 페이먼츠|[레포지토리](https://github.com/hwannow/android-payments/tree/hwannow)|[1단계 PR](https://github.com/woowacourse/android-payments/pull/9)|[2단계 PR](https://github.com/woowacourse/android-payments/pull/41)|[3단계 PR](https://github.com/woowacourse/android-payments/pull/65)|[4단계 PR](https://github.com/woowacourse/android-payments/pull/92)
|만들면서 배우는 DI|[레포지토리](https://github.com/hwannow/android-di/tree/hwannow)|[1단계 PR](https://github.com/woowacourse/android-di/pull/157)|[2,3단계 PR](https://github.com/woowacourse/android-di/pull/186)||[4단계 PR](https://github.com/woowacourse/android-di/pull/204)|

### 📍 레벨 4에서 배운 것
1. Compose로 화면을 처음부터 만들어 봤어요.
2. ViewModel 없이 상태를 관리해 봤어요.
> StateHolder로 상태를 끌어올리고, Saver로 화면 회전 시에도 입력값이 유지되도록 했어요.
3. Compose UI를 테스트했어요.
4. DI 라이브러리를 직접 만들어 봤어요.
>  리플렉션으로 생성자와 @Inject 필드를 주입하는 Container와 Factory를 구현했어요.
5. Hilt가 어떻게 동작하는지 따라가 봤어요.
> @Qualifier로 Room과 InMemory 구현을 구분하고, Singleton·Activity·ViewModel 스코프를 생명주기에 맞춰 정리했어요.
6. DI를 별도 모듈로 분리했어요.
> 앱과 DI 코드를 나누고, 두 ViewModel이 같은 Repository 인스턴스를 공유하는지 테스트했어요.

## Soft Skill - 글쓰기
[글쓰기 레포지토리](https://github.com/hwannow/woowa-writing/tree/hwannow)

## 테코톡
[환노의 안드로이드 위젯 테코톡](https://youtu.be/ISzqcmAI2D0?si=HHT1NUjWffIm16qs)
