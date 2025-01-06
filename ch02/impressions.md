일급 객체를 활용함으로써 코드들이 간결해지고 변화하는 요구사항에 쉽게 대응할 수 있게 되는 작업을 코드로 연습하며 경험하니 이해가 잘 됐다. 그러나 이렇게 추상화를 하면 할수록 코드를 이해하는데 어려움을 겪을 수 있을 것 같다는 생각이 들었다. 그래서 이 부분에 대해서는 팀원들과 의논해서 팀의 상황에 맞게 끊어내는 것이 필요해 보인다.

확장 가능성을 고려한 코드와 유연한 코드의 딜레마에서 기준을 잡는 것은 언제나 정답이 없는 것 같다.

---

### 동작 파라미터화 개념 및 장점

1. **동작 파라미터화의 개념**
    
    - 메서드 내부적으로 다양한 동작을 수행할 수 있도록 코드를 메서드 인수로 전달하는 기법.
2. **동작 파라미터화를 활용한 장점**
    
    - 변화하는 요구사항에 더 잘 대응할 수 있는 코드를 구현할 수 있다.
    - 나중에 엔지니어링 비용을 줄일 수 있다.
3. **코드 전달 기법**
    
    - 동작을 메서드의 인수로 전달할 수 있는 방식으로 유연성을 제공.