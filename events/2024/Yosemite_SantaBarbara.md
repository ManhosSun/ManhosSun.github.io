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

### Tunnel View

@@image-center
![](/assets/images/events/2024/tunnel-view.jpg)
@@
@@image-caption
Tunnel View
@@
\\

**Tunnel View**는 미국 요세미티 국립공원 내 Wawona Tunnel의 동쪽 끝, Wawona Road (Highway 41)에 위치한 경치 좋은 전망대입니다. 
이 전망대는 1933년 개장 이후로 방문객들이 요세미티 계곡의 상징적이고 광활한 경치를 보고 기록해 왔습니다. 

Tunnel View에서는 요세미티 계곡을 둘러싼 화강암 벽의 거대함을 보여주며, El Capitan, Half Dome, Sentinel Rock, Cathedral Rocks, 그리고 Bridalveil Fall의 클래식한 전망을 제공합니다. 
특히 일몰이나 폭풍이 지나간 후의 경치는 더욱 화려합니다.

Wawona Tunnel은 1931년 1월 30일에 건설이 시작되어 1933년 6월 18일에 개방되었습니다. 
거의 1마일 길이의 터널을 만들기 위해 약 230톤의 다이너마이트를 사용하여 화강암을 뚫었습니다. 
Tunnel View와 Wawona Tunnel은 "National Register of Historic Places"에 등재되어 있습니다.

### El Capitan

@@image-center
![](/assets/images/events/2024/El_Capitan.jpg)
@@
@@image-caption
Southwest face (left, in light) and southeast face (right, in shade) of El Capitan from Yosemite Valley; the Nose lies between the two faces
@@
\\

**El Capitan**은 미국 캘리포니아 주의 요세미티 국립공원에 위치한 수직으로 솟은 화강암 바위입니다. 
이 거대한 바위는 요세미티 계곡의 북쪽에 위치해 있으며, 그 높이는 약 **3,000 피트 (약 914m)**에 달합니다. 
이는 Empire State Building의 높이의 2.5배, 에펠탑의 높이의 3배 이상에 해당합니다.

El Capitan은 그 거대한 크기와 수직으로 솟은 모습 때문에 암벽 등반의 세계적인 명소로 알려져 있습니다. 
El Capitan의 이름은 1851년에 계곡을 탐험하던 Mariposa Battalion에 의해 지어졌습니다. 
El Capitan은 스페인어로 "대장"이나 "족장"을 의미하며, 이는 현지 원주민의 바위에 대한 이름인 “Tutokanula” 또는 "Rock Chief"의 대략적인 스페인어 번역입니다.


### Half Dome

@@image-center
![](/assets/images/events/2024/Half_Dome_from_Glacier_Point.jpg)
@@
@@image-caption
Sunset over Half Dome from Glacier Point
@@
\\

**Half Dome**은 미국 캘리포니아 주의 요세미티 국립공원에 위치한 화강암 바위입니다. 
이 독특한 모양의 바위는 공원 내에서 잘 알려진 암석 형태로, 한 쪽은 수직으로 떨어지는 반면 다른 세 면은 매끄럽고 둥글게 보이는 돔을 반으로 잘라낸 것처럼 보입니다.
Half Dome의 높이는 해발 **8,800 피트 (약 2,682m)**이며, 요세미티 계곡 위로 **4,800 피트 (약 1,463m)**를 솟아올라 있습니다. 

Half Dome 등산로를 따라 걷다 보면 요세미티의 가장 인기 있는 등산로를 걸을 수 있으며, Vernal과 Nevada 폭포를 볼 수 있고, Sequoia 나무가 우거진 그늘진 숲을 걸을 수 있습니다. 
하지만 이 등산로의 가장 흥미로운 부분은 Half Dome 케이블을 따라 최종 등반과 정상에서의 보상인 요세미티의 최고의 전망입니다.
등산객들은 대부분 10시간에서 12시간 동안 Half Dome를 등반하는데, 일부는 더 오래 걸립니다.

@@image-center
![](/assets/images/events/2024/HalfDomeTraffic.jpeg)
@@
@@image-caption
Half Dome Cable Route
@@
\\

### Sentinel Rock

@@image-center
![](/assets/images/events/2024/SentinelRock.jpg)
@@
@@image-caption
Sentinel Rock
@@
\\

**Sentinel Rock**은 미국 캘리포니아 주의 요세미티 국립공원에 위치한 화강암 바위입니다. 
이 바위는 요세미티 계곡을 가로질러 요세미티 폭포를 마주보며 요세미티 계곡 위로 솟아 있습니다. 
Sentinel Rock의 높이는 해발 **7,038 피트 (약 2,145m)**에 달합니다.

Sentinel Rock은 요세미티 계곡의 남쪽 절벽에서 대량의 암석이 거의 동서로 경사진 관절을 따라 분리되면서 형성되었습니다. 
이로 인해 Sentinel Rock의 북쪽 면은 거의 수직으로 형성되었습니다.


### Cathedral Rocks

@@image-center
![](/assets/images/events/2024/Cathedral_Rocks.jpg)
@@
@@image-caption
Cathedral Rocks
@@
\\

**Cathedral Rocks**는 미국 캘리포니아 주의 요세미티 국립공원에 위치한 화강암 바위입니다. 
이 바위는 요세미티 계곡의 남쪽 가장자리에 위치해 있으며, 요세미티 계곡 위로 **2,000 피트 (약 610m)**를 솟아 있습니다. 
Cathedral Rocks는 세 개의 주요 정상으로 구성되어 있으며, 이들은 **Higher, Middle, 그리고 Lower Cathedral Rocks**라고 불립니다.


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


### Swinging Bridge Picnic Area

@@image-center
![](/assets/images/events/2024/SwingingBridgePicnicArea.jpg)
@@
@@image-caption
Swinging Bridge Picnic Area
@@
\\


@@image-center
![](/assets/images/events/2024/SwingingBridgePicnicAreaRoute.jpg)
@@
@@image-caption
Swinging Bridge Picnic Area 걸어가는 길
@@
\\

**Swinging Bridge Picnic Area**는 **요세미티 국립공원** 내에 있는 피크닉 지역입니다. 
이곳은 **Merced 강**을 따라 위치하고 있으며, **Yosemite 폭포**의 멋진 경치를 감상할 수 있습니다. 
이 지역에는 피크닉 테이블과 그릴이 편리하게 배치되어 있습니다. 
그런데 이름과 달리 Swinging Bridge는 실제로 흔들리지 않습니다. 
이전 Swinging Bridge는 1964년 홍수로 인해 손상되어 고정 다리로 교체되었습니다. 
이 피크닉 지역은 **새벽부터 어두워질 때까지** 이용 가능하며, **Southside Drive**에 위치해 있습니다. 
피크닉 지역은 **선착순으로 이용**할 수 있으며, 예약은 불가능합니다. 
또한 **곰과의 거리를 유지**하고, **야생 동물에게 먹이를 주지 않도록 주의**해야 합니다. 
요세미티의 물은 위험할 수 있으므로 봄철에는 안전한 거리에서 감상하는 것이 좋습니다. 
Swinging Bridge Picnic Area는 접근성을 고려하여 설계되었으며, 휠체어 이용자를 위한 테이블과 화장실, 그리고 주차 공간이 마련되어 있습니다.


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

