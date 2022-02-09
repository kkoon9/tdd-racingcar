## 요구사항
- [ ] 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- [ ] 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- [ ] 전진하는 조건은 0에서 9사이에서 random값을 구한 후 random값이 4이상일 경우 전진하고, 3이하의 값이면 멈춘다.

- [ ] 각 자동차에 이름을 부여할 수 있다. 자동차 이름은 5자를 초과할 수 없다.
- [ ] 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- [ ] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
- [ ] 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.

### 자동차
- [ ] 자동차는 전진할 수 있다.
- [ ] 자동차는 random값이 4 이상이면 움직인다.
- [ ] 자동차는 random값이 3 이하이면 멈춘다.
- [ ] 자동차의 random값이 음수이면 예외를 던진다.
- [ ] 자동차의 random값이 9 초과이면 예외를 던진다.
- [ ] 자동차는 이름을 가진다.
- [ ] 자동차의 이름은 5자를 초과하면 예외를 던진다.
- [ ] 자동차의 이름은 빈값(null 포함)이면 예외를 던진다.
- [ ] 자동차의 이름에 쉼표(,)를 포함하면 예외를 던진다.
- [ ] 자동차의 이름을 구분하는 구분자가 쉼표(,)가 아닐 경우 예외를 던진다.
- [ ] 자동차의 이름이 중복된다면 예외를 던진다.

### 레이스(경주)
- [ ] 이동 횟수가 숫자가 아니면 예외를 던진다.
- [ ] 이동 횟수가 빈값(null 포함)이면 예외를 던진다.
- [ ] 이동 횟수가 음수이면 예외를 던진다.  
- [ ] 자동차 간의 이동 거리를 가진다.
- [ ] 자동차 경주가 완료되면 우승자를 가려낸다.
- [ ] 우승자는 여러 명일 수 있다.
 