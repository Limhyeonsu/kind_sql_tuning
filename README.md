# 친절한 SQL튜닝

## [1. SQL 처리 과정과 I/O](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/01.SQL%EC%B2%98%EB%A6%AC%20%EA%B3%BC%EC%A0%95%EA%B3%BCIO.md)
* SQL 파싱과 최적화
* SQL 공유 및 재사용
* 데이터 저장 구조 및 I/O 메커니즘

## [2. 인덱스 기본](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/02.%EC%9D%B8%EB%8D%B1%EC%8A%A4.md)
* 인덱스 구조 및 탐색
* 인덱스 기본 사용법
* 인덱스 확장기능 사용법

## [3. 인덱스 튜닝](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/03.%EC%9D%B8%EB%8D%B1%EC%8A%A4%ED%8A%9C%EB%8B%9D.md)
* 테이블 액세스 최적화
* 부분범위 처리 활용
* 인덱스 스캔 효율화
* 인덱스 설계

## [4. 조인 튜닝](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/04.NL%EC%A1%B0%EC%9D%B8.md)
* NL 조인
* 소트 머지 조인
* 해시 조인
* 서브쿼리 조인

## [5. 소트 튜닝](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/05.%EC%86%8C%ED%8A%B8%ED%8A%9C%EB%8B%9D.md)
* 소트 연산에 대한 이해
* 소트가 발생하지 않도록 SQL 작성
* 인덱스를 이용한 소트 연산 생략
* SortArea를 적게 사용하도록 SQL 작성

## [6. DML 튜닝](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/06.DML%ED%8A%9C%EB%8B%9D.md)
* 기본 DML 튜닝
* Direct Path I/O 활용
* 파티션을 활용한 DML 튜닝
* Lock과 트랜잭션 동시 제어

## [7. SQL 옵티마이저](https://github.com/Limhyeonsu/kind_sql_tuning/blob/main/07.SQL%20%EC%98%B5%ED%8B%B0%EB%A7%88%EC%9D%B4%EC%A0%80.md)
* 통계정보와 비용 계산 원리
* 옵티마이저에 대한 이해

## 부록. SQL 분석 도구