- 👋 Hi, I’m @TsViron
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
TsViron/TsViron is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="assets/css/style.css">
        <title>MS</title>
</head>
<body>
<header class="header">
    <div class="container">
        <div class="header_inner">
            <div class="header_logo">ASM</div>

            <nav class="nav">
                <a class="nav_link active" href="#">Главная</a>
                <a class="nav_link" href="#">Правила</a>
                <a class="nav_link" href="#">Топ</a>
                <a class="nav_link" href="#">Память</a>
                <a class="nav_link" href="#">"Зона"</a>
            </nav>
        </div>
     </div>
</header>


<div class="intro">
    <div class="container">
        <div class="intro_inner">
            <h2 class="intro_suptitle">Добро пожаловать в</h2>
            <h1 class="intro_title">ASM сообщество</h1>

            <a class="btn" href="#">Beta</a>
         </div>
    </div>

    <div class="slider">
        <div class="container">
            <div class="slider_inner">
                <div class="slider_item active">
                   <span class="slider_number">01</span>
                   intro
                </div>
                <div class="slider_item">
                   <span class="slider_number">02</span>
                   intro
                </div>
                <div class="slider_item">
                   <span class="slider_number">03</span>
                   intro
                </div>
                <div class="slider_item">
                   <span class="slider_number">04</span>
                   intro
                </div>
            </div>
        </div>
   </div>
</div>


<section class="section">
    <div class="container">

        <div class="section_header">
            <h1 class="section_suptitle">О нас</h1>
            <div class="section_text">
                <p>То ли из-за вудуистского ритуала, то ли из-за вируса, действующего только на мёртвую плоть, мёртвые стали восставать в виде зомби. Армии пытались противостоять им, но тщетно. Вследствии зомби-апокалипсиса уцелели только мы и мы решили что сыграть в мафию находясь в прочном бункере лучшее что мы можем сейчас сделать</p>
            </div>
        </div>

        <div class="about">
            <div class="about_item">
                <div class="about_img">
                    <img src="assets/img/revik.jpg" alt="" width="500" height="400">
                </div>
                <div class="about_text">текст</div>
            </div>

            <div class="about_item">
                <div class="about_img">
                    <img src="assets/img/manyak2.jpg" alt="" width="500" height="400">
                </div>
                <div class="about_text">текст</div>
            </div>

            <div class="about_item">
                <div class="about_img">
                    <img src="assets/img/slyapa.jpg" alt="" width="500" height="400">
                </div>
                <div class="about_text">текст</div>
            </div>
        </div>
            
    </div>
</section>

        
<div class="statistics">
    <div class="container">

        <div class="stat">
            <div class="stat_item">
                <div class="stat_num">24</div>
                <div class="stat_text">Участники</div>
            </div>
            <div class="stat_item">
                <div class="stat_num">15</div>
                <div class="stat_text">Кол-во игр</div>
            </div>
            <div class="stat_item">
                <div class="stat_num">6</div>
                <div class="stat_text">Победы Мирных</div>
            </div>
            <div class="stat_item">
                <div class="stat_num">9</div>
                <div class="stat_text">Победы Мафии</div>
            </div>
            <div class="stat_item">
                <div class="stat_num">21:00</div>
                <div class="stat_text">Время Сбора</div>
            </div>
        </div>

    </div>
</div>


    <section class="section">
        <div class="container">
            
            <div class="section_header">
                <h3 class="section_suptitle">Чем мы занимаемся</h1>
                <div class="section_text">
                    <p>Мы любительский клуб мафии, созданный под началом Shelter (игра для комапаний), обычное интернет комьюнити, пара-тройка десятков игроков, решивших провести время с удовольствием и интересом</p>
                </div>
            </div>

            <div class="wedo">
                <div class="wedo_item">
                    <img src="assets/img/art_maf.jpeg" width="560" alt="">
                </div>
                <div class="wedo_item">
                    <div class="xz1">
                        <div class="xz1_item">
                            <div class="xz1_header">
                                <img class="xz1_icon" src="assets/img/krasnorechie_2.png" alt="">
                                <div class="xz1_title">Красноречие</div>
                            </div>
                            <div class="xz1_content"></div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>


</body>
</html>

body {
    margin: 0;

    font-size: 15px;
    line-height: 1.6;
    color: #333;
}
*,
*:before,
*:after {
    box-sizing: border-box;
}

h1, h2, h3, h4, h5, h6 {
    margin: 0;
}

/* contanier*/
.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
}

/*Intro*/
.intro {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    height: 100vh;

    background: url(../img/ono.jpeg) center no-repeat;
    background-size: cover;

    opacity: 0.9;
}

