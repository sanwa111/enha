## Contents

    

1. 통신 방식 
2. 이동통신 규격 
    

2.1. KT의 2G 강제종료 사건

2.2. KT 2G 완전 종료 이후

2.3. 어떻게든 스마트폰을 사용해보고 싶다

[[edit](http://rigvedawiki.net/r1/wiki.php/CDMA?action=edit&section=1)]

## 1. 통신 방식 ¶

> 코드 분할 다중 접속  
Code Division Multiple Access

  

여러 사용자가 통신 자원([전파망](%EC%A0%84%ED%8C%8C.md))을 공유하면서 동시에 이용하기 위한 방식중 하나로,
사용자마다 고유한 코드를 이용하는 데에서 이름이 붙여졌다. [보안](%EB%B3%B4%EC%95%88.md)을 목적으로 개발되고
있었으나 알파넷과 마찬가지로 뭐 전세계에서 사용하고 있는 실정.

  

통신을 위해서 사용자마다 할당된 코드를 변환 키로 이용하여 보내고자 하는 신호를 특유의 패턴으로 변환하여 전송하며, 수신측에서는 다시 이
키를 이용하여 패턴에서 원래의 신호를 복원한다. 이 때 다른 키를 이용해 만들어진 신호는 복원할 때 잡음처럼 변환되므로 키를 모르는 다른
사용자는 원래의 내용을 알수없어 보안성이 강하며, 여러 사용자가 같은 주파수 대역을 이용하기 쉬우므로 통화 효율이 높다.`[1]` 코드로
채널을 구분하여 전체 주파수를 사용하기 때문에 넓은 주파수 대역을 사용하여 Diversity(일정한 수신강도 유지)가 뛰어나고
Fading(급격한 송수신 주파수 변경)이 적으며 Soft Handoff(기지국을 바꿀 때 통화가 유지되는 것. 반대는 Hard
Handoff로, 잠깐 통화가 끊기는 것)가 쉽다.`[2]`

  

CDMA를 쉽게 이야기하면 같은 방에 여러사람이 대화하고 있는데 대화하고 있는 두 사람끼리는 같은 언어를 쓰고 또다른 사람들은 각각 다른
언어를 써서 이야기한다고 보면 된다.`[3]`

  

2G의 cdmaOne(본 문서의 2번 항목)에 적용되었으며 [3G](3G.md) 기술인 WCDMA와 HSPA 등도 CDMA 기술을
이용하지만, [LTE](LTE.md)나 [WiMAX](WiMAX.md) 등 [4G](4G.md)에는 적용되지 않았다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/CDMA?action=edit&section=2)]

## 2. 이동통신 규격 ¶

  * 상위 항목 : [2G](2G.md)

**국제전기통신연합(ITU) 인증 이동통신 기술**

구분

3GPP 계열

3GPP2 계열

IEEE 계열

기타

1세대(1G)

\-

AMPS

2세대([2G](2G.md))

[GSM](GSM.md)

[cdmaOne](CDMA.md)

2.5세대(2.5G)

GRPS  
EDGE  
(E-GPRS)

[CDMA2000 1x](CDMA2000.md)

3세대([3G](3G.md))

[WCDMA](WCDMA.md) \- UMTS  
[TD-SCDMA](TD-SCDMA.md)

[EV-DO](CDMA2000.md)  
[EV-DO rev. A·B](CDMA2000.md)

3.5세대(3.5G)