### Mar Monte Hotel
산타 바바라 해변에 위치한 고급 호텔입니다.
우리가 여행의 마지막 이틀을 묵을 곳이죠.
호텔 사이트에서 호텔 전경과 우리가 묵을 객실, 야외 수영장 사진을 찾았습니다.

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

  <div class="gallery">
    <a target="_blank" href="/assets/images/events/2024/treeBurn (1).jpg">
      <img src="/assets/images/events/2024/treeBurn (1).jpg" alt="Mountains" style="width:600">
    </a>
    <div class="desc">화재현장을 뒤로 한 부인</div>
  </div>

  <div class="gallery">
    <a target="_blank" href="/assets/images/events/2024/treeBurn (2).jpg">
      <img src="/assets/images/events/2024/treeBurn (2).jpg" alt="Mountains" style="width:600">
    </a>
    <div class="desc">화재현장을 뒤로 한 남편</div>
  </div>

  <div style="clear: both"></div>
~~~

\\
살펴보니 2022년 Washburn fire라는 큰 산불이 있었군요.
2022년 7월 11일 발화해서 2022년 8월 1일 진화되었었네요.
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
부인은 눈이라고 주장하고 더스티는 하얀 페인트를 칠한 것이라 합니다.
남편은 처음에는 눈이라고 했다가 다시 바위로 의견을 바꿉니다.
...
역시나 부인이 옳았습니다. :+1: :sweat_smile: 
겨우내 덮여있던 눈이 녹는 중인가 봅니다.

~~~
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (1).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (1).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (2).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (3).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (4).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (5).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (6).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (7).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (8).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (9).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (9).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/wayToWashburn01 (10).jpg">
      <img src="/assets/images/events/2024/wayToWashburn01 (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
<div style="clear: both"></div>
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

  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (1).jpg">
      <img src="/assets/images/events/2024/washburn (1).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">더스티를 노리는 부인</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (2).jpg">
      <img src="/assets/images/events/2024/washburn (2).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">계속해서 더스티를 노리는 부인</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (13).jpg">
      <img src="/assets/images/events/2024/washburn (13).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">결국 부인에게 덜미를 잡힌 더스티</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (3).jpg">
      <img src="/assets/images/events/2024/washburn (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (4).jpg">
      <img src="/assets/images/events/2024/washburn (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (5).jpg">
      <img src="/assets/images/events/2024/washburn (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (14).jpg">
      <img src="/assets/images/events/2024/washburn (14).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">여유있게 멋진 풍경을 바라보는 부인의 뒷모습</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (15).jpg">
      <img src="/assets/images/events/2024/washburn (15).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">여유있게 멋진 풍경을 바라보는 남편의 뒷모습</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (6).jpg">
      <img src="/assets/images/events/2024/washburn (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">어설픈 실력으로 셀카에 도전한 남편</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (16).jpg">
      <img src="/assets/images/events/2024/washburn (16).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편의 어설픈 셀카를 응징한 부인</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (7).jpg">
      <img src="/assets/images/events/2024/washburn (7).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">셀카에 재도전한 남편</div>
  </div>
   <div class="gallery">
    <a href="/assets/images/events/2024/washburn (18).jpg">
      <img src="/assets/images/events/2024/washburn (18).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">이어지는 삼엄한 꾸짖음</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (8).jpg">
      <img src="/assets/images/events/2024/washburn (8).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">다시 한번 셀카에 도전한 남편</div>
  </div>
 
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (19).jpg">
      <img src="/assets/images/events/2024/washburn (19).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">또 다시 준엄한 질책</div>
  </div>
<div class="gallery">
    <a href="/assets/images/events/2024/washburn (17).jpg">
      <img src="/assets/images/events/2024/washburn (17).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">깨달음을 얻은 남편에 뿌듯한 부인</div>
  </div>

  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (9).jpg">
      <img src="/assets/images/events/2024/washburn (9).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (10).jpg">
      <img src="/assets/images/events/2024/washburn (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (11).jpg">
      <img src="/assets/images/events/2024/washburn (11).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (12).jpg">
      <img src="/assets/images/events/2024/washburn (12).jpg" alt="Snow" style="width:100%">
    </a>
  </div>

  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (20).jpg">
      <img src="/assets/images/events/2024/washburn (20).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">Washburn에 출몰한 더스티</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (21).jpg">
      <img src="/assets/images/events/2024/washburn (21).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">Washburn의 매력에 참지 못하고 카메라를 들이댄 더스티</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (22).jpg">
      <img src="/assets/images/events/2024/washburn (22).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">바위 위에 또 다시 출몰한 더스티</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (23).jpg">
      <img src="/assets/images/events/2024/washburn (23).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">바위 위에서 치명적인 더스티</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (24).jpg">
      <img src="/assets/images/events/2024/washburn (24).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">남편 산할아버지 구름 모자 썼네</div>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/washburn (25).jpg">
      <img src="/assets/images/events/2024/washburn (25).jpg" alt="Snow" style="width:100%">
    </a>
    <div class="desc">Washburn을 떠나기 전 마지막 가르침을 잊지 않은 부인</div>
  </div>
<div style="clear: both"></div>
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

  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (1).jpg">
      <img src="/assets/images/events/2024/glacierPoint (1).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (2).jpg">
      <img src="/assets/images/events/2024/glacierPoint (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
<div style="clear: both"></div>
~~~
\\

주차장을 나서니 요세미티 밸리로 향하는 트레일도 있군요.
우리는 Glacier Point로 향합니다.
휠체어도 다닐 수 있도록 길을 만들었네요.
도착한 전망대...
Washburn에서 보았던 광경을 좀 더 다른 각도로, 좀 더 넓은 전망대로 보게 되네요.
물론 웅장한 그 절경은 변함없습니다만, 처음 Washburn에서 느꼈던 만큼의 감동은 오지 않았습니다. :unamused:

~~~
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (3).jpg">
      <img src="/assets/images/events/2024/glacierPoint (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (4).jpg">
      <img src="/assets/images/events/2024/glacierPoint (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (5).jpg">
      <img src="/assets/images/events/2024/glacierPoint (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (6).jpg">
      <img src="/assets/images/events/2024/glacierPoint (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (7).jpg">
      <img src="/assets/images/events/2024/glacierPoint (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (8).jpg">
      <img src="/assets/images/events/2024/glacierPoint (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (9).jpg">
      <img src="/assets/images/events/2024/glacierPoint (9).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (10).jpg">
      <img src="/assets/images/events/2024/glacierPoint (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (11).jpg">
      <img src="/assets/images/events/2024/glacierPoint (11).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (12).jpg">
      <img src="/assets/images/events/2024/glacierPoint (12).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (13).jpg">
      <img src="/assets/images/events/2024/glacierPoint (13).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (14).jpg">
      <img src="/assets/images/events/2024/glacierPoint (14).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (15).jpg">
      <img src="/assets/images/events/2024/glacierPoint (15).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (16).jpg">
      <img src="/assets/images/events/2024/glacierPoint (16).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (21).jpg">
      <img src="/assets/images/events/2024/glacierPoint (21).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (17).jpg">
      <img src="/assets/images/events/2024/glacierPoint (17).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (18).jpg">
      <img src="/assets/images/events/2024/glacierPoint (18).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (19).jpg">
      <img src="/assets/images/events/2024/glacierPoint (19).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (20).jpg">
      <img src="/assets/images/events/2024/glacierPoint (20).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (22).jpg">
      <img src="/assets/images/events/2024/glacierPoint (22).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/glacierPoint (23).jpg">
      <img src="/assets/images/events/2024/glacierPoint (23).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
