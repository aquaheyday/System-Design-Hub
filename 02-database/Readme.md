# Database

웹 서버(웹/모바일 트래픽 처리) 와 데이터베이스 서버(데이터 처리) 르ㄹ 분리하면 각각을 독립적으로 확장할 수 있다.

관계형 데이터베이스(Relational DataBase, RDB)
관계형 데이터베이스 시스템(Relational DataBase Managenment System, RDBMS)라고도 부른다. RDBMS 중 유명한 것으로는 MySQL, 오라클, PostgreSQL 등이 있다.
관계형 데이터베이스는 자료를 테이블과 열, 컬럼으로 표현한다.
**SQL을 사용하면 여러 테이블에 있는 데이터를 그 관계에 따라 조인(join) 연산을 하여 합칠 수 있다.**

비-관계형 데이터베이스
비 관계형 데이터베이스는 NoSQL이라고도 부른다. 대표적인 것은 CouchDB, Neo4j, Cassandra, HBase, Amazon DynamoDB등이 있다.
NoSQL은 네 부류로 나눌 수 있는데, 키0값 저장소(key-value store), 그래프 저장소(graph store), 컬럼 저장소(column store), 문서 저장소(document store) 가 있다.
**비 관게형 데이터베이스는 일반적으로 조인 연산은 지원하지 않는다.**

대부분의 시스템에서는 관계형 데이터베이스가 사용된다. 아래의 내용과 같은 조건이 필요할 때는 비-관계형 데이터베이스가 좋은 선택일 수 있다.

- 낮은 응담 지연시간(latency)이 필요
- 다루는 데이터가 비정형(unstructured) 일 때
- 데이터(json, yaml, xml 등)르ㄹ 직렬화하거나(serialize), 역직렬화(deserial-ize) 할 수 있기만 하면 될 때
- 아주 많은 양의 데이터를 저장할 필요가 있을 때
