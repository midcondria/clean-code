# 시스템 제작과 시스템 사용을 분리하라
초기화 지연(lazy initialization) 기법 사용 시 장점도 있지만 단점도 있다.
일반 런타임 로직에 객체 생성 로직을 섞어놓은 탓에 service 가  null일때 아닐때 모두 테스트해야하므로 책임이 두개이므로 작게나마 단일 책임 원칙을 깬다

1. Main 분리
2. 추상 팩토리
3. 의존성 주입

등의 객체 지향적인 설계로 의존성을 해소한다.


# 확장
관심사를 적절히 분리해 관리한다면 소프트웨어 아키텍처는 점진적으로 발전할 수 있다.
ex) AOP
