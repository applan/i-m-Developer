# Range 
1M ~ 2M

# What?
네트워크 & DB 기본기 + 주력 언어 성능 이해

# Goal
- 기초 CS(네트워크, DB, OS) 지식을 탄탄하게
- 주력 언어(Java/Python)의 내부 동작 이해
- 기본기 기반의 성능 개선 경험 쌓기

# Process
## 1주차 ~ 2주차 : 네트워크 
### 공부
- HTTP/1.1 vs HTTP/2 vs HTTP/3 차이
- TCP 3-way handshake & 4-way termination
- DNS 동작, CDN 구조

### 실습 과제
- curl로 HTTP 요청 보내보고 응답 헤더 분석
- Nginx를 로컬에 띄우고 reverse proxy 구성

## 3주차 ~ 4주차 : DB & SQL 튜닝
### 공부
- Index 자료구조(B-Tree, Hash)
- 트랜잭션 격리 수준 (READ COMMITTED, SERIALIZABLE)
- 조인(Join) 동작 원리
### 실습 과제
- MySQL에서 EXPLAIN으로 쿼리 실행 계획 확인
- 인덱스 전후 속도 비교 실험

## 5주차 ~ 8주차 : 주력 언어 심화
### 공부
- 언어별 메모리 구조, GC, 동시성 처리
- 비동기 처리 패턴 (Java CompletableFuture / Python asyncio)
### 실습 과제
- 동일 로직을 동기 vs 비동기 구현 후 성능 비교
- 스트레스 테스트 (ab 또는 wrk 툴 사용)

# Question 
- HTTP Keep-Alive가 왜 성능을 높일까?
- 인덱스를 잘못 쓰면 왜 오히려 느려질까?
- GC 튜닝이 필요한 상황은 언제일까?