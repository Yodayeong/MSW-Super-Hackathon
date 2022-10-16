## [MOD 강좌 Chapter 1] 기본의 이해



- preset list에서 타일..등을 가져오기

  ![1](chapter1.assets/1.PNG)



- publishing을 통한 게임 출시

  ![2](chapter1.assets/2.PNG)



- map list를 통해 여러개의 맵을 저장

  ![3](chapter1.assets/3.PNG)



- maplestory map을 통해 다양한 맵을 불러올 수 있음

  ![4](chapter1.assets/4.PNG)



- 여기서 시작을 통해 시작위치 설정

  ![5](chapter1.assets/5.PNG)



- npc의 property 중, AutoShowEnable을 활성화하고 메세지를 적어주면 말풍선이 뜸

  ![6](chapter1.assets/6.PNG)

  ![7](chapter1.assets/7.PNG)



- 새 그룹 추가로 내가 쓰는 것들만 따로 모아두기

  ![화면](chapter1.assets/화면.png)
  
  

- workspace에서 model과 script 관리 / 엔티티의 원본 모델이 저장됨

  ![image-20221004013857960](chapter1.assets/image-20221004013857960.png)



- Add Component를 통해 객체에 속성 부여 가능

  ![image-20221004014826523](chapter1.assets/image-20221004014826523.png)

  (**TweenLineComponent **=> 시작점과 목적점 사이를 이동)

  ![image-20221004014953494](chapter1.assets/image-20221004014953494.png)

  ![image-20221004015303679](chapter1.assets/image-20221004015303679.png)

  (**ClimbableComponent **=> 객체에 올라갈 수 있도록 해줌)

  ![image-20221004015616023](chapter1.assets/image-20221004015616023.png)



- layer를 추가할 수 있음 => 타일이나 객체를 여러개 사용 가능

  ![image-20221004015845348](chapter1.assets/image-20221004015845348.png)



- 객체 여러개가 겹칠 때, OrderInLayer로 배치 가능

  ![image-20221004020019438](chapter1.assets/image-20221004020019438.png)



- Script 생성

  ![image-20221004020409861](chapter1.assets/image-20221004020409861.png)

  ![image-20221004020755996](chapter1.assets/image-20221004020755996.png)

  (**Property**)

  ![image-20221004020814055](chapter1.assets/image-20221004020814055.png)

  ![image-20221004020823712](chapter1.assets/image-20221004020823712.png)

  (**Function**)

  ![image-20221004021045316](chapter1.assets/image-20221004021045316.png)

  ![image-20221004021134622](chapter1.assets/image-20221004021134622.png)

  - OnBeginPlay : 게임이 처음 시작할때
  - OnUpdate : update 될때마다
  - OnEndPly : 객체가 파괴됐을때

  ![image-20221004021346252](chapter1.assets/image-20221004021346252.png)

  - new를 통해 새로운 함수를 생성할 수도

  ![image-20221004021531130](chapter1.assets/image-20221004021531130.png)

  - 추가한 function을 불러올 수도 있음

  (**Entity Event Handler**)

  => 엔티티에서 발생되는 다양한 event를 추가

  ![image-20221004022221882](chapter1.assets/image-20221004022221882.png)

  ![image-20221004022230199](chapter1.assets/image-20221004022230199.png)

  (**메서드 자체의 속성**)

  ![image-20221004022600128](chapter1.assets/image-20221004022600128.png)

  ![image-20221004022609305](chapter1.assets/image-20221004022609305-16648179704299.png)

  - server에서만 / client에서만 / 둘다 상관없이 무조건 실행되게



- 작성한 Script를 **Plain Text** 형태로 볼 수도 있음

  ![image-20221016154215996](chapter1.assets/image-20221016154215996.png)



- 기본 component들은 **SpriteRenderComponent**로 설정되어 있음

  ![image-20221016154440255](chapter1.assets/image-20221016154440255.png)

  (**Sprite RUID**를 통해 이미지들을 바로 변경하거나, 해당 RUID를 활용해 같은 객체를 만들 수 있음)

  ![image-20221016154729758](chapter1.assets/image-20221016154729758.png)

  ![image-20221016154814655](chapter1.assets/image-20221016154814655-16659028957531.png)



- **resource** 직접 추가하기

  ![image-20221016155725830](chapter1.assets/image-20221016155725830.png)

  ![image-20221016162521754](chapter1.assets/image-20221016162521754.png)

  ![image-20221016162538031](chapter1.assets/image-20221016162538031.png)

  ![image-20221016162555668](chapter1.assets/image-20221016162555668-16659051590763.png)

  ![image-20221016163620304](chapter1.assets/image-20221016163620304.png)

  ![image-20221016163631080](chapter1.assets/image-20221016163631080.png)

  (**이미지 슬라이싱**)

  ![image-20221016163947427](chapter1.assets/image-20221016163947427.png)

  ![image-20221016163956394](chapter1.assets/image-20221016163956394.png)

  ![image-20221016164007019](chapter1.assets/image-20221016164007019.png)

  
  
  
  
  
