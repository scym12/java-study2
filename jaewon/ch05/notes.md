예외, 단정, 로깅

<테스트>
테스트 방법의 1
- 직접 서버를 띄워서 들어가보고 테스트해본다

테스트 방법의 2
junit
-assertEquals(기대값, 실제값);
-assertThat(실제값, is(값));
-@Test(expected = Exceptionname.class)
-서버에 직접 통신을 할수도 있다.
-의미 있는 테스트케이스 만들기
-테스트주도개발
    1. 존재하지 않는 메소드를 먼저 테스트로 만든다.
    2. 메소드를 만든다.
    3. 테스트를 돌린다.
    4. 통과하면 리팩토링을 진행한다.
코드를 작성하면 기록이 남고, 예상하지 못한 문제를 찾을 확률이 높다.
