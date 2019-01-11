# Factory Pattern
> 팩토리 패턴은 크게 팩토리 메소드 패턴과 추상 팩토리 패턴으로 나뉜다. <br>
- 전자는 객체를 생성하기 위한 하나의 인터페이스만 정의하고, 서브클래스에서 이를 구현하여 어떤 객체를 생성할지 결정하는 패턴이다. <br>
- 후자는 팩토리용 인터페이스에 여러 개의 메소드를 선언하고, 하위 팩토리 클래스는 인터페이스 메소드를 구현해서 어떤 객체를 생성할지 결정하는 패턴이다.