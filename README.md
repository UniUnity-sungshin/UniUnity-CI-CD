# ÜniÜnity CI/CD 파이프라인 구축
안녕하세요.👋 UniUnity는 대학교 인근상권을 한눈에 보여주는 서비스입니다.

소상공인 상가 정보와 제휴혜택 정보를 제공하고, 대학교와 학생, 인근상권 상인에게 커뮤니티를 제공해요!

ÜniÜnity 오픈소스 서비스에 여러분들도 기여해보세요 :)

<br>

## 📑  ÜniÜnity CI/CD Pipeline 테스트를 위한 매뉴얼(ÜniÜnity 오픈소스 서비스에 기여하는 매뉴얼)
<details>
    <summary> ÜniÜnity 오픈소스 서비스에 기여하는 매뉴얼 보러가기 </summary>
  <br>

![35](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/eae6555d-0dc3-44e7-a700-0171e5f3e0fe)
![36](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/4c1c8c60-186d-4d8e-9ea9-6d8ec38e6442)
![37](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/c8828b58-59cb-4c31-a75a-7a6487a88549)
![38](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/d5a31ff5-98d5-44a4-a084-e07bcec0fcc3)
- 현재 GCP 비용문제로 서버를 닫아놔서 접속이 불가능합니다. 언제든지 기여하고 싶으면 서버를 재가동 시켜드리겠습니다.(이슈를 통해 연락부탁드립니다.)

![39](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/e7486e44-c12e-44bf-99ad-2bd49977c3b7)
![40](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/7f00e0b7-7049-449c-b992-82b71089f933)
![41](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/def9d3cc-617b-4b6e-b993-e257b5dd0bc9)
![42](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/f5b192b9-2628-4eab-b1d0-8efcbe35b872)
![43](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/775b1b31-171d-4740-80e6-9c90627b2503)
![44](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/1f5919a9-5122-439d-89bd-625513405dd8)
![45](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/7282cbbf-5452-4412-825b-0be189ac9c73)
![46](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/234b45a6-a710-4f2b-87d6-e85ec1979d6b)
![47](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/e243f63d-35c0-4d1e-8964-46762009a80b)




</details>
<br>

## 🎥  ÜniÜnity CI/CD Pipeline 구축 Demo Video
데모영상 보러가기 :  https://youtu.be/cEX1cwVgqnc?si=xWjsScVd3oJxatxA

<br>

## 🛠  ÜniÜnity CI/CD Pipeline Architecture
![48](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/6aa43937-dd46-4de2-822d-a400ff60d729)

* 사용한 언어/툴 

  * front-end : HTML,CSS, Javascript
  * back-end :  node-js/visual studio code, mysql, firebase-storage, Google Cloud Platform
  * CI/CD : Jenkins, Docker, Kubernetes

<br>


## 🔮 Team 
2023학년 2학기 오픈소스 소프트웨어 팀프로젝트 8팀
- Lead: 최애림

- 나은영, 박지현, 오영서


<br>

## 🎤 Presentation
![1](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/132a1537-73c8-4acb-afc5-cbb805f1009d)

- 안녕하십니까 오픈소스 소프트웨어 팀프로젝트 8팀 발표를 시작하겠습니다

  
![2](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/d1ddf566-bdd6-4a29-b91b-3c1da6a567cf)

- 깃허브를 활용한 개발 및 협업, CI/CD 파이프라인 구축, 어려웠던 점과 해결방안 나눈 뒤 데모영상과 함께 프로젝트를 진행하며 느낀점까지 발표해보려 합니다.


![3](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/b6117186-30ee-42cf-8fac-0dd472801c8e)

- 먼저 깃허브를 활용한 개발 및 협업 과정입니다


![4](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/83b3b9e8-9811-43c1-83f6-56db81624083)

- 대다수의 팀에서 이 방법으로 개발을 진행하셨을 것 같은데요, 저희도 깃허브 풀리퀘스트를 통해 자신의 코드를 올리고, 수정된 코드를 확인하며 merge하는 과정을 거쳐 개발을 진행했습니다