[HSDPA, HSUPA](WCDMA.md)  
[TD-HSDPA](TD-SCDMA#s-4.1.md)  
[TD-HSUPA](TD-SCDMA#s-4.2.md)

[EV-DO rev. C](CDMA2000.md)  
(UMB)

4세대([4G](4G.md))

HSPA+, [LTE](LTE.md)·[TD-LTE](TD-LTE.md)  
[LTE Advanced](LTE%20Advanced.md)  
([Carrier Aggregation](Carrier%20Aggregation.md))

[WiBro](WiBro.md)/[Mobile WiMAX](Mobile%20WiMAX.md)  
[WiBro Evolution](WiBro%20Evolution.md)

  

한국 통신사 주파수 할당 내역 - CDMA`[4]`

통신사

주파수

상향 대역폭

하향 대역폭

기타

[SK텔레콤](SK%ED%85%94%EB%A0%88%EC%BD%A4.md)

Band 0 800 MHz

5 MHz

5 MHz

CDMA 글로벌 통용 주파수

[KT](KT.md)

2012년 3월 19일부로 사업 철수

[LG U+](LG%20U+.md)

Band 4 1.8 GHz

10 MHz

10 MHz

공식적으로 전 세계에서 [LG U+](LG%20U+.md)만 **CDMA로 사용**`[5]`

  
미국에서 개발한 2세대 이통통신 서비스. **2G**라는 이름으로도 불리며
[SK텔레콤](SK%ED%85%94%EB%A0%88%EC%BD%A4.md)에서 "95A/B 방식"`[6]`이라고 부르는 것들도 여기에
해당한다. 스마트폰 보급 이후로 한국에서는 2G라고 하면
[스마트폰](%EC%8A%A4%EB%A7%88%ED%8A%B8%ED%8F%B0.md)이
아닌폰([피처폰](%ED%94%BC%EC%B2%98%ED%8F%B0.md))을 총칭하는 뜻으로 인식되기도 한데, 이는 대단히 잘못된
생각으로서 피처폰이라고 할지라도 **[쇼를 해라](olleh.md) 이후 세대부터 이미 2G와 전혀 관계없는
[3G](3G.md)([WCDMA](WCDMA.md))망을 사용한다.** 참고로 쇼를 해라가 등장한 게 2007년 3월경인데,
따라서 그 때의 기술력으로도 충분히 스마트폰 만들 수 있었다. 배때지 쳐부른 한국 이통사가 그쪽에 관심이 없어서 국산 스마트폰 출시가
3-4년이 늦어진 거지. 즉, **피처폰이라고 무조건 2G폰이 아니라 일부만 2G폰**이라는 뜻이다. 최근 구할 수 있는 2G 공기기들은
대부분 [CDMA2000](CDMA2000.md)이나 [EV-DO](CDMA2000#s-2.2.md)에 서술된 방식을 사용한다.
이 페이지는 cdmaOne, IS-95로 링크해도 접근할 수 있다.

  

[대한민국](%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD.md)에서는 90년대 중반 퀄컴의 CDMA
1X(cdmaOne, IS-95) 상용화 프로젝트를 실시하여, 1996년
[SK텔레콤](SK%ED%85%94%EB%A0%88%EC%BD%A4.md)의 전신인 한국이동통신이 디지털 011`[7]``[8]`이라는
이름으로, [신세기통신](%EC%8B%A0%EC%84%B8%EA%B8%B0%ED%86%B5%EC%8B%A0.md)이 파워디지털
017이라는 이름으로 세계 최초로 상용 서비스를 시작하였다. 두 회사의 주파수 대역은 소위 황금 주파수라고 불리는 800 MHz 대. 이 때
SK텔레콤은 22 MHz와 8 MHz를 할당받았고 신세기통신은 SK텔레콤이 할당받은 주파수 사이의 20 MHz를 할당받았다.

  

이듬해인 1997년에는 1.8 GHz대역의 CDMA 기술을 이용한 개인휴대 통신 서비스(PCS)를 한국 통신 프리텔`[9]`에서 PCS
016이라는 이름으로, 한솔PCS에서 원샷 018이라는 이름으로, [LG텔레콤](LG%20U+.md)에서 LG019PCS라는 이름으로
시작했다. 주파수는 세 회사 각각 20MHz씩 할당 받았다. 한솔PCS는 한솔엠닷컴으로 사명을 변경하였다가, 이후 KTF에
인수되었다.`[10]` 또한 2002년에 신세기통신은 SK텔레콤에 인수되었다.

  

2004년부터 이동전화의 식별번호를 사업자에 관계없이 010으로 통합하는 정책에 따라 신규가입의 경우 식별 번호를 010으로만 부여받게
되었다. 이는 번호이동 제도 운용 및 PCS 사업자를 배려하는 차원에서 이뤄졌으며 3세대 통신망 부터는 무조건 010 번호를 사용하게 되는데
이러한 정책으로 인하여 후술하는 문제가 발생하게 된다.

  

도입초기에는 세계최초의 CDMA상용화라는 측면에서 환영을 받았으나 로열티 문제로 비난을 받기도 했으며
[SK텔레콤](SK%ED%85%94%EB%A0%88%EC%BD%A4.md) VS PCS간의 통화품질 논쟁이 벌어지기도 했다.

  

사실 세계적으로는 [GSM](GSM.md)이 대세로, CDMA 계열의 이동통신 서비스를 제공하는 회사가 많지 않다.
<del>[갈라파고스](%EA%B0%88%EB%9D%BC%ED%8C%8C%EA%B3%A0%EC%8A%A4%ED%99%94.md)가 되고
싶지는 않을거 아냐</del> [대한민국](%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD.md)은 특이한 케이스로
모든 이동통신 회사에서 CDMA를 쓰고 있다. 이웃나라 중에는 [중국](%EC%A4%91%EA%B5%AD.md)의
[차이나텔레콤](%EC%B0%A8%EC%9D%B4%EB%82%98%ED%85%94%EB%A0%88%EC%BD%A4.md),
[일본](%EC%9D%BC%EB%B3%B8.md)의 [KDDI](KDDI.md)`[11]`가
[CDMA2000](CDMA2000.md)을 서비스중. 기술 원산지인 [미국](%EB%AF%B8%EA%B5%AD.md)에서도
[버라이즌](%EB%B2%84%EB%9D%BC%EC%9D%B4%EC%A6%8C.md)과
[스프린트](%EC%8A%A4%ED%94%84%EB%A6%B0%ED%8A%B8.md)만 CDMA를 사용한다.

  

그럼에도 우리나라에 수백만명의 가입자가 아직도 CDMA를 고수하고 있고, 이 때문에 통신사에서도 쉽사리 종료하지 못해 서비스를 유지하고 있는
이유는 **현행법상 기존의 식별번호(011, 016, 017`[12]`, 018, 019)를 그대로 사용할 수 있는 서비스는 CDMA가
유일**하기 때문이다. 사업상 번호유지가 절실하거나 혹은 오랜 시간 함께해온 번호를 쉽사리 버리지 못해서 어쩔 수 없이 CDMA에 남아 있는
것. 애초에 통신사별로 이 번호, 저 번호 따로 부여했다가 나중에 010으로 <del>강제</del> 통합하겠다는 정부<del>의
[병크](%EB%B3%91%ED%81%AC.md)</del>가 원인 제공자이다. 게다가 이젠 010도 부족해지고 있다(…).
<del>020 새로 만들고 그것도 모자라면 030에서 쓰던 기존 팩스번호는 한 곳으로 정리시키고선 할당할 지도 모른다</del>

  

참고로 [LG U+](LG%20U+.md)는 [2014년](2014%EB%85%84.md),
[SK텔레콤](SK%ED%85%94%EB%A0%88%EC%BD%A4.md)은 [2018년](2018%EB%85%84.md)에
CDMA 서비스를 종료할 예정이라고 한다.`[13]` 하지만 2015년이 지났지만 두 통신사 모두 CDMA를 종료하지 않고있다. 앞으로도
고객이 있으면 서비스를 유지하겠다고.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/CDMA?action=edit&section=3)]

### 2.1. KT의 2G 강제종료 사건 ¶

2007년 WCDMA를 비롯한 [3G](3G.md)서비스의 상용화 이후 CDMA가입자는 서서히 줄고 있다. 특히 **2011년 6월
30일에 2G/2.5G 서비스를 종료할 예정이었던** KT는 2009년경부터 단말기 공급을 거의 하지 않았고 3G로의 가입자 전환을
적극적으로 벌인 결과 2011년 5월 기준으로 가입자가 89만명에 불과한데, 이는 950만명에 달하는 SK텔레콤 2G가입자 수의 1/10에도
못 미친다. KT는 2011년 4월 7일부터는 신규가입도 아예 중단했다. 또한 KT에서는 2010년 부터는 기지국을 추가로 신설하지 않고
있기 때문에 불통되는 곳이 있을 수 있다.`[14]` 드디어 2011년 4월, KT에서는 [방송통신위원회](%EB%B0%A9%EC%86%A1%ED%86%B5%EC%8B%A0%EC%9C%84%EC%9B%90%ED%9A%8C.md)에 서비스 종료 신청을 했으나 허가를 받지
못해서 그 전에 <del>KT에 낚여서</del> 3G로 전환한 사람들만 [호구](%ED%98%B8%EA%B5%AC.md)가
되었다(...). 서비스 전환 노력이 부족하다는 이유로 승인 유보를 받았다고. 대략 50만명 이하까지는 돼야 허가가 날 듯.

  

2011년 9월 1.8 GHz 전파 경매에서 [SK텔레콤](SK%ED%85%94%EB%A0%88%EC%BD%A4.md)과 입찰과열이
일어나면서 통신비 인하방안에 먹구름을 끼게 한 정부의 병크가 터지자 [KT](KT.md)는 대승적 차원에서 주파수 입찰을 포기하겠다고
말했다. 하지만 소문으로는 정부에 잘보여서 [2G](2G.md) 종료허가 좀 받아보려고 그런다는 소문이 있었다. KT는 1.8 GHz를
받지 못했고 결국 1.8 GHz에서 서비스하던 2G를 종료하지 못하면 [LTE](LTE.md) 서비스를 시작할 수 없게 되면서 KT는
곤란한 상황에 빠졌다고 한다. 전화와 문자로 2G 종료 떡밥을 계속 날리면서 2011년 10월 현재 20만명의 가입자만 남았다고 한다.
2011년 10~11월엔 2G 고객 전부를 찾아다니며 2G를 해지해 달라고 요청하고 있다. 나이 든 직원이 찾아와서 집안사정까지 하소연하며
설득을 하는 모습 or 하청업체를 동원해 협박조로 설득하는 모습을 본 2G 고객들이 KT의 악랄함을 인터넷에 토로하고 있다.

  

2011년 11월 24일. 기어코 조건부이나마 2G 종료허가가 났다. 그 조건은 2주 뒤인 12월 8일까지 잔여 가입자 15만명에게
우편통지를 포함한 2가지 이상의 방법으로 2G종료 공지를 하는 것과 직권해지 6개월 유예`[15]` 이용자 보호대책으로는 자사 3G로
전환하면 월6,000원 x 24개월할인 + 3G 피쳐폰 무약정 제공, 3G 스마트폰으로 기기변경할 경우 특가<del>라 쓰고 생색내기라
읽는다</del>`[16]`로 제공. 해지(번호이동 포함) 시 가입비 환불 명목으로 30,000원`[17]`지급. 쓰고 있던 핸드폰 반납시
기기보상금 33,000원 추가 보상. 교통비 명목으로 10,000원 보상. 합계 40,000원~73,000원 보상. 선불폰은 일괄적으로
10,000원 보상.

  

그 와중에 2011년 12월 7일 서울행정법원은 모 카페 회원과 KT 2G 이용자 900여명이 2G 서비스 중단을 정지해달라며
방송통신위원회을 상대로 낸 **KT PCS 서비스 중단 승인 집행정지** 가처분 신청을 받아들여서 KT는 예기치 않은 상황에 부딪치게
되었다. 이 판결 소식에 충격 받은 <del>KT</del>방송통신위원회는 <del>전투력을 긴급 보강하여</del> 즉시항고를 하였으며,
2011년 12월 26일 판결에서는 결과를 완전히 뒤집는 상황이 발생하였다.

  

이로서 KT는 2G(CDMA)서비스를 종료를 할 수 있게 되었고 새로운 LTE 광고<del>성질급한 한국사람</del>가 나오면서
[LTE](LTE.md) 서비스가 시작되었다. 2012년 1월 3일 서울을 필두로 단계적으로 종료가 시작되었다.

  

**KT PCS(2G) 서비스 종료 일자별 해당 지역**  

  * 2012년 1월 3일: 서울특별시 전 지역 종료
  * 2012년 1월 18일: 6대 광역시, 경기도 17개 시(市), 제주도 전지역 종료
  * 2012년 2월 2일: 경기도 10개 시(市), 지방 58개 모든 시(市)`[18]`지역 종료
  * 2012년 3월 19일: 그 외 나머지 전 지역(군(郡)지역) 종료 - **완전 종료 완료**.  
이로서 2012년 3월 19일 오전 10시, 전국의 모든 KT 2G 기지국의 [전원이 내려졌고](%EC%9E%A5%EB%B9%84%EB%A5%BC%20%EC%A0%95%EC%A7%80%ED%95%A9%EB%8B%88%EB%8B%A4.md), 이렇게 **KT의 2G 서비스는
역사속으로 사라졌다.**  

간혹 "어? 저 KT에서 2G폰 쓰고 있는데 아직 잘 되는데요." 또는 "말로만 종료한다고 하고, 실제로는 아직 종료 안 했어요." 라는
사람들도 있고, 심지어 "난 끝까지 버틸 거야. 쓰는 사람이 있는데 지들이 어떻게 끊어?" 라며 아직 2G에 버티고 있는 것처럼 말하며
엄청난 보상`[19]`을 기대하는 <del>아주 무식한</del> 사람도 간혹 있는데, 이런 사람들은 뭔가 단단히 착각하고 있는 것이다.
KT의 2G서비스는 이미 2012년초에 종료되어서 진짜 KT 2G폰은 현재 전화가 아예 터지지도 않으며 시각이 맞지 않아 시계로도 쓸 수
없다. 현재 전화가 잘 된다면 그것은 2G폰이 아니라 3G폰으로서 서비스 종료와는 전혀 관계가 없다. <del>아무리 기다려도 안 끊긴다
3G 종료는 아직 멀었다</del>

  

이러한 오해는『2G=일반폰, 3G=스마트폰』이라고 잘못 알려진 공식 때문이다. 일반폰(피처폰)이라고 하여도 오히려 3G폰이 훨씬 더 많다.
특히 KT는 2007년 3G 서비스 런칭이후부터는 <del>이 기회에 2G 시절의 만년 SK텔레콤 콩라인에서 벗어나려고 SHOW라는 별도의
3G 서비스 브랜드까지 등장시켜 엄청난 광고 물량공세와 3G 위주의 폰 공급거기에 공짜로 폰 바꿔준다는 텔레마케팅 등의 막장영업까지 동원한
2G 죽이기을 하는 등</del> 치열한 마케팅의 결과, 첨부터 3G 가입자의 비율이 이동통신사 3사중 가장 높았다. 기기가 거의 안
나오다보니 대부분의 KT 가입자들은 폰 바꾸면서 알게 모르게 이미 3G로 다 넘어 간 것. 참고로 2008년 5월 출시된 와인 2(LG-
KV3900)가 마지막 KT 2G폰이다. 폰에 SHOW 마크가 있으면 2G폰이 아니라 무조건 3G폰이다. 자세한 것은
[피처폰](%ED%94%BC%EC%B2%98%ED%8F%B0.md)항목 참조.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/CDMA?action=edit&section=4)]

