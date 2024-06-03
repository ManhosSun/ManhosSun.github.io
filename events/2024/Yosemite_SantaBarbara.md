@def title = "요세미티 공원과 산타 바바라 여행"

@def tags = ["2024", "요세미티 공원", "산타 바바라", "여행"]

# 요세미티 공원과 산타 바바라 여행

2024년 5월 27일은 공휴일인 메모리얼 데이입니다.
우리 부부는 공휴일을 맞아 요세미티 공원을 여행할 계획을 세웠습니다.
더스티도 함께 가고자 합니다.
더스티의 추천으로 산타 바바라도 들를 계획입니다.

\tableofcontents <!-- you can use \toc as well -->

##  여행 일정 및 장소
여행 일정은 다음과 같습니다.

@@image-center
![](/assets/images/events/2024/travel_map.jpg)
@@
@@image-caption
여행 경로
@@
\\


1. 첫째날 (5월 26일)
   * 집 -> Hyatt Place Fresno

@@image-center
![](/assets/images/events/2024/day1map.jpg)
@@
@@image-caption
첫째날 경로 (집에서 Hyatt Place Fresno)
@@
\\

2. 둘째날 (5월 27일)
   * Hyatt Place Fresno -> Yosemite Valley Lodge

@@image-center
![](/assets/images/events/2024/day2map.jpg)
@@
@@image-caption
둘째날 경로 (Hyatt Place Fresno에서 Yosemite Valley Lodge)
@@
\\

3. 세째날 (5월 28일)
   * Yosemite Valley Lodge에서 계속 머뭄

4. 네째날 (5월 29일)
   * Yosemite Valley Lodge -> Mar Monte Hotel

@@image-center
![](/assets/images/events/2024/day4map.jpg)
@@
@@image-caption
네째날 경로 (Yosemite Valley Lodge에서 Mar Monte Hotel)
@@
\\

5. 다섯째날 (5월 30일)
   * Mar Monte Hotel에서 계속 머뭄

6. 여섯째날 (5월 31일)
   * Mar Monte Hotel -> 집

@@image-center
![](/assets/images/events/2024/day5map.jpg)
@@
@@image-caption
다섯째날 경로 (Mar Monte Hotel에서 집)
@@
\\

## 사전 정보

### Hyatt Place Fresno

우리가 첫날밤에 묵을 호텔!
실내 수영장과 운동설비를 갖추고 조식도 무료 제공해주는 멋진 호텔입니다.
호텔에 전기 자동차 충전기도 갖추어 투숙객이 무료로 충전할 수 있습니다.
호텔 웹사이트에서 찾은 멋진 사진들을 훑어보며 마음껏 즐기리라 다짐합니다.

~~~

<!-- Container for the image gallery -->
<div class="slideContainer">

  <!-- Full-width images with number text -->
  <div class="mySlides">
    <div class="numbertext">1 / 5</div>
      <img src="/assets/images/events/2024/Hyatt-Place-Fresno-Breakfast.webp" style="width:100%">
  </div>
  <div class="mySlides">
    <div class="numbertext">2 / 5</div>
      <img src="/assets/images/events/2024/Hyatt-Place-Fresno-Coffee.webp" style="width:100%">
  </div>
  <div class="mySlides">
    <div class="numbertext">3 / 5</div>
      <img src="/assets/images/events/2024/Hyatt-Place-Fresno-Gallery-Kitchen.webp" style="width:100%">
  </div>
  <div class="mySlides">
    <div class="numbertext">4 / 5</div>
      <img src="/assets/images/events/2024/Hyatt-Place-Fresno-Indoor-Swimming-Pool.webp" style="width:100%">
  </div>
  <div class="mySlides">
    <div class="numbertext">5 / 5</div>
      <img src="/assets/images/events/2024/Hyatt-Place-Fresno-King-Corner.webp" style="width:100%">
  </div>

<!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="/assets/images/events/2024/Hyatt-Place-Fresno-Breakfast.webp" style="width:100%" onclick="currentSlide(1)" alt="조식 부페">
    </div>
    <div class="column">
      <img class="demo cursor" src="/assets/images/events/2024/Hyatt-Place-Fresno-Coffee.webp" style="width:100%" onclick="currentSlide(2)" alt="커피와 차">
    </div>
    <div class="column">
      <img class="demo cursor" src="/assets/images/events/2024/Hyatt-Place-Fresno-Gallery-Kitchen.webp" style="width:100%" onclick="currentSlide(3)" alt="부엌">
    </div>
    <div class="column">
      <img class="demo cursor" src="/assets/images/events/2024/Hyatt-Place-Fresno-Indoor-Swimming-Pool.webp" style="width:100%" onclick="currentSlide(4)" alt="실내 수영장">
    </div>
    <div class="column">
      <img class="demo cursor" src="/assets/images/events/2024/Hyatt-Place-Fresno-King-Corner.webp" style="width:100%" onclick="currentSlide(5)" alt="소파 슬리퍼가 있는 킹베드 객실">
    </div>
  </div>
