# ELEC211 / 기초전자실험및설계 / 2019년도 / 1학기 / 송재원
## 기초전자실험및설계 과목을 통햬 배운 점과 보고서를 정리 및 나열하였음.

### <노튼 정리>
#### I. 실험 목적 및 배경이론
1) 실험목적
(1) 노튼 정리를 이해하고 이를 응용할 수 있는 능력을 키운다.
(2) 밀만의 정리를 실험적으로 확인한다.

2) 배경이론
 회로의 임의의 소자에 흐르는 전류를 간단히 구하기 위해 노튼 정리를 이용한다. 노튼 회로는 전류원과 저항이 병렬로 연결되어 있는 회로를 의미한다.
(1) 단자 법칙 이용 : 회로의 V와 I에 관계된 단자법칙을 구하여 노튼 회로로 등가 시킨다. 임의의 회로의 단자법칙이 다음과 같다면  단자법칙에서 I의 계수에 -를 붙인 것이 노튼 등가회로의 저항이 되고 상수항을 으로 나눈 것이 노튼 등가회로의 전류원이 된다. 따라서 단자법칙을 이용하여 노튼 등가회로로 대치 시킬 수 있다.

(2) 개방-단락 이용 : 등가 시키고자 하는 회로의 임의의 영역에서 회로를 단락시킨다. 그 때의 단락된 지점에서 흐르는 전류가 노튼 등가회로의 단락전류원 이 된다. 회로의 모든 전원을 제거하고(전압원은 단락, 전류원은 개방) 구한 회로의 저항은 가 된다. 따라서 개방-단락을 이용하여 노튼 등가회로의 전류원과 저항의 값을 구해 쉽게 대치시킬 수 있다.

(3) 밀만의 정리 : 노튼 정리의 응용으로 여러 개의 전압원이 병렬로 연결되어있는 회로에서 단자전압을 쉽게 구할 수 있다. 병렬로 연결된 여러 전압원을 등가 전류원으로 바꾸면(테브난-노튼 등가회로 이용) 회로는 여러개의 전류원과 저항이 병렬로 접속되어있는 회로가 된다. 여기에서 모든 전류원과 저항을 단일 전류원과 저항으로 등가 시킬 수 있다. 그렇다면 회로는 한 개의 전류원과 한 개의 저항이 병렬로 접속된 간단한 노튼회로로 대치되고 단자전압은 저항에 걸리는 전압이 된다. 따라서  이 된다. 이를 ‘밀만의 정리’라 한다.

#### II. 실험내용
1) 실험기구 : 전원공급기, 전류 및 전압 계측기, 실험에 필요한 저항, 프로토 보드, 전원공급기를 이용한 전류원 등
2) 실험 방법 및 과정
① 실험 방법
Experiment 1 
15V의 전원이 인가되고 4개의 저항이 연결되어 있는 회로를 구성한다. 1) 회로의 ab단락전류를 측정한다. 2) ab지점에서 본 회로의 저항을 측정한다. 3) ab지점에 여러 부하저항을 연결하여 부하전류를 측정한다. 
Experiment 2
15V의 전원과 100mA의 전류원이 인가되고 3개의 저항이 연결되어 있는 회로를 구성한다. 1) ab지점에서 본 회로의 전류를 측정한다. 2) ab지점에서 본 회로의 저항을 측정한다. 3) ab지점에 여러 부하저항을 접속하고 부하전류를 측정한다.
Experiment 3
전압원과 저항이 직렬로 연결되어있는 회로를 1쌍 병렬로 구성한다. 저항과 전압원을 바꾸어가며 ab지점에서 본 단자 전압을 측정한다.(밀만의 정리 이용)

실험 1 (단락전류 측정)
실험 2 (단락전류 측정)
실험 3 (회로구성)

