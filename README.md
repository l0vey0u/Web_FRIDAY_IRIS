[contributors-shield]: https://img.shields.io/github/contributors/l0vey0u/Infra_FRIDAY_IRIS?style=flat-square
[contributors-url]: https://github.com/l0vey0u/Infra_FRIDAY_IRIS/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/l0vey0u/Infra_FRIDAY_IRIS.svg?style=flat-square
[forks-url]: https://github.com/l0vey0u/Infra_FRIDAY_IRIS/network/members
[stars-shield]: https://img.shields.io/github/stars/l0vey0u/Infra_FRIDAY_IRIS?style=flat-square
[stars-url]: https://github.com/l0vey0u/Infra_FRIDAY_IRIS/stargazers
[issues-shield]: https://img.shields.io/github/issues/l0vey0u/Infra_FRIDAY_IRIS.svg?style=flat-square
[issues-url]: hhttps://github.com/l0vey0u/Infra_FRIDAY_IRIS/issues
[license-shield]: https://img.shields.io/github/license/l0vey0u/Infra_FRIDAY_IRIS.svg?style=flat-square
[license-url]: https://github.com/l0vey0u/Infra_FRIDAY_IRIS/blob/main/LICENSE

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache 2.0 License][license-shield]][license-url]

<h1 align="center"> I R I S </h1>
<p align="center">
  <img src="https://github.com/l0vey0u/Infra_FRIDAY_IRIS/blob/main/team_logo.png" width="200" alt="team logo">
</p>

## 개발 배경

[![음식물 처리비용의 실태](https://i.ytimg.com/vi/g5WXqBOQYzc/original.jpg)](https://youtu.be/g5WXqBOQYzc)

많이 주문해서 돈이 많이 들고 넘치게 만들어서 잔반이 많아지고 그 많은 것을 처리하려고 돈이 또 많이 드는 이런 악순환 어디서 시작된 것일까?

주말 저녁, 병영 식당에 가보면 먹는 사람은 확연히 적은데 만들어져있는 밥은 평소와 변함이 없다.

이로인해 **잔식**(배식대에 남은 음식)이 많이 발생한다.

하지만 조리병은 공식 식수인원(총원 - 휴가자, 출타자, .... )에 맞게 조리했을 뿐이다.

실제로 섭취하는 인원 수를 제대로 계산하면 해결할 수 있지 않을까?

식수 인원이 매일 다른 일반 식당과 달리 병영식당과 같은 단체급식소는 **일정한 식수인원의 패턴**만 알아낸다면 효과적인 예측이 가능하다.
이를 실현하기 위해 여러 서비스를 만들고 각 서비스 간의 유기적인 연결을 통해 능동적인 분석 및 예측을 하게 하였다. 

## 기능 설계

 -  추후 추가 예정

## 컴퓨터 구성 / 필수 조건 안내 (Prerequisites)

* Docker Engine 버젼 19.03 이상 
* Docker Compose 버젼 1.27.4 이상

## 기술 스택 (Technique Used)

### Server(back-end)

 -  Nginx 
 -  uWSGI
 -  MYSQL

### front-end

 -  Flask
 -  SQLAlchemy

## 설치 안내 (Installation Process)

0. Docker 미 설치 시 해당 글을 참고하여 설치

- ["Install Docker at ubuntu 20.04"](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04)
- ["Install Docker at Windows 10"](https://www.wsgvet.com/ubuntu/180?sfl=wr_subject%7C%7Cwr_content&stx=NAS&sst=wr_hit&sod=desc&sop=and&page=1)

1. Docker Compose 미 설치시 해당 스크립트 실행

```bash
$ ./install_docker-compse.sh
```

## 프로젝트 사용법 (Getting Started)

- 추후 추가 예정

## 팀 정보 (Team Information)

- Pyo Sehun (kimpyo9357@naver.com), Github Id: kohari0912
- Jeong Deokho (duckhoim@naver.com), Github Id: l0vey0u

## 저작권 및 사용권 정보 (Copyleft / End User License)

 * [Apache 2.0](https://github.com/l0vey0u/Infra_FRIDAY_IRIS/blob/main/LICENSE)
