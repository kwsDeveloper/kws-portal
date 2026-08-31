# KWS 업무 포털 (kws-project)

대한사회복지회 사내 업무 링크 포털  
→ **포털 주소**: https://kwsdeveloper.github.io/kws-project

---

## PC 처음 설정 (한 번만)

**PC 2, 3에서 최초 1회 실행:**

```bash
cd C:\ClaudeProject
git clone https://github.com/kwsDeveloper/kws-project.git
```

→ `C:\ClaudeProject\kws-project\` 폴더가 생성됩니다.

---

## 반복 작업

### PC 1 (주 작업 PC)
Claude Code에서 요청만 하면 자동으로 GitHub에 저장됩니다.
- 링크 추가/수정 → "복지넷 링크 추가해주세요"
- 문서 생성 → "인수인계 PDF 만들어주세요"

### PC 2, 3
PC 1에서 변경이 있을 때마다 아래 한 줄 실행:

```bash
git pull
```

| 상황 | PC 2, 3 할 일 |
|------|--------------|
| 포털 링크가 변경됐을 때 | `git pull` → 브라우저에서 포털 새로고침 |
| 새 문서가 생겼을 때 | `git pull` → HTML 파일 더블클릭 → `Ctrl+P` → PDF 저장 |

---

## 관리자 패널

포털 우상단 **자물쇠 아이콘** 클릭 → 비밀번호 입력

| 기능 | 위치 |
|------|------|
| 링크 추가·수정·삭제 | 링크 관리 탭 |
| 로고·배경 이미지 변경 | 설정 탭 |
| 폰트·글자 크기 변경 | 설정 탭 |
| 조직명·비밀번호 변경 | 설정 탭 |

---

## 비밀번호 분실 시

Supabase 대시보드 → Table Editor → `config` 테이블 → `adminPw` 행 value 직접 수정  
→ 대시보드 주소: https://supabase.com/dashboard/project/czrdvknzbkmryvnjyiki

---

## 문의

GitHub 저장소: https://github.com/kwsDeveloper/kws-project
