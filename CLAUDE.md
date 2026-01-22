# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 🎯 프로젝트 목적

개인 학습 추적 및 포트폴리오 저장소. 진행 중인 학습 주제, 스터디 일정, 프로젝트 링크를 문서화합니다.

## 🏗️ 저장소 구조

### 핵심 파일
- `README.md`: 학습 주제, 스터디 일정, 외부 프로젝트 링크가 포함된 메인 프로필
- `AGENTS.md`: 저장소 유지보수를 위한 기여자 가이드

### 특징
- 문서 중심 저장소 (코드 실행 없음)
- 빌드/테스트 명령어 없음
- Markdown 기반 콘텐츠 관리

## 📝 콘텐츠 업데이트 가이드

### README.md 학습 테이블 형식
```markdown
|**시작일**|**종료일**|**요일**|**모임**|**주제**|**비고**|
|:---:|:---:|:---:|:---:|:---:|:---:|
| YYYY.MM.DD | YYYY.MM.DD | 요일 | 그룹명 | 주제 | [링크](URL) |
```

### 날짜 형식
- **일관성 유지**: `YYYY.MM.DD` (예: 2025.01.22)
- **진행 중**: 시작일만 표시, 종료일은 `-`
- **완료**: 시작일과 종료일 모두 표시

### 테이블 정렬
- 최신 학습 항목을 위에 배치
- 완료된 항목은 HTML 주석(`<!-- -->`)으로 보존
- 날짜 기준 내림차순 정렬

## 🔄 Git 워크플로우

### 커밋 메시지
```bash
# 학습 테이블 업데이트
"Update learning schedule table"

# 정렬 작업
"Sort learning table by date"

# 콘텐츠 추가
"Add {주제} to learning tracker"
```

### PR 생성
```bash
gh pr create --title "Update learning tracker" \
  --body "Added new learning items: {주제}"
```

## 📋 작업 시 주의사항

1. **양방향 언어**: 한국어/영어 혼용 가능 (명확성 우선)
2. **링크 검증**: 외부 프로젝트 링크는 HTTPS 사용
3. **일관성**: 기존 스타일 및 형식 유지
4. **간결성**: 헤딩은 짧고 명확하게

## 🚫 하지 말아야 할 것

- 빌드/테스트 명령어 추가 시도 (문서 전용 저장소)
- 민감 정보(API 키, 토큰) 추가
- 기존 테이블 형식 변경
- 날짜 형식 변경 (YYYY.MM.DD 고수)

## 📚 참고 문서

- `AGENTS.md`: 저장소 유지보수 세부 가이드
- 글로벌 개발 철학: `~/.claude/CLAUDE.md`
