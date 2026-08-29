# quiz

퀴즈 플랫폼(몰리's 퀴즈)에서 쓰는 이미지를 저장하는 저장소.
이미지는 `images/` 폴더 안에 올린다.

## 이미지 URL 만드는 법

1. `images/` 폴더에 이미지 업로드
2. 업로드한 이미지 파일 클릭해서 열기 (blob 링크가 나옴)
   - 예: `https://github.com/sopoongstudio/quiz/blob/커밋해시/images/파일명.png`
3. 아래 두 가지를 바꿔서 raw 링크 만들기
   - `github.com` → `raw.githubusercontent.com`
   - `/blob/` 삭제
   - 결과: `https://raw.githubusercontent.com/sopoongstudio/quiz/커밋해시/images/파일명.png`
4. 이 raw 링크를 퀴즈 플랫폼의 "이미지 URL" 칸에 붙여넣기

헷갈리면 blob 링크를 Claude한테 주고 "raw로 바꿔줘"라고 하면 바로 변환해줌.