② 실험 과정
![image](https://user-images.githubusercontent.com/58419421/99375363-ff9db400-2906-11eb-8127-038d575edf37.png)

#### III. 실험결과 및 과제
① 실험 결과
![image](https://user-images.githubusercontent.com/58419421/99375489-24922700-2907-11eb-9bec-971dcbb93b8e.png)
1) 실험1과 실험2의 노튼 등가회로를 그리고 단락전류와 단자에서 본 등가 어드미턴스를 구하라.
![image](https://user-images.githubusercontent.com/58419421/99375554-34117000-2907-11eb-94c7-340e0d629454.png)
2) 실험1과 실험2의 노튼 정리가 성립하는지 확인하고 실험3의 밀만의 정리가 성립하는지 확인하라.
실험에서는 실험1과 실험2 모두 다 기존의 회로에 부하저항을 연결하여 부하전류를 측정하였다. 하지만 이론값을 구할 때에는 기존의 회로를 노튼 회로로 간단하게 치환한 후에 부하전류 이론값을 계산하였다. 이론값과 측정값에 약간의 오차는 발생하였지만 이는 무시가능한 양이므로 실험1과 실험2의 노튼의 정리는 성립한다고 할 수 있다.
실험3에서는 기존의 회로에 저항과 전압원을 바꾸어가며 단자전압을 측정하였다. 하지만 이론값을 구할 때에는 밀만의 정리를 이용하여 모든 전압원을 노튼 회로(저항과 전류원이 병렬)로 등가 시킨 후에 모든 전류원과 모든 저항을 각각 1개의 전류원과 저항으로 등가 시켰다. 따라서 회로는 1개의 전류원과 저항이 병렬로 연결된 간단히 노튼회로로 대치되었다. 여기에서 저항과 전압이 바뀔 때마다 등가전류원과 등가저항이 값이 바뀌었고 그 때의 단자전압의 이론값을 구해보았다. 결과적으로 측정값과 이론값 사이에는 무시가능한 수준의 오차를 제외하고는 동일하였다. 따라서 밀만의 정리가 성립한다고 할 수 있다.(자세한 계산과정은 고찰참고)

② 과제
1) 실험 회로의 노튼 등가회로를 그려라.
실험1과 실험2의 등가회로는 실험결과 참고, 실험3의 등가회로는 고찰참고

2) 쌍대성에 대하여 설명하라.
쌍대성이란 A와 B가 켤레, 즉 쌍을 이루고 있다는 것인데 엄밀한 정의는 그 분야에 따라 다르다. 실험7의 테브난회로와 실험8의 노튼회로는 쌍대관계를 이루고 있다고 할 수 있는데 이유는 다음과 같다. 실험7 테브난 회로에서의 단자법칙 , 실험8 노튼 회로에서의 단자법칙 에서 Rt와 Rn이 같고 Vt와 RnIn이 같으면 두 회로는 등가이다. 따라서 테브난 회로를 Rn=Rt이고 In=Vt/Rn 인 노튼 회로로 치환 시킬 수 있고 그 두 회로는 등가이다. 따라서 쌍대관계에 의해서 테브난회로는 노튼회로로 노튼회로는 테브난 회로로 쉽게 등가 시킬 수 있고 임의의 회로를 테브난회로 또는 노튼회로로 바꿀 수 있다. 단자 ab간에  여러 개의 임피던스가 직렬로 연결된 경우에는 테브난 등가회로를 이용하는 것이 유리하고, 여러 개의 어드미턴스가 병렬로 연결된 경우에는 노튼 등가회로를 이용 하는 것이 유리하다.

#### IV. 고찰
이번 실험은 복잡한 회로에서 부하저항을 연결하여 그 부하전류를 측정해보는 실험이었다. 실험7 테브난 회로와 매우 유사한 실험이였는데 단지 차이점은 테브난 회로는 테브난 등가회로를 이용하여 부하전류를 구하는 실험이였고 이번 실험8 노튼회로는 노튼회로를 이용하여 부하전류를 측정하는 실험이다. 실험에서 기존의 회로는 매우 복잡한 회로로 그 부하전류를 실험적으로 측정은 쉽게 할 수 있지만 이론값을 구하는 과정이 까다로웠다. 그 이유는 회로가 복잡하기 때문에 저항이 바뀔 때마다 키르히호프 법칙을 적용하여 부하전류를 구하기가 까다롭기 때문이다. 따라서 이론값을 구하기 위해서 회로를 노튼회로로 치환시킨 후 부하전류를 구하면 쉽게 구할 수 있었다. 다음은 회로를 노튼 회로로 치환시키는 과정이다. 

1. 실험1의 노튼 등가회로를 구하기 위해서는 1) ab 단락전류를 구하여야 한다. ab가 단락되면 680저항에 걸리는 전압이 0, 전류가 0가 된다. 따라서 680저항은 개방된다. 2) 300에 흐르는 전류를 I, 1K에 흐르는 전류를 I1이라 둔다면 우리가 구하고자하는 단락전류는 (I-I1)이 된다. 여기서 KVL을 적용하면 15=300I+100I1, 15=300I+100(I-I1)이 되고 두 식을 연립하여 미지수를 구하면 I=38.37mA, I1=3.48mA가 된다. 즉 ab단락전류 Is=I-I1=34.88mA 가 된다. 3) ab지점에서 본 회로의 등가저항을 구하여야한다. 그러기 위해서 회로의 모든전원을 제거한다.(전압원 단락, 전류원 개방) 따라서 ab지점에서 본 회로의 등가저항 Rab=223.7 이다. 4) 따라서 회로는 34.88mA의 전류원과 223.7의 저항이 병렬로 연결된 간단한 노튼회로로 치환된다.

