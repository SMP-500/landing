# landing

모루 **소개 페이지 · 지원 사이트**. App Store 의 Marketing URL · Support URL 이 여기를 가리킵니다.

돈이 어디로 갔는지 30초 안에 알게 하는 개인 원장형 가계부입니다.

> 제품 정의는 [SMP-500/didim](https://github.com/SMP-500/didim) 이 단일 진실 원천입니다.

| 파일 | 내용 |
| --- | --- |
| `index.html` | 한 장짜리 제품 소개 |
| `manual.html` | 앱 사용설명서 |
| `privacy.html` | 개인정보 처리방침 — App Store 의 Privacy Policy URL 이 가리키는 곳 |

셋 다 **의존성 없는 단일 HTML 파일**입니다. 이미지가 없어 화면이 바뀌어도 낡지 않습니다. 빌드 단계가 없고, 브라우저로 바로 열립니다.
라이트·다크 모두 대응합니다.

---

## 여기 적힌 숫자와 문장의 출처

이 저장소는 제품을 **설명**할 뿐 정의하지 않습니다. 금액 계산 방식·용어·제품 원칙이
바뀌면 먼저 SSoT 를 고치고 여기로 내려옵니다.

| 페이지의 내용 | 근거 |
| --- | --- |
| 이체는 지출이 아니다 · 초안은 집계에 안 들어간다 | [09-SPEC](https://github.com/SMP-500/didim/blob/main/quality/behavior-spec.md) |
| 제품 원칙 6가지 | [종이 가계부에서 출발한 설계](https://github.com/SMP-500/didim/blob/main/docs/superpowers/specs/2026-08-07-ledger-design.md) |
| 용어 (썼어요 / 들어왔어요 / 남았어요 / 옮겼어요) | [05-IA §9](https://github.com/SMP-500/didim/blob/main/product/glossary.md) |
| 처리방침의 내용 | [product/privacy.md](https://github.com/SMP-500/didim/blob/main/product/privacy.md) |
| 테스트 숫자 | [14-SPRINT](https://github.com/SMP-500/didim/blob/main/process/sprint.md) |

---

## 배포와 주소

`main` 이 GitHub Pages 로 바로 섭니다 — 빌드 없음, 병합이 곧 배포입니다.

| 용도 | 주소 |
| --- | --- |
| Marketing URL (소개) | `https://smp-500.github.io/landing/` |
| Support URL (설명서·문의) | `https://smp-500.github.io/landing/manual.html` |

**사이트 소스는 이 저장소 한 곳에만 둡니다.** 다른 곳에 사본을 두면 반드시 갈라집니다.
커스텀 도메인을 붙이면 `CNAME` 파일 한 줄을 여기 더하고 위 표를 고칩니다.
지원 페이지의 문의 이메일은 `manual.html` 의 `#contact` 장에 있습니다.

발표 자료(`keynote.html`)는 앱 화면이 낡아 뺐습니다. 필요하면 git 이력(`0ada283` 이전)에서 꺼내
**현재 화면으로 다시 찍어** 넣습니다.

---

## 커밋

커밋 기록에는 **사람만** 남습니다. AI 도구가 붙이는 공동 작성자 트레일러
(`Co-Authored-By: Claude` 등)는 `.githooks/commit-msg`가 지우고,
`.github/workflows/commit-hygiene.yml`이 최종 강제합니다.

```bash
git config core.hooksPath .githooks   # 한 번만
```
