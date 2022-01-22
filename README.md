## 삼성전자 클론 코딩 반응형 웹페이지

### 🖥환경
- HTML
- CSS
- Bootstrap

### 🖼썸네일
![04-full](https://user-images.githubusercontent.com/83056872/128046523-4f78cb7c-d5ec-4759-a157-9e1d155fcb07.jpg)

### ✍중요

**캐러셀을 이용한 이미지 슬라이드**
![캐러셀](https://user-images.githubusercontent.com/83056872/128046880-6f4325c1-b42e-4132-bc0d-b37f8ed4e423.JPG)
```html
<div id="myCarousel" class="carousel slide" data-ride="carousel">
<!-- Indicators -->
<ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active">새로운 Galaxy</li>
    <li data-target="#myCarousel" data-slide-to="1">Galaxy S21 5G</li>
    <li data-target="#myCarousel" data-slide-to="2">BESPOKE제트</li>
    <li data-target="#myCarousel" data-slide-to="3">BESPOKE냉장고</li>   
</ol>

<!-- Wrapper for slides -->
<div class="carousel-inner" role="listbox">
    <div class="item active">
        <div id="vid">
            <video autoplay loop muted width="100%" height="100%">
                <source src="img/galaxy.webm" type="video/mp4"/>
            </video>
        </div>
        <div id="vid_mobile">
            <video autoplay loop muted width="100%" height="100%">
                <source src="img/galaxy_mobile.webm" type="video/mp4"/>
            </video>
        </div>
        <div class="carousel-caption caption_pc">
            <h3>새로운 Galaxy
            <br>
            사전판매 알림신청
            </h3>
            <p>알림 신청 후 사전 구매 시 네이버페이 포인트 더블 적립!</p>
        </div>
        <div class="carousel-caption caption_mobile">
            <h3>새로운 Galaxy
            <br>
            사전판매 알림신청
            </h3>
            <p>알림 신청 후 사전 구매 시 네이버페이 포인트 더블 적립!</p>
        </div>
    </div>

    <div class="item">
        <img class="img_pc" src="img/img01_pc.webp" alt="Galaxy S21">
        <img class="img_mobile" src="img/img01_mobile.webp" alt="Galaxy S21">
        <div class="carousel-caption caption_pc">
        <h3>Galaxy S21 I S21+
            <br>
            S21 Ultra 5G
        </h3>
        <p>지금 삼성닷컴에서 중고폰 추가보상 혜택으로 만나보세요!</p>
        </div>
        <div class="carousel-caption caption_mobile">
            <h3>Galaxy S21 I S21+
            <br>
            S21 Ultra 5G
        </h3>
        <p>지금 삼성닷컴에서 중고폰 추가보상 혜택으로 만나보세요!</p>
        </div>
    </div>

    <div class="item">
        <img class="img_pc" src="img/img02_pc.webp" alt="BESPOKE 제트">
        <img class="img_mobile" src="img/img02_mobile.webp" alt="BESPOKE 제트">
        <div class="carousel-caption caption_pc" style="color:black;">
            <h3>BESPOKE 제트 런칭</h3>
            <p>최대 18만 혜택 받고
            <br>
            새로워진 삼성 BESPOKE 제트를 만나보세요
            </p>
        </div>
        <div class="carousel-caption caption_mobile" style="color:black;">
            <h3>BESPOKE 제트 런칭</h3>
            <p>최대 18만 혜택 받고
            <br>
            새로워진 삼성 BESPOKE 제트를 만나보세요
            </p>
        </div>
    </div>

    <div class="item">
        <img class="img_pc" src="img/img03_pc.webp" alt="BESPOKE 냉장고">
        <img class="img_mobile" src="img/img03_mobile.webp" alt="BESPOKE 냉장고">
        <div class="carousel-caption caption_pc" style="color:black;">
            <h3>2021 New
            <br>
            BESPOKE 냉장고
            </h3>
            <p>2021 새로운 컬러와 삼성닷컴 단독 혜택을 만나보세요</p>
        </div>
        <div class="carousel-caption caption_mobile" style="color:black;">
            <h3>2021 New
            <br>
            BESPOKE 냉장고
            </h3>
            <p>2021 새로운 컬러와 삼성닷컴 단독 혜택을 만나보세요</p>
        </div>
    </div>
</div>
```

### 🏷URL
http://leap22.dothome.co.kr/sec/
