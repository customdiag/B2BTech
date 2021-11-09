# HUONG DAN

## Huong dan khoi tao

### Cai NodeJS v4.8

Cai nodeJS v4.8.x: <https://nodejs.org/en/blog/release/v4.8.6/> theo huong dan nay: <https://stencil.bigcommerce.com/docs/prerequisites-windows>

### Cai Stencil CLI/Framework

Danh lenh:

```bash
npm install -g @bigcommerce/stencil-cli
```

Co loi thi coi huong dan o day: <https://stencil.bigcommerce.com/docs/installing-stencil-cli-1>


### Tai source code theme

Danh lenh de git source ve:

```bash
git clone https://github.com/tvlgiao/bc-april-dev.git
```

Cai cac Node module can thiet:

```bash
cd bc-apri-dev
npm install
```

### Ket noi den server BigCommerce

Danh lenh:

```bash
stencil init
```

Nhap vao:

- URL: 
- Client ID: 
- Access Token: 

### Chay theme o local

Danh lenh:

```
stencil start
```

Mo URL tren web browser: <http://localhost:3000/>


## Huong dan code

- CSS files: `assets/scss`
- HTML files: `templates/*`
- HTML homepage: `templates/pages/home.html`

**Code toan bo css style car trong file `assets/scss/vendor/april/style-car/main.scss`**

Co the tao cac file trong thu muc `assets/scss/vendor/april/` de chua cac file include trong `main.scss`.

## Static HTML

```html
<div class="papaAprilCar-countdownBanner" id="emthemesModezBannersBlockHomeCountdown">
    <div class="papaAprilCar-countdownBanner-background" style="background-image:url(https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-countdown-bg.jpg)">
            <div class="container">
                <div class="papaAprilCar-countdownBanner-img">
                <a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-countdown-img.png" alt="669x556" class="wow slideInLeft" /></a>
                <div class="papaAprilCar-countdownBanner-badget wow bounceIn" data-wow-delay="1s">
                    <p class="inner">only <strong>$299.00</strong></p>
                </div>
            </div>
            <div class="papaAprilCar-countdownBanner-content">
                <p class="papaAprilCar-countdownBanner-title wow slideInUp" style="background-image:url(https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-countdown-title-bg.png)">#APRILSTORE</p>
                <h3 class="papaAprilCar-countdownBanner-text wow tada" data-wow-delay="500ms"><a href="#">SALE UP TO 40% OFF</a></h3>
                <p class="papaAprilCar-countdownBanner-countdown wow fadeInUp" data-wow-delay="1s" data-countdown="2020-12-12T00:00:00Z">
                    <span class="item"><span class="day" data-countdown-day>00</span> <span class="label">days</span></span>
                    <span class="item seperator">:</span>
                    <span class="item"><span class="hour" data-countdown-hour>00</span> <span class="label">hours</span></span>
                    <span class="item seperator">:</span>
                    <span class="item"><span class="min" data-countdown-min>00</span> <span class="label">mins</span></span>
                    <span class="item seperator">:</span>
                    <span class="item"><span class="sec" data-countdown-sec>00</span> <span class="label">secs</span></span>
                </p>
            </div>
        </div>
    </div>
</div>
```


