Learn git



What is Git?



VCS(Version control System) / SCM(Source Code Manager)

git은 버전관리를 한다. github과 다르다



| Coommand                              | Description                                      | Example                                         |
| ------------------------------------- | ------------------------------------------------ | ----------------------------------------------- |
| `$git init`                           | `.git 디렉토리 생성 및 초기화`                   | `$git init`                                     |
| `$git add <FILE>`                     | `<FILE> 을 트랙/스테이징 한다`                   | `$git add index.html`                           |
| `$git add <PATH>`                     | `<PATH> 안의 전체 파일을 트랙/스테이징 한다`     | `$git add .`                                    |
| `$git commit -m "message"`            | `마직막 add를 해서 스테이징 상태를 commit`       | `$git commit  -m "First Commit"`                |
| `$git remote add origin <REMOTE URL>` | `Remote Repo를 가리킨다`                         | `$git remote add origin https://remoterepo.git` |
| `$git push -u  origin master`         | `Remote Repo를 push한다`                         | `$git push -u origin master`                    |
| `$git commit --amend`                 | 가장 최근 commit message를 수정한다              | `$git commit --amend`                           |
| `.gitignore`                          | `.gitignore에 있는 파일은 트랙하지 않는다`       | `logfile, *.logfile, logfile/`                  |
| `$git branch <branch name>`           | `branch를 만든다`                                | `$git branch about-page`                        |
| `$git checkout <branch name>`         | `master -> branch로 변경`                        | `$git checkout about-page`                      |
| `html:5 tab enter`                    | `html5 양식 자동 완성`                           |                                                 |
| `$git merge branch`                   | `master에서 branch를 merge한다.`                 | `$git merge about-page`                         |
| `$git branch -d branch`               | `branch를 지운다`                                | `$git branch -d about-page`                     |
| `$git checkout -b branch`             | `branch를 만들고 바로 이동한다 `                 | `$git checkout -b help-page`                    |
| `$git checkout branch:sha`            | `복구하고 싶은 branch로 가서 소스코드를 복사`    | `$git checkout 8104`                            |
| `$git checkout -f`                    | `실수로 master에서 파일을 지웠을 때 다시 살리기` | `$git checkout -f`                              |
|                                       |                                                  |                                                 |