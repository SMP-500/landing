# landing

디딤 **제품 스토리 · 발표 자료**.

> 제품 정의는 [SMP-500/didim](https://github.com/SMP-500/didim) 이 단일 진실 원천입니다.

| 파일 | 내용 |
| --- | --- |
| `index.html` | 한 장짜리 제품 소개 |
| `keynote.html` | 발표 자료 (16:9) |

둘 다 **의존성 없는 단일 HTML 파일**입니다. 빌드 단계가 없고, 브라우저로 바로 열립니다.
라이트·다크 모두 대응합니다.

---

## 여기 적힌 숫자와 문장의 출처

이 저장소는 제품을 **설명**할 뿐 정의하지 않습니다. 금액 계산 방식·용어·제품 원칙이
바뀌면 먼저 SSoT 를 고치고 여기로 내려옵니다.

| 페이지의 내용 | 근거 |
| --- | --- |
| 결제자 ≠ 부담자 | [09-SPEC §2](https://github.com/SMP-500/didim/blob/main/09-SPEC.md) |
| 제품 원칙 5가지 | [01-PRD](https://github.com/SMP-500/didim/blob/main/01-PRD.md) |
| 용어 (여행 / 총무 / 장면 / 결제자 / 부담자) | [05-IA §9](https://github.com/SMP-500/didim/blob/main/05-IA.md) |

---

## 커밋

커밋 기록에는 **사람만** 남습니다. AI 도구가 붙이는 공동 작성자 트레일러
(`Co-Authored-By: Claude` 등)는 `.githooks/commit-msg`가 지우고,
`.github/workflows/commit-hygiene.yml`이 최종 강제합니다.

```bash
git config core.hooksPath .githooks   # 한 번만
```
