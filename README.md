# 방탈출 질문지

미술을 주제로 한 연령별(5세~초6) 방탈출 질문지 웹앱입니다. 빌드 과정 없이 정적 파일 그대로 배포됩니다.

## 파일
- `index.html` 앱 본체. 문제는 이 파일의 `TIERS` 목록에서 고칩니다.
- `manifest.webmanifest`, `sw.js`, `icons/` 홈 화면 설치와 오프라인 실행용
- 수정해서 올릴 때마다 `sw.js` 맨 위의 `VERSION` 숫자를 하나 올리면 기기에 새 버전이 확실히 반영됩니다.

## 배포 (GitHub + Vercel)
1. 이 폴더의 파일 전체를 GitHub 저장소(`art-escape-room`)에 올립니다.
2. Vercel에서 Add New → Project로 그 저장소를 선택하고 Framework Preset은 Other, 나머지는 기본값으로 Deploy 합니다.
3. 이후 저장소에 올릴 때마다 자동으로 다시 배포됩니다.

## 갤럭시 탭에 설치
Chrome에서 배포 주소를 열고 메뉴 → 홈 화면에 추가(또는 앱 설치)를 누릅니다.
