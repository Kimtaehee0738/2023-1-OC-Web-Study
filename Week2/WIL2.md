git은 소스코드의 변화를 조율하는 역할을 하는 버전관리자이다. git의 큰 특징은 협업을 가능하게 한다는 점이다.

파일에는 intracked, unmodified, modified, staged 이렇게 4가지 상태가 있다. 

working directory(작업공간)에서 코드를 직접 작성하면 add를 통해 staging area에 내가 작성한 변화를 쌓는다. 그 이후 commit을 하면 local repository에 저장된다. 

이 모든 과정은 내 컴퓨터 안에서만 이뤄지므로 협업을 하려면 서버가 필요하다. 따라서 githurb같은 remote tepository에 push, clone, pull등의 명령어로 변화를 보낸다. 