### 2.2. KT 2G 완전 종료 이후 ¶

이에 원고측도 대법원에 재항고를 하였으나, 2012년 2월 1일 기각되었다. 이 후 본안소송이 시작되어 2012년 3월에 다시 준비서면을
제출하였으나, 2012년 5월 8일 서울행정법원은 이를 기각하였다. 그리고 서울고등법원 항소심, 대법원의 상고심 모두 기각되었다.`[20]`

  

이와 별개로 **01X는 2G망의 휴대폰만 사용 가능**`[21]``[22]`에 대한 부당함으로 모 카페에서는 **이동전화 식별번호 통합추진
위헌소송**을 오래 전부터 준비하고 있었으며, 2012년 5월 8일에 헌법재판으로는 드물게 **공개변론**까지도 진행이 되었음에도 불구하고
2013년 7월 25일, [헌법재판소](%ED%97%8C%EB%B2%95%EC%9E%AC%ED%8C%90%EC%86%8C.md)는
"이동전화 식별번호 통합추진 위헌확인"을 각하, 기각했다.[헌법재판소 2011헌마63](http://www.ccourt.go.kr/home/
storybook/storybook.jsp?eventNo=2011%ED%97%8C%EB%A7%8863&mainseq=130&seq=21&li
st_type=05)

  