2. 실험2의 노튼 등가회로를 구하기 위해서 1) ab단락전류를 구한다. ab가 단락되면 우리가 구하고자하는 단락전류는 우측의 200에 흐르는 전류이다. 2) 좌측의 200에 흐르는 전류를 I, 100에 흐르는 전류를 I1이라 한다면 KVL과 KCL에 의해 15=200I+100I1, 15=200I+(I-I1+100)*200 이라는 두 개의 방정식이 얻어진다. 위 두식을 연립하여 풀면 I=31.25mA, I1=87.5mA가 된다. 3) 우리가 구하고자하는 단락전류는 200에 흐르는 전류이므로 단락전류=I-I1+100mA=43.75mA 가 된다. 4) AB지점에서 본 회로의 등가저항을 구하기 위해 회로의 모든 전압원은 단락시키고 전류원은 개방시킨다. 따라서 Rab=266.6이다.

3. 실험3은 기존의 회로에 저항과 전압을 바꾸어가며 단자전압 측정값을 구할 수 있었다. 회로를 노튼 등가회로로 치환시킨 후 측정값을 구해도 되지만 그 방법은 까다롭기 때문에(이유는 4번에서 설명) 기존의 회로를 이용하여 측정값을 구하였다. 하지만 이론값을 구할 때에는 밀만의 정리를 이용하여 노튼 등가회로로 치환 시킨 후에 이론값을 구하는 게 편리하였다. 1) 그 과정으로 다음과 같다.
![image](https://user-images.githubusercontent.com/58419421/99375649-53a89880-2907-11eb-9f5a-5af10f78e3cc.png)
위의 그림과 같이 실험회로는 밀만의 정리를 이용하여 쉽게 전류원 1개와 저항 1개가 병렬로 연결된 노튼 등가회로로 대치시킬 수 있다. 2) 다음으로 단자전압을 구하여야 하는데 단자전압은 저항에 걸리는 전압이므로  이다. 따라서 밀만의 정리를 이용하여 V1,V2,R1,R2가 바뀔 때 마다 이론값을 쉽게 구할 수 있었다.

4. 실험7 테브난실험과 달리 실험8 노튼회로실험은 기존의 실험회로를 노튼 등가회로로 바꾼 후 실험값을 측정하기가 까다로웠다. 그 이유는 테브난 회로는 전압원을 사용하기 때문에 쉽게 테브난 회로(전압원과 저항이 직렬)로 치환 가능하였지만 노튼회로는 전류원을 사용하기 때문에(전류원 저항 병렬) 전류원을 이용한 회로를 구성하기가 까다로웠다. 그 이유로는 전원공급기에는 전압원이나 전류원을 구성하는 버튼이 따로 없기 때문에 우리가 직접 전원공급기를 전류원 역할을 할 수 있도록 전류원처럼 만들어야 하기 때문이다. 이 말은 전원공급기의 전압 공급은 최대치로 설정한 다음 원하는 전류값만큼 설정하는 것인데 이 과정이 쉬운 것이 아니었다. 그 이유로 전류원을 구성해서 전류계측기로 전류를 측정하면 오차가 발생하기 때문인데 그 이유로 1) 계측기를 전류원 양단에 연결하여 측정하면 오차가 발생하였다. 왜냐하면 이러한 측정방법은 전류원과 계측기가 병렬로 연결된 것이기 때문에 올바른 전류값이 측정되지 않았다. 따라서 부하저항을 연결하여 직렬로 전류원의 전류값을 측정하여야 한다. 2) 하지만 부하저항에 따라 전류원의 전류값이 다르게 측정되었다. 그 이유는 저항값에 따라 그 저항이 받아들일 수 있는 전류값이 달라지기 때문이다. 3) 따라서 시행착오를 반복하다 얻은 결론은 부하저항을 연결하는 것이 아니라 일반 점프선(저항이 없는 도선)을 연결하여 계측기-점프선-전류원을 직렬로 측정하면 올바른 전류값이 측정되었다. 4) 따라서 이러한 이유들로 테브난 실험과 달리 노튼실험은 기존의 회로를 노튼등가회로로 대치시킨 후 실험값을 측정하기가 어려웠다. 따라서 실험에서는 기존의 회로를 건드리지 않고 부하전류를 측정하였다.

5. 3번실험을 진행할 때에 전압원과 저항이 직렬로 연결되어있는 테브난회로를 노튼회로로 바꾸었었다. 마찬가지로 실험 1과 실험2 모두 노튼회로로 등가 시키는 것이 아니라 테브난회로로 등가 시켜서 이론적 부하전류값을 구하여도 무방하였다. 그 이유로는 테브난회로와 노튼회로는 쌍대관계이기 때문이다. 

### <중첩의 원리와 가역정리>
#### I. 실험 목적 및 배경이론
1) 실험목적
(1) 중첩의 원리를 이해하고 이용 방법을 익힌다.
(2) 가역정리를 이해하고 실험을 통하여 확인한다.
(3) 4단자 회로망에 있어서의 형 회로의 변환 방법을 익힌다.

