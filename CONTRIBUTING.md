# Contributing

[한국어 안내](#한국어)

Secure Watch manages design, documentation, and code contributions in the open.

| Purpose | Channel |
| --- | --- |
| Ideas and design proposals | GitHub Discussions |
| Confirmed bugs and actionable work | GitHub Issues |
| Documentation and code changes | Pull requests |
| Private security vulnerabilities | The process defined in `SECURITY.md` |

Before contributing, check whether a related Discussion or Issue already exists. Pull requests should include the purpose of the change, key decisions, validation results, and related Issues.

Repository-specific contribution guidelines take precedence.

## Access and contribution boundaries

Secure Watch keeps public OSS contributions open while restricting repository administration:

- Anyone may read public repositories, open Issues and Discussions, and submit pull requests from a fork.
- Protected default branches accept changes through reviewed pull requests rather than direct pushes.
- Repository visibility changes, deletion, transfer, team creation, and organization settings are restricted to organization owners.
- Repository write access is granted per repository through maintainer teams; organization membership does not grant write access by default.
- Workflows from external fork pull requests require maintainer approval before they run.

These organization defaults are administrative controls. Each repository must still configure its own branch rules, CODEOWNERS, required checks, and maintainer permissions.

## Commit messages

Use the following format:

```text
<type>(<scope>): <short summary>
```

Recommended types are `feat`, `fix`, `docs`, `ci`, and `chore`. Useful scopes include `profile`, `policy`, `template`, `label`, `workflow`, and `community`.

Every commit must reference a related Issue with `Refs #123` or `Fixes #123`. Create the Issue before committing if one does not exist.

---

## 한국어

Secure Watch는 설계, 문서, 코드 기여를 공개적으로 관리합니다.

| 목적 | 사용 위치 |
| --- | --- |
| 아이디어와 설계 제안 | GitHub Discussions |
| 확인된 버그와 실행 가능한 작업 | GitHub Issues |
| 문서와 코드 변경 | Pull requests |
| 비공개 보안 취약점 | `SECURITY.md`에 정의된 절차 |

기여하기 전에 관련 Discussion이나 Issue가 있는지 확인합니다. Pull request에는 변경 목적, 주요 결정, 검증 결과와 관련 Issue를 포함합니다.

저장소별 기여 안내가 있으면 해당 안내가 우선합니다.

### 접근 권한과 기여 경계

Secure Watch는 공개 OSS 기여를 열어두되 저장소 관리 권한은 제한합니다.

- 누구나 공개 저장소를 읽고 Issue와 Discussion을 작성하며 fork에서 Pull request를 보낼 수 있습니다.
- 보호된 기본 브랜치는 직접 push가 아니라 검토된 Pull request를 통해 변경합니다.
- 저장소 공개 범위 변경, 삭제, 이관, 팀 생성과 조직 설정은 조직 Owner가 담당합니다.
- 저장소 쓰기 권한은 메인테이너 팀을 통해 저장소별로 부여하며, 조직 멤버십만으로 기본 쓰기 권한을 부여하지 않습니다.
- 외부 fork Pull request의 workflow는 메인테이너 승인 후 실행됩니다.

조직 기본 설정은 관리상의 통제 기준입니다. 각 저장소에서 브랜치 규칙, CODEOWNERS, 필수 검증과 메인테이너 권한을 별도로 설정해야 합니다.

### 커밋 메시지

다음 형식을 사용합니다.

```text
<type>(<scope>): <짧은 요약>
```

권장 type은 `feat`, `fix`, `docs`, `ci`, `chore`입니다. 사용할 수 있는 scope 예시는 `profile`, `policy`, `template`, `label`, `workflow`, `community`입니다.

모든 커밋은 `Refs #123` 또는 `Fixes #123` 형식으로 관련 Issue를 명시합니다. 관련 Issue가 없으면 커밋 전에 먼저 생성합니다.
