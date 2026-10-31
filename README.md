# 미술책 속 다섯 개의 방

미진사 고등학교 「미술 창작」의 2·4·7·8·10단원을 살펴보는 5단계 방탈출 게임입니다. 방 안의 작품과 쪽지를 보고 교과서에 인쇄된 쪽수를 찾습니다. `index.html`을 브라우저에서 열어 실행할 수 있습니다.

## GitHub Pages 배포

1. GitHub 저장소 최상위에 `index.html`, `style.css`, `app.js`와 `assets` 폴더 전체를 올립니다. 원본 PDF는 올리지 않아도 됩니다.
2. 저장소의 **Settings → Pages**에서 **Deploy from a branch**, `main`, `/ (root)`를 선택해 저장합니다.
3. 생성된 Pages 주소를 학생들에게 공유합니다.

## 교사용 정답과 수정

1번 방 15쪽(2단원), 2번 방 28쪽(4단원), 3번 방 42쪽(7단원), 4번 방 52쪽(8단원), 5번 방 65쪽(10단원)입니다. PDF 화면 번호가 아닌 책에 인쇄된 쪽수입니다. `app.js`의 `rooms` 배열에서 문제와 정답을 수정할 수 있습니다. 정답은 웹 코드에서 확인할 수 있으므로 평가 보안보다는 교과서 탐색 활동에 적합합니다.

이미지는 제공된 교과서에서 발췌했습니다.

## 참고 및 이미지

게임의 진행 화면은 [아트타임 어드벤처 1](https://joyhanju.github.io/#/art-time-adventure1)의 방 탐색, 가방, 대화창 구성을 참고했습니다. 작품 이미지는 제공된 교과서에서 발췌했으며 미술실 배경은 이미지 생성 도구로 제작했습니다. 생성 프롬프트: “Korean high-school art textbook escape adventure game, whimsical hand-painted art classroom with perspective, wooden floor, green and ochre walls, art supplies and a mysterious door; no text or characters.”
