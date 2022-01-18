- 딥빡치네. ... --

- 스프링 jpa 로 자주 쓰는 라이브러리 lombok 과 jackson 에서 알수없는 에러가 생겼다
- 어제까지 문제없이 실행되던 로그인에서 typeerror가 발생 lombok

```
com.fasterxml.jackson.databind.exc.InvalidDefinitionException
```

- model 클래스에 @NoArgsConstructor 과 @AllConstructor를 넣어줘서 해결

### 짤막메모

- @NoArgsConstructor 란?
  - jackson library가 빈 생성자가 없는 모델을 생성하는 방법을 모르기 때문에 Dto 클래스에 빈 생성자를 추가해주어야 한다.
- @AllConstructor 란?
