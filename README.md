# 기초팀 학우 여러분을 위한 레포지토리입니다

## 사용법

1. 우선, 이 레포지토리를 로컬 저장소(개인 컴퓨터)로 가져가주세요

    - git bash를 열고, 이 레포지토리 폴더가 있으면 좋겠는 경로로 이동해주세요

        - Documents, 내 문서, 문서 폴더에 코드를 모아놓기 위한 폴더(예: workspaces)를 만들고 이용하기를 *추천*합니다 (필수 아님)

        - `cd 폴더이름` 을 통해 특정 폴더로 이동합니다(폴더 더블클릭과 같은 효과)

        - `cd ..` 을 통해 상위 폴더(이전 폴더)로 이동합니다

        - `ls` 를 통해 현재 경로에 있는 모든 폴더와 파일의 목록을 터미널에 출력합니다

    - `git clone https://github.com/tsum-18/basic-team.git` 명령어를 실행해 레포지토리를 복사합니다

1. 과제를 작성하고 저장하세요

    - `code .` 을 통해 Visual Studio Code로 레포지토리 폴더를 엽니다

    - `/레포지토리 경로/본인이름/` 에 새 파이썬 파일을 만들고 (ex. `assign_4.py`) 과제를 수행해 결과를 저장합니다

1. 깃을 이용해 커밋하세요

    - `git status` 명령어를 통해 현재 수정 정보를 확인합니다(필수 아님)

    - **`git pull origin main` 을 통해 다른 사람이 수정한 기록이 있다면 pull을 받습니다** (매우 중요. 이 절차를 수행하지 않으면 conflict(충돌)이 발생할 우려가 있습니다)

    - `git add .` 을 통해 내가 반영한 수정사항을 모두 staging 합니다

    - `git commit -m "커밋 제목"` 을 통해 staging 된 변경사항들을 커밋합니다

        - 커밋하면, 비로소 깃을 통해 레포지토리에 수정사항이 기록된 것입니다!

    - 마지막으로 `git push origin main` 을 통해 원격 레포지토리에 (온라인에) 모든 수정사항을 반영시킵니다
