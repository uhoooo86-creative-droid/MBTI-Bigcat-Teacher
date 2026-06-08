# 🎴 MBTI 활동 카드

MBTI 유형별 영어 수업 활동 카드 16장.  
카드 클릭 → 음원 재생 + 교구 PDF 다운로드.

---

## 📁 폴더 구조

```
mbti-activity/
├── index.html              ← 메인 웹 페이지
├── data/
│   └── cards.json          ← 16장 카드 데이터 (JSON)
└── assets/
    ├── audio/              ← MP3 음원 파일 (32개)
    │   ├── INTJ_bgm.mp3
    │   ├── INTJ_instruction.mp3
    │   └── ... (각 유형별 bgm + instruction)
    └── pdf/                ← 교구 PDF 파일 (16개)
        ├── INTJ_card.pdf
        └── ... (각 유형별 1장)
```

---

## 🔄 실제 파일 교체 방법

### 음원 교체
`assets/audio/` 폴더의 placeholder MP3를 실제 파일로 교체하세요.  
파일명 규칙: `{TYPE}_bgm.mp3` / `{TYPE}_instruction.mp3`

| 파일명 | 용도 |
|--------|------|
| `INTJ_bgm.mp3` | 수업 중 BGM |
| `INTJ_instruction.mp3` | 활동 안내 음성 |

### 교구 교체
`assets/pdf/` 폴더의 placeholder PDF를 실제 교구로 교체하세요.  
파일명 규칙: `{TYPE}_card.pdf`

---

## 🚀 GitHub Pages 배포

```bash
git init
git add .
git commit -m "init: MBTI activity cards"
git remote add origin https://github.com/{username}/mbti-activity.git
git push -u origin main
```

Settings → Pages → Branch: main / root → Save  
→ `https://{username}.github.io/mbti-activity/`

---

## 🎨 MBTI 그룹

| 그룹 | 유형 | 색상 |
|------|------|------|
| 분석가 NT | INTJ INTP ENTJ ENTP | 인디고 |
| 외교관 NF | INFJ INFP ENFJ ENFP | 에메랄드 |
| 관리자 SJ | ISTJ ISFJ ESTJ ESFJ | 레드 |
| 탐험가 SP | ISTP ISFP ESTP ESFP | 앰버 |

---

> placeholder 음원 및 PDF는 무음/빈 파일입니다. 실제 콘텐츠로 교체 후 사용하세요.
