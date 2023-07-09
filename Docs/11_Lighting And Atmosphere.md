# 11. Lighting And Atmosphere

## Light
+ ### Sky Atmosphere
    하늘의 대기를 시뮬레이트 함
    + 파란 하늘
    + 대기에 빛의 퍼짐
    + 노을
    <br><br>

+ ### Directional Lighting 
    태양을 시뮬레이트 함
    + 방향성을 같는다.
    + 최대 두개 생성 가능(해와 달)
    + **Atmosphere sun light**: 설치된 라이트가 2개 일 경우 각각 0 과 1로 설정하여 아래 단축키로 라이트의 방향을 수정할 수 있따.
        + Ctrl+L: 첫번째 라이트
        + Ctrl+Shift+L: 두번째 라이트
    + **Forward Shading priority**: 설치된 2개의 라이트의 Priority가 동일할 경우 경고를 표시한다. 주 라이트를 높은 값으로 설정한다.
    + **Use Temperature**: 태양의 색 온도를 변경
    

    <br><br>

+ ### Sky Light
    ?

## Light Mobility
+ ### Static
    + 인게임에서 라이트 변경 불가능(위치, 방향, 강도, 색)
    + 연산이 빠름
    + 라이트 Bake 가능
    <br><br>

+ ### Stationary
    + 인게임에서 조명의 강도나 색을 바꾸는 것은 가능 단, 위치, 방향을 바꾸지는 못함.
    + 움직이지 않는 정적인 물체를 대상으로 라이트를 부분 Bake 
    <br><br>

+ ### Movable
    * 게임 중에 변경(이동)이 가능한 광원
    + 실시간 계산이기 때문에 Bake 필요 없음
    + 가장 코스트가 큼 
    <br><br>

## 안개 & 그룸
+ ### Exponential Height
    + 안개를 시뮬레이트함
    + Sky Sphere의 위에서 아래로 내려갈 수 록 밀도가 높아짐.
    + Fog Density: 안개의 밀도를 조절.
    <br><br>
+ ### Volumetric Cloudes
    + 동적 구름
    + 빛의 퍼짐(대기 현상)