.intro_inner {
    width: 100%;
    max-width: 880px;
    margin: 0 auto;

    text-align: center;
}

.intro_title {
    color: #fff;
    font-size: 84px;
    font-weight: 700;
    text-transform: uppercase;
    line-height: 1;

}

.intro_title:after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin: 60px auto;

    background-color: #fff;
}

.intro_suptitle {
    margin-bottom: 20px;

    font-size: 52px;
    color: #fff;  
    text-align: center;  
}

/* Header */
.header {
    width: 100%;
    padding-top: 30px;

    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
}

.header_inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.header_logo {
    font-size: 30px;
    font-weight: 700;
    color: #fff;

}

/* nav */
.nav {
    font-size: 14px;
    text-transform: uppercase;
}

.nav_link {
    display: inline-block;
    vertical-align: top;
    margin: 0 15px;
    position: relative;

    color: #fff;
    text-decoration: none;

    transition: color 0.2s linear;
}

.nav_link:after {
    content: "";
    display: block;
    width: 100%;
    height: 3px;

    background-color: #fce38a;
    opacity: 0;

    position: absolute;
    top: 100%;
    left: 0;
    z-index: 1;

    transition: opacity 0.2s linear;
}

.nav_link:hover {
    color: #fce38a;
}

.nav_link:hover:after,
.nav_link.active::after {
    opacity: 1;
}

.nav_link.active {
    color: #fce38a;
}

/* button */
.btn {
    display: inline-block;
    vertical-align: top;
    padding: 10px 30px;

    border: 3px solid #fff;

    font-size: 14px;
    font-weight: 700;
    color: #fff;
    text-transform: uppercase;
    text-decoration: none;

    transition: background 0.2s linear, color 0.2s linear;
}

.btn:hover {
    background-color: #fff;
    color: #333;
}

/* slider */
.slider {
    width: 100%;

    position: absolute;
    bottom: 0;
    left: 0;
    z-index: 1;
}

.slider_inner {
    display: flex;
    justify-content: space-between;
    margin-top: 30px;
}

.slider_item {
    width: 23%;
    padding: 20px 0;
    position: relative;

    border-top: 3px solid #fff;
    opacity: 0.7;

    font-size: 18px;
    color: #fff;
    text-transform: uppercase;
}

.slider_item.active {
    opacity: 1;
}

.slider_item.active::before {
    content: "";
    display: block;
    width: 80px;
    height: 3px;

    background-color: red;

    position: absolute;
    top: -3px;
    left: 0;
    z-index: 1;
}

.slider_number {
    font-size: 24px;
    font-weight: 700;
}

/* section */
.section {
    padding: 80px 0;


}

.section_header {
    width: 100%;
    max-width: 950px;
    margin: 0 auto 40px;  

    text-align: center;
}

.section_suptitle {
    font-size: 24px;
    color: #333;
}

.section_suptitle:after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin: 30px auto;

    background-color: #ff0000;
}

.section_text {
    color: #333;
    size: 15px;
}

/* about */

.about {
    margin-top: 80px;
    display: flex;
    justify-content: space-between;
}

.about_item {
    width: 500px;
    margin-right: 170px;

    position: relative;
}

.about_item:hover .about_img {
    transform: translate3d(-10px, -10px, 0);
}

.about_item:hover .about_img img {
    opacity: 0.2;
}

.about_item:hover .about_text {
    opacity: 1;
}

.about_img {
    background: linear-gradient(to bottom, #f38181, #fce38a);
    
    margin-left: -150px;

    transition: transform 0.2s linear;
}

.about_img img {
    display: block;
    transition: opacity 0.2s linear;
}

.about_text {
    width: 56%;

    font-size: 18px;
    color: #fff;
    text-transform: uppercase;
    font-weight: 700;
    text-align: center;
    opacity: 0;

    position: absolute;
    top: 50%;
    left: 0;
    z-index: 2;
    transform: translate3d(0, -50%, 0);

    transition: opacity 0.2s linear;
}

/* statistics */
.statistics {
    background-color: #585858;
}

.stat {
    display: flex;
}

.stat_item {
    flex: 1 1 0;
    padding: 40px 25px;

    border-left: 1px solid #808080;

    text-align: center;
    color: #fff;
}

.stat_item:last-child {
    border-right: 1px solid #808080;
}

.stat_num {
    margin-bottom: 10px;
    font-size: 72px;
    font-weight: 700;
    line-height: 1;
}

.stat_text {
    font-size: 14px;
    text-transform: uppercase;
}

/* We do */
.wedo {
    display: flex;
}

.wedo_item {
    width: 50%;
}
