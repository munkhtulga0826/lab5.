# lab5.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./styles/main.css" />
    <link rel="stylesheet" href="./styles/menu.css" />
    <title>Lab 5</title>
  </head>
  <body>
      <div class="page1">
    <!-- Navigation end baigaa -->
    <nav class="navbar">
      <div class="content">
        <ul class="items">
          <li class="menu-item">
            <a href="#" onclick="callMenu()"><i class="fa fa-bars" aria-hidden="true"></i></a>
          </li>
          <li><a href="#"><h1>SONS.MN</h1></a></li>
        </ul>
      </div>
    </nav>
    <!-- Hailt ba card uud -->
    <div class="container">
      <div class="search-container">
        <div class="search-bar">
            <input class="search-input" type="text" placeholder=" Хайх үгээ оруулна уу" name="search">
            <a class="search-icon"><i class="fa fa-search" aria-hidden="true"></i></a>
            </input>
        </div>
      </div>
      <section class="card-container">
          <div class="card">
            <img src="http://www.sons.mn/files/news/TEG.jpg" width="120px" >
            <div class="card-text">
                <h2 class="card-header">
                    ТЕГ: Хятад иргэд их хэмжээний бэлэн ба бэлэн бус валют хилээр нэвтрүүлсэн
                </h2>
                <div class="card-date">
                    <i class="fa fa-calendar date-icon" aria-hidden="true"></i>
                    <p class="date-text">2019-11-7 08:08:35</p>
                </div>
                <div class="card-footer">
                    <h3>Эх сурвалж:</h3>
                    <img src="data:image/png;base64,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" width="120px">
                </div>
            </div>
          </div>
          <div class="card">
            <img src="http://www.sons.mn/files/news/51_20191104150256.jpg" width="120px" >
            <div class="card-text">
                <h2 class="card-header">
                    Хоригдлуудад ажиллсан цалинг нь дутуу бодож олгодог зэрэг зөрчил илэрчээ
                </h2>
                <div class="card-date">
                    <i class="fa fa-calendar date-icon" aria-hidden="true"></i>
                    <p class="date-text">2019-11-7 08:04:26</p>
                </div>
                <div class="card-footer">
                    <h3>Эх сурвалж:</h3>
                    <img src="data:image/png;base64,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" width="120px">
                </div>
            </div>
          </div>
          <div class="card">
            <img src="http://www.sons.mn/files/news/520f15_xi_jinping_kerry_lam_x974.jpg" width="120px" >
            <div class="card-text">
                <h2 class="card-header">
                    Хонг Конгийн захирагчид бүрэн итгэж байгаа Ши Жиньпин илэрхийлжээ
                </h2>
                <div class="card-date">
                    <i class="fa fa-calendar date-icon" aria-hidden="true"></i>
                    <p class="date-text">2019-11-7 07:58:37</p>
                </div>
                <div class="card-footer">
                    <h3>Эх сурвалж:</h3>
                    <img class="ikon-img" src="https://content.ikon.mn/ikon/images/ikon@2x.png" width="130px">
                </div>
            </div>
          </div>
          <div class="card">
            <img src="http://www.sons.mn/files/news/6dc576_open-uri20191104-22161-1cnjpru_x974.jpg" width="120px" >
            <div class="card-text">
                <h2 class="card-header">
                    Хийн хоолойг Монголоор дайруулах асуудалд нухацтай хандаж, хамтран ажиллахыг хүсэв
                </h2>
                <div class="card-date">
                    <i class="fa fa-calendar date-icon" aria-hidden="true"></i>
                    <p class="date-text">2019-11-7 08:08:35</p>
                </div>
                <div class="card-footer">
                    <h3>Эх сурвалж:</h3>
                    <img src="data:image/png;base64,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" width="120px">
                </div>
            </div>
          </div>
          <div class="card">
            <img src="http://www.sons.mn/files/news/dbedd3_74605599.jpg" width="120px" >
            <div class="card-text">
                <h2 class="card-header">
                    Оны эхний есөн сарын байдлаар хавдрын өдрийн хими эмчилгээнд 281 хүн хамрагджээ
                </h2>
                <div class="card-date">
                    <i class="fa fa-calendar date-icon" aria-hidden="true"></i>
                    <p class="date-text">2019-11-7 08:08:35</p>
                </div>
                <div class="card-footer">
                    <h3>Эх сурвалж:</h3>
                    <img src="data:image/png;base64,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" width="120px">
                </div>
            </div>
          </div>
      </section>
    
    </div>
    <!-- Playback. CSS dee uuniig fixed bolgovol bainga door chin naaldana -->
    <div class="playbar-box">
        <div class="playbar-container">
            <div class="playbar-flex">
                <div class="playbar">
                    <p class="slider-time">00:44</p>
                    <input type="range" class="play-slider">
                    <p class="slider-time">02:03</p>
                </div>
            </div>
            
            <div class="playhandler-container">
                <div class="playhandler">
                <i class="fa fa-step-backward" aria-hidden="true"></i>
                <i class="fa fa-pause-circle stop-icon" aria-hidden="true"></i>
                <i class="fa fa-step-forward" aria-hidden="true"></i>
                </div>
                
            </div>
        </div>
    </div>
    
</div>
    <!-- Modal. Navigation iin tovch deer daranguud garj ireh content. Uuniig hylbar bolgoh uudnees Javascript iin bas oruulchihay. -->
    <div class="menu-container">
        <div class="navbar-menu">
            <div class="menu-header">
                <img src="http://www.sons.mn/images/logo.png">
                <a onclick="closeMenu()"><i class="fa fa-times close-icon" aria-hidden="true"></i></a>
            </div>
            <div class="menu-choices">
                <ul>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">БҮХ МЭДЭЭ</h1></button></div></li>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">УЛС ТӨР</h1></button></div></li>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">НИЙГЭМ</h1></button></div></li>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">ЭДИЙН ЗАСАГ</h1></button></div></li>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">ТЕХНОЛОГИ</h1></button></div></li>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">СПОРТ</h1></button></div></li>
                    <li><div class="menu-item-container"><button class="menu-item-button"><h1 class="menu-text">ДЭЛХИЙД</h1></button></div></li>
                </ul>
            </div>
            <div class="menu-img">
                <img src="http://www.sons.mn/files/banner/banner.png">
            </div>
        </div>
    </div>
    
    <script>
        let page1 = document.querySelector(".page1");
        let navbarMenu = document.querySelector(".navbar-menu");
        function callMenu(){
            page1.style.display = "none";
            navbarMenu.style.display = "block";
        }
        function closeMenu(){
            page1.style.display = "block";
            navbarMenu.style.display = "none";
        }
    </script>
</body>
</html>
