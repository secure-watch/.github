# Label templates

[한국어 문서](README.ko.md)

These files define label profiles for different Secure Watch repository types.

GitHub does not apply this directory automatically. Use the profile that matches a repository when it is created, then apply the labels manually or through a future synchronization workflow.

| Profile | Intended repository |
| --- | --- |
| `organization.yml` | `.github` |
| `community.yml` | `discussions` |
| `java.yml` | Java product repositories |
| `documentation.yml` | Documentation repositories |
| `website.yml` | Website and profile repositories |

`Status`, `Priority`, and `Target` should be managed as fields in the organization Project rather than labels.

Only labels defined by the selected profile should be managed automatically. Repository-specific labels must be preserved.
