# 내 GitHub Pages 블로그

GitHub Pages를 사용한 개인 블로그입니다.

## 소개

이 블로그는 GitHub Pages를 활용하여 무료로 호스팅되는 정적 웹사이트입니다.

## 기능

- 📝 간단한 블로그 포스팅
- 🎨 반응형 디자인
- 🚀 빠른 배포 (git push만 하면 자동 배포)
- 🔒 HTTPS 지원

## 로컬에서 실행하기

이 블로그는 정적 HTML 파일로 구성되어 있어 별도의 빌드 과정이 필요 없습니다.

```bash
# 저장소 클론
git clone https://github.com/<사용자명>/github-pages.git

# 로컬에서 확인 (간단한 HTTP 서버 실행)
cd github-pages
python -m http.server 8000
```

브라우저에서 `http://localhost:8000`으로 접속하시면 블로그를 확인할 수 있습니다.

## 배포

main 브랜치에 변경사항을 push하면 자동으로 GitHub Pages에 배포됩니다.

```bash
git add .
git commit -m "블로그 내용 업데이트"
git push origin main
```

## GitHub Pages 설정

1. 저장소의 Settings 탭으로 이동
2. 좌측 메뉴에서 "Pages" 선택
3. Source에서 "Deploy from a branch" 선택
4. Branch는 "main"과 루트 디렉토리 "/(root)" 선택
5. Save 버튼 클릭

배포가 완료되면 `https://<사용자명>.github.io/github-pages/`에서 블로그를 확인할 수 있습니다.

## 커스터마이징

`index.html` 파일을 수정하여 블로그를 원하는 대로 커스터마이징할 수 있습니다.

## 라이선스

MIT License