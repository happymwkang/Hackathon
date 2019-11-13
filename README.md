
## Shinhan Hackathon 사전 안내

---

### 1. 해커톤 API 소개

- 본 해커톤에 사용되는 API 명세서는 실제 신한은행, 신한카드, 신한금투, 신한생명에서 사용되고 있는 명세서를 기준으로 만들어졌습니다.
  'API명세서' 폴더내에 Excel로 정리가 되어있으며 해당 문서를 참고하시면 됩니다.

- HTTPS 및 IP whitelist 등의 '보안' 부분과 OAuth 2.0등 access token 교환방식 등의 '인증' 과정은 생략되어 있습니다. 짧은 시간동안 해커톤 과정에서 
  개발하시게 될 결과물의 완성도에 더 집중하실 수 있게 해당 부분은 생략 하였으므로 바로 원하시는 API를 호출 하시면 됩니다.

- 해커톤에 쓰일 API들은 실제 그룹사의 개발계와는 연결되어 있지 않습니다. 따라서, 요청 파라미터에 따라 다른 Data가 오지 않으며 애초에 정해진 data만 리턴되게 됩니다.
  따라서, 참가자의 아이디어 구현에 필요한 data는 API 응답으로 받은 data를 원하는 형태대로 가공하여 쓰셔도 됩니다.

---

### 2. 해커톤 서버 구성

- API서버는 해커톤이 진행되는 신한 L 타워 11층의 네트워크망에 붙은 PC/서버만 접속이 가능합니다. 즉, 외부 일반 ISP사업자의 인터넷 망에서는 접속이 되지 않습니다.

- API서버의 URI는 API 명세서를 참고하여 주시면 되며 각 그룹사는 포트로 구분되어 있습니다. 호출 IP 및 포트는 아래를 참고 부탁 드립니다.
  * http://10.3.17.61:8080 신한은행
  * http://10.3.17.61:8081 신한카드
  * http://10.3.17.61:8082 신한금투
  * http://10.3.17.61:8080 신한생명
  
