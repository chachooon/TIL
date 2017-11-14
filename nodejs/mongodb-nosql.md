 ^2017-11-14^

#### 1. NoSQL 

NoSQL이란 SQL을 사용하지 않는 비관계형 데이터 베이스를 말한다.<br>관계형 데이터베이스는 시스템의 신뢰도를 높이지만 SQL문을 읽어들이고 실행하는데 많은 리소스가 필요, 성능이 떨어지기쉽다.  반면에 NoSQL은 성능을 최우선시, 자바스크립트 객체를 그대로 저장할수 있어서 노드에서 데이터를 저장하기에 좋다.  실시간 처리, 대용량 트래픽 필요한 메시징시스템, 클라우드 서비스로 서버를 구성하는 경우 성능이 좋은 NoSQL을 사용.<br>

설치하기

```bash
$ brew install mongodb
$ mongod --dbpath /Users/<username>/<foldername>
```

쉘에서 실행하기

```bash
$ mongo
>
```
