# 시카숲 쉼터 (프로토타입)

밤의 숲을 3D 캐릭터로 걸어 다니며 100 / 300 / 700 숲에서 따끔함 연출을 체험하는 페이지입니다.
서버 없이 `index.html` 한 장으로 동작합니다. 광고·구매 유도 요소는 없습니다.

## GitHub Pages로 공개하기
1. GitHub에서 New repository로 저장소를 만듭니다. (Public)
2. 이 폴더의 파일(`index.html`, `.nojekyll`, `README.md`)을 저장소에 업로드합니다.
3. Settings > Pages > Source를 "Deploy from a branch", Branch는 `main` / `/ (root)`로 선택하고 Save합니다.
4. 1~2분 뒤 `https://<계정>.github.io/<저장소명>/` 주소로 로그인 없이 접속할 수 있습니다.

## 주의
- Three.js(r128)를 cdnjs에서 불러옵니다. 사내 보안 정책상 외부 CDN이 막히면 `three.min.js`를 저장소에 넣고 `index.html`의 script 주소를 `./three.min.js`로 바꾸세요.
- 아바타는 임시 캐릭터입니다. 시카짱 원본 모델로 교체해 주세요.
- "스며드는 3분"은 연출용 시간입니다. 실제 흡수 시간이 아닙니다.
