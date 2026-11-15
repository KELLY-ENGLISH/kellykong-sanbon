# 켈리영어독서학원 홈페이지

산본 켈리영어독서학원의 홈페이지입니다.

주소: https://KELLY-ENGLISH.github.io/kellykong-sanbon/

빌드 과정이 없는 정적 사이트입니다. `index.html` 한 파일에 화면·스타일·동작이 모두 들어 있고, `main` 브랜치에 올린 내용이 몇 분 뒤 위 주소에 그대로 반영됩니다.

## 폴더

```
index.html              홈페이지 (여기만 고치면 됩니다)
worksheets/             워크시트 체험판 3종 (Trolley Lab, Justice Lab, UBI Lab)
assets/video/           홍보 영상(mp4)과 대표 장면(webp)
assets/emo/             켈리콩 이모티콘 47종 (e01.webp = 움직임, e01-s.webp = 멈춘 그림)
assets/img/             원장 사진, 워크시트 화면, 링크 미리보기 이미지
assets/fonts/           글꼴 (Pretendard, Noto Serif KR 한글 2,780자 묶음)
.nojekyll               GitHub Pages가 파일을 그대로 내보내게 하는 빈 파일
```

## 자주 고치는 곳

| 하고 싶은 일 | 고칠 곳 |
|---|---|
| 이달의 소식 바꾸기 | `index.html`의 `<!-- 이달의 소식 -->` 섹션. `data-until="2026-11-30"` 날짜가 지나면 자동으로 "신청 마감"으로 바뀌고 첫 화면의 소식 띠가 사라집니다. 첫 화면의 소식 띠 문구, 자주 묻는 질문의 체험 수업 답도 함께 바꿉니다. |
| 영상 추가 | mp4를 `assets/video/`에 넣고, `index.html` 아래쪽 `VIDEOS` 목록에 한 줄 추가. `src`가 비어 있으면 "영상 연결 예정" 카드로 보입니다. |
| 워크시트 추가 | html을 `worksheets/`에 넣고, `LABS` 목록에 한 줄 + `<!-- 워크시트 체험 -->` 섹션의 카드 한 덩어리를 복사해 고칩니다. |
| 전화번호 | `index.html`에서 `010-9892-4088`과 `01098924088`을 찾아 모두 바꿉니다. |
| 카카오톡 채널 바로가기 | 지금은 채널 이름을 복사하는 버튼입니다. 채널 주소(`https://pf.kakao.com/...`)가 있으면 바로가기 버튼으로 바꿀 수 있습니다. |
| 원장 사진 | `assets/img/kelly-hero.webp`, `kelly-hero-640.webp`, `kelly-portrait.webp`를 같은 이름으로 교체. 배경이 밝은 종이색(#f5f4ef)에 가까운 사진이 책 페이지와 자연스럽게 이어집니다. |
| 카카오톡 링크 미리보기 | `index.html` 위쪽의 `og:title`, `og:description`, `og:image`. 이미지는 `assets/img/og-cover.jpg`(1200×630)입니다. |
| 색 | `index.html` 맨 위 `:root`의 `--navy`, `--yellow` 등. |

브라우저에서 파일을 올릴 때는 한 번에 100개, 파일당 25MB까지입니다.

## 글꼴과 음성

- Pretendard (SIL Open Font License 1.1), Noto Serif KR (SIL Open Font License 1.1). 자주 쓰는 한글 2,780자만 담은 묶음이라, 드문 글자는 기기의 기본 글꼴로 보일 수 있습니다.
- 이모티콘의 글씨는 주아(Jua, SIL Open Font License 1.1)입니다.
- 홍보 영상과 워크시트 체험판의 음성은 AI 음성입니다.
