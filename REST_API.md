# REST API
## REST 구성
* 자원(Resource) -> URI (Uniform Resorce Identifier)
* HTTP메서드 -> 작업에 대한 정의 (C/R/U/D)
* 표현(Representation) -> Client 와 Server 간 자원의 상태를 전달하는 방법으로 JSON, XML 등의 형식을 사용한다.
  (ex) URI + GET/POST/PUT/DELETE

## API란?
* Application Programming Interface
* 다른 소프트웨어 어플리케이션에서 사용할 수 있는 기능을 제공하는 인터페이스
* 어플리케이션 간 데이터를 교환하고 상호 작용하도록 도움을 줌
  ### Private API
  * 비공개 API
  * 주로 기업 내부 시스템에서의 통신을 위해 사용
  ### Public API
  * 공개 API
  * 대부분이 REST 방식으로 작성되어 있음
## REST API (REST+API)
* 기존의 전송방식과는 달리 서버는 요청으로 받은 리소스에 대해 순수한 데이터를 전송
* 기존의 GET/POST 외에 PUT,DELETE 방식을 사용하여 리소스에 대한 CRUD 처리 가능
