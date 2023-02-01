# HTTP

목차
- 모든 것이 HTTP
- 클라이언트 서버 구조
- Stateful, Stateless
- 비연결성(connectionless)
- HTTP 메세지


## 모든 것이 HTTP
HTTP(HyperText Transfer Protocol)로 출발
지금은 모든 것을 HTTP메세지에 담아서 전송

- HTML, TEXT
- IMAGE, 음성, 영상, 파일
- JSON, XML(API)

거의 모든 형태의 데이터 전송이 가능 </br>
서버 간에 데이터를 주고받을 때도 대부분 HTTP를 사용한다.


### HTTP의 역사

- HTTP/0.9 1991년 : GET 메서드만 지원, HTTP 헤더 X
- HTTP/1.0 : 1996년 : 메서드, 헤더 추가
- HTTP/1.1 1997년 : 가장 많이 사용, 우리에게 가장 중요한 버전
    - RFC2068(1997) -> RFC2616(1999) -> RFC7230~7235(2014)
- HTTP/2 2015년 : 성능 개선
- HTTP/3 진행중 : TCP대신에 UDP사용, 성능 개선 


### 기반 프로토콜

- TCP : HTTP/1.1, HTTP/2
- UDP : HTTP/3
- 현재 HTTP/1.1 주로 사용


### HTTP 특징

- 클라이언트 서버 구조
- 무상태 프로토콜(stateless), 비연결성
- HTTP 메세지
- 단순함, 확장 가능