<div style="clear: both"></div>
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
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (1).jpg">
      <img src="/assets/images/events/2024/tunnelView (1).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (2).jpg">
      <img src="/assets/images/events/2024/tunnelView (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (3).jpg">
      <img src="/assets/images/events/2024/tunnelView (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (4).jpg">
      <img src="/assets/images/events/2024/tunnelView (4).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (5).jpg">
      <img src="/assets/images/events/2024/tunnelView (5).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (6).jpg">
      <img src="/assets/images/events/2024/tunnelView (6).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (7).jpg">
      <img src="/assets/images/events/2024/tunnelView (7).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (8).jpg">
      <img src="/assets/images/events/2024/tunnelView (8).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (9).jpg">
      <img src="/assets/images/events/2024/tunnelView (9).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/tunnelView (10).jpg">
      <img src="/assets/images/events/2024/tunnelView (10).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
<div style="clear: both"></div>
~~~
\\

본래는 그 후의 여정으로 Bridalveil Fall, Cathedral Beach, Swinging Bridge Picnic Area 등을 들르려 했었지만 오랜 운전 시간과 부인의 부상으로 숙소로 곧장 향하기로 결정하였습니다.
하지만 남편을 부르는 어머니 자연...
우리는 화장실이 구비된 Bridalveil Fall 입구에 들렀습니다.
비록 예정대로 Bridalveil Fall 앞까지 가지는 못했지만 입구에서 폭포의 아름다운 모습을 담아봅니다.

~~~
  <div class="gallery">
    <a href="/assets/images/events/2024/bridalveilFall (1).jpg">
      <img src="/assets/images/events/2024/bridalveilFall (1).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/bridalveilFall (2).jpg">
      <img src="/assets/images/events/2024/bridalveilFall (2).jpg" alt="Snow" style="width:100%">
    </a>
  </div>
  <div class="gallery">
    <a href="/assets/images/events/2024/bridalveilFall (3).jpg">
      <img src="/assets/images/events/2024/bridalveilFall (3).jpg" alt="Forest" style="width:100%">
    </a>
  </div>
<div style="clear: both"></div>
~~~
\\

드디어 도착한 숙소...
부인이 최고의 노하우로 예약한, 요세미티 공원 내 최고의 숙박 시설...
바로 요세미티 랏지입니다.
체크인을 한 후 라운지에서 간단한 저녁 식사를 합니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/rounge.jpg">
      <img src="/assets/images/events/2024/rounge.jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">라운지에서도 가르침을 잊지 않은 부인</div>
  </div>
<div style="clear: both"></div>
~~~
\\

저녁식사 후 부인의 발목상태를 확인한 후 숙소에서 가까운 Lower Yosemite 폭포로 향합니다.
포장된 길로 이어져 있어 부인의 발목에 큰 무리가 가지는 않을 듯 합니다.

폭포로 향하는 길에 많은 이들이 함께 합니다.
곳곳에 멋진 풍경도 있고 상쾌하군요.
드디어 폭포에 다다릅니다.
강우량이 많았던 지난 겨울 쌓였던 눈이 녹아내리는 좋은 때 방문하여 수량이 많군요.
시원한 물줄기가 상쾌한 소리와 함께 쏟아집니다.
장관입니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (15).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (15).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">숙소 주차장에서 보이는 Upper Yosemite 폭포</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (1).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 다소곳한 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (2).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 다소곳한 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (3).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 엄지척 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (4).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 엄지척 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (5).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (5).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (6).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 발랄한 부인 뒷모습</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (7).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 발랄한 부인 뒷모습</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (8).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 발랄한 부인 뒷모습</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (9).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (9).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 발랄한 부인 뒷모습</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (10).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (10).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Lower Yosemite 폭포로 가는 길에 발견한 멋진 곳</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (11).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (11).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">멋진 곳에서 남편은 승리</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (12).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (12).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">멋진 곳에서 부인도 찰칵</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFall_evening (13).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFall_evening (13).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">드디어 눈 앞에 펼쳐진 Lower Yosemite 폭포</div>
</div>
<div style="clear: both"></div>
~~~
\\