![오픈소스소프트웨어8팀발표자료](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/d1daf66e-9782-494c-ad31-ae56912e57b9)

- 또한 저희는 이슈 탬플릿을 생성하여 이슈를 업로드하며 팀원들에게 요구사항을 요청하고 확인하며 개발을 진행했습니다.


![6](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/5d307f76-1526-4742-b793-98ffc996cccc)

- 생성된 이슈는 open issue, 해결한 issue는 close처리하며 요청사항 처리여부를 확인했습니다


![7](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/a338988f-642a-4df8-864b-aae8f4cbdc3f)

- 이렇게 팀원 각자 올린 이슈를 확인하고, 해당 이슈를 처리한 코드를 풀리퀘스트해가며(8페이지 넘김)


![8](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/704060f2-37a2-4cff-933c-ecc487f28030)

- (~7페이지 이어서)팀원들과 함께 코드리뷰를 해가며 개발을 진행했습니다.


![9](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/87a5da15-8477-4f42-bb85-a1569d66849b)

- 또한 저희는 feat, refactor, fix 등 본인의 수정사항을 한번에 알아볼 수 있도록 커밋을 진행하였습니다.


![10](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/698aab9f-07cb-46df-9155-471fe8435c01)

- 개발과정에서 저희는 깃허브 브랜치를 나누어 해당 용도에 맞는 브랜치를 이용하여 개발을 진행했습니다. develop브랜치에서 주로 개발을 진행했으며 기능 수정이 필요할 경우 feature브랜치에서, 최종적으로 기능이 완성되면 main브랜치에 병합하는 식으로 개발을 진행했습니다.


![11](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/a632c163-6693-40ef-acac-8cb7de89a3b1)

- 다음은 젠킨스와 쿠버네티스 그리고 도커를 이용하여 구축한 CI/CD 환경을 살펴보도록 하겠습니다.


![14](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/d9cbbf83-e58b-4ba1-ace9-3553ae61f599)

- 먼저 작업할 Github 레포지토리에 Jenkins 서버를 연결하기 위해 Webhooks을 설정하였고 이를 통해 깃헙에서 소스 코드 변경이 일어나면 자동으로 CI/CD 파이프라인을 시작하도록 하였습니다.  


![12](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/fdb3ddab-8bea-4049-9d6d-8660b20dce59)

- 여러 브랜치에서 동시에 작업할 수 있도록 젠킨스에 멀티 브랜치 파이프라인을 생성하여 로컬 환경에서 git push를 하면 webhook url로 HTTP POST 요청을 보내도록 하였습니다.


![13](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/d75f22b8-df78-4ac6-8980-87bda3c9758b)

- CI 환경을 구축하기 위해서는 두 가지의 파일이 필요한데 첫 번째로 젠킨스 파일은 스테이지에 각 단계의 실행 순서와 조건을 적어 작성하도록 합니다. 저희는 복사, 이미지 빌드, 이미지 푸시, 배포의 단계로 작성하였습니다.


![15](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/615522d2-e017-4f55-b6ce-2acd0c517c85)

- 두 번째로 도커 파일에는 저희가 배포할 웹 어플리케이션인 uniunity의 환경을 적어 작성하였습니다. 추후 이 두 가지의 파일을 가지고 파이프라인이 시작되면 이미지를 빌드하게 됩니다.


![16](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/fc5dda23-c3c1-4e47-955e-56e0e9dce373)

- 다음으로 CD구축에 대해 발표하겠습니다.
- 앞단계에서 빌드한 도커이미지를 도커 허브에 푸시하는것을 자동화하여 서버에서 해당 이미지를 사용할 수 있도록 하였습니다. 오른쪽화면은 푸시된 이미지결과 입니다.


![17](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/52f71c45-a342-472a-adfb-91bbeb896ec2)

