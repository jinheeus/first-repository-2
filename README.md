# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 오명수님
- 리뷰어 : 김지수


# PRT(Peer Review Template)

- [o]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**

- [o]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

      def Q1():
      answer = ''.join(random.sample('0123456789', 5))
      print('===숫자 야구 게임===')
      attempt = 0

      while True:
          guess = input('5가지 숫자를 입력하세요. / quit하면 loop 탈출')
          if guess == 'quit':
              break


- 숫자를 랜덤으로 돌려서 게임을 직접 탈출할 때까지 지속할 수 있는 부분이 핵심이라고 생각했습니다.
        
- [o]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
        
- [o]  **4. 회고를 잘 작성했나요?**
        
- [o]  **5. 코드가 간결하고 효율적인가요?**

        while True:
        guess = input('5가지 숫자를 입력하세요. / quit하면 loop 탈출')
        if guess == 'quit':
            break
        if len(guess) != 5 or not guess.isdigit():
            print('다시 입력하세요.')
            continue

        elif len(set(guess)) != 5:
            print('다시 입력해주세요. 서로 다른 5가지 숫자로 !')
            continue



# 회고(참고 링크 및 코드 개선)
```
명수님과 함께 한 그루님께서 전공자임에도 불구하고 함께 노력하며 확실히 코드를 이해하려고 하신 모습이 인상 깊었습니다.
또한, 저희 팀이 만든 코드와는 다르게 직접 게임을 탈출하기 전까지는 계속 새로운 숫자를 랜덤을 돌려서 지속할 수 있는 방식이 제일 기억에 남는 것 같습니다.
```
