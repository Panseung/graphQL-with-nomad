### API

- Application
- Programming
- Interface

interface란 상호작용할 수 있는 것을 뜻함 (ex: remote controller)

api란 개발자들이 애플리케이션과 상호작용 할 수 있는 수단과 같음





### REST api vs Graphql api

차이 : 버튼들이 어떻게 노출되어 있는지

REST api : 서버와 통신할 때 URL로 이루어짐

수많은 URL들로 이루어져 있으며 각각 모두 다른 작업을 실행



### REST api 문제점 두가지 == Graphql이 해결한 문제점 두가지

1. over-fetching : 필요 이상으로 너무 많은 data를 받는 것
2. under-fetching : 필요 한 data보다 적게 받는 것



### Graphql

- 단 하나의 request만으로 필요한 모든 data를 받을 수 있음
- 하나의 api에 하나의 request만 보냄
- graphiQL : graphql query를 쓰고 보낼 수 있게 해주는 browser tool
- 모든 data들이 type을 가지고 있음 -> 자동완성 가능 (이게 왜 인과인지는 잘 몰겠음)
- 연습사이트 : https://graphql.org/swapi-graphql
- 

