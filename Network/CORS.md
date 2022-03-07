# CORS 정책

교차 출처 리소스 공유(Cross-Origin Resource Sharing)으로 출처(URL, 포트, 호스트)등이 다른 경우에 접근할 수 있는 권한을 부여하도록 브라우저에게 알려주는 정책입니다.

예를 들어 `http://baejiu.com`에서 `http://baejiu.com/data` 로 요청을 하게 된다면 보안상의 이유로 브라우저는 스크립트에서 시작한 교차 출처 HTTP 요청을 제한합니다.

API를 사용하는 웹 애플리케이션은 자신의 출처와 동일한 리소스만 불러올 수 있으며, 다른 출처의 리소스를 불러오기 위해서는 서버츨 응답에서 접근 권한을 주는 CORS 헤더를 포함해 해결할 수 있습니다.
Node.js의 경우 cors 모듈을 사용할 수 있습니다.

[참고]  
[교차 출처 리소스 공유(CORS)](https://developer.mozilla.org/ko/docs/Web/HTTP/CORS)
