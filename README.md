# 라우트 가드의 기본 구현입니다.

## 이슈 사항

History 기반의 navigate로 인한 오류를 잡기 위해서 window.location.href를 사용해야합니다. 

#### 권한에 따른 요청이 필요할 때 새로고침이 필요한 상황이 오는 것 같습니다. 그래서 HTTP 요청을 새로 호출하는 location.href 를 사용해야합니다.