- 쿠버네티스를 사용하여 웹애플리케이션을 배포하기 위해서 Deployment를 작성하였습니다. 어플리케이션을 2개의 복제본으로 배포하기 위해 리플리카셋은 2개로 설정하였으며, 컨테이너는 앞서 만든 이미지를 사용하도록 하였습니다. 또한 데이터베이스 연결 정보는 시크릿을 통해 환
  경 변수로 설정하도록 하였습니다.
  
![18](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/1765ef93-037e-4bb4-b8ba-0a590ca73954)

-  다음으로 외부에서 웹애플리케이션이 접근 가능하도록 서비스를 작성하였습니다. 서비스 유형은 로드밸런서로 설정하였습니다.

  
![19](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/4f06d788-c871-488f-aab0-cb7b81b709ed)

- 다음으로 시크릿을 사용하여 민감한 db정보를 안전하게 관리하도록 하였습니다. 왼쪽 사진과 같이 시크릿을 생성하여 apply해주었습니다. 오른쪽은 웹애플리케이션이 DB접근을 성공한 결과입니다.

  
![20](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/f518d344-ea1c-48c2-bed5-3e0fb1bc574f)

- 다음은 CI/CD파이프라인 구축 성공 실행화면입니다


![21](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/b792a102-d837-4c49-9751-b6a876065e3b)

- Kubernetes 클러스터에 웹애플리케이션 배포 자동화 성공 실행화면입니다.


![22](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/b8d427a2-aff6-4c31-acfc-307dd2678605)

- 다음은 어려웠던 점과 해결방안에 대해 발표하겠습니다.


![23](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/a192c81b-56fd-471d-8b1f-a8101d4c1dcb)

- 첫번째 문제점은 DB정보를 깃허브에 올리지 않고 CD를 구축하는 것에 어려움을 겪었습니다. 기존에 .env파일에서 관리하던 DB정보는 깃허브에 올리지 않았기 때문에 깃허브 코드로 젠킨스에서 이미지를 빌드하면 .env파일 정보가 이미지에 들어있지 않기때문에 배포시 DB와 연결이 되지 않았습니다.  쿠버네티스의 시크릿을 사용하여 해결하였습니다. 시크릿은 쿠버네티스 API를 통해 쉽게 node.js웹 애플리케이션 소스코드에서 관리 할 수 있기 때문에 시크릿을 사용하였습니다.

  
![24](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/1b4eae08-9a76-41fd-a800-1c8a5707fc02)

- 왼쪽 사진과 같이 기존 db정보를 시크릿파일에 작성하고 apply해주었으며, 오른쪽 사진과 같이 deployment리소스env에 시크릿파일에서 작성한 환경변수를 주입해주었습니다.

![25](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/c3e4f784-17c3-406d-8822-7bd30087beb5)

- 그 후 쿠버네티스 API를 이용하여 node.js웹애플리케이션에서 시크릿을 가져오고 이를 nodejs웹애플리케이션 환경변수로 설정해주는 방식으로 해결하였습니다.


![26](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/5d86a17e-adf1-4211-8f3e-0fea01842f73)

- 하지만 바로 성공이 되었으면 좋았었겠지만~ 서비스 계정이 시크릿 리소스를 읽는데 문제가 발생하였습니다. 이는 시크릿리소스를 읽는 권한이 없어서 발생한 문제 였습니다


![27](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/61ad143f-5d36-478b-a9ea-fae9a6934e4a)

- ClusterRole과 ClusterRoleBinding을 생성하여 서비스계정이 시크릿을 읽을 수 있도록 권한을 설정해주어 해결하였습니다.


![28](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/8dc5a5b7-e7b0-429f-9e57-d6817e3072e0)

- 3번째 문제점은 로드밸런서를 이용해 서비스를 배포했는데 인터넷이 연결이 안되는 문제가 발생하였습니다. 이는 웹애플리케이션에서 설정한 포트와 서비스의 targetPort를 동일하게 설정하지 않아 문제가 발생하였던 것이었습니다. 그래서 로드밸런서를 이용할때는 포트번호 매핑에 주의해야한다는 교훈을 얻었습니다.