</div>

<div style="clear: both"></div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("demo");
  let captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
  captionText.innerHTML = dots[slideIndex-1].alt;
}
</script>
~~~
\\

### Wawona Hotel

Wawona Hotel은 캘리포니아 주 요세미티 국립공원에 위치한 역사적인 호텔입니다. 1856년에 처음 개장한 이 호텔은 요세미티 국립공원에서 가장 오래된 호텔 중 하나로, 빅토리아 스타일의 건축 양식을 자랑합니다.

주요 특징 및 역사:

1. **역사적 배경**:
   - Wawona Hotel은 19세기 중반 골드 러시 시기에 지어졌습니다.
   - 원래는 피터 조든(Peter Jorden)이 "클락 앤드 무어즈"라는 이름으로 세웠으며, 이후 현재의 이름으로 변경되었습니다.
   - 1977년에는 국가 사적지(National Historic Landmark)로 지정되었습니다.

2. **건축 및 디자인**:
   - 빅토리아 양식의 건물로, 고전적인 목재 구조와 넓은 베란다가 특징입니다.
   - 아름다운 정원과 골프 코스가 주변에 있으며, 방문객들에게 고전적인 매력을 제공합니다.

3. **시설 및 서비스**:
   - 호텔에는 전통적인 객실, 식당, 라운지 및 다양한 편의 시설이 마련되어 있습니다.
   - 숙박객들은 주변의 트레일, 승마, 골프 등의 야외 활동을 즐길 수 있습니다.

4. **위치 및 접근성**:
   - Wawona Hotel은 요세미티 국립공원의 남쪽 입구 근처에 위치해 있으며, 요세미티 밸리(Yosemite Valley)와 마리포사 그로브(Mariposa Grove)와 가깝습니다.
   - 차량으로 쉽게 접근할 수 있으며, 공원 내부 셔틀 버스 서비스도 제공합니다.

Wawona Hotel은 자연과 역사의 아름다움을 동시에 즐길 수 있는 장소로, 요세미티 국립공원을 방문하는 많은 관광객들에게 인기 있는 숙소입니다.

### Washburn Point

@@image-center
![](/assets/images/events/2024/WashburnPoint.jpg)
@@
@@image-caption
Washburn Point
@@
\\

Washburn Point은 아름다운 전망을 제공하는 곳으로, 이곳에서는 Half Dome과 Sierra Nevada 동쪽 크레스트의 경치를 감상할 수 있습니다.
Washburn Point는 Glacier Point에서 약 1마일 떨어진 곳으로, Half Dome을 아름답게 감상할 수 있는 독특한 전망을 제공합니다. 
또한, 이 위치에서 방문객들은 "거대한 계단" 폭포인 Nevada와 Vernal, 그리고 Illilouette 폭포를 감상할 수 있습니다. 
이 지점은 Wawona에서 Yosemite Valley로 가는 최초의 도로를 건설한 Washburn 형제의 이름을 따서 지어졌습니다.

Half Dome은 요세미티에서 가장 눈에 띄는 랜드마크 중 하나입니다. 
이 화강암 돔의 정상은 계곡 바닥에서 4,800피트 떨어져 있으며 총 고도는 8,844피트(2,695미터)입니다. 

### Glacier Point

@@image-center
![](/assets/images/events/2024/GlacierPoint.jpg)
@@
@@image-caption
Glacier Point
@@
\\

Glacier Point는 요세미티 계곡 위에서 멋진 경치를 제공하는 세계적으로 유명한 전망대입니다. 
이 곳에서는 요세미티 계곡, Half Dome, 그리고 Yosemite Falls를 감상할 수 있으며, 공원의 남동쪽 고봉들도 매혹적으로 펼쳐집니다.

Glacier Point는 요세미티 계곡이 위치한 Yosemite Valley 또는 Wawona에서 각각 30마일(약 1시간 운전) 떨어진 곳에 있습니다. 
날씨가 허용되는 한 도로는 열려 있으며, 눈이 도로를 덮고 상태가 허용되면 크로스컨트리 스키 트랙이 유지됩니다. 
Glacier Point에서는 짧고 포장된 휠체어 접근 가능한 산책로를 따라 Yosemite Valley의 Curry Village에서 3,214피트 높이의 지점까지 갈 수 있습니다. 
이곳에서는 Yosemite의 고산 지역을 감상할 수 있습니다.

