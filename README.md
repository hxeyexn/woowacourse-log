# woowacourse-log

> **우아한테크코스 6기: 모바일 안드로이드 활동 기록**  
2024.02 - 2024.11
> - Kotlin, 가독성 좋은 코드의 중요성과 OOP를 학습했습니다.
> - TDD, 테스트를 학습하고, 코드 리뷰를 경험했습니다.
> - MVC, MVP, MVVM를 점진적으로 안드로이드 미션에 적용해보며 디자인 패턴들의 차이점 학습했습니다.
> - 유연성 강화 스터디, 회고, 데일리 미팅, 글쓰기 등 소프트 스킬을 학습했습니다.

<br>

## 목차
- [Level1: Kotlin, MVC 학습]()
  - **미션**: 자동차 경주, 로또, 블랙잭, 오목
  - **방과후 수업**: 팩토리 함수, 의존성과 DIP  

- [Level2: Android, MVP, MVVM 학습]()
  - **미션**: 영화 티켓 예매, 영화 극장 선택, 쇼핑 장바구니, 쇼핑 주문
  - **테코톡**: Android UI Test

- [Level3: 서비스 런칭]()
   - **스타카토**: 추억하고 싶은 일상을 '즉시 간편하게' 지도 위에 기록할 수 있는 서비스

- [Level4: DI, View, Compose]()
  - **미션**: 만들면서 배우는 DI, 뷰 챌린지, Compose 회원가입
  - 테크니컬 라이팅: ObservableField와 LiveData의 이해(+ Data Binding와 결합하기)

- [글쓰기 미션: 유연성 강화]()

<br>

## Level 1
### 🏎️ 자동차 경주 미션
> 역할과 책임이 명확한 함수를 구현하는 방법에 대해 학습했습니다.  
> 도메인 모델 내 메서드의 테스트 커버리지 100% 달성을 시도해 보며 객체를 설계하는 연습을 했습니다.

