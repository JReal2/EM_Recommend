# 응급실 연계 서비스 포탈
![스크린샷 2025-01-01 174328](https://github.com/user-attachments/assets/3b2f0506-136c-4a51-ac93-96d09a2013e2)

**KT AIVLE School 7차 미니프로젝트**
<br>
제작기간 : 2024.12.18~2023.12.26

## <u>👨‍🔧Team
 ### AI트랙 충남/충북 21조
<table>
    <thead>
        <tr>
            <th>이름</th>
            <th>역할</th>
            <th>개발 영역</th>
        </tr>
    </thead>
    <tbody>
      <tr>
            <td>이정렬</td>
            <td>  
                조장
            </td>
            <td>
              <ul>
                  <li>백엔드</li>
                  <li>프론트엔드</li>
              </ul>
            </td>
        </tr>
        <tr>
            <td>강홍규</td>
            <td>  
                코드 테스트
            </td>
            <td>
              <ul>
                  <li>백엔드</li>
                  <li>프론트엔드</li>
              </ul>
            </td>
        </tr>
        <tr>
            <td>김대현</td>
            <td>  
                타임 키퍼
            </td>
            <td>
              <ul>
                  <li>모델 튜닝</li>
              </ul>
            </td>
        </tr>
        <tr>
            <td>김준혁</td>
            <td>  
                 발표
            </td>
            <td>
              <ul>
                  <li>프론트엔드</li>
              </ul>
            </td>
        </tr>
        <tr>
          <td>김찬주</td>
            <td>  
                 서기
            </td>
            <td>
              <ul>
                  <li>프론트엔드</li>
              </ul>
            </td>
        </tr>
        <tr>
          <td>이형주</td>
            <td>  
                PPT 제작
            </td>
            <td>
              <ul>
                  <li>프론트엔드</li>
              </ul>
            </td>
        </tr>
    </tbody>
</table>


## </u> 🧐Project Objectives
<h3>프로젝트 목표</h3>
6차 미니프로젝트에서 제작한 음성 인식 및 응급 상황 분류 모델을 사용해 응급상황 인식 및 응급실 연계 서비스 포털 구축 및 배포 

  <br>
  <br>
  
## 💻System Design

<h3> Tech Stack </h3>
<li>FE</li>
<div align="left">
  <img src="https://img.shields.io/badge/html5-E34F26?style=flat&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/css3-1572B6?style=flat&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/NaverMaps-03C75A?style=flat&logo=naver&logoColor=white" />
</div>
<br>

<li>BE</li>
<div align="left">
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Conda-Forge&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
	<img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white" />
  <img src="https://img.shields.io/badge/Intellij%20IDE-000000?style=flat&logo=intellijidea&logoColor=white" />
	<img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat&logo=ApacheTomcat&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" />
  </div>
  <br>
  
<li>AI</li>
<div align="left">
  <img src="https://img.shields.io/badge/Python-007396?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white"/>
</div>
<br>
<li>ETC</li>
<div align="left">
	  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
</div>
<br>

### System Requirements

![스크린샷 2025-01-01 184543](https://github.com/user-attachments/assets/23a450b2-529c-47c2-acdc-92d90c764547)


## 📲Result

<br>

   ### 시스템 구성도
![스크린샷 2025-01-01 203557](https://github.com/user-attachments/assets/7f64e0e4-c0fc-4859-b3ce-d82a98c72c87)


  ### Spring 웹 서버 주요기능
   - #### 로그인 & 회원가입 
      - <b>로그인 페이지 : 30분간 세션 유지 및 로그인 하지 않은 유저는 해당 로그인 페이지로 이동</b><br>
      ![스크린샷 2024-12-26 144649](https://github.com/user-attachments/assets/cf92958b-91de-413b-b6d7-ba346e05d7fe)
	<br>
      - <b>아이디 비밀번호 틀릴 시 오류 UI 표출</b>
	![스크린샷 2024-12-25 215402](https://github.com/user-attachments/assets/ad551afd-d280-4140-8a46-6e3c38d0d267)

      - <b>회원가입 페이지</b>
	![스크린샷 2024-12-25 215335](https://github.com/user-attachments/assets/7e5f2f06-ee33-4327-b618-829a242d8efb)

      - <b>회원가입시 이미 존재하는 ID일 경우 오류 UI 표출</b>
 	![스크린샷 2024-12-25 215348](https://github.com/user-attachments/assets/24b33e0a-3df3-4973-bd8b-c54223d8aafa)
<br><br>
 - #### 유저 응급 상태 입력
      - <b>유저 응급 상태 입력 페이지</b>
	![스크린샷 2024-12-26 144708](https://github.com/user-attachments/assets/0597bacb-595c-4a04-87f0-190350bfa99e)

      - <b>위치정보 자동입력 버튼 클릭 시 권한 요청 후 현재 유저의 위/경도 자동 입력</b>
	![home5](https://github.com/user-attachments/assets/977b52e5-c180-4ff8-bcbe-8eee2bbaf85d)
	![그림2](https://github.com/user-attachments/assets/7d1271c9-6ef7-47cb-88f6-4ca46b397a9b)

      - <b>유저 응급 상태 텍스트 방식으로 입력</b>
	![그림3](https://github.com/user-attachments/assets/27c65e4d-f671-49ed-911c-3ca2d637bfce)


      - <b>마이크 사용 권한 설정</b>
	![그림5](https://github.com/user-attachments/assets/a24da623-acce-4f4c-a690-d13e3be708ff)

      - <b>유저 응급 상태 음성 녹음 방식으로 입력</b>
	![그림7](https://github.com/user-attachments/assets/a71b2894-d577-4a3a-be10-c14cd31f50f4)
	![그림6](https://github.com/user-attachments/assets/37509186-27e3-4891-b521-462c80b92ab7)

      - <b>병원 탐색 버튼 클릭으로 유저 응급 상태 텍스트 / 음성 파일과 사용자 위치 정보 AI서버(FastAPI서버)로 전송</b>
	![그림4](https://github.com/user-attachments/assets/1864a329-8513-4ff5-90d1-91416148dc16)
	

<br><br>
 - #### 응급 상황 분석 결과
      - <b>응급 상황이라고 판단 될 시 (응급 등급이 1~3 등급일 경우) 가장 가까운 응급실 3곳 표시</b>
      	![스크린샷 2024-12-26 144900](https://github.com/user-attachments/assets/0ade8e47-7b73-4785-af4d-5d73d838d1f3)
      - <b>응급 상황이 아니라고 판단 될 시 (응급 등급이 4~5 등급일 경우) 안내 문구 표시</b>
	![스크린샷 2024-12-26 145016](https://github.com/user-attachments/assets/0f203d1a-1c1c-4c37-a071-6f6c37ff3c73)

<br><br>
- #### 병원 상세 정보 및 경로 표시
	- <b>추천 병원 정보 카드 클릭 시 해당 응급실에 대한 세부 정보 및 이동 경로 표시</b>
	![스크린샷 2024-12-26 144914](https://github.com/user-attachments/assets/7a3b7719-482f-4e27-a384-2df27bbcec94)







<br><br>
  - #### 관리자 페이지




<br><br>
### FastAPI 서버 주요기능
![image](https://github.com/user-attachments/assets/b31e5363-f4f0-4acd-9287-7dc03065691c)
<br>
- <b>REG Model을 추가하여 6차 미니 프로젝트에서 Fine-Tuning한 Bert Model의 분류 정확도 성능을 높혔음</b>
  ![image](https://github.com/user-attachments/assets/d5b75e1d-fda5-4088-8c8b-6fb2f7129f43)


      
<br><br>
  ### 배포
   - #### Docker


<br><br>
   - #### Azure
<br><br>

  ## 🎓Conclusion

  
<br><br>