### Bridalveil Fall

@@image-center
![](/assets/images/events/2024/BridalveilFall.webp)
@@
@@image-caption
Bridalveil Fall
@@
\\

Bridalveil Fall은 캘리포니아 요세미티 계곡에서 가장 눈에 띄는 폭포 중 하나입니다. 
이 폭포는 높이 188미터(617피트)로 연중 흐르며, Yosemite Valley를 따라 내려오는 물줄기 중 하나입니다. 


### Lower Yosemite Fall

@@image-center
![](/assets/images/events/2024/LowerYosemiteFall.webp)
@@
@@image-caption
Lower Yosemite Fall
@@
\\

@@image-center
![](/assets/images/events/2024/lowerYosemiteFall.jpg)
@@
@@image-caption
Lower Yosemite Fall 가는 길
@@
\\

Lower Yosemite Fall은 북미에서 가장 높은 폭포의 일부로, 최종적으로 320피트(98미터) 떨어집니다. 
봄과 초여름에는 폭포의 물량이 최고조에 달해 소리가 귀를 찢을 듯하게 크며, 기저에서 발판 위에 서면 물을 뿌려받을 수 있습니다. 
이 짧고 쉬운 산책로는 상하로 요세미티 폭포의 화려한 경치를 감상할 수 있습니다. 
포장된 루프 트레일은 요세미티 폭포와 요세미티 크릭의 다양한 전망점을 제공하며, 자연과 문화 역사에 대해 자세히 알아볼 수 있는 다양한 전시물이 있습니다.



### Cathedral Beach

@@image-center
![](/assets/images/events/2024/CathedralBeachPicnicArea.jpg) 
@@
@@image-caption
Entrance to Cathedral Beach Picnic Area from Southside Drive
@@
\\

