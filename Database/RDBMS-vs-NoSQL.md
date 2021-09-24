# RDBMS vs NoSQL

<br>

## 💡 RDBMS
> Relational DataBase Management System. 관계형 데이터베이스를 생성, 수정, 삭제 관리할 수 있는 소프트웨어

&nbsp; &nbsp; 관계형 데이터베이스는 현재 가장 많이 사용되고 있는 데이터베이스의 한 종류다. 관계형 데이터베이스는 테이블들이 관계를 맺고 모여있는 집합체로 이해할 수 있다. 이러한 테이블 간 관계를 나타내기 위해 **외래 키(foreign key)** 를 사용하고 외래 키를 통해 테이블 간 Join이 가능하다. 정규화 과정을 통해서 데이터 중복을 최소화한다. SQL이란, 이러한 RDBMS의 데이터를 관리하기 위해 설계된 특수 목적의 프로그래밍 언어이다.


RDBMS를 정리하면 다음 특징이 있다.
- 데이터는 정해진 데이터 **스키마**에 따라 테이블에 저장된다.
- 테이블들은 **관계**를 가지고 있으며 이를 FK를 이용하여 설정합니다.<br>

<br>

## 💡 NoSQL
> Not Only SQL. 관계형 데이터베이스가 아닌 다른 형태의 데이터 저장 기술

&nbsp; &nbsp; NoSQL은 RDBMS의 가장 큰 특징이라고 했던 스키마와 관계가 모두 없다. 스키마가 없기 때문에 **유연한 형태로 데이터를 저장**한다. 관계를 정의 하지 않기 때문에 테이블 조인도 존재 하지 않는다. 때문에 데이터는 애플리케이션이 필요로 하는 형식으로 저장된다. 덕분에 복잡한 조인을 할 필요도 없으며 조회 성능이 빠르다. 하지만 **데이터가 여러 컬렉션에 중복** 되어 있기 때문에 수정 시 모든 컬렉션에서 수행해야 할 가능성이 있다. 

<br>

## 💡 RDBMS vs NoSQL : Scaling
> 데이터베이스 서버의 확장성은 '수직적' 확장과 '수평적' 확장으로 나누어진다.

관계형 데이터베이스는 일반적으로 수직적 확장만 지원한다.
- 수직적 확장 <br>
    : 단순히 데이터베이스 서버의 성능을 향상시킨다. (ex. CPU 업그레이드)<br>
- 수평적 확장<br>
    : 더 많은 서버가 추가되고 데이터베이스가 전체적으로 분산된다. <br>


<br>

## 💡 RDBMS vs NoSQL

<img src="https://user-images.githubusercontent.com/70243735/134645339-e6dfa5fa-9d10-4c06-902c-44f6d8d22ce3.png" width="800px">


<br>

&nbsp; &nbsp; 선택 경우는 제시 방법이지 완전한 정답으로 정해져 있는 것은 아니다. RDBMS를 선택해서 복잡한 JOIN문을 만들지 않도록 설계하여 단점을 없앨 수도 있고 NoSQL을 선택해서 중복 데이터를 줄이는 방법으로 설계해서 단점을 없앨 수도 있다. RDBMS와 NoSQL은 대체될 수 있는 것이 아니고, 각각 필요한 시점에 적절히 선택해서 사용해야 한다. 둘 다 같이 쓰는 상호보완적인 존재가 될 수도 있다.


<br>
<br>