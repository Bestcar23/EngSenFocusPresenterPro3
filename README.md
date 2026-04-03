# 영어 지문 Presenter 정적 배포본

이 폴더는 빌드가 이미 완료된 정적 배포본입니다.

## GitHub 업로드 방법
1. ZIP 파일을 내려받아 압축을 풉니다.
2. 안의 파일들(`index.html`, `assets`, `vercel.json`, `README.md`)을 GitHub 저장소 루트에 업로드합니다.
3. Vercel에서 해당 GitHub 저장소를 Import합니다.

## Vercel 설정
- Framework Preset: Other
- Build Command: 비워두기
- Install Command: 비워두기
- Output Directory: .

`vercel.json`에 이미 빌드/설치 생략 설정이 들어 있으므로, 별도 빌드 없이 정적 파일만 바로 배포됩니다.