~~~
<center>
<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/lowerYosemiteFall_evening (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/lowerYosemiteFall_evening (2).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/lowerYosemiteFall_evening (3).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

폭포를 맘껏 감상한 후 숙소로 돌아와 쉽니다.
부인이 공들여 예약한 만큼, 숙소도 아늑합니다.
걱정했던 부인의 발목을 얼음으로 찜질하며 회복을 기원합니다.
이렇게 요세미티 공원에서의 첫 날이 저뭅니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/yosemiteLodge (1).jpg">
      <img src="/assets/images/events/2024/yosemiteLodge (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 숙소 화장실</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/yosemiteLodge (2).jpg">
      <img src="/assets/images/events/2024/yosemiteLodge (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 숙소 침실</div>
</div>

<div style="clear: both"></div>
~~~

## 셋째 날 (Yosemite Valley Lodge)

@@image-center
![](/assets/images/events/2024/day3route.jpg)
@@
@@image-caption
이동 경로
@@
\\

안락한 숙소에서 편안한 밤을 보내고 눈을 뜬 아침은 맑고 상쾌합니다.
지난 밤 날벌레가 두려워 나가 보지 못했던 발코니에 나가 봅니다.
더 없이 상쾌한 요세미티 공원의 아침 풍경을 감상합니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/lodgeMorning (1).jpg">
      <img src="/assets/images/events/2024/lodgeMorning (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 발코니에서 본 아침 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeMorning (2).jpg">
      <img src="/assets/images/events/2024/lodgeMorning (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 발코니에서 본 아침 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeMorning (3).jpg">
      <img src="/assets/images/events/2024/lodgeMorning (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 발코니에서 본 아침 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeMorning (4).jpg">
      <img src="/assets/images/events/2024/lodgeMorning (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 발코니에서 본 아침 풍경</div>
</div>


<div style="clear: both"></div>
~~~

~~~
<center>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/lodgeMorning (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

오늘의 일정은 Mist Trail을 통해 Vernal 폭포까지 가는 것입니다. 
걱정했던 부인의 발목도 살짝 붓긴 했지만 크게 상태가 악화되지는 않았습니다.
산행을 조심스럽게 해도 될 듯 합니다.

숙소에서 간단한 아침 식사를 마친 후, 우리는 셔틀 버스를 타고 Curry Village로 향합니다.
셔틀 버스를 타고 창 밖을 바라보니 아침 풍경이 볼 만 합니다.
몇몇 명소나 경치가 좋은 곳에는 이미 많은 사람들이 차를 대고 즐기고 있고, 도로 옆으로도 몇몇 이들이 걸어 지나갑니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/shuttleView (1).jpg">
      <img src="/assets/images/events/2024/shuttleView (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Curry Village를 향하는 셔틀에서 바라본 Bridalveil Fall</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/shuttleView (2).jpg">
      <img src="/assets/images/events/2024/shuttleView (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Curry Village를 향하는 셔틀에서 바라본 Bridalveil Fall</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/shuttleView (3).jpg">
      <img src="/assets/images/events/2024/shuttleView (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 공원을 걷고 있는 관광객들</div>
</div>
<div style="clear: both"></div>
~~~
\\

본래 Vernal 폭포를 향하는 Mist Trail로 가기에 가장 가까운 셔틀버스 정류장은 16번 Happy Isles 정류장이지만, Curry Village 인근 공사로 정류장들이 문을 닫아 Curry Village 호텔 앞에서 내립니다.
호텔 주차장을 가로질러 Mist Trail로 향하는 Happy Isles Loop Road를 따라 걸어갑니다.
가는 길에 보이는 풍경들이 멋집니다.
사진으로 담아봐야 겠습니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (1).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Curry Village 주차장에서 바라본 Glacier Point 방향 경치</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (2).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Curry Village 주차장에서 엄지척 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (3).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mist Trail로 향하는 소로에서의 경치</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (4).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mist Trail로 향하는 소로에서의 경치</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (5).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mist Trail로 향하는 소로에서의 경치</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (6).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mist Trail로 향하는 소로에서의 경치</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/curryGlacierPoint (7).jpg">
      <img src="/assets/images/events/2024/curryGlacierPoint (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mist Trail로 향하는 소로에서의 경치</div>
</div>

<div style="clear: both"></div>
~~~
\\

걷다보니 시원한 물소리가 나며 멋진 다리가 나타납니다.
Happy Isles Bridge입니다.
시원하게 흐르는 물줄기를 사진과 동영상으로 담아 봅니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (1).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mt Broderick을 배경으로 다리 옆 물줄기를 바라보는 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (2).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">부인이 바라보았던 물줄기</div>
</div>
<div style="clear: both"></div>
~~~
\\

~~~
<center>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/happyIslesBridge (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/happyIslesBridge (2).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

다리를 지나 이곳 저곳 풍경이 나쁘지 않습니다.
사진으로 담아야겠습니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (3).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (3).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (4).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (4).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (5).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Mist Trail을 향하는 더스티와 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (6).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (6).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/happyIslesBridge (7).jpg">
      <img src="/assets/images/events/2024/happyIslesBridge (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">발목 부상에도 불구하고 멋진 춤사위를 펼친 부인</div>
</div>
<div style="clear: both"></div>
~~~
\\

계속해서 Mist Trail로 향합니다.
구비 구비 멋진 풍경이 펼쳐집니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (2).jpg">
      <img src="/assets/images/events/2024/toMistTrail (2).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (3).jpg">
      <img src="/assets/images/events/2024/toMistTrail (3).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (4).jpg">
      <img src="/assets/images/events/2024/toMistTrail (4).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (5).jpg">
      <img src="/assets/images/events/2024/toMistTrail (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">돌벽 앞의 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (6).jpg">
      <img src="/assets/images/events/2024/toMistTrail (6).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (7).jpg">
      <img src="/assets/images/events/2024/toMistTrail (7).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (8).jpg">
      <img src="/assets/images/events/2024/toMistTrail (8).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (9).jpg">
      <img src="/assets/images/events/2024/toMistTrail (9).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (10).jpg">
      <img src="/assets/images/events/2024/toMistTrail (10).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (12).jpg">
      <img src="/assets/images/events/2024/toMistTrail (12).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (14).jpg">
      <img src="/assets/images/events/2024/toMistTrail (14).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toMistTrail (15).jpg">
      <img src="/assets/images/events/2024/toMistTrail (15).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div style="clear: both"></div>
~~~
\\

~~~
<center>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/toMistTrail (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/toMistTrail (2).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/toMistTrail (3).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/toMistTrail (4).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/toMistTrail (5).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

드디어 Mist Trail Head로 향하는 Vernal Falls Foot Bridge 다리가 나옵니다.
흐르는 물이 장관이네요.
사진을 찍지 않을 수 없습니다.
부인도 홀린 듯 셀카를 찍습니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (5).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Vernal Falls Foot Bridge에서 부인의 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (3).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">한 장으로는 부족한 부인의 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (4).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Vernal Falls Foot Bridge에서 부인 하트</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (1).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Vernal Falls Foot Bridge에서 남편 엄지척</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (2).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Vernal Falls Foot Bridge에서 남편 하트</div>
</div>
<div style="clear: both"></div>
~~~
\\

~~~
<center>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFallsFootBridge (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

Mist Trail을 걸어 올라가다 보니 드디어 보이기 시작한 Vernal Falls!!!
조금씩 물기가 올라오고 물소리도 커집니다.
이름과 걸맞게 물안개도 피어 있습니다.
사전에 살펴본 정보로는 물이 많이 튀어 비옷을 입고 가야한다고 알고 있었습니다만 내려오는 사람들도 그렇고 조금 젓는 정도는 괜찮을 것 같습니다.
간단한 의견 타진 후 준비한 우의 판초는 없어도 상관없다고 결정합니다.
폭포를 향해 전진합니다.

음...
잘못된 결정이었군요.
가까이 갈 수록 튀는 물의 양이 장난이 아닙니다.
준족을 자랑하며 이미 사라진 더스티는 어쩔 수 없습니다.
부인과 남편은 급히 준비한 비닐 우의를 착용합니다.
하지만 엄청난 물의 양과 바람은 간단한 우의 만으로 머리와 옷이 젓는 것을 막을 수 없게 하는군요.
조금씩 험해지는 길과 물에 젖어 미끄러운 바닥은 폭포로의 접근을 더욱 힘들게 합니다.
엄청난 장관을 옆에 두고서도 감히 한 눈을 팔 수는 없군요.
부인 발목의 부상이 걱정되지만 천천히 조심해서 폭포를 오릅니다.

어렵게 폭포의 정상에 도달합니다.
정상에서 보는 폭포의 장관이 엄청납니다.
물에 젖은 머리와 옷을 따뜻한 햇볕에 말리며 정상의 돌바닥에 주저 앉아 조금 숨을 돌립니다.
눈으로 사진으로 폭포의 장관을 한껏 담아봅니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (2).jpg">
      <img src="/assets/images/events/2024/vernalFall (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">드디어 보이기 시작한 Vernal Fall</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (3).jpg">
      <img src="/assets/images/events/2024/vernalFall (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">우의를 착용하고 흐뭇한 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (4).jpg">
      <img src="/assets/images/events/2024/vernalFall (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">투명 날개옷을 입은 선녀 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (5).jpg">
      <img src="/assets/images/events/2024/vernalFall (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">우의 착용 후 부인을 향해 경례!</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (6).jpg">
      <img src="/assets/images/events/2024/vernalFall (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">젖은 머리 남편과 뽀송한 부인의 셀카</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (8).jpg">
      <img src="/assets/images/events/2024/vernalFall (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 하단의 무지개</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (9).jpg">
      <img src="/assets/images/events/2024/vernalFall (9).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상을 향해 영차</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (10).jpg">
      <img src="/assets/images/events/2024/vernalFall (10).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (11).jpg">
      <img src="/assets/images/events/2024/vernalFall (11).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (12).jpg">
      <img src="/assets/images/events/2024/vernalFall (12).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (13).jpg">
      <img src="/assets/images/events/2024/vernalFall (13).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (14).jpg">
      <img src="/assets/images/events/2024/vernalFall (14).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (15).jpg">
      <img src="/assets/images/events/2024/vernalFall (15).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상을 노리다 잠시 휴식한 부인의 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (16).jpg">
      <img src="/assets/images/events/2024/vernalFall (16).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상을 노리다 새앙쥐가 된 남편의 엄지척</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (17).jpg">
      <img src="/assets/images/events/2024/vernalFall (17).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">부인의 승리를 함께 축하하는 젖은 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (18).jpg">
      <img src="/assets/images/events/2024/vernalFall (18).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 물안개를 뚫고 나온 부인의 미모</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (19).jpg">
      <img src="/assets/images/events/2024/vernalFall (19).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 물안개를 뚫고 나온 부인의 아름다움</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (20).jpg">
      <img src="/assets/images/events/2024/vernalFall (20).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 내려다 본 물줄기</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (21).jpg">
      <img src="/assets/images/events/2024/vernalFall (21).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 Glacier Point 방향으로 바라본 풍경</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (22).jpg">
      <img src="/assets/images/events/2024/vernalFall (22).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 전망대 방향으로 돌진하는 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (23).jpg">
      <img src="/assets/images/events/2024/vernalFall (23).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포로 다가가는 물줄기</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (24).jpg">
      <img src="/assets/images/events/2024/vernalFall (24).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 Mt Broderick 방향으로 바라본 풍경</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (25).jpg">
      <img src="/assets/images/events/2024/vernalFall (25).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포로 떨어지는 물줄기</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (26).jpg">
      <img src="/assets/images/events/2024/vernalFall (26).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 Clark Point 방향으로 바라본 바위 절벽</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (27).jpg">
      <img src="/assets/images/events/2024/vernalFall (27).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 바라본 폭포 하류</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (28).jpg">
      <img src="/assets/images/events/2024/vernalFall (28).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 바라본 Liberty Cap</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (29).jpg">
      <img src="/assets/images/events/2024/vernalFall (29).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 바라본 Liberty Cap</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (30).jpg">
      <img src="/assets/images/events/2024/vernalFall (30).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포를 정복한 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (31).jpg">
      <img src="/assets/images/events/2024/vernalFall (31).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포에 승리한 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (32).jpg">
      <img src="/assets/images/events/2024/vernalFall (32).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (33).jpg">
      <img src="/assets/images/events/2024/vernalFall (33).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상 풍경</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (37).jpg">
      <img src="/assets/images/events/2024/vernalFall (37).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (38).jpg">
      <img src="/assets/images/events/2024/vernalFall (38).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (39).jpg">
      <img src="/assets/images/events/2024/vernalFall (39).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (40).jpg">
      <img src="/assets/images/events/2024/vernalFall (40).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (42).jpg">
      <img src="/assets/images/events/2024/vernalFall (42).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (43).jpg">
      <img src="/assets/images/events/2024/vernalFall (43).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (45).jpg">
      <img src="/assets/images/events/2024/vernalFall (45).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 댄싱퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (41).jpg">
      <img src="/assets/images/events/2024/vernalFall (41).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 셀카퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (44).jpg">
      <img src="/assets/images/events/2024/vernalFall (44).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 셀카퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (53).jpg">
      <img src="/assets/images/events/2024/vernalFall (53).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 셀카퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (54).jpg">
      <img src="/assets/images/events/2024/vernalFall (54).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 셀카퀸이 된 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (46).jpg">
      <img src="/assets/images/events/2024/vernalFall (46).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 셀카킹이 된 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (47).jpg">
      <img src="/assets/images/events/2024/vernalFall (47).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 푸근한 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (48).jpg">
      <img src="/assets/images/events/2024/vernalFall (48).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 푸근한 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (49).jpg">
      <img src="/assets/images/events/2024/vernalFall (49).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 푸근한 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (50).jpg">
      <img src="/assets/images/events/2024/vernalFall (50).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 즐거운 부인과 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (52).jpg">
      <img src="/assets/images/events/2024/vernalFall (52).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 즐거운 부인과 남편 파트 2</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (51).jpg">
      <img src="/assets/images/events/2024/vernalFall (51).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 정상에서 흑막이 된 더스티</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (55).jpg">
      <img src="/assets/images/events/2024/vernalFall (55).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포를 내려가다 셀카퀸이 된 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (56).jpg">
      <img src="/assets/images/events/2024/vernalFall (56).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">욕심껏 4개의 폴을 움켜쥐고 폭포를 내려가는 검은 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (57).jpg">
      <img src="/assets/images/events/2024/vernalFall (57).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폴에 과욕을 부리면서 폭포를 내려가는 검정 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (58).jpg">
      <img src="/assets/images/events/2024/vernalFall (58).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편과 부인이 떠나도 변함없는 폭포</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (59).jpg">
      <img src="/assets/images/events/2024/vernalFall (59).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편과 부인이 떠나도 변함없는 폭포</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFall (61).jpg">
      <img src="/assets/images/events/2024/vernalFall (61).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편과 부인이 떠나도 변함없는 무지개</div>
</div>

<div style="clear: both"></div>
~~~
\\

~~~
<center>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFall (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFall (2).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFall (3).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFall (4).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<br>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFall (5).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/vernalFall (6).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

웅장한 폭포의 감동을 뒤로 하고 하산길에 오른 남편과 부인...
준비해 간 등산 폴의 덕을 톡톡히 보며 조심 조심 산을 내려 옵니다.
한참 걷다 보니 Vernal Falls Foot Bridge에 도착했습니다.
올라갈 때 보았던 그 모습 그대로 남편과 부인을 기다려 주었던 다리 위에서 사진을 찍습니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (6).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">기다려준 다리 위에서 남편 미소</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (7).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">기다려준 다리에게 부인 미소</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (8).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">기다려준 다리에게 부인 미소</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/vernalFallsFootBridge (9).jpg">
      <img src="/assets/images/events/2024/vernalFallsFootBridge (9).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">하산하는 남편과 부인을 묵묵히 지켜봐 준 Vernal 폭포와 Liberty Cap</div>
</div>

<div style="clear: both"></div>
~~~
\\

다리를 지나 Curry Village로 길을 재촉합니다.
돌아오며 새로운 각도로 보여지는 풍경이 좋습니다.
길 모퉁이를 도는 부인 모습이 풍경과 아주 잘 어울립니다.
급히 사진을 찍습니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (1).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">오후에도 멋진 하산길 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (2).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (3).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (4).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (5).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (6).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (7).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toCurryVillage (8).jpg">
      <img src="/assets/images/events/2024/toCurryVillage (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">풍경과 잘 어울어진 부인의 하산길</div>
</div>

<div style="clear: both"></div>
~~~
\\

산을 거의 내려오는데 한참 먼저 내려갔던 더스티가 멋적은 웃음을 지으며 다가옵니다.
또 다시 아뿔싸!!!
더스티도 발목을 접질렀군요.
걷는 것이 불편해 보입니다.
여행에 닥쳐온 두번째 위기...
많이 다치지는 않았나 걱정이 되는군요.
상태를 지켜봐야 겠습니다.

Curry Village에 도착했군요.
이미 저녁 식사를 할 시간이 되었습니다.
Curry Village에서 판매하는 핏자가 맛이 있다는 소문입니다.
그냥 갈 순 없지요.
요세미티 공원의 명소인 El Capitan의 이름을 딴 컴비네이션 핏자를 주문합니다.
소시지와 올리브 등등 여러 가지 재료로 꽉찬 핏자 군요.

첫입은 맛있었지만 계속 먹으니 남편과 부인의 입맛에는 너무 짠 핏자였습니다.
차라리 기본 핏자로 주문하는 것이 좋았겠다 싶었지만 Curry Village 명품인 핏자도 미션 완료했습니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/curryVillagePizza.jpg">
      <img src="/assets/images/events/2024/curryVillagePizza.jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Curry Village 명물 핏자집</div>
</div>

<div style="clear: both"></div>
~~~
\\

이제 핏자를 맛있게 먹고 숙소로 돌아갈 때입니다.
셔틀버스가 마침 왔군요.
바로 올라타고 숙소로 향합니다.

무사히 숙소에 도착한 일행...
이틀의 숙소를 따로 예약한 더스티가 오늘 묵을 숙소는 남편과 부인의 숙소와 가깝습니다.
발목을 다친 더스티와 부인을 위해 얼음을 준비하는 남편...
그나마 가까와진 더스티의 숙소가 조금 도움이 되는군요.

요세미티에서의 마지막 밤, 남편과 부인은 숙소 앞에서 밤하늘을 살펴봅니다.
숙소 근처라 주변이 밝지만 그래도 꽤 많은 별이 보입니다.
그 중 북두칠성이 바로 머리 위에 선명히 보이는 군요.
사진을 찍을 요량으로 남편이 핸드폰을 들이 대지만 별이 제대로 찍히지는 않습니다.
눈으로만 감상해야 하겠습니다.

하루의 모든 일정을 마치고 피곤한 몸을 침대에 뉘웁니다.
산행을 감행한 부인의 발목과 꽤 많이 다친 듯한 더스티 발목 모두 걱정입니다.
다음날 크게 악화되지 않기를 바라며 눈을 감습니다.

## 넷째 날 (Mar Monte Hotel)
요세미티 공원에서의 마지막 날 아침이 밝았습니다.
다행히 부인의 발목은 심하게 악화되지는 않았습니다.
조금은 이른 아침, 요세미티 공원을 떠나기 전에 Lower Yosemite Falls를 들러보기로 합니다.
숙소를 나와 머물렀던 숙소 전경을 사진으로 담아 봅니다.

@@image-center
![](/assets/images/events/2024/lodge.jpg)
@@
@@image-caption
이틀을 머물렀던 요세미티 숙소
@@
\\

숙소에서 폭포로 가는 길은 랏지 주차장을 거쳐갑니다.
주차장에서도 풍경이 좋습니다.
화강암 절벽들과 Upper Yosemite 폭포가 보이네요.
사진에 담아봅니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/lodgeParkingLot (1).jpg">
      <img src="/assets/images/events/2024/lodgeParkingLot (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 주차장에서 본 아침 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeParkingLot (2).jpg">
      <img src="/assets/images/events/2024/lodgeParkingLot (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 주차장에서 본 아침 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeParkingLot (3).jpg">
      <img src="/assets/images/events/2024/lodgeParkingLot (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 주차장에서 본 Upper Yosemite Falls</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeParkingLot (4).jpg">
      <img src="/assets/images/events/2024/lodgeParkingLot (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite Lodge 주차장에서 본 Upper Yosemite Falls</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lodgeParkingLot (5).jpg">
      <img src="/assets/images/events/2024/lodgeParkingLot (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Upper Yosemite Falls 남편 엄지척</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lodgeParkingLot (6).jpg">
      <img src="/assets/images/events/2024/lodgeParkingLot (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Upper Yosemite Falls를 배경으로 평온한 부인</div>
</div>

<div style="clear: both"></div>
~~~
\\

간단한 사진 촬영 후 다시 걸음을 재촉합니다.
Lower Yosemite Falls Trail에 들어서니 첫날 저녁 때 지나쳤던 예쁜 장소들이 눈에 들어옵니다.
사진 촬영의 순간이 돌아왔군요.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (1).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Trail 입구에서 남편과 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (2).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">통나무에 기댄 부인 (통나무 안보이는 ver.)</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (3).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">통나무에 기댄 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (4).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">통나무를 깔고 앉은 남편 엄지척</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (5).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 향해 당당한 부인 뒷모습</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (6).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 흐뭇한 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (8).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Yosemite 폭포를 배경으로 남편 엄지척</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (9).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (9).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Trail에서 부인을 반겨준 머리뾰족새</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (10).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (10).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Trail에서 부인을 반겨준 머리뾰족새</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (11).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (11).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Trail에서 부인을 반겨준 머리뾰족새</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (12).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (12).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Trail에서 기대에 찬 부인 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (13).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (13).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">Trail에서 기대에 찬 부인과 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (14).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (14).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">화강암 바위 앞 부인의 승리</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (15).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (15).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편 화강암 엄지척</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (16).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (16).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">화강암의 균열을 소개하는 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (17).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (17).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">균열 속으로 들어가려는 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (18).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (18).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">균열에 승리한 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (19).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (19).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배한 균열을 가여워하는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (20).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (20).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">균열에게 승리한 남편을 축하하는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (21).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (21).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">균열의 패배에 봉기한 바위들에게 둘러싸인 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (22).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (22).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">바위들을 손가락 하나로 여유있게 제압한 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFallsTrail (23).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFallsTrail (23).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">제압된 바위를 가엽게 여긴 부인</div>
</div>

<div style="clear: both"></div>
~~~
\\

조금 더 걷다보니 폭포에 다달았습니다.
오전 일찍 오니 사람도 별로 없고 폭포를 맘껏 즐길 수 있어 좋습니다.
이런 폭포 옆에서 살면서 이렇게 자주 산책할 수 있으면 좋겠다 싶네요.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (1).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (1).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">아침이라 한가한 폭포 앞</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (2).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (2).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 앞으로 홀린 듯 다가가는 부인의 뒷모습</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (3).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 앞으로 홀린 듯 다가가는 부인의 뒷모습</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (4).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 앞으로 홀린 듯 다가가는 부인의 뒷모습</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (5).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포 앞으로 홀린 듯 다가가는 부인의 뒷모습</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (6).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">아침에도 열심인 폭포에게 남편이 엄지척</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (7).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">엄지척 한번은 정이 없어요</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (8).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">엄지척은 삼세번</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (9).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (9).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포의 정신공격을 이겨낸 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (10).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (10).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포를 이겨내 뿌듯한 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (11).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (11).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배에 눈물을 흘리는 폭포</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (12).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (12).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">폭포를 이겼으니 파이팅!</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (13).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (13).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">승리의 여운을 즐기는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (14).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (14).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">승리가 뿌듯한 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (15).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (15).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">승리를 즐기는 부인과 함께 축하하는 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (16).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (16).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">승리를 즐기는 부인과 함께 축하하는 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (17).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (17).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">승리를 즐기는 부인과 함께 축하하는 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/lowerYosemiteFalls (18).jpg">
      <img src="/assets/images/events/2024/lowerYosemiteFalls (18).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배하고 굴복한 폭포를 뒤로 한 남편과 부인</div>
</div>

<div style="clear: both"></div>
~~~
\\

~~~
<center>
<video width="70%" styles="" controls>
      <source src="/assets/images/events/2024/lowerYosemiteFalls (1).mp4" type="video/mp4">
      Your browser does not support the video tag.
</video>

</center>
~~~
\\

폭포 감상을 마치고 다시 숙소로 돌아갑니다.
돌아가는 길에도 추억 사냥은 계속 됩니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (1).jpg">
      <img src="/assets/images/events/2024/toLodge (1).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (2).jpg">
      <img src="/assets/images/events/2024/toLodge (2).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (3).jpg">
      <img src="/assets/images/events/2024/toLodge (3).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">안이 파여 멋진 나무</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (4).jpg">
      <img src="/assets/images/events/2024/toLodge (4).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무 안으로 들어가기 전 몸가짐을 바로 하는 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (5).jpg">
      <img src="/assets/images/events/2024/toLodge (5).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무 안으로 들어간 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (6).jpg">
      <img src="/assets/images/events/2024/toLodge (6).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무 안으로 들어가 머리를 기울인 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (7).jpg">
      <img src="/assets/images/events/2024/toLodge (7).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">부인의 나무 안 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (8).jpg">
      <img src="/assets/images/events/2024/toLodge (8).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무 안 부인 클로즈업</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (9).jpg">
      <img src="/assets/images/events/2024/toLodge (9).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무 안 남편 엄지척</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (10).jpg">
      <img src="/assets/images/events/2024/toLodge (10).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무 안 남편 엄지척 ver.2</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (11).jpg">
      <img src="/assets/images/events/2024/toLodge (11).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">버릇 없이 덤빈 나무에게 승리한 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (12).jpg">
      <img src="/assets/images/events/2024/toLodge (12).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편의 승리를 함께 기뻐한 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (13).jpg">
      <img src="/assets/images/events/2024/toLodge (13).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배한 나무를 가엾게 여기는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (14).jpg">
      <img src="/assets/images/events/2024/toLodge (14).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">부인의 간지러움 공격에 크게 당한 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (15).jpg">
      <img src="/assets/images/events/2024/toLodge (15).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">부인의 공격에 흐뭇해 하는 부인과 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (16).jpg">
      <img src="/assets/images/events/2024/toLodge (16).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">아름다운 자연에 기쁨을 분출하는 부인과 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (17).jpg">
      <img src="/assets/images/events/2024/toLodge (17).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">밝은 미래로 향하는 트레일</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (18).jpg">
      <img src="/assets/images/events/2024/toLodge (18).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">트레일 위에서 행복한 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (19).jpg">
      <img src="/assets/images/events/2024/toLodge (19).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">트레일 위에서 행복한 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (20).jpg">
      <img src="/assets/images/events/2024/toLodge (20).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배로 점철된 트레일의 모든 것을 가엾게 여기는 부인</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (21).jpg">
      <img src="/assets/images/events/2024/toLodge (21).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">행복으로 향하는 트레일</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (22).jpg">
      <img src="/assets/images/events/2024/toLodge (22).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">건강으로 향하는 트레일</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (23).jpg">
      <img src="/assets/images/events/2024/toLodge (23).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">나무들의 합공을 이겨낸 남편</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (24).jpg">
      <img src="/assets/images/events/2024/toLodge (24).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">남편에게 패배한 나무들을 위로하는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (25).jpg">
      <img src="/assets/images/events/2024/toLodge (25).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">트레일에 있는 요세미티 폭포 청동 모형</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (26).jpg">
      <img src="/assets/images/events/2024/toLodge (26).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">청동 모형 이름표</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (27).jpg">
      <img src="/assets/images/events/2024/toLodge (27).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">돌아오는 길의 랏지 주차장 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (28).jpg">
      <img src="/assets/images/events/2024/toLodge (28).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">돌아오는 길의 랏지 주차장 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (29).jpg">
      <img src="/assets/images/events/2024/toLodge (29).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">돌아오는 길의 랏지 주차장 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (30).jpg">
      <img src="/assets/images/events/2024/toLodge (30).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배에도 굴하지 않은 폭포</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (31).jpg">
      <img src="/assets/images/events/2024/toLodge (31).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">패배에도 굴하지 않은 폭포</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (32).jpg">
      <img src="/assets/images/events/2024/toLodge (32).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">랏지로 돌아온 부인 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (33).jpg">
      <img src="/assets/images/events/2024/toLodge (33).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">랏지로 돌아온 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (34).jpg">
      <img src="/assets/images/events/2024/toLodge (34).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">돌아오는 길의 랏지 주차장 풍경</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/toLodge (35).jpg">
      <img src="/assets/images/events/2024/toLodge (35).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">승리를 만끽하며 숙소로 돌아가는 부인의 뒷모습</div>
</div>

<div style="clear: both"></div>
~~~
\\

숙소에 도착해 간단한 아침을 먹으며 출발 준비를 하고 있으니 더스티에게서 연락이 옵니다.
전날 다친 발목 상태가 그리 좋지 않은가 봅니다.
운전에는 무리가 없지만 제대로 걷지 못하고 절뚝 거리는 모양입니다.
산타 바바라까지의 여정을 취소하고 집에 돌아가 회복하는 것은 어떠냐는 의견에 그 정도는 아니라 합니다.
서둘러 정리를 마치고 체크아웃을 합니다.

돌아가는 차 안에서 요세미티 공원을 나가기 전 마지막으로 풍경을 담습니다.
아쉬움에 셔터를 많이 누릅니다.
달리는 차 안에서 찍은 사진들이라 아쉬운 사진들이 많군요.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (1).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (1).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (2).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (2).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (8).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (8).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (9).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (9).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (10).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (10).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (13).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (13).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (14).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (14).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (16).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (16).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (17).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (17).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (18).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (18).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (19).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (19).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (21).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (21).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (23).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (23).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (24).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (24).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (25).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (25).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (26).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (26).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (27).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (27).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (28).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (28).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (29).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (29).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (30).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (30).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (31).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (31).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (32).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (32).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (38).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (38).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (39).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (39).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (41).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (41).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (42).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (42).jpg" alt="Forest" style="width:100%">
    </a>
</div>


<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (44).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (44).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (45).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (45).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (47).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (47).jpg" alt="Forest" style="width:100%">
    </a>
</div>


<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (49).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (49).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (51).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (51).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (52).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (52).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (54).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (54).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (55).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (55).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (57).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (57).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (58).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (58).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (59).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (59).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (63).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (63).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (64).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (64).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (65).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (65).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (66).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (66).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (67).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (67).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (68).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (68).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (69).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (69).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (71).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (71).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (72).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (72).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (73).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (73).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (74).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (74).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (75).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (75).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">자연 경관에 지친 눈을 쉬게해 줄 자동차 뒷자석 남편 셀카</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (77).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (77).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (78).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (78).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (79).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (79).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (81).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (81).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (82).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (82).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (85).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (85).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (87).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (87).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (89).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (89).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (90).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (90).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (91).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (91).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (92).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (92).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (93).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (93).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (94).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (94).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (95).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (95).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (96).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (96).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (97).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (97).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (98).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (98).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (100).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (100).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (103).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (103).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (104).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (104).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (105).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (105).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (106).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (106).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (107).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (107).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (108).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (108).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (109).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (109).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (110).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (110).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/leavingYosemite (111).jpg">
      <img src="/assets/images/events/2024/leavingYosemite (111).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div style="clear: both"></div>
~~~
\\

차는 계속 달려 South Entrance를 지나 드디어 요세미티 공원을 빠져 나갑니다.
공원아, 안녕!
공원을 나오니 엄청난 화강암 절벽들은 사라져도 소나무와 멀리 보이는 산등성이들이 보기 좋습니다.
화재로 검게 탄 나무들이 특별한 광경을 연출하기도 합니다.
공원을 나와서도 남편의 전화기는 사진을 찍느라 불을 뿜습니다.
전망대에 잠깐 멈춰 부인과 남편의 사진을 찍기도 합니다.

~~~
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (1).jpg">
      <img src="/assets/images/events/2024/afterEntrance (1).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (2).jpg">
      <img src="/assets/images/events/2024/afterEntrance (2).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (3).jpg">
      <img src="/assets/images/events/2024/afterEntrance (3).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (6).jpg">
      <img src="/assets/images/events/2024/afterEntrance (6).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (7).jpg">
      <img src="/assets/images/events/2024/afterEntrance (7).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (8).jpg">
      <img src="/assets/images/events/2024/afterEntrance (8).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (9).jpg">
      <img src="/assets/images/events/2024/afterEntrance (9).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (11).jpg">
      <img src="/assets/images/events/2024/afterEntrance (11).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (12).jpg">
      <img src="/assets/images/events/2024/afterEntrance (12).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (13).jpg">
      <img src="/assets/images/events/2024/afterEntrance (13).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (14).jpg">
      <img src="/assets/images/events/2024/afterEntrance (14).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (15).jpg">
      <img src="/assets/images/events/2024/afterEntrance (15).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (16).jpg">
      <img src="/assets/images/events/2024/afterEntrance (16).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (18).jpg">
      <img src="/assets/images/events/2024/afterEntrance (18).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (19).jpg">
      <img src="/assets/images/events/2024/afterEntrance (19).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (20).jpg">
      <img src="/assets/images/events/2024/afterEntrance (20).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (21).jpg">
      <img src="/assets/images/events/2024/afterEntrance (21).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (22).jpg">
      <img src="/assets/images/events/2024/afterEntrance (22).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (23).jpg">
      <img src="/assets/images/events/2024/afterEntrance (23).jpg" alt="Forest" style="width:100%">
    </a>
</div>


<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (27).jpg">
      <img src="/assets/images/events/2024/afterEntrance (27).jpg" alt="Forest" style="width:100%">
    </a>
</div>


<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (29).jpg">
      <img src="/assets/images/events/2024/afterEntrance (29).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (30).jpg">
      <img src="/assets/images/events/2024/afterEntrance (30).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (31).jpg">
      <img src="/assets/images/events/2024/afterEntrance (31).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (32).jpg">
      <img src="/assets/images/events/2024/afterEntrance (32).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (33).jpg">
      <img src="/assets/images/events/2024/afterEntrance (33).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (34).jpg">
      <img src="/assets/images/events/2024/afterEntrance (34).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (36).jpg">
      <img src="/assets/images/events/2024/afterEntrance (36).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (37).jpg">
      <img src="/assets/images/events/2024/afterEntrance (37).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (38).jpg">
      <img src="/assets/images/events/2024/afterEntrance (38).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (39).jpg">
      <img src="/assets/images/events/2024/afterEntrance (39).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (41).jpg">
      <img src="/assets/images/events/2024/afterEntrance (41).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (42).jpg">
      <img src="/assets/images/events/2024/afterEntrance (42).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (43).jpg">
      <img src="/assets/images/events/2024/afterEntrance (43).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (44).jpg">
      <img src="/assets/images/events/2024/afterEntrance (44).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (45).jpg">
      <img src="/assets/images/events/2024/afterEntrance (45).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (46).jpg">
      <img src="/assets/images/events/2024/afterEntrance (46).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (47).jpg">
      <img src="/assets/images/events/2024/afterEntrance (47).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (48).jpg">
      <img src="/assets/images/events/2024/afterEntrance (48).jpg" alt="Forest" style="width:100%">
    </a>
</div>


<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (49).jpg">
      <img src="/assets/images/events/2024/afterEntrance (49).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (50).jpg">
      <img src="/assets/images/events/2024/afterEntrance (50).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (51).jpg">
      <img src="/assets/images/events/2024/afterEntrance (51).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (52).jpg">
      <img src="/assets/images/events/2024/afterEntrance (52).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (53).jpg">
      <img src="/assets/images/events/2024/afterEntrance (53).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (54).jpg">
      <img src="/assets/images/events/2024/afterEntrance (54).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (55).jpg">
      <img src="/assets/images/events/2024/afterEntrance (55).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (57).jpg">
      <img src="/assets/images/events/2024/afterEntrance (57).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (58).jpg">
      <img src="/assets/images/events/2024/afterEntrance (58).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (59).jpg">
      <img src="/assets/images/events/2024/afterEntrance (59).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (60).jpg">
      <img src="/assets/images/events/2024/afterEntrance (60).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (61).jpg">
      <img src="/assets/images/events/2024/afterEntrance (61).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (62).jpg">
      <img src="/assets/images/events/2024/afterEntrance (62).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (63).jpg">
      <img src="/assets/images/events/2024/afterEntrance (63).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (64).jpg">
      <img src="/assets/images/events/2024/afterEntrance (64).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (65).jpg">
      <img src="/assets/images/events/2024/afterEntrance (65).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (66).jpg">
      <img src="/assets/images/events/2024/afterEntrance (66).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (68).jpg">
      <img src="/assets/images/events/2024/afterEntrance (68).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (71).jpg">
      <img src="/assets/images/events/2024/afterEntrance (71).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (72).jpg">
      <img src="/assets/images/events/2024/afterEntrance (72).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (73).jpg">
      <img src="/assets/images/events/2024/afterEntrance (73).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (75).jpg">
      <img src="/assets/images/events/2024/afterEntrance (75).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (76).jpg">
      <img src="/assets/images/events/2024/afterEntrance (76).jpg" alt="Forest" style="width:100%">
    </a>
 </div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (77).jpg">
      <img src="/assets/images/events/2024/afterEntrance (77).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (78).jpg">
      <img src="/assets/images/events/2024/afterEntrance (78).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (79).jpg">
      <img src="/assets/images/events/2024/afterEntrance (79).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (81).jpg">
      <img src="/assets/images/events/2024/afterEntrance (81).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (82).jpg">
      <img src="/assets/images/events/2024/afterEntrance (82).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (83).jpg">
      <img src="/assets/images/events/2024/afterEntrance (83).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (84).jpg">
      <img src="/assets/images/events/2024/afterEntrance (84).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (87).jpg">
      <img src="/assets/images/events/2024/afterEntrance (87).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (89).jpg">
      <img src="/assets/images/events/2024/afterEntrance (89).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (90).jpg">
      <img src="/assets/images/events/2024/afterEntrance (90).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (91).jpg">
      <img src="/assets/images/events/2024/afterEntrance (91).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">화재로 소실된 나무들을 위로하는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (92).jpg">
      <img src="/assets/images/events/2024/afterEntrance (92).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">화재를 이겨낸 숲에게 엄지척을 보내는 남편</div>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (93).jpg">
      <img src="/assets/images/events/2024/afterEntrance (93).jpg" alt="Forest" style="width:100%">
    </a>
    <div class="desc">화재를 이겨낸 숲에게 따뜻한 미소를 보내는 부인</div>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (94).jpg">
      <img src="/assets/images/events/2024/afterEntrance (94).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (95).jpg">
      <img src="/assets/images/events/2024/afterEntrance (95).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (96).jpg">
      <img src="/assets/images/events/2024/afterEntrance (96).jpg" alt="Forest" style="width:100%">
    </a>
</div>
<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (97).jpg">
      <img src="/assets/images/events/2024/afterEntrance (97).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (100).jpg">
      <img src="/assets/images/events/2024/afterEntrance (100).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (103).jpg">
      <img src="/assets/images/events/2024/afterEntrance (103).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div class="gallery">
    <a href="/assets/images/events/2024/afterEntrance (104).jpg">
      <img src="/assets/images/events/2024/afterEntrance (104).jpg" alt="Forest" style="width:100%">
    </a>
</div>

<div style="clear: both"></div>
~~~
\\

차는 거침없이 달려 Oakhurst에 도착했습니다.
발목 부상의 통증을 참으며 운전하는 가엾은 더스티에게 Advil 진통제를 하사하고 떠나는 차창밖으로 재미있는 장소가 눈에 띕니다.
바로 Yosemite Cinema입니다.
YOSEMITE VR 이란 영화를 볼 수 있군요.

@@image-center
![](/assets/images/events/2024/yosemiteCinema.jpg)
@@
@@image-caption
요세미티 공원을 가상 현실로 접할 수 있는 Yosemite VR 영화를 절찬리 상영 중인 Yosemite Cinema
@@
\\

자동차는 계속 달립니다.

## 다섯째 날 (Mar Monte Hotel)

