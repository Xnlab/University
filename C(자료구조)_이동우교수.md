Chapter1
========
프로그램(program)
 - 자료(data), 자료구조(data structure)
 - 알고리즘(algorithm) : 표현/기술 방법의 종류

데이터타입(data type), 추상데이터타입(abstract data type)
 - 정보은닉

성능분석
 - 실시간 수행측정, 시간복잡도, 공간복잡도
 - 빅오 표기법

C언어 표기법
 - #define
 - Typedef
 - struct
<hr/>

알고리즘
--------
- 입력 : 0개 이상의 입력이 존재해야 한다
- 출력 : 1개 이상의 출력이 존재해야 한다
- 명백성 : 각 명령어의 의미는 모호하지 않고 명확해야 한다
- 유한성 : 한정된 수의 단계 후에는 반드시 종료되어야 한다
- 유효성 : 각 명령어들은 실행 가능한 연산이어야 한다.

기술 방법
 - 영어나 한국어와 같은 자연어
 - 흐름도(flow chart)
 - 의사 코드(pseudo-code)
 - C와 같은 프로그래밍 언어

자료
----
 - 기초 자료형 : char, int, float, double
 - 파생 자료형 : 배열, 포인터
 - 사용자 정의 자료형 : 구조체, 공용체, 열거형

데이터 타입
 - 데이터의 집합과 연산의 집합

추상 데이터 타입
 - 데이터 타입을 추상적(수학적)으로 정의한 것
 - 데이터나 연산이 *무엇(what)* 인가는 정의되지만 데이터나 연산을 *어떻게(how)* 컴퓨터 상에서 구현할 것인지는 정의되지 않음

빅오 표기법
 - 자료의 개수가 많은 경우에는 차수가 가장 큰 항이 가장 영향을 크게 미치고 다른 항들은 상대적으로 무시될 수 있다
 - 시간복잡도 함수에서 가장 영향을 크게 미치는 항만을 고려하면 충분하다

Chapter1_과제
-------------
Create(x) : 집합 x를 생성한다

Insert(x, y) : 집합 x에 원소 y를 저장한다

Remove(x, y) : 집합 x에서 원소 y를 제거한다

Is_In(x, y) : 집합 x에 원소 y가 존재하는지 확인한다

Union(x, y) : 집합 x와 집합 y의 합집합을 구한다

Intersection(x, y) : 집합 x와 y의 교집합을 구한다

Difference(x, y) : 집합 x와 y의 차집합을 구한다

<hr/>

Chapter2
========
순환(recursion), 반복(iteration)
순환 알고리즘, 반복 알고리즘
활성 레코드(activation record), 시스템 스택
순환 알고리즘의 구조
순환의 원리
 - 분할 정복(devide and conquer)
순환 알고리즘과 반복 알고리즘의 성능 비교
 - factorial
 - 거듭 제곱
 - 피보나치 수열
 - 하노이 탑

순환이란?
 - 알고리즘이나 함수가 수행 도중에 자기 자신을 다시 호출하여 문제를 해결하는 기법
 - 문제의 정의자체가 *순환적으로 되어 있는 경우* 에 적합한 방법