Cathedral Beach는 요세미티 계곡에 위치한 아름다운 피크닉 지역입니다. 
이곳은 Merced 강을 따라 펼쳐진 풍경을 감상할 수 있는 피크닉 테이블과 그릴이 편리하게 배치되어 있습니다. 
El Capitan의 경치를 제공하며, 해변에서 짧은 산책로를 따라 가면 주차장에서 쉽게 접근할 수 있습니다. 
이곳은 Bridalveil Fall에서 몇 마일 떨어진 Southside Drive에 위치해 있으며, 무료 요세미티 계곡 셔틀(정류장 #10)을 통해 접근할 수도 있습니다. 

@@image-center
![](/assets/images/events/2024/shuttlemap.jpg)
@@
@@image-caption
Yosemite Shuttle 지도
@@
\\

@@image-center
![](/assets/images/events/2024/YosemiteMap.jpg)
@@
@@image-caption
요세미티 공원 지도
@@
\\

### Vernal Falls
Vernal Falls는 미국 캘리포니아주에 위치한 요세미티 국립공원 내의 유명한 폭포입니다. 이 폭포는 메르세드 강(Merced River) 상류에 위치해 있으며, 약 97미터(318피트)의 높이를 자랑합니다. Vernal Falls는 요세미티의 아름다운 자연 경관 중 하나로, 많은 등산객과 관광객들이 방문하는 명소입니다.

1. **위치**: Vernal Falls는 요세미티 밸리의 동쪽 끝에 위치하며, Mist Trail이라는 인기 있는 등산로를 통해 접근할 수 있습니다. 이 등산로는 네바다 폭포(Nevada Fall)까지 이어지며, 총 길이는 약 8.7킬로미터(5.4마일)입니다.

2. **등산 경로**: Mist Trail은 Vernal Falls로 가는 가장 인기 있는 경로입니다. 이 경로는 이름에서 알 수 있듯이 폭포에서 흩날리는 물안개로 인해 대부분의 길이 미끄럽고 젖어있습니다. 등산객들은 경로를 따라가며 멋진 경치를 감상할 수 있습니다.

3. **계절**: Vernal Falls는 봄과 초여름에 가장 아름답습니다. 이 시기에는 눈 녹은 물이 강을 따라 흘러 폭포의 수량이 많아지고, 강력한 수압을 자랑합니다. 여름과 가을에는 수량이 줄어들지만, 여전히 인상적인 경치를 제공합니다.

4. **안전**: Vernal Falls 근처의 등산로는 미끄럽고 가파른 구간이 많아 안전에 주의해야 합니다. 적절한 등산화와 충분한 물을 준비하는 것이 중요합니다.

Vernal Falls는 자연의 아름다움과 요세미티의 웅장함을 직접 경험할 수 있는 장소로, 많은 사람들이 이곳에서 자연의 경이로움을 즐기며 휴식을 취합니다.

@@image-center
![](/assets/images/events/2024/vernalnevadaphoto.webp)
@@
@@image-caption
Vernal Falls와 Nevada Falls
@@
\\

### Nevada Falls
네바다 폭포(Nevada Fall)는 미국 캘리포니아주 요세미티 국립공원에 위치한 유명한 폭포입니다. 이 폭포는 요세미티 밸리의 동쪽 끝에 위치하며, 메르세드 강의 지류인 마다라인 포크(Madeira Fork)에서 떨어집니다. 네바다 폭포는 그 웅장한 높이와 아름다운 주변 경관으로 많은 관광객과 등산객을 끌어들이고 있습니다.

1. **높이**: 네바다 폭포의 높이는 약 181미터(594피트)로, 요세미티 내에서도 특히 높은 폭포 중 하나입니다. 이 폭포는 위쪽의 작은 폭포인 에머랄드 풀(Emerald Pool)에서 시작하여, 아래쪽으로 떨어집니다.

2. **위치와 접근성**: 네바다 폭포는 요세미티 국립공원의 인기 있는 등산로인 Mist Trail과 John Muir Trail을 통해 접근할 수 있습니다. Mist Trail을 따라 올라가면 먼저 Vernal Falls를 지나고, 그 후 네바다 폭포에 도달할 수 있습니다. John Muir Trail은 조금 더 완만한 경사로 되어 있어, 다양한 경로를 즐길 수 있습니다.

3. **등산 경로**: 네바다 폭포로 가는 등산로는 길고 도전적인 구간이 많아, 경험이 있는 등산객들에게 적합합니다. 그러나 경로를 따라 올라가면서 요세미티의 아름다운 경관을 감상할 수 있어 매우 보람찬 경험이 될 수 있습니다.

4. **계절**: 네바다 폭포는 봄과 초여름에 가장 활발하게 흐릅니다. 이 시기에는 눈 녹은 물이 강을 따라 흘러 폭포의 수량이 많아집니다. 여름과 가을에는 수량이 줄어들지만, 여전히 아름다운 경치를 제공합니다.

5. **안전**: 네바다 폭포 근처의 등산로는 가파르고 미끄러운 구간이 많아, 등산객들은 안전에 주의해야 합니다. 적절한 등산 장비와 충분한 물을 준비하는 것이 중요합니다. 또한, 폭포 근처에서는 항상 물의 흐름에 주의해야 합니다.

네바다 폭포는 요세미티 국립공원의 자연미를 대표하는 장소 중 하나로, 많은 사람들이 이곳을 방문하여 자연의 경이로움을 체험합니다.

### Cook's Meadow Loop

@@image-center
![](/assets/images/events/2024/CooksMeadowLoop.jpg)
@@
@@image-caption
Cook's Meadow Loop
@@
\\

Cook's Meadow Loop는 미국 캘리포니아주 요세미티 국립공원 내에 있는 인기 있는 하이킹 및 산책로입니다. 이 루프는 요세미티 밸리의 중심부를 지나며, 공원의 주요 명소를 감상할 수 있는 쉬운 경로로 유명합니다.

1. **길이 및 난이도**: Cook's Meadow Loop는 약 1마일(1.6킬로미터) 길이의 평탄한 경로로, 난이도가 낮아 모든 연령대와 체력 수준의 방문객에게 적합합니다. 하이킹보다는 산책에 가깝기 때문에 가족 단위 방문객들도 많이 찾습니다.

2. **경치**: 이 루프를 따라 걷다 보면 요세미티의 유명한 랜드마크들을 한눈에 볼 수 있습니다. 특히 하프 돔(Half Dome), 요세미티 폭포(Yosemite Falls), 로열 아치(Royal Arches) 등의 장엄한 경치를 감상할 수 있습니다. 계절에 따라 다양한 야생화와 야생동물도 관찰할 수 있습니다.

3. **사진 촬영**: Cook's Meadow Loop는 사진 촬영을 하기에 최적의 장소입니다. 특히 일출과 일몰 시간에는 햇빛이 절벽과 폭포를 비추어 멋진 사진을 찍을 수 있습니다. 요세미티 폭포의 물줄기가 가장 잘 보이는 곳 중 하나이기도 합니다.

4. **접근성**: Cook's Meadow Loop는 요세미티 밸리 비지터 센터와 가까워 접근성이 뛰어납니다. 비지터 센터에서 도보로 쉽게 접근할 수 있으며, 주차장도 가까이에 있어 편리합니다.

5. **계절별 특징**: 봄과 초여름에는 눈 녹은 물로 인해 요세미티 폭포의 수량이 많아지며, 푸른 초목과 야생화가 가득합니다. 가을에는 붉게 물든 단풍과 맑은 하늘이 아름다워 또 다른 매력을 선사합니다. 겨울에는 눈 덮인 풍경을 즐길 수 있지만, 일부 구간은 미끄러울 수 있으니 주의해야 합니다.

Cook's Meadow Loop는 요세미티의 자연미를 쉽게 즐길 수 있는 경로로, 자연을 사랑하는 모든 이들에게 추천할 만한 산책로입니다.

### Yosemite Valley Loop Trail

@@image-center
![](/assets/images/events/2024/YosemiteValleyLoopTrail.webp)
@@
@@image-caption
El Capitan bridge 위로 우뚝 솟은 El Capitan
@@
\\

Yosemite Valley Loop Trail은 미국 캘리포니아주 요세미티 국립공원 내의 아름다운 하이킹 경로 중 하나로, 요세미티 밸리를 한 바퀴 도는 루프 트레일입니다. 이 트레일은 요세미티의 장엄한 자연 경관을 감상할 수 있는 완벽한 기회를 제공합니다.

1. **길이 및 난이도**: Yosemite Valley Loop Trail은 전체 길이가 약 20.8킬로미터(13마일)로, 긴 하이킹을 즐기는 이들에게 적합합니다. 난이도는 중간 정도이며, 트레일의 일부 구간은 평탄하고 나머지 구간은 약간의 오르막과 내리막이 있습니다. 하이킹 경험이 있는 사람들이나 체력이 좋은 사람들에게 추천할 만한 코스입니다.

2. **경치**: 이 트레일을 따라 걷다 보면 요세미티 밸리의 다양한 명소를 감상할 수 있습니다. 하프 돔(Half Dome), 엘 캐피탄(El Capitan), 요세미티 폭포(Yosemite Falls), 브라이덜베일 폭포(Bridalveil Fall) 등 요세미티의 대표적인 랜드마크들을 한눈에 볼 수 있습니다. 계절에 따라 다른 풍경을 제공하여, 언제 방문해도 아름다운 경치를 즐길 수 있습니다.

3. **트레일 구간**: Yosemite Valley Loop Trail은 두 가지 선택 옵션을 제공합니다. 전체 루프를 걷거나, 북쪽 루프(약 11.6킬로미터, 7.2마일) 또는 남쪽 루프(약 9.2킬로미터, 5.7마일)만 걷는 방법입니다. 각각의 루프는 요세미티 밸리의 다른 면모를 보여주므로, 시간과 체력에 맞춰 선택할 수 있습니다. 전체루프는 약 5시간에서 7시간 걸리며, 반만 돌면 2.5에서 3.5시간이 걸립니다.

4. **접근성**: 트레일의 시작 지점은 요세미티 빌리지(Yosemite Village) 근처에 있으며, 비지터 센터와 가까워 쉽게 접근할 수 있습니다. 요세미티 밸리 내의 셔틀 버스를 이용하여 트레일의 여러 지점에서 시작할 수 있어 편리합니다.

5. **자연과 야생동물**: 트레일을 걷다 보면 다양한 식물과 야생동물을 만날 수 있습니다. 계절에 따라 다채로운 야생화가 피고, 사슴, 다람쥐, 다양한 새들 등 요세미티의 야생동물을 관찰할 수 있습니다.

6. **주의사항**: 트레일의 일부 구간은 미끄럽거나 험한 지형일 수 있으므로, 적절한 등산화를 착용하고 충분한 물과 간식을 준비하는 것이 중요합니다. 여름철에는 더위에 대비하고, 겨울철에는 눈과 얼음에 주의해야 합니다.

Yosemite Valley Loop Trail은 요세미티의 자연미를 만끽할 수 있는 최고의 하이킹 코스 중 하나로, 자연을 사랑하는 하이커들에게 추천할 만한 경로입니다.

@@image-center
![](/assets/images/events/2024/valleyloopmap.jpg)
@@
@@image-caption
Yosemite Valley Loop Trail 지도
@@
\\




## 첫째 날 (Hyatt Place Fresno)

들뜬 마음으로 잠을 설친 후, 우리는 더스티가 운전하는 폭스바겐 ID.4를 타고서 오전 10시 40분 경 집에서 출발합니다.
그전날 밤에 100%로 충전한 자동차는 중간 중간 충전소를 들려 충전을 하며 여행 첫날밤을 보낼 Fresno로 향합니다.

고속도로를 달려 달려 도착한 호텔.
비어있는 충전기 앞에 주차하고 기쁘게 체크인을 합니다.
자, 이제 시원하게 수영을 하며 여독을 풀어볼까요?

그런데 아뿔싸...
수영장은 문을 닫았군요.
아쉽지만 수영장 옆에 위치한 체육관으로 가서 운동을 합니다.
첫날 밤이 이렇게 저뭅니다.

## 둘째 날 (Yosemite Valley Lodge)

둘째 날이 밝았습니다.
이미 조식 부페를 오전 6시 30분부터 사용할 수 있다는 정보를 확보했던 우리는 6시 좀 넘어서 눈을 뜨고 맙니다.
6시 40분 경, 남편은 먼저 첫 식사를 할 생각으로 1층 식당으로 향했습니다.

이른 시간에 이용객들이 별로 없으리라는 기대는 최대한 일찍 식사를 마치고 요세미티 공원으로 향하려는 투숙객들로 인해 무산되고 맙니다.
예상 외로 많은 사람들 틈에서 남편은 혼자 꿋꿋이 식사를 합니다.
인근 농장에서 공수되었다는 cage free 계란으로 만든 스크램블 에그가 맛있습니다.
다시 부인과 올 생각에 적당히 첫 식사를 마치고 객실로 향합니다.

조금 쉰 후, 이번에는 부인과 함께 식당을 향합니다.
새벽보다는 사람들이 적군요.
부인도 스크램블 에그를 맛있어 합니다.
부페가 문을 닫을 9시 조금 전에 마지막 식사를 할 생각에 남편은 또 다시 적당히 식사를 마칩니다.

객실에서 잠시 휴식을 취한 남편은 9시가 되기 전 마지막 식사를 하러 식당을 향합니다.
식당에 도착하기 이전부터 부산함이 느껴집니다.
식당에 도착한 남편은 너무 많은 이용객에 당황합니다.
이미 빈 자리는 없고 음식도 동이 났군요.
음식을 담을 접시마저 없어서 이용객들이 음식과 새 접시를 요구합니다.
그냥 떠나기는 아쉬워 새 접시와 계란 요리가 나오기를 기다려 음식을 담고 객실로 향합니다.
아쉽지만 이렇게 조식을 마칩니다. 
호텔을 떠나 요세미티로 향합니다.

@@image-center
![](/assets/images/events/2024/day2route.jpg)
@@
@@image-caption
이동 경로
@@
\\

도로 옆 소나무들이 많습니다.
그런데 많은 나무들이 타버렸네요.
큰 화재가 있었나 봅니다.

~~~
<div class="gallery">
  <a target="_blank" href="/assets/images/events/2024/treeBurn01.jpg">
    <img src="/assets/images/events/2024/treeBurn01.jpg" alt="TreeBurn01" width="600" height="auto">
  </a>
</div>

<div class="gallery">
    <a target="_blank" href="/assets/images/events/2024/treeBurn02.jpg">
      <img src="/assets/images/events/2024/treeBurn02.jpg" alt="Forest" style="width:600">
    </a>
</div>

  <div class="gallery">
    <a target="_blank" href="/assets/images/events/2024/treeBurn03.jpg">
      <img src="/assets/images/events/2024/treeBurn03.jpg" alt="Mountains" style="width:600">
    </a>
  </div>
  <div class="gallery">
    <a target="_blank" href="/assets/images/events/2024/treeBurn04.jpg">
      <img src="/assets/images/events/2024/treeBurn04.jpg" alt="Mountains" style="width:600">
    </a>
  </div>

  <div style="clear: both"></div>
~~~

\\
살펴보니 2022년 Washburn fire라는 큰 산불이 있었군요.
2022년 7월 11일 발화해서 2022년 8월 1일 진화되었네요.
자나깨나 산불조심!!! :fire:

이렇게 산길을 구비구비 지나다 보니 Yosemite South entrance에 도착하였습니다.
이제 공원 안으로 들어갑니다.

@@image-center
![](/assets/images/events/2024/day1route.jpg)
@@
@@image-caption
요세미티 공원 이동 경로
@@
\\

첫 목적지는 WashburnPoint 입니다.
또 다른 명소인 Glacier Point를 가는 길에 있습니다.
가는 길에 들르면 되겠군요.

차는 달려 어느덧 South Entrance에 도착했습니다.
35불을 내어주니 환영해줍니다.

@@image-center
![](/assets/images/events/2024/southEntrance.jpg)
@@
@@image-caption
요세미티 공원 South Entrance
@@
\\

입구에서 좀 오르다보니 자연이 더스티를 부르는군요.
마침 Wawona Hotel 입구가 보입니다.
더스티는 망설임없이 들어섭니다.
호텔 전경이 아름답군요.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/wawonaHotel (5).jpg">
      <img src="/assets/images/events/2024/wawonaHotel (5).jpg" alt="Snow" style="width:600">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wawonaHotel (1).jpg">
      <img src="/assets/images/events/2024/wawonaHotel (1).jpg" alt="Snow" style="width:600">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wawonaHotel (6).jpg">
      <img src="/assets/images/events/2024/wawonaHotel (6).jpg" alt="Forest" style="width:600">
    </a>
  </div>

  <div style="clear: both"></div>
~~~
\\

주변의 고목들도 멋집니다.
멋진 풍경 속에 예쁜 부인의 사진을 찍지 않을 수 없군요.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/wawonaHotel (2).jpg">
      <img src="/assets/images/events/2024/wawonaHotel (2).jpg" alt="Snow" style="width:600">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wawonaHotel (3).jpg">
      <img src="/assets/images/events/2024/wawonaHotel (3).jpg" alt="Snow" width = "1200">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wawonaHotel (4).jpg">
      <img src="/assets/images/events/2024/wawonaHotel (4).jpg" alt="Forest" style="width:1200">
    </a>
  </div>

<div style="clear: both"></div>
~~~
\\

잠깐의 휴식 후 다시 길을 떠납니다.
그런데 차창밖으로 화재의 흔적과 함께 이상한 장면을 목격합니다.
해가 쨍쨍 쬐는 바깥으로 하얀 눈이 쌓인 듯 합니다.
바깥 온도를 살펴보니 20도가 약간 안되는 것 같습니다.
차 안에서 토론이 벌어집니다.
부인은 눈이라고 주장하고 더스티는 바위라 합니다.
남편은 처음에는 눈이라고 했다가 다시 바위로 의견을 바꿉니다.
역시나 부인이 옳았습니다. :+1: :sweat_smile: 
겨우내 덮여있던 눈이 녹는 중인가 봅니다.

~~~
<div class="row">
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (1).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (1).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (2).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (3).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (4).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (5).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (6).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (7).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (8).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (9).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (9).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/wayToWashburn01 (10).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
</div>
~~~
\\

조금 더 오르다 보니 우측에 Washburn 표시가 있네요.
냉큼 들어섭니다.
차에 내려 Washburn 경치를 보니 우와 하는 감탄이 절로 나오네요.
장엄한 자연 경관이 한 눈에 보여 이래서 요세미티에 오는구나 싶습니다.
Half Dome, Mt Broderick, Liberty Cap, Nevada Fall과 Vernal Fall이 한 눈에 보이는 대단한 장관이었습니다.
더스티도 부인도 남편도 엄청난 장관을 눈과 카메라에 담기에 정신이 없습니다.
셀카를 찍지 않는 남편도 뛰어난 경관에 한번 도전해 봅니다.
바위 위에 서있는 남편 사진에 부인은 "산할아버지 구름모자 썼네"라고 부제를 붙여봅니다.

~~~
<div class="row">
  <div class="column">
    <a href="/assets/images/events/2024/washburn (1).jpg">
      <img src="/assets/images/events/2024/washburn (1).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (2).jpg">
      <img src="/assets/images/events/2024/washburn (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (3).jpg">
      <img src="/assets/images/events/2024/washburn (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (4).jpg">
      <img src="/assets/images/events/2024/washburn (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (5).jpg">
      <img src="/assets/images/events/2024/washburn (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (6).jpg">
      <img src="/assets/images/events/2024/washburn (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (7).jpg">
      <img src="/assets/images/events/2024/washburn (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (8).jpg">
      <img src="/assets/images/events/2024/washburn (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (9).jpg">
      <img src="/assets/images/events/2024/washburn (9).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (10).jpg">
      <img src="/assets/images/events/2024/washburn (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (11).jpg">
      <img src="/assets/images/events/2024/washburn (11).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/washburn (12).jpg">
      <img src="/assets/images/events/2024/washburn (12).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
</div>
~~~
\\
~~~
<center>
<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/washburn (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>
</center>
~~~
\\

엄청난 자연 경관에 대한 경탄을 누르고 다시 차에 올라 Glacier Point로 향합니다.
Washburn 보다 더 명소로 알려진 Glacier Point이기에 좀 더 큰 기대에 가슴이 두근거립니다.
드디어 도착했군요.
인기있는 명소인 만큼 주차장에 차들이 많습니다.
주차장에서 걸어가는 길에 쌓여있는 눈을 발견합니다.
부인이 옳았음을 다시 한번 확인합니다.

~~~
<div class="row">
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (1).jpg">
      <img src="/assets/images/events/2024/glacierPoint (1).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (2).jpg">
      <img src="/assets/images/events/2024/glacierPoint (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
</div>
~~~
\\

주차장을 나서니 요세미티 밸리로 향하는 트레일도 있군요.
우리는 Glacier Point로 향합니다.
휠체어도 다닐 수 있도록 길을 만들었네요.
도착한 전망대...
Washburn에서 보았던 광경을 좀 더 다른 각도로, 좀 더 넓은 전망대로 보게 되네요.
물론 웅장한 그 절경은 변함없습니다만, 처음 Washburn에서 느꼈던 만큼의 감동은 오지 않았습니다. :unamused:

~~~
<div class="row">
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (3).jpg">
      <img src="/assets/images/events/2024/glacierPoint (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (4).jpg">
      <img src="/assets/images/events/2024/glacierPoint (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (5).jpg">
      <img src="/assets/images/events/2024/glacierPoint (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (6).jpg">
      <img src="/assets/images/events/2024/glacierPoint (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (7).jpg">
      <img src="/assets/images/events/2024/glacierPoint (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (8).jpg">
      <img src="/assets/images/events/2024/glacierPoint (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (9).jpg">
      <img src="/assets/images/events/2024/glacierPoint (9).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (10).jpg">
      <img src="/assets/images/events/2024/glacierPoint (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (11).jpg">
      <img src="/assets/images/events/2024/glacierPoint (11).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (12).jpg">
      <img src="/assets/images/events/2024/glacierPoint (12).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (13).jpg">
      <img src="/assets/images/events/2024/glacierPoint (13).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (14).jpg">
      <img src="/assets/images/events/2024/glacierPoint (14).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (15).jpg">
      <img src="/assets/images/events/2024/glacierPoint (15).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/glacierPoint (16).jpg">
      <img src="/assets/images/events/2024/glacierPoint (16).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
</div>
~~~
\\
~~~
<center>
<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/glacierPoint (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>
</center>
~~~
\\

웅장하고 멋진 장관을 감상하고 차로 돌아가던 중...
호사다마일까요.
부인이 발목을 삐끗 접지르고 맙니다.
바닥에 움푹 파인 구멍을 미처 보지 못하였던 것이죠. :cry:
요세미티 관광의 첫 날, 우리는 큰 위기를 맞이하게 되었습니다.

발목이 붓고 통증으로 걷기 힘들어도 부인은 포기하지 않습니다.
산행을 위해 가져온 지팡이를 딛고서 터널뷰로 향합니다.

~~~
<div class="row">
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (1).jpg">
      <img src="/assets/images/events/2024/tunnelView (1).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (2).jpg">
      <img src="/assets/images/events/2024/tunnelView (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (3).jpg">
      <img src="/assets/images/events/2024/tunnelView (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (4).jpg">
      <img src="/assets/images/events/2024/tunnelView (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (5).jpg">
      <img src="/assets/images/events/2024/tunnelView (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (6).jpg">
      <img src="/assets/images/events/2024/tunnelView (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (7).jpg">
      <img src="/assets/images/events/2024/tunnelView (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/tunnelView (8).jpg">
      <img src="/assets/images/events/2024/tunnelView (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
</div>
~~~
\\

본래는 그 후의 여정으로 Bridalveil Fall, Cathedral Beach, Swinging Bridge Picnic Area 등을 들르려 했었지만 오랜 운전 시간과 부인의 부상으로 숙소로 곧장 향하기로 결정하였습니다.
하지만 남편을 부르는 어머니 자연...
우리는 화장실이 구비된 Bridalveil Fall 입구에 들렀습니다.
비록 예정대로 Bridalveil Fall 앞까지 가지는 못했지만 입구에서 폭포의 아름다운 모습을 담아봅니다.

~~~
<div class="row">
  <div class="column">
    <a href="/assets/images/events/2024/bridalveilFall (1).jpg">
      <img src="/assets/images/events/2024/bridalveilFall (1).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/bridalveilFall (2).jpg">
      <img src="/assets/images/events/2024/bridalveilFall (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/assets/images/events/2024/bridalveilFall (3).jpg">
      <img src="/assets/images/events/2024/bridalveilFall (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
</div>
~~~
\\

## 셋째 날 (Yosemite Valley Lodge)

@@image-center
![](/assets/images/events/2024/day3route.jpg)
@@
@@image-caption
이동 경로
@@
\\


## 넷째 날 + 다섯째 날 (Mar Monte Hotel)

@@image-center
![](/assets/images/events/2024/Mar-Monte-HotelAerial-View-Beach.webp)
@@
@@image-caption
Mar Monte Hotel 전경
@@
\\

@@image-center
![](/assets/images/events/2024/Mar-Monte-Hotel-King-Bed.webp)
@@
@@image-caption
King 베드 침실
@@
\\

@@image-center
![](/assets/images/events/2024/Mar-Monte-Hotel-Pool.webp)
@@
@@image-caption
Pool
@@
\\
