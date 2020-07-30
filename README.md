# Spring Web HTTPS and HTTP2
keytool 을 이용한 RSA 인증서 생성<br>
properties 파일을 이용한 HTTPS와 HTTP2.0 설정<br>
curl로 서버 동작 확인 curl -I -k --http2 http(s)://localhost:8088/hello<br>
-k 는 공인받은 인증서가 아니라 개인생성한 인증서 사용의 경우 주는 옵션
