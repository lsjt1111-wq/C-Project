# C# 기본기와 코딩테스트 취업 준비 가이드

브라우저에서 열리는 정적 웹페이지입니다. 외부 라이브러리나 빌드 과정은 필요하지 않습니다.

## 내 PC에서 미리보기

`index.html` 파일을 더블클릭하면 브라우저에서 열립니다.

## GitHub Pages로 공개해서 Discord에 링크 공유하기

1. GitHub에 로그인하고 새 저장소(repository)를 만듭니다. 예: `csharp-study-guide`
2. 저장소는 **Public**으로 설정합니다.
3. 이 폴더의 `index.html`을 저장소 최상위(root)에 업로드하고 커밋합니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. Build and deployment에서 **Deploy from a branch**를 선택합니다.
6. Branch는 `main`, 폴더는 `/(root)`를 선택하고 **Save**를 누릅니다.
7. 게시가 완료되면 Pages 화면에 표시되는 주소를 엽니다. 주소는 보통 `https://깃허브아이디.github.io/저장소이름/` 형태입니다.
8. 생성된 **웹 주소**를 Discord 채팅에 붙여넣어 공유합니다. `.html` 파일 자체를 붙이는 것과 달리, 호스팅된 URL을 공유해야 사이트로 열립니다.

이 HTML에는 Discord 링크 미리보기용 제목과 설명 메타데이터가 포함되어 있습니다. 미리보기 표시 여부와 갱신 시점은 Discord의 캐시에 따라 달라질 수 있습니다.

## 파일 구성

- `index.html`: 사이트 본문과 디자인이 모두 들어 있는 단일 페이지
