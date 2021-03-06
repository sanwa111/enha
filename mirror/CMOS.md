Complementary Metal–Oxide Semiconductor  
상보성 금속산화막 반도체.

[집적회로](%EC%A7%91%EC%A0%81%ED%9A%8C%EB%A1%9C.md)의 한 종류. 휴대용 계산기, 전자시계, 소형
컴퓨터 등에 널리 채용되고 있다.  
MOSFET 소자로서 Drain/Source 단자가 p+ 로 도핑된 PMOS와 Drain/Source 단자가 n+로 도핑된 NMOS 소자 둘
다 사용하는 공정을 의미한다. 따라서 PMOS 또는 NMOS 한 종류의 MOSFET만 사용될 경우 CMOS라 하지 않는다. 주로
마이크로프로세서나 SRAM 등의 디지털 집적회로를 구성하는 데 이용된다. 전력 소모가 적다는 이점이 있다. BJT소자를 이용한 공정보다
가격이 싸고 저전력 회로 구현이 가능하다.

## Contents

    

1. PC에서의 CMOS 
2. CMOS 이미지 센서 

[[edit](http://rigvedawiki.net/r1/wiki.php/CMOS?action=edit&section=1)]

### 1. PC에서의 CMOS ¶

일반적인 컴퓨터의 CMOS 셋업은 컴퓨터에 어떤 하드디스크가 장착되어 있는가, 어떤 VGA 카드를 사용하는가 등을 사용자가
[BIOS](BIOS.md)/[UEFI](UEFI.md)에 저장하여 컴퓨터에게 어떤 주변기기들이 장착되어 있으며 어떻게 제어해야
할지 알려 주는 절차이다. 여기에서 걸리고, [오버클럭](%EC%98%A4%EB%B2%84%ED%81%B4%EB%9F%AD.md)이나
하드웨어의 문제, 부팅 순서도 이 곳에서 정한다. 좀 심하게 말하자면 컴퓨터를 잘 다루는 사람과 평범하게 쓰는 사람들의 분기점? 당연한
말이지만 잘못 건드리면 무슨 일이 벌어질지 아무도 모른다. 이거 잘못 건드렸다가 CPU를 태워먹은 사람들도 꽤 많다...

  

컴퓨터 전원이 꺼져도 내용을 저장할수 있도록 별도의 [건전지](%EA%B1%B4%EC%A0%84%EC%A7%80.md)`[1]`를
통해서 전원을 공급받기에, 건전지의 수명이 다 하면 깜박이가 된다. CMOS가 자꾸 지워지면`[2]` 건전지를 갈아주자. 흔히들 수은전지라고
말하는데 리튬배터리이다. 수은전지는 안 쓴지 한참되었다. CMOS라고 부르는 이유도 CMOS S램에 건전지로 전력 공급을 해서 BIOS의
설정을 저장한다고 해서 CMOS라고 전통적으로 불린 것이다.

  

키보드나 마우스, 램 등에 문제가 생기면 삐익-하는 소리를 내주니 참고.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/CMOS?action=edit&section=2)]

### 2. CMOS 이미지 센서 ¶

보통 [디지털카메라](%EB%94%94%EC%A7%80%ED%84%B8%20%EC%B9%B4%EB%A9%94%EB%9D%BC.md)에서의
CMOS라면 이것을 말한다.

  

2000년대 초반까지만 해도 CMOS는 CCD에 비할 때 화질에서 굉장히 불리하였다. 그리하여 휴대폰 카메라 센서나 CCTV 센서 등으로
사용되는 것이 일반적이었지만, 기술의 발전으로 단점을 훌륭히 극복. 2010년 현재 사용되는 거의 대부분의
[DSLR](DSLR.md)은 CMOS를 채용하고 있으며, [이면조사센서](%EC%9D%B4%EB%A9%B4%EC%A1%B0%EC%82%AC%20%EC%84%BC%EC%84%9C.md) 등도 CMOS를
기반하여 만들어지고 있다. 설계구조상 [CCD](CCD.md)에 비해 전력 소모가 적다는 것이 가장 큰 차이이며. 불량화소 문제나
센서부 고장 등의 문제에서도 CCD에 비해 나은 기술이 되었다. 그리고 가격이 상대적으로 저렴하다. 태생적으로 CCD에 비하면 노이즈가 많은
편이지만, 발열이 적어 장시간 노출의 핫픽셀에는 되려 더 나은 결과를 보여주기도 한다.

  

![http://publiclab.org/sites/default/files/geiger.gif](http://publiclab.org/si
tes/default/files/geiger.gif)

[[GIF external image]](http://publiclab.org/sites/default/files/geiger.gif)

  
덤으로, CMOS 이미지 센서는 괜찮은 난수 생성기 혹은 방사선 측정기가 될수 있다. 일단 중요한건 카메라 렌즈에서 끼이는 노이즈는 꽤나
적다는것. 그래서 보통 이런 노이즈를 잡기 위해서 카메라 렌즈를 가려놓아야 한다. 사진은 시간당 10 시버트를 방출하는 세슘 137 선원앞에
스마트폰으로 촬영한 것.

  

최근엔 이를 이용한 CRAYFIS가 발족되기도 했다. 300
엑사[전자볼트](%EC%A0%84%EC%9E%90%EB%B3%BC%ED%8A%B8.md)짜리 OMG 입자를 카메라의 CMOS로
검출해내는데, OMG 입자의 경우 가리지 않아도 엄청난 에너지로 인해서 스마트폰의 CMOS에 노이즈를 주는데 이 노이즈를 검출해내어 데이터를
서버로 보내는 것.

`\----`

  * `[1]` 대개 [그래픽카드](%EA%B7%B8%EB%9E%98%ED%94%BD%EC%B9%B4%EB%93%9C.md)가 꽂히는 자리([PCI-E](PCI-E.md)) 근처에 있다.
  * `[2]` 쉽게 말해, 시스템의 시간이 1970년 1월 1일로 초기화 된다던가... 물론 전지를 뺐다 끼워도 멀쩡한 제품도 있다.

