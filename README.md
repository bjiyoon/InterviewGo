<div align=center>  
  
# **🎙️ InterviewGo 🎙️**
### 🔷 AI-based Mock Interview Application 🔷
![image](https://github.com/user-attachments/assets/df911c9d-643b-4865-b7aa-7cffd935928a)  
음성인식을 이용한 모의면접 어플리케이션입니다.  
AI면접관이 질문을 하면 사용자는 휴대폰의 마이크를 통해 답변하는 형식으로,  
면접 종료 후 간단한 피드백도 받아볼 수 있습니다.
* * *

### 🎨 UI/UX 🎨  
![inter_ss_1](https://github.com/user-attachments/assets/62970cd5-d067-472d-b417-30af1795d87e)
![inter_ss_2](https://github.com/user-attachments/assets/02d4732f-0f4c-469f-9a6e-3ac2ab0a6dea)  
어디든 들고 다니며 간편하게 면접연습을 한다는 컨셉에 맞춰서 간단하고 직관적으로 설계하려 노력했습니다.  
초반 회원가입을 거친 후, 메인화면인 Dashboard에서 각 컴포넌트를 보여주거나 이동하는 구조입니다.  
* * *

### 🛠️ Development Tools 🛠️
**Frontend:** React Native  
**Backend:** fastAPI  
**Database:** MongoDB  
**Deployment:** CloudType, GooglePlayStore  
* * *

### 👩‍💻 Role 👩‍💻  
( One of the 3 team members )  
Project-Planning  
Implementation of the voice recognition  
Frontend Development  
* * *

### 🧱 Architecture 🧱  
![inter_img2](https://github.com/user-attachments/assets/dd1fb108-cffa-4f7b-8d57-8dde785659f9)
![inter_img2-1](https://github.com/user-attachments/assets/710a766f-d5a6-428e-b3d8-37b61bbfa7c4)  
크게 유저, 그리고 면접을 담당하는 인터뷰, 채용공고 조회요청을 위한 리크루트 이 3가지로 운용됩니다.  
먼저 유저가 이메일, 닉네임, 비밀번호를 서버에 전달하면  
서버는 validation을 거쳐 최종적으로 database에 저장하게 됩니다.  
  
면접을 담당하는 인터뷰도 사용자가 원하는 직무와, 면접방 타이틀을 서버에 전달하면  
챗 컨트롤러가 받아 챗 데이터와 송수신하여 면접질문 및 평가를 돌려주게 됩니다.  
* * *

### 🔑 Key Features 🔑
![inter_img3-0](https://github.com/user-attachments/assets/0082a7fb-100b-442e-a5b9-96ae9c696035)
![inter_img3-1](https://github.com/user-attachments/assets/4cf67244-eab1-4503-b6ff-bbd531dd5ea5)  
이 어플리케이션의 주 핵심기능은 음성면접입니다.  
가상의 AI면접관이 우선 텍스트로 질문을 주면 사용자는 마이크 버튼을 눌러 말로 답변을 하며 면접을 진행하는 형식입니다.  
면접관은 GPT 3.5 turbo모델을 가지고 AI HUB에서 인용한 채용면접데이터를 추가적용하여 파인튜닝했습니다.  

![inter_img4-0](https://github.com/user-attachments/assets/0d141766-819e-451e-a2fe-498b83c68b69)
![inter_img4-1](https://github.com/user-attachments/assets/ce3cb5aa-24aa-432e-8383-6706cd5db9dd)
![inter_img4-2](https://github.com/user-attachments/assets/3dcddeab-e91f-41c8-811a-f20c37e43568)  
* * *
  
### 📈 Result 📈
![inter_img_result](https://github.com/user-attachments/assets/3759f454-fd90-4ab3-b528-004c93aad4a3)  
메인화면의 '전체기록보기' 버튼을 통해 이제껏 진행한 이력을 확인할 수 있습니다.  
게시판은 토글기능을 넣어 제작했으며 클릭하여 열고 닫는 형식입니다.  
* * *
  
### 📝 Conclusion 📝  
  
InterviewGo 프로젝트를 시작하게 된 계기는 면접을 준비하는 사람들이  
보다 효과적으로 연습할 수 있는 도구가 필요하다고 느꼈기 때문입니다. 기존의 모의 면접 어플리케이션은 비효율적이고  
심지어 일부 기능이 제대로 구현이 안 된 어플리케이션도 있었기에,  
과연 이 앱들이 면접자들에게 정말로 도움이 될까? 하는 생각에서  
AI와 음성 인식 기술을 활용해 좀 더 개연성 있고, 실감나는 경험을 제공하고자 했습니다.  
  
진행 과정에서 여러 과제들이 있었지만 제 파트에서의 가장 큰 도전 과제는 음성 인식의 정확도였습니다.  
이를 해결하기 위해 다양한 API 및 라이브러리를 테스트하고, 사용자 피드백을 적극적으로 반영하여  
알고리즘을 개선했습니다.  
이 과정에서 React-native라는 프레임워크를 좀 더 잘 알게 되었습니다.  
  
또한 팀원들과의 협업을 통해 다양한 의견을 조율하고, 효과적인 프로젝트 관리 방법을 익혔습니다.  
특히, 일정 관리와 효율적인 커뮤니케이션의 중요성을 느낄 수 있었습니다.  
  
향후에는 사용자 경험을 개선하기 위해 피드백 시스템을 더욱 정교화하고,  
다양한 직군의 면접 질문을 추가할 계획입니다.  
또, 면접 내용을 요약하는 기능을 넣어 면접자들이 언제든 다시 꺼내어 확인할 수 있도록  
좀 더 기능을 추가할 생각입니다. 이를 통해 InterviewGo를 더 많은 사람들에게 유용한 도구로 발전시키고자 합니다.  
  
아직은 많이 부족한 프로젝트지만, 앞으로 발전할 수 있는 계기가 되길 바랍니다.  
  
봐 주셔서 감사합니다. 좋은 하루 되세요.



</div>
