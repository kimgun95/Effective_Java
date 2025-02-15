# Effective_Java 스터디

### ITEM

2장. 객체 생성과 파괴
- [x] 1. 생성자 대신 정적 팩터리 메서드를 고려하라
- [x] 2. 생성자에 매개변수가 많다면 빌더를 고려하라
- [x] 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라
- [x] 4. 인스턴스화를 막으려거든 private 생성자를 사용하라
- [x] 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라
- [x] 6. 불필요한 객체 생성을 피하라
- [x] 7. 다 쓴 객체 참조를 해제하라
- [x] 8. finalizer와 cleaner 사용을 피하라
- [x] 9. try-finally보다는 try-with-resources를 사용하라

<br>

3장. 모든 객체의 공통 메서드
- [x] 10. equals는 일반 규약을 지켜 재정의하라
- [x] 11. equals를 재정의하려거든 hashCode도 재정의하라
- [x] 12. toString을 항상 재정의하라
- [x] 13. [clone 재정의는 주의해서 진행하라](https://obtainable-poppyseed-72e.notion.site/item-13-clone-da235f49eb104e5da3dee9ae41010258?pvs=4)
- [x] 14. Comparable을 구현할지 고려하라

 <br>

 4장. 클래스와 인터페이스
- [x] 15. 클래스와 멤버의 접근 권한을 최소화하라
- [x] 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라
- [x] 17. 변경 가능성을 최소화하라
- [x] 18. 상속보다는 컴포지션을 사용하라
- [x] 19. [상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라](https://obtainable-poppyseed-72e.notion.site/item-19-461b0c9e18d848e3bc1d3cda44e10590?pvs=4)
- [x] 20. 추상 클래스보다는 인터페이스를 우선하라
- [x] 21. 인터페이스는 구현하는 쪽을 생각해 설계하라
- [x] 22. 인터페이스는 타입을 정의하는 용도로만 사용하라
- [x] 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라
- [x] 24. [멤버 클래스는 되도록 static으로 만들라](https://obtainable-poppyseed-72e.notion.site/item-24-static-99a24eb5913f42dea548c2edbf00a0e7?pvs=4)
- [x] 25. [톱레벨 클래스는 한 파일에 하나만 담으라](https://obtainable-poppyseed-72e.notion.site/item-25-5229df8e4e30416a9f4df26cd241486a?pvs=4)


 <br>

5장. 제네릭
- [x] 26. 로 타입은 사용하지 말라
- [x] 27. 비검사 경고를 제거하라
- [x] 28. [배열보다는 리스트를 사용하라](https://obtainable-poppyseed-72e.notion.site/item-28-27735e40dfd04d008ba7a9519a69575f?pvs=4)
- [x] 29. 이왕이면 제네릭 타입으로 만들라
- [x] 30. 이왕이면 제네릭 메서드로 만들라
- [x] 31. 한정적 와일드카드를 사용해 API 유연성을 높이라
- [x] 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라
- [x] 33. 타입 안전 이종 컨테이너를 고려하라

<br>

6장. 열거 타입과 애너테이션
- [x] 34. int 상수 대신 열거 타입을 사용하라
- [x] 35. [ordinal 메서드 대신 인스턴스 필드를 사용하라](https://obtainable-poppyseed-72e.notion.site/item-35-ordinal-f42d2d0a722e47299d0306caf6be4c25?pvs=4)
- [x] 36. [비트 필드 대신 EnumSet을 사용하라](https://obtainable-poppyseed-72e.notion.site/item-36-Enumset-e37d90983d12486db5772b9a476f8a5f?pvs=4)
- [x] 37. ordinal 인덱싱 대신 EnumMap을 사용하라
- [x] 38. [확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라](https://obtainable-poppyseed-72e.notion.site/item-38-ae085e6be7834fa6a1f7041ba81de3f3?pvs=4)
- [x] 39. 명명 패턴보다 애너테이션을 사용하라
- [x] 40. @Override 애너테이션을 일관되게 사용하라
- [x] 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라

<br>

7장. 람다와 스트림
- [x] 42. 익명 클래스보다는 람다를 사용하라
- [x] 43. 람다보다는 메서드 참조를 사용하라
- [x] 44. 표준 함수형 인터페이스를 사용하라
- [x] 45. [스트림은 주의해서 사용하라](https://docs.google.com/presentation/d/1pqAiPjIBzWVGbTeDtHi93APgRJIbGyo8/edit?usp=sharing&ouid=101177928260409286799&rtpof=true&sd=true)
- [x] 46. 스트림에서는 부작용 없는 함수를 사용하라
- [x] 47. 반환 타입으로는 스트림보다 컬렉션이 낫다
- [x] 48. 스트림 병렬화는 주의해서 적용하라

<br>

8장. 메서드
- [x] 49. [매개변수가 유효한지 검사하라](https://obtainable-poppyseed-72e.notion.site/item-49-1c9a5e09939744749ffdf851a44c5301?pvs=4)
- [x] 50. 적시에 방어적 복사본을 만들라
- [x] 51. [메서드 시그니처를 신중히 설계하라](https://obtainable-poppyseed-72e.notion.site/item-51-cf4b7bfdfacc4e44adad1578bb8ab29d?pvs=4)
- [x] 52. 다중정의는 신중히 사용하라
- [x] 53. 가변인수는 신중히 사용하라
- [x] 54. null이 아닌, 빈 컬렉션이나 배열을 반환하라
- [x] 55. 옵셔널 반환은 신중히 하라
- [x] 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라

<br>

9장. 일반적인 프로그래밍 원칙
- [x] 57. 지역변수의 범위를 최소화하라
- [x] 58. [전통적인 for 문보다는 for-each 문을 사용하라](https://obtainable-poppyseed-72e.notion.site/item-58-for-for-each-b534ca224ba14669914f5395a93a3166?pvs=4)
- [x] 59. 라이브러리를 익히고 사용하라
- [x] 60. 정확한 답이 필요하다면 float와 double은 피하라
- [x] 61. [박싱된 기본 타입보다는 기본 타입을 사용하라](https://obtainable-poppyseed-72e.notion.site/item-61-2ecd3c55d75a492289648f341aa18f54?pvs=4)
- [x] 62. 다른 타입이 적절하다면 문자열 사용을 피하라
- [x] 63. 문자열 연결은 느리니 주의하라
- [x] 64. 객체는 인터페이스를 사용해 참조하라
- [x] 65. [리플렉션보다는 인터페이스를 사용하라](https://obtainable-poppyseed-72e.notion.site/item-65-47ec68d7824c43428d3628b742dae0b2?pvs=4)
- [x] 66. [네이티브 메서드는 신중히 사용하라](https://obtainable-poppyseed-72e.notion.site/item-66-816a3933f7764b988446e6dca7b1e2f8?pvs=4)
- [x] 67. 최적화는 신중히 하라
- [x] 68. 일반적으로 통용되는 명명 규칙을 따르라

<br>

10장. 예외
- [ ] 69. 예외는 진짜 예외 상황에만 사용하라
- [ ] 70. 복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라
- [x] 71. 필요 없는 검사 예외 사용은 피하라
- [x] 72. 표준 예외를 사용하라
- [x] 73. [추상화 수준에 맞는 예외를 던지라](https://obtainable-poppyseed-72e.notion.site/item-73-10412371269d459e87e2f0743b694b91?pvs=4)
- [x] 74. [메서드가 던지는 모든 예외를 문서화하라](https://obtainable-poppyseed-72e.notion.site/item-74-a6711211aa0f4891bb570fa2b18c4c77?pvs=4)
- [x] 75. 예외의 상세 메시지에 실패 관련 정보를 담으라
- [x] 76. 가능한 한 실패 원자적으로 만들라
- [x] 77. 예외를 무시하지 말라

<br>

11장. 동시성
- [x] 78. [공유 중인 가변 데이터는 동기화해 사용하라](https://obtainable-poppyseed-72e.notion.site/item-78-e5c999b8ceea4ff0b9d3fc288eacb95b?pvs=4)
- [x] 79. 과도한 동기화는 피하라
- [x] 80. 스레드보다는 실행자, 태스크, 스트림을 애용하라
- [x] 81. wait와 notify보다는 동시성 유틸리티를 애용하라
- [x] 82. 스레드 안전성 수준을 문서화하라
- [x] 83. 지연 초기화는 신중히 사용하라
- [x] 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라

<br>

12장. 직렬화
- [ ] 85. 자바 직렬화의 대안을 찾으라
- [ ] 86. Serializable을 구현할지는 신중히 결정하라
- [ ] 87. 커스텀 직렬화 형태를 고려해보라
- [ ] 88. readObject 메서드는 방어적으로 작성하라
- [ ] 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라
- [ ] 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라

### 진행 방식
 - 매주 일요일 오후 9시 스터디 진행
 - 매 스터디마다 1인당 Item 1개씩 발표를 진행, 매 주마다 총 Item 4개씩 공부합니다. (Item 분량에 따라 유동적으로 갯수 결정, 통상적으로 4개)
 - 스터디가 끝나고 다음 스터디에 발표할 Item을 정합니다.
 - 매 스터디 전날 자정까지 발표 자료를 PR로 올립니다.
 - 발표가 끝나고 질문 시간을 갖습니다.
 - 질문과 그에 대한 답은 Issues를 통해서 남깁니다.
 - 발표나 자료에 대해서 궁금한 내용을 남겨주세요.

<br>

 - 각자 맡은 부분에 대해서 자료 업로드는 챕터 - 아이템 번호 의 구조로 남깁니다.
 - 이슈 작성시 [ItemXX] ~~ 의 구조로 합니다.
 - 발표 순서는 Item의 번호대로 합니다.
