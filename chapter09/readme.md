# TDD 법칙 세 가지
실패하는 단위 테스트를 작성할 때까지 실제 코드를 작성하지 않는다.
컴파일은 실패하지 않으면서 실행이 실패하는 정도로만 단위 테스트를 작성한다.
현재 실패하는 테스트를 통과할 정도로만 실제 코드를 작성한다.


# 깨끗한 테스트 코드 유지하기
단위 테스트는 코드에 유연성, 유지보수성, 재사용성을 제공하는 버팀목


# 테스트 당 assert 하나
개념 당 assert 문 수를 최소로 줄여라
테스트 당 개념 하나만 테스트하라


# F.I.R.S.T.  - 근본이 없다 by. 성동

Fast 빠르게
-테스트는 빨라야한다. 느리면 자주 못돌려서 결국 코드 품질이 망가진다

Independent 독립적으로
-각 테스트는 서로 의존하면 안된다. 의존하면 하나가 실패하면 나머지도 잇달아 실패하므로 원인을 진단하기 어려워진다.

Repeatable 반복가능하게
-어떤 환경에서도 반복 가능해야한다. 실제 환경, QA 환경, 노트북 환경에서도 실행 가능해야한다.

Self-Validating 자가검증하는
-테스트는 bool 값으로 결과를 내야한다.테스트가 스스로 성공과 실패를 가늠하지 않는다면 판단은 주관적이 되며 지루한 수작업 평가가 필요하게 된다.

Timely 적시에
-단위 테스트는 테스트하려는 실제 코드를 구현하기 직전에 구현한다.
실제 코드를 구현한 다음에 테스트 코드를 만들면 실제 코드가 테스트 가 불가능 하도록 실제 코드를 설계할수도 있다.

