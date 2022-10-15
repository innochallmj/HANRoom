<img src="https://capsule-render.vercel.app/api?type=waving&color=7BD1D2&height=270&section=header&text=HanBang%20&fontSize=90&fontColor=363636" />


<h3 align="center">✨Welcome to HANBANG✨</h3>
<h4 align="center">Team Name: 공우꺼</h4>
<h4 align="center">Project Name: 한 방</h4>

<h2 align="center"> 캡스톤 디자인 시연동영상 : https://youtu.be/MEHMfiI7w0E </h2>


## Profile
- 이영주(전자공학과)
> phone: 010-4057-3740 <br>
> e-mail: magic3740@naver.com
 
- 이명주(스마트iot) 
> phone: 010-9634-5012 <br>
> e-mail: innochallmj@naver.com

- 이소민(스마트iot)
> phone: 010-5490-9132 <br>
> e-mail: somin9132@naver.com

- 홍소희(빅데이터학과)
> phone: 010-5580-8941 <br>
> e-mail: ghdthgml3578@naver.com

- 윤희연(빅데이터학과)
> phone: 010-9261-3422 <br>
> e-mail: dkzndk05@naver.com<br>

---------------------------------------

## Execution Plan
- summary
>  학기가 시작되기 전, 많은 학생들 또는 한림대학교 근처 직장에 근무하는 사람들이 자취방을 구하기 위한 노력을 한다. 하지만, 직방같은 어플이나 에브리타임, 한림대 다음 카페와 같은 커뮤니티 어플에는 학교 주변의 원룸에 관한 정보가 많이 나와 있지 않다. 그래서 흔히 ‘발품을 팔아’ 방을 구하곤 한다. 하지만 코로나가 잠잠해지지 않는 요즘에는 많은 자취방을 돌아다니며 맘에 드는 방을 구하기가 힘들고, 외부인에게 자신이 거주하는 방을 보여주는 것이 꺼려진다.
 그래서 우리는 한림대학교 주변의 방 정보를 제공하는 어플이 있으면 좋겠다고 생각해 이 주제를 선정하게 되었다. 한림대학교 주변 방의 정보를 사용자에게 알려주고, 방 정보를 등록하고 싶은 사람은 등록할 수 있도록 하여 집 주인과 계약자가 조금 더 편리하게 방을 알아보고 계약할 수 있도록 하는 어플을 만들 계획이다. 사용자가 거주하고 싶은 위치와 주변 편의시설, 가격 등을 고려하여 검색할 수 있는 기능을 함께 만들어 원하는 방을 조금 더 빠르게 찾을 수 있도록 한다.

- Plan
>  한림대학교 근처에 많은 방 정보를 일일이 검색해서 찾아야 하는 번거로움을 줄이고, 맞춤 검색, 거주민 리뷰 등의 기능들을 이용하여 보다 편리하고 쉽게 집을 구할 수 있도록 하기 위함이다.

- Contents
> 우리가 개발할 어플리케이션의 기능을 크게 세 가지로 나누면 집주인이 내놓은 집에 대한 정보, 예를 들면 월세나 보증금, 집 안의 방 개수 등을 입력하여 등록하는 기능, 원하는 조건의 집을 쉽게 찾아 구할 수 있도록 특정 조건을 포함해서 검색하는 맞춤 검색 기능, 교통 여건, 주변 환경 등 직접 살아본 사람들의 별점 리뷰와 솔직한 리뷰를 읽어볼 수 있는 거주민 리뷰 기능으로 나뉜다.
 우선 첫 번째로, 집주인이 집의 정보를 등록할 수 있는 기능에서 월세 및 보증금, 위치 주변 시설뿐만 아니라 집의 이미지나 영상이 등록 가능 하도록 만들 것이고, 이를 DB에 저장할 것이다.
 집을 찾는 사람을 위한 맞춤 검색 기능에서는 원하는 조건으로 검색 시 알맞는 집의 정보가 출력되도록 java를 기반으로 하는 앱에 DB를 연동시킬 것이다. 
 마지막으로 거주민 리뷰 기능에서는 우선 집에 대한 리뷰를 작성하는 사람이 실거주자인지 확인을 해야 한다. 그러므로 리뷰를 작성하기 위해서는 택배 운송장이나 고지서 등으로 확인하는 절차를 거친 후 리뷰를 작성 가능하도록 한다. 또한, 허위로 작성된 리뷰는 신고할 수 있도록 신고 기능을 추가할 것이다. 그리고 비슷한 어플들과 차별을 두기 위해서 거주자와 집을 찾고 있는 사람들 간의 커뮤니티 공간을 만들어 필요한 정보를 얻을 수 있도록 하고, 거주자가 놓고 가는 가구나 거주자가 필요하지 않은 물건 등을 사고 팔 수 있는 기능도 함께 만들 예정이다.
 
 ------------------------------------------------
 
 - Expectancy Effects
 > 1. 학교 근처에 원하는 조건의 매물을 직접 발품 팔며 돌아다니지 않고도, 어플에서 제공하는 지도 뷰를 통해 매물 주변의 교통 여건이나 편의 시설 등의 주변 환경을 볼 수 있으며, 매물 시설을 사전에 건물주가 올려놓은 영상이나 이미지 화면으로 볼 수 있어 매물에 대한 상세정보 확인도 가능하기 때문에 매우 효율적으로 원하는 매물을 알아볼 수 있다.  
> 2. 실거주민들의 직설적인 평가와 리뷰 작성 기능으로 실시간으로도 솔직한 후기 확인이 가능하며, 매물에 대한 건물주와의 소통 뿐만 아니라 사용자들 간의 소통도 원활히 가능하다.
> 3. 빅데이터에 저장된 매물 정보들을 통해 사용자 맞춤 매물 추천 서비스 기능을 적극 활용할 수 있도록 하여, 원하는 조건에 부합하지 않는 매물 탐색 시간은 줄여주되 소비자의 만족은 최대로 줄 수 있는 매물 탐색이 가능하다.
> 4. 매물 탐색 과정 중 마음에 들었던 매물들에 대해서만 다시 볼 수 있도록 저장하는 기능이 있어 일일이 어떤 매물이 괜찮았는지 기억할 필요 없이 한번의 클릭으로 불편함을 해소시켜 준다.
> 5. 새로운 매물에 대한 상시 업데이트가 가능하여 주기적으로 발품을 팔며 다니지 않고도 상시 올라오는 매물 정보 수집이 가능하다.

- Utilization Plan
> 집을 구하기 위해 고생하는 학생들을 위해 한림대학교에서만 한정되는 어플이 아니라, 더 나아가 다른 학교들이나 회사까지도 적용할 수 있는 효과를 기대한다.



