# 👨‍👧‍👧 프로젝트 소개
> 내용 추가
<br>

## 프로젝트 목표
<p>내용 추가</p>
<p>내용 추가</p>

### ✅ 프로젝트 핵심 기능
<table>
 <tr>
  <td><img src="" width="250px;" alt=""></td>
  <td><img src="" width="250px;" alt=""></td>
  <td><img src="" width="250px;" alt=""></td>
  <td><img src="" width="250px;" alt=""></td>
 </tr>
 <tr>
  <td><h4>메인페이지</h4></td>
  <td><h4>글 작성</h4></td>
  <td><h4>토픽 둘러보기</h4></td>
  <td><h4>마이페이지</h4></td>
 </tr>
</table>
<br>

### 🌐 API 명세서 
[API 명세서 ]()

### 📑 ERD
![Image]()

### ⚙️ Service Architecture
![image]()

### 프로젝트 환경
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=Spring+Boot&logoColor=white"/> <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/JPA-007396?style=flat&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/PL/SQL-FFD800?style=flat&logo=oracle&logoColor=black"/>
<img src="https://img.shields.io/badge/Kotlin-0095D5?style=flat&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white"/>

<br>

# 👨‍👧‍👧 팀소개
> 새싹 현대 IT&E 채용확정형 MSA기반 FullStack개발자 양성과정 8기 2차 프로젝트 <strong>Team - TTT</strong>


<table>
 <tr>
    <td align="center"><a href="https://github.com/LSMJJAng"><img src="" width="200px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/popopododo"><img src="" width="200px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/thals0"><img src="" width="200px;" alt=""></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/LSMJJAng"><b>이승민</b></a></td>
    <td align="center"><a href="https://github.com/popopododo"><b>김동욱</b></a></td>
    <td align="center"><a href="https://github.com/thals0"><b>이소민</b></a></td>
  </tr>
  <tr> 
    <td align="center">
     <p>데이터 베이스 ERD 설계</p>
     <p>스프링 REST 기반 CRUD API 구현</p>
    </td>
    <td align="center">
     <p>AWS 기반 서비스 클라우드 설계와 배포 및 서비스 아키텍처 설계</p>
     <p>프로젝트 CI/CD를 통한 배포 자동화</p>
    </td>
    <td align="center">
     <p>React 기반 클라이언트 FE 개발</p>
     <p>프로젝트 디자인 및 UI/UX 설계</p>
     <p>프로젝트 일정 관리 및 이슈 관리</p>
    </td>
  </tr> 
</table>

<br>

## ⚙ 팀운영 방식

<table>
 <tr>
    <td align="center"><h4>노션</h4></td>
    <td align="center"><h4>Git</h4></td>
   <td align="center"><h4>Figma</h4></td>
  </tr>
  <tr>
    <td align="center"><img src="" width = 300px></td>
    <td align="center"><img src="" width = 300px</td>
    <td align="center"><img src="" width = 300px</td>
  </tr>
  <tr> 
    <td>노션 팀 페이지를 활용하여 매일 스크럼 진행 및 기록</td>
    <td>이슈 기반의 깃 브랜치 전략을 통한 프로젝트 관리</td>
    <td>Figma를 통한 Prototype 및 디자인 관리</td>
  </tr> 
</table>

<br>

## 🙏 Ground Rule
### 기본적인 Rule
- **개발 코어 타임 09시 ~ 18시**
- **의견 대립이 끝나지 않을 시 10분 휴식 후 각자의 의견 다시 정리해서 무조건 다수결로 진행**
- **의견에 대해 근거나 대안을 고민해보고 이야기 하기**
- **에러사항 1시간 이상 진행 사항이 없을 시 공유**
<br>

### 📌 Code Convention

- #### 프로젝트 디렉토리 구조 - 기능별로 그룹화
  예시 사진
  ![image]()

- 작명 - 약칭 사용은 지양하고 사용 필요시 팀원들과 사전에 협의한다
- 파일(클래스 등등)명 - UpperCamelCase EX) RowMapper, Reservation
- 함수(메서드)명 - LowerCamelCase EX) toString, withUserId
- 변수명 - LowerCamelCase EX) toString, withUserId
- 주석 - 주석은 최소 function or Method 단위로 작성한다
- 들여쓰기 - 들여쓰기는 space 4칸으로 설정한다

<br> 

### 🛠 Development Environment

### 📌 Branch Strategy

<details>
<summary>Git Workflow</summary>
<div markdown="1">       

```
 1. local - feature에서 각자 기능 작업
 2. 작업 완료 후 local - dev 에 PR 후 Merge
 3. 이후 remote - develop 으로 PR
 4. 코드 리뷰 후 Confirm 받고 Merge
 5. remote - develop 에 Merge 될 때 마다 모든 팀원 remote - dev pull 받아 최신 상태 유지
 ```

</div>
</details>


| Branch Name | 설명 |
| :---: | :-----: |
| main | 초기 세팅 존재 |
| develop | 로컬 develop merge 브랜치 |

### 📌 Commit Convention

##### [TAG] 메시지 

| 태그 이름  |                             설명                             |
| :--------: | :----------------------------------------------------------: |
|  [CHORE]   |                  코드 수정, 내부 파일 수정                   |
|   [FEAT]   |                       새로운 기능 구현                       |
|   [ADD]    | FEAT 이외의 부수적인 코드 추가, 라이브러리 추가, 새로운 파일 생성 |
|  [HOTFIX]  |             issue나 QA에서 급한 버그 수정에 사용             |
|   [FIX]    |                       버그, 오류 해결                        |
|   [DEL]    |                     쓸모 없는 코드 삭제                      |
|   [DOCS]   |                 README나 WIKI 등의 문서 개정                 |
| [CORRECT]  |       주로 문법의 오류나 타입의 변경, 이름 변경에 사용       |
|   [MOVE]   |               프로젝트 내 파일이나 코드의 이동               |
|  [RENAME]  |                파일 이름 변경이 있을 때 사용                 |
| [IMPROVE]  |                     향상이 있을 때 사용                      |
| [REFACTOR] |                   전면 수정이 있을 때 사용                   |

