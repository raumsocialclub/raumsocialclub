# RAUM SOCIAL CLUB — 배포 파일

## 구성
- index.html        사이트 본체 (단일 파일, 이미지 내장)
- admin/index.html  관리자 페이지 (Supabase 로그인 필요)
- vercel.json       Vercel 설정 (빌드 없음)

## 첫 배포
1. GitHub 저장소 raumsocialclub/raumsocialclub → Add file → Upload files
   → 이 폴더의 index.html, vercel.json, admin 폴더를 드래그 → Commit
2. Vercel → 프로젝트 raumsocialclub2026 → Settings → Git
   → Connect Git Repository → raumsocialclub/raumsocialclub
   → Framework Preset: Other / Build Command: 비움 / Output Directory: 비움
3. 배포 완료 후 확인
   사이트   https://raumsocialclub2026.vercel.app
   관리자   https://raumsocialclub2026.vercel.app/admin

## 이후 수정 반영
저장소에서 index.html 을 같은 이름으로 다시 Upload → Commit → 자동 재배포.
주소는 그대로 유지됩니다.
