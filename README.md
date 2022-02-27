<p align="center">
    <img width="200px;" src="https://raw.githubusercontent.com/woowacourse/atdd-subway-admin-frontend/master/images/main_logo.png"/>
</p>
<p align="center">
  <img alt="npm" src="https://img.shields.io/badge/npm-6.14.15-blue">
  <img alt="node" src="https://img.shields.io/badge/node-14.18.2-blue">
  <a href="https://edu.nextstep.camp/c/R89PYi5H" alt="nextstep atdd">
    <img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fedu.nextstep.camp%2Fc%2FR89PYi5H">
  </a>
</p>

<br>

# 지하철 노선도 미션
[ATDD 강의](https://edu.nextstep.camp/c/R89PYi5H) 실습을 위한 지하철 노선도 애플리케이션

<br>

---

## 4단계 제약사항
- 정차 시간은 무시한다.
- 경로 조회 시 막차 시간은 무시한다.
- 환승 시간은 무시한다.
- 상행선, 하행선은 같은 시간간격으로 운행한다.

## 추가사항
- `가장빠른도착시간`경로 로 조회하면 `도착시간`은 가장빠른도착시간 경로 상의 도착시간으로 나온다.
- `최단거리`경로로 조회하면 `도착시간`은 최단거리 경로 상의 도착시간으로 나온다.
- duration 은 기존과 동일하게 배차시간 고려하지 않고 순수하게 역간 이동시간의 총합으로 나온다.

<br>

---

## 🚀 Getting Started

### Install
#### npm 설치
```
cd frontend
npm install
```
> `frontend` 디렉토리에서 수행해야 합니다.

### Usage
#### webpack server 구동
```
npm run dev
```
#### application 구동
```
./gradlew bootRun
```
