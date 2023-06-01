# AIFFEL Campus Online 4th Code Peer Review Templete

- 코더 : 이영빈, 허남철
- 리뷰어 : 조웅제


# PRT(PeerReviewTemplate) 

각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.

- [x] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?

- [x] 주석을 보고 작성자의 코드가 이해되었나요?

  > 위 항목에 대한 근거 작성 필수

  ```
  - [x] # 1. 플레이어수 입력
  
    n = int(input("플레이어수 를 입력하세요"))
    n_list = [0 for _ in range(n)]
  
  # 순서구현
  
  start = 0
  while True:
      result = False
      a = start % n # i 차례번호
      value_dice = roll_dice()
      board(a,n_list, value_dice)
      
  
  # 2. 차례로 주사위 던지기
  
  # 3. 이동 경로 출력
  
  # 4. 승리 조건 판단
  
      for i in n_list:
          if i >= 100 :
              print(f"{chr(a+65)}가 승리")# 승리문 출력
              result = True
      if result:
          break
      start += 1
  
  ```

  

- [x] 코드가 에러를 유발할 가능성이 없나요?

  >위 항목에 대한 근거 작성 필수

- [x] 코드 작성자가 코드를 제대로 이해하고 작성했나요?

  > 위 항목에 대한 근거 작성 필수

- [x] 코드가 간결한가요?

  > 위 항목에 대한 근거 작성 필수