```html
<div class="papaAprilCar-4colInfo" id="emthemesModezBannersBlockHome4ColInfo">
    <div class="container">
        <div class="papaAprilCar-4colInfo-col wow slideInUp">
            <div class="papaAprilCar-4colInfo-col-icon">
                <img src="https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-4col-info-icon1.png" alt="30x30">
            </div>
            <h3 class="papaAprilCar-4colInfo-col-heading">30 DAYS RETURN</h3>
            <p class="papaAprilCar-4colInfo-col-text">Phasellus rhoncus a dui quis elemen turn. In non feugiat massa. Proin luctus, ligula pharetra quam.</p>
        </div>
        <div class="papaAprilCar-4colInfo-col wow slideInUp" data-wow-delay="200ms">
            <div class="papaAprilCar-4colInfo-col-icon">
                <img src="https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-4col-info-icon2.png" alt="30x30">
            </div>
            <h3 class="papaAprilCar-4colInfo-col-heading">FREE DELIVERY</h3>
            <p class="papaAprilCar-4colInfo-col-text">Suspendisse dapibus vestibulum justo sed rhoncus. Cras vehicula quam sem, sed ornare rutrumeu.</p>
        </div>
        <div class="papaAprilCar-4colInfo-col wow slideInUp" data-wow-delay="400ms">
            <div class="papaAprilCar-4colInfo-col-icon">
                <img src="https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-4col-info-icon3.png" alt="30x30">
            </div>
            <h3 class="papaAprilCar-4colInfo-col-heading">SECURE RETURNS</h3>
            <p class="papaAprilCar-4colInfo-col-text">Quisque porta magna erat, eu feugiat felis finibus luctus. Sed risus libero, viver raet, orci pharetra.</p>
        </div>
        <div class="papaAprilCar-4colInfo-col wow slideInUp" data-wow-delay="600ms">
            <div class="papaAprilCar-4colInfo-col-icon">
                <img src="https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-4col-info-icon4.png" alt="30x30">
            </div>
            <h3 class="papaAprilCar-4colInfo-col-heading">ONLINE SUPPORT 24/7</h3>
            <p class="papaAprilCar-4colInfo-col-text">Maximus nibh nec turpis ultricies, euismod posuere justo mollis. Duis malesuada blandit mauris.</p>
        </div>
    </div>
</div>
```


```html
<div class="papaAprilCar-drivingBanner" id="emthemesModezBannersBlockHomeDriving">
    <div class="papaAprilCar-drivingBanner-background" style="background-image:url(https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-driving-bg.png)">
        <div class="container">
            <div class="papaAprilCar-drivingBanner-content wow slideInUp">
                <h3 class="papaAprilCar-drivingBanner-title"><a href="#">FOR COMFOTABLE DRIVING</a></h3>
                <p class="papaAprilCar-drivingBanner-text">KEEP YOUR CAR AS GOOD AS NEW</p>
            </div>
            <div class="papaAprilCar-drivingBanner-img wow slideInLeft" data-wow-delay="500ms">
                <a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/caril/demo/images/home-driving-img.png" alt="1068x273"></a>
                <div class="papaAprilCar-drivingBanner-badget wow bounceIn" data-wow-delay="2s">
                    <div class="inner"><a href="#">SHOP<small>NOW</small></a></div>
                </div>
            </div>
        </div>
    </div>
</div>
```


```html
<div class="papaAprilCar-brand-wrap">
    <div class="container">
        <div id="emthemesModezBannersBlockBrandsCarousel" class="emthemesModez-brandCarousel-container" data-section-type="brands-logo">
            <div class="emthemesModez-brandCarousel" data-emthemesmodez-brand-carousel="">
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="0"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand01.png" alt="Sample Brand 1" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="0.2s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand02.png" alt="Sample Brand 2" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="0.4s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand03.png" alt="Sample Brand 3" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="0.6s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand04.png" alt="Sample Brand 4" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="0.8s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand05.png" alt="Sample Brand 5" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="1s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand01.png" alt="Sample Brand 6" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="1.2s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand02.png" alt="Sample Brand 7" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="1.4s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand03.png" alt="Sample Brand 8" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="1.6s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand04.png" alt="Sample Brand 9" /></a></div>
                <div class="emthemesModez-brandCarousel-slide wow slideInUp" data-wow-delay="1.8s"><a href="#"><img src="https://tvlgiao.github.io/bigcommerce-themes/laparis/demo/images/brand05.png" alt="Sample Brand 10" /></a></div>
            </div>
        </div>
    </div>
</div>
```