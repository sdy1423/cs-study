- 참고 https://gmlwjd9405.github.io/2018/09/21/rest-and-restful.html

## REST란

- "Representational State Transfer"의 약자
  - 자원을 이름으로 구분하여 해당 자원의 상태를 주고 받는 모든 것.
- HTTP URI를 통해 자원(Resource)을 명시하고, HTTP Method(POST, GET, PUT, DELETE)를 통해 해당 자원에 대한 CRUD Operation을 적용하는 것.
  - CRUD Operation
    - Create : 생성(POST)
    - Read : 조회(GET)
    - Update : 수정(PUT)
    - Delete : 삭제(DELETE)
    - HEAD : header 정보 조회(HEAD)

## REST 구성 요소

- 자원(Resource) : URI
- 행위(Verb) : HTTP Method
- 표현(Representation of Resource)

## REST 특징

- Server-Client
- Stateless
- Cacheable
- Layered System
- Code-On-Demand
- Uniform Interface

## REST API란

- REST 기반으로 서비스 API를 구현한 것

## REST API 설계 규칙

- 슬래시 구분자는 계층 관계를 나타내는데 사용한다.
- URI 마지막 문자로 슬래시를 포함하지 않는다.
- 하이픈(-)은 URI 가독성을 높이는 데 사용한다.
- 밑줄(\_)은 URI에 사용하지 않는다.
- URI 경로에는 소문자가 적합하다.
- 파일확장자는 URI에 포함하지 않는다.

## RESTful 이란

- 'REST API'를 제공하는 웹 서비스를 'RESTful'하다고 할 수 있다.
- REST를 REST 답게 쓰기 위한 방법.