|PR|Repository|
|:---:|:---:|
|[1, 2단계](https://github.com/woowacourse/kotlin-racingcar/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[kotlin-racingcar](https://github.com/hxeyexn/kotlin-racingcar/tree/step2)|

<br>

### 🎱 로또 미션
> TDD로 프로그래밍 요구 사항을 구현하며 정확하고 빠르게 피드백을 얻는 방법을 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1, 2단계](https://github.com/woowacourse/kotlin-lotto/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[kotlin-lotto](https://github.com/hxeyexn/kotlin-lotto/tree/step2)|

<br>

### 🃏 블랙잭 미션
> 객체 지향의 다형성을 이용해 조건문을 줄이는 방법을 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1, 2단계](https://github.com/woowacourse/kotlin-blackjack/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[kotlin-blackjack](https://github.com/hxeyexn/kotlin-blackjack/tree/step2)|

<br>

### ⚪️ 오목 미션
> 오목 콘솔 프로그램을 구현 후, 이를 안드로이드 프로젝트로 마이그레이션 하는 경험을 했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/kotlin-omok/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[kotlin-omok](https://github.com/hxeyexn/kotlin-omok/tree/step3)|

<br>

### 🧑‍🏫 방과후 수업 진행
> [팩토리 함수](https://velog.io/@hxeyexn/Kotlin-%ED%8C%A9%ED%86%A0%EB%A6%AC-%ED%95%A8%EC%88%98), [의존성과 DIP](https://velog.io/@hxeyexn/OOP-%EC%9D%98%EC%A1%B4%EC%84%B1%EA%B3%BC-DIP%EC%9D%98%EC%A1%B4-%EC%97%AD%EC%A0%84-%EC%9B%90%EC%B9%99)에 대해 학습하고 크루들을 대상으로 방과후 수업을 진행하는 시간을 가졌습니다.
   
  <img width="300" alt="image" src="https://github.com/user-attachments/assets/4e6e741c-05d5-4135-a8e6-62c7b78a297a" />

<br>
<br>

## Level 2
### 🎟️ 영화 티켓 예매 미션
> UI 테스트(Espresso)를 학습하고, MVC를 MVP로 리팩터링하는 경험을 했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/android-movie-ticket/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[android-movie-ticket](https://github.com/hxeyexn/android-movie-ticket/tree/step3)|

<br>

### 🍿 영화 극장 선택 미션
> DataBinding과 BindingAdapter에 대해 학습했습니다.  
Room을 사용하여 데이터를 저장하는 방법을 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/android-movie-theater/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[android-movie-theater](https://github.com/hxeyexn/android-movie-theater/tree/step3)|

<br>

### 🛍️ 쇼핑 장바구니 미션
> AAC ViewModel과 LiveData에 대해 학습했습니다.  
실 서버 없이 서버 연동을 테스트하는 방법(MockWebServer)을 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/android-shopping-cart/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[android-shopping-cart](https://github.com/hxeyexn/android-shopping-cart/tree/step3)|

<br>

### 🛒 쇼핑 주문 미션
> 비동기(Thread & Handler, Coroutines)과 Retrofit을 이용한 실 서버 연동을 학습했습니다. 
네트워크 에러 핸들링에 대해 깊게 고민해봤습니다.

<br>

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/android-shopping-cart/pulls?q=is%3Apr+is%3Aclosed+%ED%95%B4%EB%82%98)|[android-shopping-order](https://github.com/hxeyexn/android-shopping-order/tree/step3)|


<br>

## Level 3
### 📱 서비스 런칭  
스타카토 기획, 디자인, 개발에 전반적으로 기여하여 서비스를 런칭했습니다.

> **스타카토란?**   
추억하고 싶은 일상을 '즉시 간편하게' 지도 위에 기록할 수 있는 서비스입니다.  

- [Google Play Store](https://play.google.com/store/apps/details?id=com.on.staccato)
- [GitHub](https://techcourse.woowahan.com/s/Zjqb3Sa1/ls/RGVunMZv)
- [소개 홈페이지](https://sites.google.com/view/woowacourse-demo-6th/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8/%EC%8A%A4%ED%83%80%EC%B9%B4%ED%86%A0?authuser=0&pli=1)

|![image](https://github.com/user-attachments/assets/d8c1b806-1394-4cf3-83ed-6918547536a3)|![image](https://github.com/user-attachments/assets/023e4829-1e18-4754-8599-81dac0bb5e0b)|![image](https://github.com/user-attachments/assets/dbdeaaef-1ecc-4067-976b-a0dc54799794)|![image](https://github.com/user-attachments/assets/22893247-59ea-4e96-943e-eb8f66d311e1)|![image](https://github.com/user-attachments/assets/29fc6759-8088-449f-9294-e85458362a1f)|
|:---:|:---:|:---:|:---:|:---:|

<br>

## Level 4
### 💉 만들면서 배우는 DI 미션
> DI를 직접 구현해 보며 서비스 로케이터와 의존성 주입의 차이점 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/android-di/pulls?q=is%3Apr+assignee%3Ahxeyexn+)|[android-di](https://github.com/hxeyexn/android-di/tree/step4)|

<br>

### 🎨 뷰 챌린지 미션
> onTouchEvent를 활용하여 그림판을 구현하고, 다크모드 및 태블릿 UI(가로, 세로)를 대응하는 방법을 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 3단계](https://github.com/woowacourse/android-paint/pulls?q=is%3Apr+assignee%3Ahxeyexn+)|[android-paint](https://github.com/hxeyexn/android-paint/tree/step2)|

<br>

### 🪪 Compose 회원가입 미션
> 학습 테스트를 통해 Compose에 대한 기초 지식을 학습했습니다.

|PR|Repository|
|:---:|:---:|
|[1 ~ 4단계](https://github.com/woowacourse/android-signup/pulls?q=is%3Apr+assignee%3Ahxeyexn+)|[android-signup](https://github.com/hxeyexn/android-signup/tree/step3%2C4)|

<br>

### 📝 테크니컬 라이팅
> ObservableField와 LiveData의 개념과 차이점, DataBinding과 함께 활용하는 방법을 알아보는 글을 작성했습니다.
- [ObservableField와 LiveData의 이해(+ Data Binding와 결합하기)](https://github.com/hxeyexn/woowa-writing/blob/technical_writing/technical_writing.md)

<br>

## 글쓰기 미션
> 유연성 강화 스터디의 경험을 시리즈로 작성했습니다.
- [Level1 글쓰기](https://github.com/hxeyexn/woowa-writing/blob/main/Lv1.md)
- [Level2 글쓰기](https://github.com/hxeyexn/woowa-writing/blob/main/Lv2.md)
- [Level3 글쓰기](https://github.com/hxeyexn/woowa-writing/blob/main/Lv3.md)
