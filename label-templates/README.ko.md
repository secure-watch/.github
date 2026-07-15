# 라벨 템플릿

[English](README.md)

이 디렉터리는 Secure Watch 저장소 유형별 라벨 프로필을 관리합니다.

GitHub가 이 디렉터리를 자동으로 적용하지는 않습니다. 저장소 생성 시 유형에 맞는 프로필을 선택한 뒤 수동으로 적용하거나, 추후 동기화 Workflow를 통해 적용합니다.

| 프로필 | 대상 저장소 |
| --- | --- |
| `organization.yml` | `.github` |
| `community.yml` | `discussions` |
| `java.yml` | Java 제품 저장소 |
| `documentation.yml` | 문서 저장소 |
| `website.yml` | 웹사이트 및 프로필 저장소 |

`Status`, `Priority`, `Target`은 라벨보다 조직 Project의 필드로 관리합니다.

자동으로 관리하는 라벨은 선택한 프로필에 정의된 라벨로 한정합니다. 저장소별 라벨은 보존해야 합니다.