2) 배경이론
1. 중첩의 원리
한 회로 내에 2개 이상의 전원이 존재 할 때 에는 중첩의 원리를 이용하여 회로를 해석 할 수 있다. 예를들어 한 회로에 V1전원, V2전원이 존재할 때에 임의의 점 A에서 흐르는 전류를 I라고 하자. 이 때 V2를 제거하고 V1만 존재 할 때에 점 A에 흐르는 전류는 I1, 반대로 V1을 제거하고 V2만 존재할 때에 점 A에 흐르는 전류를 I2라 한다면 I=I1+I2 가 성립한다는 것이 중첩의 원리이다. 즉 2개 이상의 전원이 존재하는 임의의 회로의 임의의 점에서 흐르는 전류는 각각의 전원이 존재할 때에 흐르는 전류의 합과 같다.(단, 전류의 방향을 주의하여야 한다.)
2. 가역 정리
임의의 수동 회로망이 선형 일 때에 순방향 입출력의 비와 역방향 입출력비가 같다는 것이다. 즉 순방향으로서 입력에 전원이 인가되었을 때에 출력에 흐르는 전류는 역방향으로서 출력에 전원을 인가하였을 때 입력에 흐르는 전류와 같다는 것이다. 입력과 출력을 전압과 전류의 관계로 표현할 수 있을 때 이 관계를 전달 저항이라 하고 순방향의 비를 순방향 전달저항, 역방향의 비를 역방향 전달 저항이라 한다. 결국 가역정리는 순방향 전달 저항과 역방향 전달 저항이 같다. 즉 입력전원이 AB단자에 인가되고 출력이 CD일때와 입력전원이 CD단자이고 출력이 AB단자일 때에 이 성립한다. 즉 순방향 전달저항과 역방향 전달저항이 같다.

3. T형 회로와 형 회로의 변환
T형 회로-형 회로는 다음과 같은 공식으로 변환 될 수 있다. 여기서 A,B,C 또는 a,b,c는 저항이라고 생각 할 수 있다.  

![image](https://user-images.githubusercontent.com/58419421/99375944-a1bd9c00-2907-11eb-8bc7-b87166f8983f.png)

#### II. 실험내용
1) 실험기구 : 전원공급기, 전류 및 전압 계측기, 실험에 필요한 저항, 프로토 보드
2) 실험 방법 및 과정
① 실험 방법
Experiment 1 – 중첩의 원리
9V와 6V의 전원이 인가되고 3개의 저항이 연결된 회로를 구성한다. 1) 2개의 전원이 모두 인가 되었을 때 각 지로에 흐르는 전류를 측정한다. 2) 9V만 인가하였을 때 위를 반복한다. 3) 6V만 인가하였을 때 위를 반복한다.
Experiment 2 - 가역정리
9V의 전원이 인가되고 3개의 저항이 연결된 회로를 구성한다. 1) 전원이 AB단자에 있을때에 CD단자의 개방회로 전압과 단락회로 전류를 측정한다.(순방향) 2) 전원이 CD단자에 있을때에 AB단자의 개방회로 전압과 단락회로 전류를 측정한다.(역방향)


실험 1 (중첩의 원리 회로)
실험 2 (가역 정리 회로)


② 실험 과정(회로구성)
![image](https://user-images.githubusercontent.com/58419421/99376042-c1ed5b00-2907-11eb-97d1-7f238360cc02.png)

#### III. 실험결과 및 과제
① 실험 결과
![image](https://user-images.githubusercontent.com/58419421/99376098-d5002b00-2907-11eb-84f0-dbf63cbe73ca.png)

1) 실험1에서 중첩의 원리를 이용하여 각 지로의 전류의 세기와 방향을 측정하라.
표 참고
2) 실험2에서 전원을 입력과 출력에 연결하였을 때의 출력에서의 개방회로 전압과 단락회로 전류를 측정하라.
표 참고

3) 측정값을 통하여 가역정리()가 성립하는지를 확인하라.
 다음과 같이 순방향 전달저항과 역방향 전달저항이 동일하다는 것을 알수 있고 그 비의 값은 3.2 라는 것을 알 수 있다.

② 과제
1) 그림 10-4의 T형 회로를 형 회로로 바꿀 때 출력측의 개방 전압과 단락 전류가 정방향 입력 회로의 출력과 같도록 R1,R2,R3를 결정하라. 그리고 형 회로를 그려라.

#### IV. 고찰
이번 실험은 수동회로망에서의 중첩의 원리와 가역정리를 알아보는 실험이였다. 실험1은 중첩의 원리를 알아보는 실험이고 실험2는 가역정리를 알아보는 실험이였다.

1. 수동회로망이란 전원이나 증폭기 등의 전력 공급원을 포함하지 않는 회로로 RLC소자로 구성된 회로를 말한다. 일반적으로 RLC회로에서는 중첩의 원리와 가역정리가 성립한다. 반면에 트랜지스터나 철심이 든 코일로 이루어진 회로는 능동회로라고 부르며 비직선적인 특성과 비선형적인 특성을 가지고 있다. 능동회로에서는 가역정리가 성립되지 않는다.

