# safety_check.md

## 확인 기준

이번 작업의 허용 위치는 아래 경로뿐이다.

- `projects/project_001/experiments/ep001_9lite/*`

## 변경 파일 확인

`git status --short` 기준 변경 파일은 모두 `projects/project_001/experiments/ep001_9lite/` 아래의 신규 파일이다.

`git diff --name-only`는 추적 중인 파일 변경이 없으므로 빈 결과를 반환한다. 즉 기존 추적 파일 수정은 없다.

신규 파일 목록은 다음과 같다.

- `projects/project_001/experiments/ep001_9lite/README.md`
- `projects/project_001/experiments/ep001_9lite/source_index.md`
- `projects/project_001/experiments/ep001_9lite/ep001_source_brief.md`
- `projects/project_001/experiments/ep001_9lite/original_ep001_material.md`
- `projects/project_001/experiments/ep001_9lite/scene_drama_card_draft.md`
- `projects/project_001/experiments/ep001_9lite/prompt_Bprime_9lite_draft.md`
- `projects/project_001/experiments/ep001_9lite/safety_check.md`

## 금지 영역 확인

다음 경로의 파일은 수정하지 않았다.

- `projects/project_001/docs/*`
- `projects/project_001/synopsis/*`
- `projects/project_001/drafts/*`
- `projects/project_001/logs/*`
- `projects/project_001/cards/*`
- `archive/*`
- 루트 `README.md`
- `prompts/*`
- `state_templates/*`

실험 원고는 작성하지 않았고, `drafts/`에 저장하지 않았다.
