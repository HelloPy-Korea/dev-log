# dev-log
HelloPy 개발 일지

## Guide

### DevLog 작성하기 - No IDE 편

1. [DevLog](https://github.com/HelloPy-Korea/dev-log) 코드 저장소에 접속한다.
2. 개발 일지를 작성할 팀을 선택한다.
> 백엔드: Backend, 프론트엔드: Frontend, 디자인: Design, 기획: ProjectManager
- ![EntryPoint](./assets/entrypoint.png)
3. 개발 일지를 추가한다.
- ![AddFile](./assets/add-file.png)
4. 파일 이름을 "년월일.md"로 설정한다.
5. 개발 일지를 작성한다.
> 개발 일지는 markdown 형식으로 작성한다. [Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/)
- ![WriteFile](./assets/write-file.png)
6. 우측 상단의 "Commit changes..." 버튼을 눌러 Commit을 준비한다.
7. Commit Message에 다음과 같은 형식으로 Message를 작성한다.
> DevLog: 년-월-일 팀 개발 일지
- ![Commit](./assets/commit.png)
8. 우측 하단의 Commit changes를 눌러 수정 사항을 반영한다.


### DevLog 작성하기 - CLI 편

```sh
# 저장소 pull 받기
git clone https://github.com/HelloPy-Korea/dev-log

# IDE 혹은 Editor를 사용하여 개발 일지 작성 (.md 파일)
# .md 파일 생성하기 MacOS or Linux
touch "fileName"

# .md 파일 생성하기 Windows - PowerShell
New-Item "fileName"

# 수정 사항 반영하기
git add "fileName"

# Commit Message 남기기
git commit -m "DevLog: 2025-01-19 Backend 개발 일지"

# Push 하기
git push origin main

# Pull 받기
git pull --rebase
```
