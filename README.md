Learn git



What is Git?



VCS(Version control System) / SCM(Source Code Manager)

git은 버전관리를 한다. github과 다르다



| Coommand                              | Description                                  | Example                                         |
| ------------------------------------- | -------------------------------------------- | ----------------------------------------------- |
| `$git init`                           | `.git 디렉토리 생성 및 초기화`               | `$git init`                                     |
| `$git add <FILE>`                     | `<FILE> 을 트랙/스테이징 한다`               | `$git add index.html`                           |
| `$git add <PATH>`                     | `<PATH> 안의 전체 파일을 트랙/스테이징 한다` | `$git add .`                                    |
| `$git commit -m "message"`            | `마직막 add를 해서 스테이징 상태를 commit`   | `$git commit  -m "First Commit"`                |
| `$git remote add origin <REMOTE URL>` | `Remote Repo를 가리킨다`                     | `$git remote add origin https://remoterepo.git` |
| `$git push -u  origin master`         | `Remote Repo를 push한다`                     | `$git push -u origin master`                    |