2. 실험1-중첩의원리에서 계산값들을 이론적으로 구하는 과정은 다음과 같다. 실험에서 전원이 모두 존재하는 경우, V1만 존재하는 경우, V2만 존재하는 경우로 총 3가지에 대해서 이론값들을 구하여야 하였는데  우선적으로 실험회로를 나타내면 그림과 같다. 수동부호규정을 만족하도록 저항의 극성과 전류의 방향을 설정하였다. 여기서 구해지는 I1, I2, I3가 계산값이 되겠다. 1) 전원이 모두 존재하는 경우에서는 KVL과 KCL을 통해 다음과 같은 3개의 방정식으로 구성된 연립방정식이 나온다. 2)V1만 존재하는 경우에는 다음과 같다.3) V3만 존재하는 경우는 다음과 같다.이 연립방정식을 풀어서 나온 I1, I2, I3값이 문제에서 구하는 이론값이 되겠다.

3. 실험1-중첩의원리에서 이론값들을 구할 때에는 I1, I2, I3가 모두 시계방향으로 흐른다고 가정하여 이론값들을 구하였다. 실험을 진행하여 실험값들을 구할 때에는 전류의 방향에 주의하여야 했는데 그 이유는 전류계를 사용하여 전류를 측정할 때 극성을 잘못 연결하면 반대극성의 전류값이 측정되기 때문이다. 따라서 전류를 측정할 때 극성에 주의하여야 했다. 극성을 판단하는 방법으로 전류계의 +단자와 –단자가 측정하고자하는 단자에 접속 될때 항상 접속되는 단자의 전위차를 고려하여야했다. 상대적으로 전위가 높은 쪽은 +단자, 전위가 낮은 쪽은 –단자를 물려서 올바르게 전류의 방향이 측정되도록 하여야했다. 
예를들어  다음 회로에서 I1과 I3를 측정할 때에는 아래쪽이 –로 전위가 낮기 때문에 전류계를 접속시킬 때 위쪽에 +를, 아래쪽에 –를 접속시킨다.(이것은 아래쪽이 접지가 되어있다고 생각해도 된다. 아래쪽이 접지되어있기 때문에 아래쪽은 –를 접속시킨다.) 주의할 점으로 I3를 측정할 때인데 I3는 1K에 흐른는 전류이므로 6V 전원과 1K저항 사이에 전류계를 접속 시켜야하였다. 여기서 6V 아래쪽은 –로 위쪽보다 6V만큼 전위가 낮다는 뜻이다. 따라서 전류계를 접속시킬 때에는 위쪽에 –단자, 아래쪽에 + 단자를 접속시켜야 하였다. 즉 이론값을 구할 때에는 전류의 방향을 모두 시계방향으로 가정하였고 측정값을 구할 때에는 전류계가 접속되는 단자의 전위차를 고려하여 측정하였다. 결과적으로는 이론값과 실험값의 방향이 동일하였다.

4. 실험에서 이론적으로 구한 이론값과 측정값은 모두 중첩의 원리를 만족한다는 것을 실험결과를 통해 알 수 있다. 예를들어 중첩의 원리에 의하면 9V와 6V의 전원이 모두 존재할 때에 I1의 값은 9V만 존재할 때의 I1과 6V만 존재할 때에의 I1의 합과 같아야 하였는데 (이론값) 14.61(모두존재)=18.04(V1만존재)-3.36(V2만존재)=14.68로 약간의 오차를 무시하면 중첩의 원리가 만족한다는 것을 알 수 있다. 마찬가지로 (실험값) 14.78(모두존재)=18.23(V1만)-3.46(V2만)=14.77도 중첩의 원리를 만족한다는 것을 알 수 있다. 여기서 –를 해주는 이유는 전류의 방향이 V1만존재할 때에는 시계방향 V2만존재할 때에는 반시계방향이기 떄문이다. 즉 전류의 방향이 다르기 때문에 –를 해주었다. 

5. 실험2-가역정리도 마찬가지로 실험1과 같은 방법으로 계산값들을 구할 수 있다. 1) 개방회로 전압을 구할 때에는 출력 단자가 개방되어있으므로 그 단자와 연결된 저항은 단락이 된다.(개방되어있으므로 전류가 0이다, 즉 저항에 걸리는 전압이 0) 따라서 개방회로 전압은 2K에 걸리는 전압이 된다. 2) 단락회로 전류를 구할 때에는 실험1과 마찬가지로 KVL과 KCL을 통해 연립방정식을 구하여 이론값들을 구할 수 있다.

