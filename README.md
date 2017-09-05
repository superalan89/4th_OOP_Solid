# OOP_Solid
OOP  설계에 대해서 알아봅니다

## SRP - Single Responsibility Principle
단일 책임의 원칙
1. 하나의 클래스는 하나의 역할만 맡는다
2. 코드 변경의  영향이 미치는 범위가 최소화 된다.


## OCP - Open Closed Principle
개방 폐쇄의 원칙
1. 확장에 열려있고 수정에 닫혀 있다.
2. 클래스간 통신을 위한 인터페이스가 확정되면 수정하지 않는다.

## LSP - Liskov Substitution Principle
리스코프 교체
1. 파생 클래스는 상위 클래스로 대체 가능해야 한다.
2. 상위 클래스의 기능을 파생 클래스가 포함해야 한다. 


## ISP - Interface Segregation Principle
인터페이스 분리
1. 특화된 여려개의 언터페이스가 범용 인터페이스 한개보다 낫다.

## DIP - Dependency Inversion Principle
의존 관계 역전
1. 추상화 된것은 구체적인 것에 의존하면 안된다.