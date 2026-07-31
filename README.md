# Mindon-Dev / .github

Mindon-Dev 조직의 **공통 이슈·PR 템플릿**입니다. 자체 템플릿이 없는 모든 저장소가 이 내용을 상속합니다.

## 구성

| 경로 | 역할 |
| --- | --- |
| `.github/ISSUE_TEMPLATE/01_requirement.yml` | ✨ Feature — 없던 것을 새로 만든다 |
| `.github/ISSUE_TEMPLATE/02_improvement.yml` | ♻️ Improvement — 있는 것을 더 낫게 만든다 |
| `.github/ISSUE_TEMPLATE/03_bug.yml` | 🐞 Bug — 동작이 잘못됐다 |
| `.github/ISSUE_TEMPLATE/config.yml` | 템플릿 선택 화면 설정 |
| `.github/pull_request_template.md` | PR 템플릿 |

## 상속 규칙

- 저장소의 `.github/ISSUE_TEMPLATE` 폴더에 **파일이 하나라도 있으면** 이 저장소의 템플릿은 **전부** 무시됩니다. 디렉터리 단위 전부 아니면 전무입니다.
- 그래서 특정 저장소만 다른 양식이 필요하면 그 저장소가 **3종을 모두** 갖고, 나머지는 여기를 상속하는 형태가 됩니다.
- 자체 템플릿을 가진 저장소가 **3개를 넘으면** 갈라지기 시작합니다. 그 전에 공통으로 되돌리세요.

## 여기 두지 않는 것

- **`ISSUE_GUIDE.md`(작성 기준)** — community health file 이 아니라 상속되지 않습니다. 각 저장소의 `.github/ISSUE_GUIDE.md` 에 둡니다.
- **라벨** — 상속되지 않습니다. 저장소마다 `scripts/setup-labels.sh` 로 생성합니다. 도메인 라벨은 프로젝트마다 다릅니다.
- **보드(Project)** — 조직 레벨에서 별도로 관리합니다.
- **프로젝트 고유 용어** — 이 저장소는 공개되어 있습니다. 도메인 이름이나 내부 화면 이름을 넣지 마세요.