6. 실험2-가역정리에서 순방향으로 전원이 인가될 때와 역방향으로 전원이 인가 될 때의 출력전류는 동일하다는 것을 이론값과 실험값을 통해 알 수 있었다.(실험결과 표 참고) 따라서 가역정리가 성립한다는 것을 알 수 있었다. 그리고 출력전류가 동일하고 입력전원이 모두 9V로 동일하다는 것을 통해 순방향 전달저항과 역방향 전달저항 역시 동일하다는 것을 알 수 있었다. 주의할 점으로 실험 당시 개방회로전압을 구했기 때문에 전달저항에서의 전압이 개방회로 전압으로 착각하였는데 그것이 아니라 입력전원의 전압이 전달저항에서의 전압이다.

7. 가역정리를 통해 한 쪽의 전달저항을 알면 반대 쪽의 전달저항을 알 수 있다. 즉 실험에서 순방향 전달저항을 알기 때문에 역방향 전달저항을 구하지 않아도 알 수 있고 순방향에서의 전류만 구하면 역방향에서의 출력전류도 알 수 있다.
8. 실험에서 약간의 오차가 발생하였다. 하지만 이는 무시할수 있는 수준으로 이 오차를 무시하면 중첩의 원리와 가역정리 모두 만족한다는 것을 알 수 있다. 오차가 발생하는 이유로는 완벽한 실험의 진행이 불가능하기 때문이다. 예를들어 저항의 값이 정확하지가 않고 계측기에서도 내부 저항이 존재하기 때문이다.

9. T형-형 회로는 4단자망으로서 중첩의 원리와 가역정리가 성립한다. 4단자망에 있어서 4개 단자의 한쌍은 입력, 또 다른 한쌍은 출력단자로 사용된다. TR소자, 즉 트랜지스터는 3단자 소자이지만 한 단자를 공통으로 사용하기 때문에 4단자망으로 쓰일 수 있다. 한 단자를 공통으로 사용하는 공통베이스, 공통이미터, 공통컬렉터 TR소자가 있다.


10. T형-형회로로 변환하는 방법

### <테브난 정리>
#### I. 실험 목적 및 배경이론
1) 실험목적
(1) 테브난 정리를 이해하고 응용할 수 있는 능력을 키운다.
(2) 테브난 정리를 실험적으로 증명한다.

2) 배경이론
 회로의 임의의 소자에 흐르는 전류를 간단히 구하기 위해 테브난 정리를 이용한다. 테브난 회로는 전압원과 저항이 직렬로 연결되어 있는 회로를 의미한다.
(1) 단자 법칙 이용 : 회로의 V와 I에 관계된 단자법칙을 구하여 테브난 회로로 등가 시킨다. 임의의 회로의 단자법칙이 다음과 같다면  단자법칙에서 I의 계수에 -를 붙인 것이 테브난 등가회로의 저항이 되고 상수항이 테브난 등가회로의 전압원이 된다. 따라서 단자법칙을 이용하여 테브난 등가회로로 대치 시킬 수 있다.

(2) 개방-단락 이용 : 등가시키고자 하는 회로의 임의의 영역에서 회로를 개방시킨다. 그 때의 개방된 지점에서의 전압은  가 된다. 회로의 모든 전원을 제거하고(단락) 구한 회로의 저항은 가 된다. 따라서 개방-단락을 이용하여 테브난 등가회로의 전압원과 저항의 값을 구해 쉽게 대치 시킬 수 있다.

#### II. 실험내용
1) 실험기구 : 전원공급기, 전류 및 전압 계측기, 실험에 필요한 저항, 프로토 보드, 5K의 가변저항 등
2) 실험 방법 및 과정
① 실험 방법
Experiment 1 
10V의 전원이 인가되고 저항 3개가 연결되어 있는 회로를 개방 그리고 단락 시켜서 와 를 구한다. 그 후 회로의 개방 되있는 부분에 서로 다른 저항을 저항을 접속하여 이 저항에 흐르는 전류를 측정한다.

Experiment 2
10V의 전원이 인가되고 저항 4개가 브릿지회로로 연결되어 있는 회로를 구성한다. 회로를 개방 그리고 단락 시켜서 와 를 구한다. 그 후 브릿지회로의 b지점과 c지점에 서로 다른 저항을 접속하여 이 저항에 흐르는 전류를 측정한다.


기존회로
테브난 등가회로


