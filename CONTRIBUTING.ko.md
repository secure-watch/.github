# 기여 안내

[English](CONTRIBUTING.md)

Secure Watch는 설계, 문서, 코드 기여를 공개적으로 관리합니다.

| 목적 | 사용 위치 |
| --- | --- |
| 아이디어와 설계 제안 | GitHub Discussions |
| 확인된 버그와 실행 가능한 작업 | GitHub Issues |
| 문서와 코드 변경 | Pull Request |
| 비공개 보안 취약점 | `SECURITY.md`에 정의된 절차 |

기여하기 전에 관련 Discussion이나 Issue가 있는지 확인합니다. Pull Request에는 변경
목적, 주요 결정, 검증 결과와 관련 Issue를 포함합니다.

저장소별 기여 안내가 있으면 해당 안내가 우선합니다.

## 접근 권한과 기여 경계

Secure Watch는 공개 OSS 기여를 열어두되 저장소 관리 권한은 제한합니다.

- 누구나 공개 저장소를 읽고 Issue와 Discussion을 작성하며 fork에서 Pull Request를
  보낼 수 있습니다.
- 보호된 기본 브랜치는 직접 push가 아니라 검토된 Pull Request를 통해 변경합니다.
- 저장소 공개 범위 변경, 삭제, 이관, 팀 생성과 조직 설정은 조직 Owner가
  담당합니다.
- 저장소 쓰기 권한은 메인테이너 팀을 통해 저장소별로 부여하며, 조직 멤버십만으로
  기본 쓰기 권한을 부여하지 않습니다.
- 외부 fork Pull Request의 Workflow는 메인테이너 승인 후 실행됩니다.

조직 기본 설정은 관리상의 통제 기준입니다. 각 저장소에서 브랜치 규칙,
CODEOWNERS, 필수 검증과 메인테이너 권한을 별도로 설정해야 합니다.

## Commit 메시지

다음 형식을 사용합니다.

```text
<type>(<scope>): <short summary>
```

권장 type은 `feat`, `fix`, `docs`, `ci`, `chore`입니다. 사용할 수 있는 scope 예시는
`profile`, `policy`, `template`, `label`, `workflow`, `community`입니다.

모든 commit은 `Refs #123` 또는 `Fixes #123` 형식으로 관련 Issue를 명시합니다.
관련 Issue가 없으면 commit 전에 먼저 생성합니다.
