# 순열

- 순열(Permutation)이란, 순서가 정해진 임의의 집합을 다른 순서로 섞는 것.  
  [1 , 2 , 3]이 있다고 가정하면 [1 , 3 , 2]같이 다른 순서로 섞는 연산을 말합니다.
  또한 n개의 집합중 n개를 고르는 순열의 갯수는 n! 이라는 규칙을 가지고 있습니다.

  예를들어, (1, 2, 3) 세 가지 중에 만들 수 있는 3자리 자연수는 총 몇개일까 세어보면  
  123, 132, 213, 231, 312, 321 총 6가지 이고 (1, 2, 3)을 이용해 만들 수 있는 1자리 자연수는  
  총 3가지입니다.

  3자리 자연수의 경우 3개중에 3개를 뽑게 되는 것이라 3!이 되어서 6이되고  
  1자리 자연수의 경우는 3개중 1개를 뽑는 것이라 1이됩니다.

  이것을 공식으로 정리하면 nPr 로 나타낼 수 있는데 n! / (n - r)! 로 풀어서 쓸 수 있습니다.  
  3개중 3개를 뽑는다면 3! / (3 - 3)! 이고 3개중 1개를 뽑으면 3!/(3 - 1)! 입니다.
