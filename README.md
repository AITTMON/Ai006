# Ai006 
master|merging 생기는 요인 <br>
현재 진행하고 있는 프로젝트에서 기존에 있는 파일명과 동일한 파일을 레파지토리(원격 저장소)에 올릴려고 하다가 충돌이 난 상황이다. <br>
*해결방법<br>
git fetch<br>
로컬의 master와 레파지토리(원격 저장소)의 master의 최신 이력을 확인할 수 있고 최신 커밋 이력을 로컬로 가져옵니다.<br>
git reset --hard origin/master <br>
현재 HEAD가 가리키는 브랜치를 옮기고 현재 로컬의 디렉토리 상태를 변경해줍니다. <br>
위의 단계를 진행하고 나면 merging 표기가 사라지게 된다.<br>
즉 overwrite update가 완료되었고 현재 충돌은 해결된 상태이다.<br>
마지막으로 충돌났던 동일한 파일명을 변경하 pull과 merge를 이용해서 레파지토리(원격 저장소)와 로컬 master를 통합시켜주면 <br>
내가 올릴려는 파일을 문제없이 레파지토리(원격 저장소)(원격 저장소)에 올릴 수 있다.<br>
<br>
*git pull 하는 방법<br>
git pull origin 브렌치명 --allow-unrelated-histories  <br>

