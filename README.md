# KWS 업무 포털 (kws-project)

대한사회복지회 사내 업무 링크 포털  
→ **포털 주소**: https://kwsdeveloper.github.io/kws-project

---

## 한 번만 하면 되는 것

### PC 1, 2, 3 — 각각 한 번씩

| 순서 | 할 일 | 어디서 | 명령 |
|------|-------|--------|------|
| 1 | GitHub CLI 설치 | Windows 터미널(cmd) | `winget install --id GitHub.cli` |
| 2 | GitHub 로그인 | Windows 터미널(cmd) | `gh auth login` |
| 3 | 전역 CLAUDE.md 생성 | Claude Code 채팅 | "전역 CLAUDE.md 만들어주세요" |

### PC 2, 3 — 프로젝트 생길 때마다 한 번

| 순서 | 할 일 | 어디서 | 명령 |
|------|-------|--------|------|
| 1 | 프로젝트 받기 | Windows 터미널(cmd) `C:\ClaudeProject` 폴더에서 | `git clone https://github.com/kwsDeveloper/kws-project.git` |

### PC 1 — 새 프로젝트 시작할 때 한 번

| 할 일 | 어디서 | 명령 |
|-------|--------|------|
| 프로젝트 생성·GitHub 연동 | Claude Code 채팅 | "새 프로젝트 시작해주세요" |

---

## 반복해서 해야 하는 것

### PC 1

| 할 일 | 어디서 | 명령 |
|-------|--------|------|
| 작업 요청 | Claude Code 채팅 | 아래 요청 예시 참고 (자동 push까지 완료) |

### PC 2, 3

| 할 일 | 어디서 | 명령 |
|-------|--------|------|
| 최신 내용 받기 | Windows 터미널(cmd) 해당 프로젝트 폴더에서 | `git pull` |
| PDF 필요할 때 | 탐색기에서 HTML 파일 더블클릭 | `Ctrl+P` → PDF로 저장 |

---

## Claude Code 요청 예시 (PC 1)

### 포털 관리
| 요청 예시 |
|----------|
| "복지넷 링크 추가해주세요. URL은 www.bokjinet.or.kr" |
| "복지넷 링크 삭제해주세요" |
| "복지넷 링크를 비활성으로 변경해주세요" |
| "카테고리명 '복지' → '사회복지'로 변경해주세요" |

### 문서 생성
| 요청 예시 |
|----------|
| "인수인계 PDF 만들어주세요" |
| "사용 매뉴얼 PDF 만들어주세요" |

### 설정 변경
| 요청 예시 |
|----------|
| "조직명을 OO복지회로 변경해주세요" |
| "전체 폰트를 나눔고딕으로 변경해주세요" |

### 기타
| 요청 예시 |
|----------|
| "현재 링크 목록 보여주세요" |
| "포털 현재 상태 설명해주세요" |
| "GitHub에 올라간 파일 목록 알려주세요" |

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