[[edit](http://rigvedawiki.net/r1/wiki.php/CDMA?action=edit&section=5)]

### 2.3. 어떻게든 스마트폰을 사용해보고 싶다 ¶

이러한 정책 등의 이유로 01X번호를 버릴 수 없는 사람은 2G에 머무를 수 밖에 없고, 2G망으로는
[스마트폰](%EC%8A%A4%EB%A7%88%ED%8A%B8%ED%8F%B0.md)을 쓸 수 없다고 알려져 있다. 그러나 그건 한국
단말기가 그런 거고 2G에 스마트폰을 쓸 방법은 존재한다. 이는 한국처럼 CDMA를 쓰는 특이한 곳으로 미국의
[버라이즌](%EB%B2%84%EB%9D%BC%EC%9D%B4%EC%A6%8C.md)과
[스프린트](%EC%8A%A4%ED%94%84%EB%A6%B0%ED%8A%B8.md)가 존재하기 때문으로, 이게 SK텔레콤과 비슷한
전파망이라서 조건이 맞는 공기계를 구해 SK텔레콤에서 개통시키면 **이론적으로는** 사용 가능한 것이다.

  

하지만 이 방법은 통신이 느린게 문제가 아니라 **굉장히 장대한 삽질**을 거쳐야 한다는 것이 문제이다.`[23]` 일단 적절한 단말기를
멀리서 사 와야 하는데 재수가 없으면 국내 기기와 ESN(일련번호) 중복`[24]`으로 등록이 불가한 경우도 있어서 최악의 경우 수십만원을
날릴 각오를 해야 한다.

  

운이 좋아 일련번호 중복을 피해서 등록을 거쳤다고 해도 이게 끝이 아니다. 정상적으로 사용하기 위해서는 서비스 프로그래밍을 거쳐야 하며,
그냥은 한글 [SMS](SMS.md)를 쓰지 못하는 등 정상 사용이 안 돼 펌웨어를 개조하거나 [커스텀펌웨어](%EC%BB%A4%EC%8A%A4%ED%85%80%20%ED%8E%8C%EC%9B%A8%EC%96%B4.md)를 만들어야 해
[안드로이드 계열과 관련된](%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C%28%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%29.md) **개발 능력이 반드시 필요**하며, 이마저도 **[MMS](MMS.md)는
사용할 수 없다**.`[25]`.`[26]` 그리고 SK텔레콤은 등록만 해 줄 뿐, 개통을 보장하지 않는다. 즉 이 과정들을 스스로 하여야
한다는 뜻. 그래도 스마트폰을 사용 가능하다는 것에 의미가 있어 010 통합반대 운동본부 등지에서 정보공유나 <del>단말기
유통</del>이 이루어지고 있는 것 같다. 단말기 구입은 ebay 등 해외 사이트에서 구입이 가능하다.

  

사실 저 방법은 2012~3년에야 나온 거고, 일반적인 경우 2G 피처폰에 [OPMD](OPMD.md)를 가입하여 USIM 꽂아 쓰거나
아예 **회선을 하나 더 개통하여**(...) 사용하는 경우가 많다. 수신은 착신전환으로 하고 발신은 통신사 바깥의 서비스를 이용하면 된다.

`\----`

  * `[1]` 사실 이론적으로는 CDMA 말고 FDMA(주파수 분할)이나 TDMA(시간 분할)이나 통화 효율은 같다. 하지만 FDMA나 TDMA는 실이용에서 혼신을 막기위해 필요한 영역(Guard Band/Guard Time)이 CDMA에 비해 훨씬 크기 때문에 실제 효율은 떨어진다.
  * `[2]` 실예로 GSM은 Soft Handoff가 안된다. 다만 [4G](4G.md)는 최신 기술이라 그런 문제가 없다.
  * `[3]` 이 비유로 CDMA의 성질을 한가지 더 설명할수 있는데, 남들이 너무 시끄럽게 말한다면 외국어라 해도 자기 말도 알아듣기 힘들것이다. 마찬가지로 CDMA도 한개의 단말기가 너무 신호를 세게 전송하면 다른 단말기는 통신에 심각한 문제가 생긴다. 따라서 CDMA 단말기는 신호 세기를 적절히 조절하는 기능이 중요하다.
  * `[4]` CDMA 주파수는 WCDMA - LTE 주파수와는 다르게 아예 다른 밴드로 묶는다. [CDMA 주파수 목록](http://niviuk.free.fr/cdma_band.php) 이에 따르면 SK텔레콤은 Band 0, LG U+는 Band 4. WCDMA/LTE 밴드 기준으로 표기한다면 SK텔레콤은 Band 5, LG U+는 Band 3이 된다.
  * `[5]` 2011년 까지 KT도 사용했지만, KT의 철수로 지금은 [LG U+](LG%20U+.md)만 사용하고 있다. 비공식적으로 한국 이외의 국가에서는 칠레의 <del>없다고 해도 무방한</del> 듣보잡 이동통신사가 이를 사용중이다.
  * `[6]` 구형 흑백폰이 해당되며 2011년 6월 30일부로 서비스 종료. 다만, 흑백폰이라 하더라도 대부분은 설정을 바꾸면 로밍 형태로 CDMA2000망에 접속하여 계속 사용이 가능하며, 1996~97년에 나온 극히 일부 구형 폰만 사용이 불가능하다.
  * `[7]` 이전에도 한국이동통신의 이동전화 011이 있었지만, AMPS기술을 이용한 1세대 이동전화였다.
  * `[8]` 이 브랜드는 1년뒤인 1997년 2월에 그 유명한 SPEED 011로 바뀌게 된다.
  * `[9]` 이후 사명을 케이티프리텔(KTF)로 변경 하였고, 2009년 모기업인 [KT](KT.md)에 합병되어 오늘날에 이른다.
  * `[10]` 사실 두 회사는 개통 초기부터 망을 공유했다.
  * `[11]` 얘네들은 R-UIM이라는 CDMA 전용 SIM 카드를 사용하고 있다.
  * `[12]` 이는 대통령 전용 식별번호로 최근에는 사용되고 있다.
  * `[13]` 아직 두 통신사 모두 공식적인 종료 일정을 발표하지는 않았으며, 일단 언론에서 알려진 CDMA 서비스 종료년도이므로 실제로는 달라질 수도 있다.
  * `[14]` [KTX](%EA%B2%BD%EB%B6%80%EA%B3%A0%EC%86%8D%EC%84%A0.md) 2단계 구간인 [동대구](%EB%8F%99%EB%8C%80%EA%B5%AC%EC%97%AD.md)~[부산](%EB%B6%80%EC%82%B0%EC%97%AD.md) 구간과 [공항철도](%EC%9D%B8%EC%B2%9C%EA%B5%AD%EC%A0%9C%EA%B3%B5%ED%95%AD%EC%B2%A0%EB%8F%84.md), [부산 도시철도 4호선](%EB%B6%80%EC%82%B0%20%EB%8F%84%EC%8B%9C%EC%B2%A0%EB%8F%84%204%ED%98%B8%EC%84%A0.md)의 거의 전 구간이 불통이다. 돈을 받고 서비스하는 상용서비스임에도 하루 수만명이 이용하는 구간에서 불통이라니...
  * `[15]` 군입대로 인한 정지자 및 해외체류자 24개월. 단, 완전종료 시점이전부터 장기정지 중인 경우만 가능.
  * `[16]` 일부 오프라인 대리점이나 인터넷에서 구입하는 것 보다도 훨씬 조건이 안 좋았다. 심지어 일부 기종은 신규가입보다도 할부원금이 높은 경우도 있었다(...).
  * `[17]` 2000년 11월 30일 이전의 KTF(PCS016)의 가입비는 50,000원이었으며, 가입비는 보증금 개념이 아닌 1회성 납부금액이며 일괄적으로 책정된 것이라 추가 지급은 불가하다는 입장. 백번 양보하더라도 01X 번호 보존을 위해 그나마 2G를 오래 유지할 것으로 예상되는 SK텔레콤으로 가려면 39,600원의 가입비가 필요하며 스마트폰과는 달리 보조금이 전혀 없는 수십만원(!)대의 2G 단말기를 자비로 구입해야 한다.
  * `[18]` 2012년 새롭게 시로 승격된 당진시와, 2012년 하반기 출범예정인 세종특별자치시 편입예정지역 포함
  * `[19]` 인터넷 등 카더라 통신에서는 "통영 삐삐 할아버지" 등 통신 서비스 종료보상으로 돈벼락 맞은 사례가 마치 사실처럼 전해지고 있는데 그런 것들은 **당연히 헛소문**이다. 2012년 KT 2G 종료 보상은 해지시 현금 40,000원(기기반납시 73,000원) 지급 또는 KT 3G로 전환시 24개월간 월6,000원 할인이 전부이며, 더 이상의 보상은 사실상 일절 없었다. 이 마저도 본인이 직접 신청하지 않으면 얄짤 없이 직권해지다. 즉, 버티면 보상은 커녕 번호마저도 소멸된다. 이는 앞으로의 타 통신사 혹은 타 통신 서비스 종료시에도 비슷할 것으로 예상된다.
  * `[20]` 이미 KT의 LTE망이 많은 지역에 깔리게 되면서 극소수를 위한 2G망을 복원시키기란 사실 무리가 있다.
  * `[21]` 2011년부터 **한시적인** 01X에서 3G 사용가능 제도가 생겼으나 2013년 12월 31일까지이다. 그 이후에는 미리 맵핑된 010 번호를 부여 받게 된다.
  * `[22]` LG U+의 CDMA EVDO Rev. A/B는 원래 2G의 개량버전이나 3G로 보기도 하며, 일단 국내에서는 3G로 분류되어서 010만 가입가능.
  * `[23]` 위험성이 상당히 크기 때문에 자료는 있으나 링크는 하지 않았음을 알린다. 해당 글을 작성한 유저들은 질문 일일이 받기 상당히 힘들다(...).
  * `[24]` ESN은 그 구조상 [IMEI](IMEI.md)에 비해 기기에 할당 가능한 경우의 수가 훨씬 적기 때문이다.
  * `[25]` 다만 삼성 갤럭시가 존재해서 좀 나은 경우도 있다. 성공사례가 있다.
  * `[26]` 일반적인(3G WCDMA/LTE) 해외 스마트폰에서도 [MMS](MMS.md) 문제가 발생하는데, 상당수의 경우 [joyn](joyn.md)이나 T메시지 설치로 해결 가능한 것처럼, 2G CDMA 스마트폰에서도 T메시지 설치로 MMS 문제는 불완전하나마 해소는 가능은 하다. T메시지 없이 성공한 사례는 [이 글과](http://blog.naver.com/hkbemil/130182813862), [이 글](http://blog.naver.com/jgkim30/207520300)을 참고.