② 실험 과정 <Experiment 1>
![image](https://user-images.githubusercontent.com/58419421/99376366-2f00f080-2908-11eb-8c16-208f39daa724.png)
![image](https://user-images.githubusercontent.com/58419421/99376392-3922ef00-2908-11eb-983e-e707ab581202.png)

#### III. 실험결과 및 과제
![image](https://user-images.githubusercontent.com/58419421/99376434-46d87480-2908-11eb-881f-676897cb7469.png)

② 과제
(1) 테브난 정리의 유용성을 설명하라.
테브난 정리는 복잡한 회로를 전압원과 저항이 직렬로 연결된 간단한 회로로 대치 시킬 수 있는 장점이 있다. 따라서 해석하기 힘든 회로를 테브난 정리를 이용하여 간단한 회로로 등가 시킬 수 있다.

(2) 휘스톤 브릿지 회로에 대해 조사하고 이를 이용한 미지 저항의 측정법을 설명하라.
브릿지 회로의 검류계가 연결된 부분의 양단전압을 0으로 만들고, 즉 단락 시킨 후 미지저항을 구한다. 단락이 되면 회로는 병렬 저항회로 2개가 직렬로 연결된 간단한 회로로 바뀌고 등가저항을 이용하여 손쉽게 미지저항을 구할 수 있다.

(3) 테브난 정리를 이용할 수 있는 회로 1개를 선택하여 테브난 등가 회로와 전류값을 구하라.
고찰참고

#### IV. 고찰
이번 실험은 테브난 정리를 이용하여 회로를 간단히 등가 시킨 후 부하저항에 흐르는 전류를 측정하는 실험이였다. 실험을 진행하고자하는 기존의 회로는 복잡한 구조의 회로였다. 그래서 회로의 두 단자에 부하저항을 연결하여 부하전류를 측정하기에는 까다로운 면이 있었다. 하지만 이 회로를 테브난 정리를 이용하여 간단히 대치시킨 후 부하저항을 연결하며 그 부하 전류를 측정하기가 상당히 편리했다. 따라서 테브난 정리는 매우 유용한 정리라 할 수 있다.

1) 테브난 정리를 이용하면 아무리 복잡한 회로망이더라도 임의의 두단자에 대해서 전압원과 저항이 직렬로 연결된 회로로 등가가 가능하다. 따라서 테브난 정리는 임의의 소자에 걸리는 전류 또는 전압을 알고자 할 때 매우 좋다.

2) 테브난 등가회로로 대치 시키는 방법은 크게 2가지로 생각해 볼 수 있다. 첫 번째로 등가시키고자 하는 회로의 임의의 두 단자에서의 단자 법칙을 구하는 것이다. V와 I에 대한 단자법칙에서  VT와 RT를 구할 수 있었다. 두 번째로는 개방과 단락을 이용한 것인데 등가시키고자 하는 회로의 임의의 두 단자 A지점과 B지점에서의 전압 Vab = VT가 되고 Rab = RT 가 되었다. 따라서 임의의 두단자에서 본 전압과 저항이 테브난 등가회로의 전압원과 저항이 되었다. 

3) 개방-단락을 이용하여 테브난 등가회로를 구할 때에는 VT를 구하기 위해서는 임의의 두 단자를 개방시켜야 했다. 개방 시켰을 때 그 양단전압이 곧 VT가 되었고 RT를 구하기 위해서는 회로 내의 모든 전원을 제거해야 했는데 전원을 제거한다는 것은 전압원의 경우에는 단락, 전류원의 경우에는 개방 시키는 것을 의미한다.

따라서 우리는 테브난 정리를 이용하여 아무리 복잡한 회로망이라도 회로망 전체의 전압, 전류 상태를 구하지 않고 회로망 중의 임의의 소자에서의 값을 손 쉽게 구할 수 있었다.

다음은 실험회로를 간단한 테브난 등가회로로 대치 시킨 후 이론값을 구하는 과정이다. 실험1의 회로는 비교적 간단하여 손쉽게 테브난 등가회로로 대치가 가능하였지만 실험2 회로는 테브난 등가회로로 대치 시키기가 힘들었다. 그 이유로 실험2의 회로는 브릿지회로로써 구조가 복잡한데 이것은 보기 쉬운 회로로 바꿈으로써 해석하기가 용이해졌다. 

그 과정이 아래에 나와있는데 주의할 점으로 Vbc를 구하기 위해서 접지를 활용하였다. Vbc=Vb-Vc 이므로 b지점에서의 전위와 c지점에서의 전위의 차이였다. 아래의 풀이과정을 보면 알겠지만 Vb는 10v의 전압이 5.6k옴에 걸리는 지점이였고, Vc는 10V의 전압이 2K옴에 걸리는 지점이였다. 이는 전압분배기로써 전압은 직렬회로의 경우 저항에 비례하여 분배되므로 각각 두 저항이 직렬로 연결되어있는 회로에 B지점과 C지점에 전압이 분배되는(전위가 분배되는)것을 통해 쉽게 Vb와 Vc를 구할 수 있었다. 따라서 구하고자하는 Vbc를 구할 수 있었다. (Vb와 Vc를 구하는 과정은 앞에서 배웠던 저항회로의 전압분배와 동일하다. 위의 사진과 동일하다)


