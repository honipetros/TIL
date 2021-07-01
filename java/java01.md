변수 -하나의 값을 저장하기 위한 공간
상수 - 한번만 값을 저장 가능한 변수
변수는 변경 가능 하지만 상수는 변경 불가
리터럴 - 그 자체로 값을 의미 하는것 = 기존의 상수
 상수는 final 을 붙이면 상수 가 된다
  int score = 100;
  score = 200;  출력하면 200으로 변경 되지만
  final score = 100;
  score = 200; 출력하면 에러가 나온다  why? 변수가 아니라 final 붙어 상수가 됬기 때문에
  final int MAX_VALUE; // 정수형 상수 MAX_VALUE를 선언
 MAX_VALUE = 100; // OK. 상수에 처음으로 값 저장
 MAX_VALUE = 200; // 에러. 상수에 저장된 값을 변경할 수 없음
 종류   리터럴     접미사   
논리형    false, true                    없음
정수형    123, 0b0101, 077, 0xFF, 100L   L
실수형    3.14, 3.0e8, 1.4f, 0x1.0p-1    f, d
문자형    'A', '1', '\n'                 없음
문자열    "ABC", "123", "A", "true"      없음
int oct =010;  // 8진수  10진수로 8
int nex =ox10; // 16진수  10진수로 16
          ##  문자 문자열 리터널 문자열 결합
          
          System.out.println(""+7+7);
          System.out.println(7+7+"");
          +빨강
            +파랑 
              +녹색



 
 