![29](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/3b1de0a0-936e-4289-b7b3-e6037c657358)

- 코드로 보자면 node.js웹서버포트와 서비스의 타켓포트를 동일하게 설정해주어 해결하였습니다.


![30](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/e6dbfa11-9724-489e-ac54-014a754e72b6)

-  개발 초기단계에서 오류가 발생하였는데요, 젠킨스 비밀번호를 찾을 수 없는 오류였습니다. initial password 명령어와 docker log 명령어를 입력해도 비밀번호를 찾을 수 없었습니다. 도커 컨테이너를 삭제해도 volume기록은 남아있었기에 재설치를 해도 같은 과정이 반복되었던 것입니다.


![31](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/667d8762-29a3-49d4-aabd-de4e9c210755)
- 일반적으로 컨테이너가 삭제되면 데이터도 함께 다 사라지나, 컨테이너의 생명주기와 상관없이 데이터의 영속성을 부여하는 것이 vloumn이기에 이와 같은 현상이 발생한 것입니다. 젠킨스 컨테이너와 연결된 volumns도 전부 지워주고 젠킨스 컨테이너를 재설치를 진행하였더니 다시 초기 비밀번호 파일을 찾을 수 있었으며 젠킨스에 로그인할 수 있었습니다.

![32](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/ed4de2ad-2549-4d6f-ab10-fdf1def8868d)
- 데모영상: https://youtu.be/cEX1cwVgqnc?si=xWjsScVd3oJxatxA

![33](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/f1973552-f738-4b09-968c-d5370eeddb2b)
- 느낀점 :
  - 나은영)
초기 설정하는 부분에서부터 오류가 나 어려움을 겪기도 했지만 실습을 따라가보며 새로운 기술을 많이 배울 수 있었습니다. 또한 기존에 진행했던 프로젝트와 연결 지어 실습한 만큼 더욱 발전할 수 있는 기회가 된 것 같아 뿌듯했습니다.
3학년이나 됐지만, 아직 여전히 개발은 항상 새롭고 어렵게 느껴졌습니다. 혼자였다면 해내지 못했을 성과를 팀원들과 함께해서 이룰 수 있던 것 같습니다. 함께해서 더욱 성장할 수 있었고 새로운 기술들도, 팀원들에게도 많이 배울 수 있는 소중한 경험이었습니다.

  - 박지현)
생각보다도 더 많은 지식과 도구들을 알아야 해서 힘들었습니다. 실습 내용이 방대하고 모든 내용이 중요했기 때문에 배우는데 있어 어려움이 많았지만 그만큼 쉽게 배우고 해볼 수 없는 과정이었고, 또한 서비스를 만드는 것에서 나아가 배포의 과정을 배울 수 있어 새로웠습니다.

  - 오영서)
처음에는 CI/CD의 개념을 이해하기 어려웠는데 직접 환경을 구축해보면서 어떠한 과정으로 통합과 배포가 이루어지는지를 알게 되었습니다. 또한, git push 명령어만을 통해 통합부터 배포까지 자동적으로 되는 것이 신기했습니다.

  - 최애림)
도커, 젠킨스,쿠버네티스를 접해보고, 기존에 만든 팀프로젝트에 CI/CD 파이프라인을 구축 해볼 수 있어서 새로운 기술에 대해 많이 배울 수 있었습니다.
기존에 만든 팀프로젝트는 소스코드에 변경사항이 발생할 때마다 매번 서버를 재가동 시켜주어야 했는데 CI/CD 파이프라인을 구축하여 이러한 과정을 생략할 수 있다는 것을 알게 되어 신기하고 재밌었습니다. 또한 팀원들과 오류를 같이 해결해 나감으로써, 같은 목표를 가지고 함께 나아갈 때 시너지를 경험할 수 있었습니다. 


![34](https://github.com/UniUnity-sungshin/UniUnity-CI-CD/assets/80438964/3afb9e17-5961-4398-969b-50eb611cb131)
