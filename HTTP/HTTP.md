# HTTP 🌿

TCP : HTTP/1.1, HTTP/2
UDP : HTTP/3
현재는 HTTP/1.1 주로 사용 

HTTP 특징
* 클리이언트/서버 구조  
    - 클라이언트와 서버는 분리 되어 있으므로 클라이언트, 서버가 각각 독립적으로 진화 할수 있음.
* 무상태 프로토콜(Stateless) (<-> Stateful 상태유지 연결성)    
    - 서버가 클라이언트의 상태를 보존 하지 않는다  
    - 장점: 서버 확장성이 높음(스케일 아웃/수평확장에 유리)  
    - 단점: 클라이언트가 추가 데이터 전송  
* 비연결성  
    - 장점: 서버의 자원을 절약 할 수 있음(최소한의 자원으로 서버를 유지)  
    - 단점 : 1. TCP/IP 연결을 새로 맺어야 함  
             2. 웹 브라우저로 사이트를 요청하면 수 많은 3. 자원들이 함께 다운로드  
             4. 지금은 HTTP **지속 연결**로 해결
* HTTP 메세지
* 단순함, 확장 가능 


[출처](모든 개발자를 위한 HTTP 웹 기본 지식)