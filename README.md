# cofa-kit

Codex 작업용 개인 템플릿 묶음 (작업 규칙 + 문서 템플릿 + 자주 쓰는 프롬프트).

## 구성
- `AGENTS.md`: Codex가 세션 시작 때 자동으로 읽는 작업 규칙
- `templates/INTERVIEW.md`: 업무 담당자 질문 순서와 기록표
- `templates/AGREEMENT.md`: 구현 전 합의문
- `templates/DECISIONS.md`: 결정 기록
- `templates/STATE.md`: 진행 상태·인수인계
- `templates/SUBMISSION_README.md`: 제출 문서 틀 (과제 지정 형식이 없을 때)
- `PROMPTS.md`: 단계별 프롬프트 (사람이 보고 복사해 쓰는 용도, 과제 폴더로 복사하지 않음)

## 가져오기 (과제 폴더에서)
```
git clone --depth 1 https://github.com/lazyzzigae/cofa-kit.git /tmp/kit
ls AGENTS.md 2>/dev/null && echo "AGENTS.md 이미 있음: 덮어쓰지 말고 합칠 것" || cp /tmp/kit/AGENTS.md .
mkdir -p docs && cp /tmp/kit/templates/*.md docs/
```
