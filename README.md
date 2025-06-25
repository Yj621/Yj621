 <div class="header">
   <div align= "center">
      <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=F5C0CA&text=YunJi's%20GitHub%20&height=150&fontSize=60&descAlignY=75&descAlign=60" alt="YunJi's GitHub">
   </div>
    </div>
<div align= "center">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 👩🏻‍💻 Contact me 👩🏻‍💻 </h2> 
         <a href=https://yj-621.notion.site/portfolio?pvs=4> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white&link=https://yj-621.notion.site/portfolio?pvs=4"> </a>
         <a href=mailto:strby621@gmail.com> <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:strby621@gmail.com"> </a>
    <a href=https://velog.io/@yj_621/posts> <img src="https://img.shields.io/badge/Velog-000000?style=for-the-badge&logo=Velog&logoColor=white&link=https://velog.io/@yj_621/posts"> </a>
   <div align= "center">
          </div><br>
    <div align= "center">  </div> 
    <h2 align="center">📧 Email 📧</h2>
<p align="center">
  <Strong> strby621@gmail.com </Strong>
</p><br>
<div align= "center">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> ✨ Tech Stack ✨ </h2>
    <div style="margin: 0 auto; text-align: center;" align= "center"> 
      <img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white">
      <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white">
          <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white">
          </div>
    </div><br>
<div align= "center">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 📋 Stat 📋 </h2>
</div>
  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Yj621&layout=compact)

<div align="left">
 
# Projects

## 1. Grow Plant -- [Repository](https://github.com/Yj621/Grow-Plant) 

<a href="https://play.google.com/store/apps/details?id=com.beee.growplant">
    <img src="https://github.com/user-attachments/assets/10c93e64-628f-48b5-80bd-968e2903d9b9" alt="썸네일" width="200">
</a>


장르 : 3D 시뮬레이션 힐링

**역할**

- **UGUI**(Anchor, Pivot, Layout Group)로 **다양한 해상도 대응** UI 개발
- **TouchPhase**로 **멀티 터치 핀치 줌·드래그 이동 기능** 구현
- 하루 이벤트 종료 시 **일차·날씨·식물 상태 변화 기록** UI
- 날씨에 따른 **BGM·효과음 변화 및 볼륨 조절** UI

**성과**

- 재도전 시 **전략**을 세울 수 있도록 구현
- **몰입감**을 높이는 동시에 편의성을 확보
- 플레이어가 **진행 상황**을 직관적으로 파악할 수 있도록 설계

## 2. RedHood's Adventure -- [Repository](https://github.com/Yj621/Red-Hood-s-Adventrue) 

[<img src="https://github.com/user-attachments/assets/0e254cbf-3567-4300-b182-55c52515b17d" alt="썸네일" width="500"/>](https://www.youtube.com/watch?v=PZdd4Z2P5N4)

장르 : 2D 플랫포머 로그라이크

**역할**

- **플레이어 구조 분리**: Player·Controller·Weapon 기능을 스크립트별로 분리  
- **Unity Scripting API**를 활용한 IDragHandler·IPointerDownHandler로 UI 드래그 이동 구현  
- **Scriptable Object**를 사용한 아이템 종류·개수·확률을 에디터에서 직관 설정  
-  인터페이스 기반으로 7가지 **업그레이드 분기 처리** 
- **State Pattern**을 사용한 상태별 행동을 독립 클래스에 캡슐화  
- 화살 발사 시 **Object Pool**을 적용

**성과**

- 스크립트 분리로 **가독성·유지보수성 크게 향상**  
- 드래그 입력 처리 **안정성 확보**
- 밸런스 조정 업무 **시간 50% 단축**  
- 신규 업그레이드 추가 시 **코드 변경량 70% 감소**  
- 풀링 적용으로 **GC 오버헤드 60% 감소**, 프레임 안정성 확보  

## 3. Absorber -- [Repository](https://github.com/Yj621/Absorber) 

[<img src="https://github.com/user-attachments/assets/d79ca6e4-c515-4db6-96f2-cdd817057411" alt="썸네일" width="500"/>](https://youtu.be/_Qos5GsNZl0)

장르 : 2D 플랫포머 액션 RPG

**역할**

- **New InputSystem**을 활용한 이동·흡수·방출·조합 기능, 접근성 향상을 위해 Dictionary 기반 조합 확인 후 무기 발사 로직 연동  
- IEnemy 인터페이스(TakeDamage(), Attack()) 선언 및 BaseEnemy 추상 클래스에 HP 관리 등 공통 로직 구현, 개별 적 클래스에서 죽음 애니메이션·아이템 드랍 로직 override  
- **State Pattern**을 사용하여 상태별 행동을 독립 클래스에 캡슐화하고, 클래스 참조 변경으로 상태 전환 처리  

**성과**

- New InputSystem 도입으로 **이동 함수 구현 시간 30% 단축**  
- 무기 조합 시스템 확장성 확보로 **신규 조합 추가 시 코드 변경량 80% 절감**  
- 인터페이스 기반 설계로 **적 타입 추가 개발 생산성 40% 향상**, 코드 중복 50% 감소  
- State Pattern 적용으로 상태 확장 및 유지보수 용이  

## 4. HalloWitch -- [Repository](https://github.com/Yj621/Witch) 

[<img src="https://github.com/user-attachments/assets/87e4635e-ddcd-4be5-baa1-068d34afb910" alt="썸네일" width="500"/>](https://youtu.be/AIIPsuBO5aQ)

장르 : 2D 뱀서라이크 로그라이크 슈팅

**역할**

- **Scriptable Object와 열거형을 활용**하여 기본 스탯 업그레이드와 스킬 습득·강화 기능 구현
- **Object Pool 활용**한 수동(Q,E) 및 자동 스킬을 Dictionary로 관리하고, OverlapCircleAll로 적 탐색 후 오브젝트 풀에서 스킬 객체 활성화
- 스킬 데이터(데미지·범위·쿨타임 등)를 Scriptable Object로 **런타임에 복제하여 Dictionary에 메모리상 관리**
- Interface 기반의 공통 메서드 선언과 개별 스킬별 override로 동작 분리 및 기즈모 표시

**성과**

- 업그레이드 항목 및 스킬 추가 시 **확장성 및 유지보수 효율 60% 향상**
- 오브젝트 풀링 적용으로 **프레임 안정성 확보**, 스킬 객체 생성 비용 **70% 감소**
- 런타임 데이터 복제를 통한 메모리 캐싱으로 **참조 속도 및 안정성 개선**


</div>
