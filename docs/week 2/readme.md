# 2주차 과제

## 영상

- [http://projectlion.io/courses/technology/ably_externship_backend#curriculum](http://projectlion.io/courses/technology/ably_externship_backend#curriculum)
- 1주차, 미션해설영상을 봐주세요.

## 주의사항

```
[공지] 미션 PREVIEW 설명

미션 문제에 대한 상세한 설명 등이 담기게 되는 것이라, 녹화 영상을 강사님 유튜브를 통해 저희가 제공을 하되, 이에 대한 녹화 및 유포, 복제등이
발생하는 경우 본 익스턴십 참여 부터, 관련된 모든 법적제재의 대상이 될수 있으므로 본 영상은 시청용으로만 이용 가능 하시다는것 유념 부탁드리겠습니다.

감사합니다.

```

## 개요

- 1주차 작업물에서 이어서 진행합니다.
- DRF는 사용하지 않습니다.
- 카카오로그인 기능을 추가합니다.
- 장바구니 기능을 추가합니다
- 서비스를 배포합니다.

## 출제자의 의도

- 주어진 제약사항 내에서 최선의 기술적 판단
- 유지보수와 작업효율을 고려하여 아키텍쳐 설계 및 라이브러리 선택

## 학습목표

- 기존 소스코드에 장바구니 기능을 추가할 수 있다.
- 외부 서비스(소셜 로그인)을 도입 할 수 있다.
- 서비스를 배포할 수 있다.(추가미션)

## 필수과제

- 지난 작업물에서 이어서 진행
- 카카오톡 로그인
- 장바구니 품목 추가(장바구니에 상품담기)
- 장바구니 품목 수량수정
- 장바구니 품목 삭제

## 추가과제

- 부트스트랩 5 적용
  - https://getbootstrap.com/
- 테일윈드 3.0, JIT 모드 적용
  - https://tailwindcss.com/
- EC2에 도커로 서비스 실행
  - 네이버클라우드나 virtualbox 에서 수행해도 됩니다.
  - 도커를 안쓰셔도 됩니다.
  - 어떠한 방법을 사용하던 IP나 도메인을 통해서 접속할 수 만 있으면 됩니다.

## Q&A

### Q01. Django rest framwork를 사용해서 구현해야 하나요?

- 2주차 미션도, MTV패턴을 이용하여 구현합니다. DRF를 사용하지 않습니다.

### Q02. postgresql은 안되나요?

- 네, Ably사의 입장으로 Maria DB 로 고정되었습니다. Ably역시 MariaDB를 사용하고 있습니다.

### Q03. db는 MySQL이나 MariaDB 중에 아무거나 사용해도 되는것인가요?

- 네, 둘중 아무거나 하셔도 상관없습니다.

### Q04. 다음미션(3주차 미션)도 2주차 작업물에서 이어가야 하나요?

- 네, 맞습니다.

### Q05. 장바구니 품목 수정은 뭔가요?

- 장바구니 품목의 수량 수정을 구현하시면 됩니다.

### Q06. 배포는 어떤식이어도 상관없나요?

- 전혀 상관없습니다. nginx, ssl 없이 하셔도 됩니다. 작동하기만 하면 됩니다. 개발모드로 띄우셔도 됩니다.

### Q07. ec2 마이크로서버 무료인가요?

- 트레픽을 많이 사용하지 않으면 무료입니다. 우리 과제를 수행하는 정도라면 비용이 발생하지 않습니다.

### Q08. 네이버클라우드 플랫폼이나 마이크로소프트 애저를 사용해도 되나요?

- 전혀 상관없습니다.

### Q09. 제출은 강사님 깃으로 하면 되나요?

- Discord의 공지사항 유튜브 주소를 참고하시어 진행하시면 되겠습니다. 또한 수업페이지에도 주소가 있으니 참고하시면 되겠습니다.
  - [과제 제출방법 1부](https://youtu.be/QAHEWqFDo5U)
  - [과제 제출방법 2부](https://youtu.be/biZXRksAm4U)
  - [과제 수행인증영상 예시](https://youtu.be/g0p_GsjAHRA)

### Q10. 제출할 때 수행인증영상도 촬영해야 하나요?

- 아래 예시와 같이, 촬영하시면 됩니다.
- 해당 영상을 유튜브에 업로드(일부공개로) 하신 후, 영상의 주소를 checklist.md 파일에 남겨주시면 됩니다.
- [과제 수행인증영상 예시](https://youtu.be/g0p_GsjAHRA)

### Q11. back 폴더는 뭔가요?

- 1주차 미션의 과제물을 그 안에 담아주시면 됩니다.