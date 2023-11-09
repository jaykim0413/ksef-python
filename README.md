# KSEF Python Source Code

## Info

- `m`개의 숫자가 동일한 확률로 나오는 주사위를 가지고 2명의 사람이 게임을 할 때, `n`번 던졌을 때 나오는 `m^n`가지의 조합들 중에 `Player 1`이 하나의 조합을 선택하고 `Player 2`도 하나의 조합을 선택할 때, `Player 1`이 `Player 2`에 대해서 승리할 확률을 연산하는 프레임워크
- `Markov Chain`을 활용한 trial이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램
- `Martingale`을 활용한 trial이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램

## Commit Titles

1. Class #2 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델

2. Homework #2 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - 1

3. Homework #2 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - 2

4. Homework #2 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - 3

5. Class #3 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델

6. Class #4 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델

7. Homework #4 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - 1

8. Homework #4 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - Revised

9. Extra - 앞서 제작한 두 모델의 결과물을 기록하는 `.txt` 파일 추가 

10. Homework #4 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - 2

11. Homework #4 - 등장할 확률이 일정한 m개의 문자 중에 하나의 문자를 뽑는 `trial`을 두 명의 `player`가 할 때, `length n`의 `case`가 다른 `length n`의 `case`에 대하여 이길 확룰을 연산하는 모델 작성하기 - 3

12. Extra - `.gitignore` 파일 추가 - 1

13. Extra - `.gitignore` 파일 추가 - 2

14. Class #5 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램

15. Homework #5 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기 - 1

16. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기

17. Extra - 새로운 프로그램의 결과를 기록하는 `.txt` 파일 추가

18. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.txt` - 1

19. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.txt` - 2

20. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.csv`, 기존 기록 파일 용량 초과하여 삭제 - 1

21. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.csv`, 기존 기록 파일 용량 초과하여 삭제 - 2

22. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.csv` - 1

23. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.csv` - 2

24. Homework #6 - `Markov Chain`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 `markov_chain_results.csv` - 3

25. Homework #7 - `Martingale`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, **File name**: `KSEF_Martinagle_ver_1.0.0.ipynb`

26. Extra - 기존에 결과 기록 파일들을 폴더에 정리

27. Homework #7 - `Martingale`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, 결과값 추가 기록 **Folder name**: `martingale_results`

28. Extra - Formated Commit Titles

29. Homework #8 - `Martingale`을 활용한 `trial`이 나올 때까지의 `E(X)` 기댓값을 구하는 프로그램 작성하기, `create_cases` 함수의 연산과정을 직접 `append`하는 과정에서 파이썬의 [itertools](["https://docs.python.org/3/library/itertools.html"]) 패캐지의 `product` 함수를 사용하여 연산 소요 시간 단축

30. Homework #9 - `Conway's Algorithm`과 `Martingale`을 활용한 `Penney's Game`에서 player 1이 player 2에 대해서 각각 선택한 패턴에 따라 승리할 확률을 기록한 표를 구하는 프로그램 작성하기, `conway_algorithm_results` 폴더에 동전을 가지고 문자열 길이가 2부터 7인 경우까지의 승리 확률 기록 파일 `.csv` 형식으로 저장

31. Homework #9 - `conway_algorithm_results` 폴더에 동전을 가지고 문자열 길이가 2부터 7인 경우까지의 승리 확률 기록 파일 `.csv` 형식으로 저장 - 1