# Harris 3D과 Procedural Animation을 활용한 등산모션 제작
2022년 1학기 소프트웨어융합캡스톤디자인 프로젝트

## 1. 개요
### 1-1. 배경
최근 나오는 게임들을 보면 캐릭터들의 움직임이 되게 입체적인 것을 확인할 수 있다. XY 평면으로만 이동하지 않고 높이 Z축으로도 이동한다는 점이다. 그렇기에 자연스럽게 벽과 상호작용하는 액션(벽타기, 오르기... 등)의 애니메이션이 필요하게 된다. 이 때 벽화 상호작용하는 액션 중 암벽등반이라는 구체적인 상황을 설정함으로써, 이의 자연스러운 애니메이션을 연출하기 위해 프로젝트를 진행하게 되었다.

### 1-2. 목표
보다 자연스러운 암벽등반 애니메이션을 연출할 수 있도록 한다.

### 1-3. 기대
Harris 3D를 비롯한 3D메쉬의 keypoint를 검출하는 알고리즘이 Point Matching 분야 뿐만 아니라 Procedural Animation에서도 활용할 수 있음을 보이고자 한다.

## 2. 활용 알고리즘 및 기술

### 2-1. Harris 3D
### 2-2. Procedural Animation
### 2-3. Megascans
### 2-4. 

## 3. 1차 구현 및 결과 (소융캡디 최종 발표)

### 3-0. Chracter Controller
#### 3-0-1. Player Input
    - WASD: 캐릭터 이동
    - Space: 점프 / 암벽등산모드 탈출
    - 암벽접근: 암벽등산모드

### 3-1. Harris 3D Keypoint 검출

### 3-2. Procedural Animation
#### 3-2-1. 

## 4. 피드백 및 추가 구현 사항 (소융캡디 최종 발표)

    - 피드백: 검출시 Keypoint들이 가까이 겹쳐져 있는 부분 수정요함
    - 피드백: 자연물을 보면 Keypoint들이 제대로 검출되지 않았다고 했는데, 두 개의 임계치를 수정해서 테스트해볼 것
        - Window Size -> Vertex Ring Number
        - Harris Operator -> Fraction of the Diagonal
    - 피드백: 발표를 할때 IK에 대해 좀 더 이야기 했으면 좋았을 것
    
    - 기타: 캐릭터 컨트롤러 조작감 수정 및  Locomotion 추가
    - 기타: 손과 발의 각도 수정
    - 기타: Github 페이지 수정하기
    - 기타: 발표 때 Keypoint 이야기할 때 Wireframe mode로 설명했으면 더 좋았을 것
    - 기타: 정상에 다다를시 올라갈 수 있도록 캐릭터 컨트롤러 수정
    - 기타: 인터페이스가 잘 되어 있는 UE5로 업그레이드 하기
        - UE5에서도 C++ 빌드할 수 있도록 환경 구성할 것
    
## 5. 피드백 수용 및 개선

## 6. 2차 구현 및 결과

## 7. 

## 8. 마무리
