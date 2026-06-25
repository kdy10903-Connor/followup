# 📊 2026년 전사 팔로업 업무 관리

## 🔄 매주 금요일 워크플로우

### 📋 Step 1: 엑셀 파일 준비
최신 팔로업 엑셀 파일을 다운로드합니다.
- 경로: `C:\Users\kdy0613\Downloads\`
- 파일명: `2026년 전사 팔로업 업무_r2 (1).xlsx` 등

### 📤 Step 2: Claude Code에 업로드
엑셀 파일을 Claude Code에 첨부합니다.

### 🚀 Step 3: 배포 요청
다음 중 하나를 말합니다:
```
"이걸로 반영해줘"
"배포해줘"
"대시보드 업데이트"
```

### ✨ Step 4: 자동 실행
다음이 자동으로 실행됩니다:
- ✅ GitHub Pages 배포 (금요일 감지)
- ✅ 이메일 초안 업데이트
- ✅ 받는 사람 목록 확인

---

## 📁 폴더 구조

```
followup/
├── index.html              # 🌐 대시보드 (GitHub Pages 배포됨)
├── email_draft.md          # 📧 주간 이메일 초안
├── email_recipients.txt    # 👥 받는 사람 목록
├── build_dashboard.py      # 🔧 대시보드 빌더 스크립트
├── .claude/settings.json   # ⚙️ 자동화 훅 설정
└── README.md              # 📖 이 파일
```

---

## 🔗 배포 링크

**팔로업 대시보드**: 
👉 https://kdy10903-connor.github.io/followup/

---

## 💡 팁

- **매주 금요일**만 자동 배포됨
- "반영해줘", "배포해줘" 같은 메시지 필수
- 이메일 초안은 매번 새로 생성되므로 내용 확인 후 사용
- 받는 사람 목록은 `email_recipients.txt` 에서 수정 가능

---

## 🔧 설정 정보

- **자동화 방식**: Claude Code 훅 (UserPromptSubmit)
- **저장소**: https://github.com/kdy10903-connor/followup
- **배포 방식**: GitHub Pages
- **업데이트**: 2026-06-26