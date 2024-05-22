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

## 첫째 날 (Hyatt Place Fresno)

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

## 둘째 날 (Yosemite Valley Lodge)

@@image-center
![](/assets/images/events/2024/day2route.jpg)
@@
@@image-caption
이동 경로
@@
\\

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


## 셋째 날 (Yosemite Valley Lodge)

@@image-center
![](/assets/images/events/2024/day3route.jpg)
@@
@@image-caption
이동 경로
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
