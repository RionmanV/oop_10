# oop_10
## Git convention(for 깃의 효율적인 사용)
**기본 push 과정(내가 작업한 버전을 깃에 업데이트)**
0. 가장 최종 버전은 "main"브랜치에 올리도록 한다
1. 내 컴퓨터(로컬 환경)에서 작업을 완료한다
2. git switch -c <브랜치 이름>으로 새로운 브랜치 생성과 동시에 브랜치를 옮긴다<br>
   - 보통 브랜치는 본인 이니셜을 따서 짓습니다. 저같은경우는 hj, hj2... 이런식으로 짓는 편입니다
   - 생성 없이 브랜치 변경만 하고싶다면 git checkout <브랜치 이름> 하면 됩니다
3. 브랜치 이름이 main에서 내가 생성한 <브랜치 이름>으로 변경되었는지 확인한다
4. git add .
   현재까지의 변경사항을 모두 로컬에 저장한다
5. git commit -m "커밋 메시지"를 통해 간단하게 작업내용을 표시한다
   보통 "날짜, 이름, 업데이트 내용"으로 표시합니다
   저는 git commit -m "1026 jjeongee design1" 이런식으로 커밋합니다
6. git push origin <브랜치 이름> 으로 push 합니다
7. github 홈페이지로 넘어와서 <브랜치 이름>과 main 브랜치를 merge 해달라고 요청합니다
8. confirm merge를 완료하고 pull request를 요청합니다
9. main 브랜치에 최종 업데이트가 완료되었습니다!
**작업 하기전에 git pull origin main**
