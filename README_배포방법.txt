REDFORM 독립 홈페이지 V1

구성
- index.html
- CNAME (GitHub Pages 커스텀 도메인용: redform.kr)
- assets/hero.webp
- assets/g01.webp
- assets/car-reset.webp
- assets/wear-module.webp

추천 무료 배포 방법: GitHub Pages
1) GitHub 계정에서 새 Public repository 생성
2) 이 폴더의 모든 파일을 repository 최상단에 업로드
3) Settings → Pages → Deploy from a branch
4) Branch: main / root 선택 후 저장
5) 사이트가 먼저 github.io 주소로 뜨는지 확인
6) Settings → Pages → Custom domain에 redform.kr 입력
7) 그 다음 가비아 DNS에서 GitHub Pages 안내에 맞춰 레코드 설정
8) DNS 반영 후 HTTPS 적용 확인

주의
- 문의 폼은 현재 redform.kr@gmail.com으로 기본 메일 앱을 여는 방식입니다.
- 공개 전에 별도 회사 이메일(예: hello@redform.kr)을 만들면 index.html의 mailto 주소를 바꾸는 것을 권장합니다.
- CNAME 파일은 GitHub Pages용입니다. 다른 호스팅을 쓰면 필요 없을 수 있습니다.