![image](https://user-images.githubusercontent.com/58419421/99376620-830bd500-2908-11eb-98ed-b31209ae9509.png)
![image](https://user-images.githubusercontent.com/58419421/99376659-8ef79700-2908-11eb-85fc-97183e18a753.png)
![image](https://user-images.githubusercontent.com/58419421/99376688-9ae35900-2908-11eb-8a0f-91be629822d1.png)


## Term Project 직접 실험 설계 해보기
실 험 계 획 서
1. 실험 제목 : 페트병을 이용한 KCL 증명

2. 실험 목표
⓵ 페트병에서의 물의 흐름을 통해 KCL을 알아본다.
 
3. 실험 내용 
1) 관련이론
키르히호프의 전류법칙(KCL) 
키르히호프의 전류법칙은 전하 보존의 법칙으로 회로망의 한 node에 유입되는 전류와 유출되는 전류가 같음을 나타내는 법칙이다. 이는 임의의 회로망에서의 전하량은 항상 보존되기 때문이다.
우리는 실생활에서 이와 유사한 현상을 이용하여 키르히호프의 전류법칙을 증명한다.

2) 실험 과정
실험 장비 및 재료 : 물, 페트병, 비커, 저울 등 

페트병과 물을 이용해서 키르히호프의 전류법칙을 실생활에서 적용한다.
페트병에 (a) 1cm*1cm 면적의 구멍, (b) 2cm*2cm 면적의 구멍을 각각 뚫고 1L의 물을 유입한다.
(a) 구멍과 (b) 구멍을 통해 유출된 물의 양은 (a)의 경우 약 200ml, (b)의 경우 약 800ml가 유출 됨을 알 수 있다.

4. 결론
회로망에서의 임의의 한 node를 페트병, 물은 전하를 나타낸다고 가정하자. 페트병에 1L의 물이 유입된 것은 노드에 1A의 전류가 유입된 것으로 볼 수 있다. 또 페트병에서 (a),(b) 구멍을 통해 200ml, 800ml의 물이 유출 된 것은 그 노드에서 0.2A, 0.8A의 전류가 유출 된 것으로 볼 수 있다. 이를 통해 “유입된 물의 양 = 유출된 물의 양” 이므로 물의 양(전하량)은 항상 보존되고 임의의 노드에서의 “유입전류 = 유출전류” 인 것을 알 수 있다. 따라서 실생활에서도 KCL과 같은 현상이 발생하며 이를 만족한다는 것을 알 수 있다.

실 험 계 획 서
1. 실험 제목 : 실생활에서의 회로설계 및 다이오드	

2. 실험 목표
⓵ 실생활에서 저항의 역할을 할 수 있는 것을 찾아본다.
⓶ 직ㆍ병렬 등가저항을 이해한다.
⓷ 옴의 법칙을 이해한다.
⓸ 건전지를 통해 임의의 전압을 생성하고 등가전원을 이해한다.
⓹ 다이오드에 대해 이해하고 도통하기 위한 조건을 알아본다.

3. 실험 내용 
1) 관련이론
⓵ 저항은 전류의 흐름을 막는 요소이다. 저항이 무한대에 가까울 경우 절연체라고 하며 전류가 흐르지 않는다. 반대로 저항이 0에 가까울 경우 전류의 손실은 0에 근사하고 도체라고 한다. 실생활에서의 대표적인 도체로는 구리가 있고 절연체로는 나무가 있다.
⓶ 저항에서의 직렬합성저항과 같이 직렬로 연결된 전압원은 등가전압원으로 대치 할 수 있다. 이를 이용하여 원하는 크기의 전압원을 만들 수 있다.
⓷ 다이오드가 도통되기 위한 조건은 순방향 BIAS로 약 0.7V 이상의 전압이 인가되어야 한다. 반대로 전압이 0.7V 이하로 인가 될 경우 도통되지 않으며 OFF된다. 

2) 실험 과정
실험 장비 및 재료 : 멀티미터, 건전지, 다이오드, 도선, 임의의 저항을 만들기 위한 전선,플라스틱 등

5V의 전압원과 다이오드, 330옴의 저항이 직렬로 연결된 회로를 설계하고자 한다.
1V 전압의 건전지 5개를 직렬로 연결하여 전원을 만든다. 
전선과 플라스틱을 이용하여 임의의 저항을 만들고 이를 직ㆍ병렬 합성하여 330옴의 크기를 가지는 등가저항을 만든다. 5V 전압원-다이오드-330옴저항이 직렬로 연결된 회로를 구성하고 다이오드가 ON이 되는 것을 확인한다.

4. 결론
우리는 실생활에서 많은 전기요소를 만들 수 있고 이를 이용하여 회로를 설계 및 제작 할 수 있다.
다이오드를 ON 시키기 위하여 다이오드 양단에 순방향으로 약 0.7V의 전압을 인가해 주어야하는데 이때 330옴의 저항이 필요하다. 우리는 실생활에서 찾은 전기요소를 이용하여 회로를 설계 할 수 있고 다이오드를 통해 이 회로가 정상 작동하는지 판단 할 수 있다. 회로가 정상 작동할 경우 다이오드(LED)는 ON 될 것이다.
#### term project에 대한 파일을 첨부하였음.
