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

## 첫째날 (Hyatt Place Fresno)

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

## 둘째날 (Yosemite Valley Lodge)

@@image-center
![](/assets/images/events/2024/day2route.jpg)
@@
@@image-caption
이동 경로
@@
\\

1. Washburn Point

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

2. Glacier Point

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

3. Bridalveil Fall

@@image-center
![](/assets/images/events/2024/BridalveilFall.webp)
@@
@@image-caption
Bridalveil Fall
@@
\\

Bridalveil Fall은 캘리포니아 요세미티 계곡에서 가장 눈에 띄는 폭포 중 하나입니다. 
이 폭포는 높이 188미터(617피트)로 연중 흐르며, Yosemite Valley를 따라 내려오는 물줄기 중 하나입니다. 


4. Lower Yosemite Fall

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



5. Cathedral Beach

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
