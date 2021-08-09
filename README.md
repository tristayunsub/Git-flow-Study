# Git-flow-Study

간단한 GitFlow 예제를 통한 협업 

유튜브 참조 :https://www.youtube.com/watch?v=VY8K9FguM-E&ab_channel=%EC%8B%9C%EB%8B%88%EC%96%B4%EC%BD%94%EB%94%A9


vscode extension: https://github.com/nvie/gitflow


vscode로 git 사용 가이드 : https://www.youtube.com/watch?v=qkRuIUSdXnw&ab_channel=%EB%91%90%EC%9B%90%EC%9D%B4Doowonee
깃 플로우 트러블슈팅


Remote에 올라간 파일/폴더 삭제
실수로 master 브랜치에서 작업
실수로 작업중인 브랜치를 삭제
특정 태그로 긴급 롤백 & 다시 hotfix


TroubleShooting 1 - make ignore already pushed


실수로 remote repository에 불필요한 파일/폴더를
Push했다. 

 .gitignore에 추가하고 삭제 후 push해도
원격에서는 지워지지 않는다.

로컬과 리모트 모두 지우고 싶다. (media2)
로컬에는 남겨두고 리모트에서만 지우고 싶다. (media)

2.

실수로 작업(Topic) 브랜치가 아닌
메인(Master) 브랜치에서 작업하고 커밋했다.

Master는 원위치하고, 작업한 소스는 살리고 싶다!!

다행히 PUSH는 하지 않았다.


PUSH까지 해버렸다


TroubleShooting 3 - Topic Branch Recovery


작업 중이던 Topic 브랜치를 실수로 삭제했다. (-D)

git reset으로 브랜치는 복구되지 않는다.

브랜치를 그대로 복원하고 싶다.


TroubleShooting 4 - Rollback Service Source


버그 수정(hotfix)해서 Tag 0.2.1 배포 후 

예기치 못한 장애가 발생했다.
얼른 0.2.0으로 Rollback 하고 다시 배포하자!


0.2.1의 소스를 이용해서 0.2.2를 작업하자.



---
### 비밀번호 확인
![비밀번호 다름](https://user-images.githubusercontent.com/73703641/128650448-a92bda90-55e1-4579-95d6-0c4b0320986f.gif)

JavaScript를 통해서 비밀번호가 일치하는지 확인하도록 했습니다.

---
