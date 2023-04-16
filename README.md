# CSS-Odev1
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Müzik Dükkanım</title>

    <style>
        body {
            background-color: lightcyan;
        }

        h1 {
            color: red;
            text-align: center;
        }

        nav {
            text-align: center;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        h2 {
            text-align: center;
            color: blueviolet;
        }

        h3 {
            text-align: center;
            color: darkorange;
        }

        ul {
            text-align: center;
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif;
            font-style: italic;
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }

        figure {
            margin: auto;
            width: 33%;
            padding: 10px;
        }

        footer {
            padding: 20px;
            text-align: center;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <h1> Müzik Dükkanım </h1>
    </header>
    <!-- Navbar -->
    <nav>
        <b>
        <a href="CSS_Ödev1.html">Ana Sayfa</a>
        <a href="Ürünlerimiz.html">Ürünlerimiz</a>
        <a href="Hakkımızda.html">Hakkımızda</a>
        <a href="İletişim.html">İletişim</a>
    </b>
    </nav>
    <!-- Ana Sayfa -->
    <!-- Section -->
    <section>
        <h2> Ana Sayfa </h2>
        <p style="text-align: center;">Müzik dükkanı sayfamıza hoşgeldiniz. Bu sayfada, birbirinden farklı ihtiyacınıza göre müzik alaeti bulabilirsiniz.Uygun fiyatta ve kalitede ürünler için; <b><a href="Ürünlerimiz.html">Ürünlerimiz</a></b> sayfasını ziyaret edin!</p>
        <br>
        <h3> Sitemizde Bulunan Müzik Aletleri</h3>
        <ul>
            <li>Gitar</li>
            <li>Bağlama</li>
            <li>Piyano</li>
            <li>Bateri</li>
            <li>Viyolansel</li>
        </ul>
        <br>
        <figure>
            <img src="https://i.ytimg.com/vi/9ss4ux9hDsI/maxresdefault.jpg" width="600" height="400"/>
        </figure>
    </section>

    <br>
    <hr>

    <section>
        <h3>Müzik Aletleri Tarihçesi</h3>
        <p>Antik çağlardan beri enstrümanların kökeni hakkında spekülasyonlar olmuştur. 19. yüzyılda, kısmen Charles Darwin ve Herbert Spencer tarafından ortaya konulan evrim teorilerinin bir sonucu olarak, antropolojik kanıtlara dayanan yeni kronolojiler ilerletildi. Bununla birlikte, araçların belirli bir bölgeye has olup olmadığını söylemek her zaman kolay değildir, çünkü bunlar ticaret veya göç yoluyla bir ülkeden diğerine yayılmış olabilir. Bununla birlikte, arp Mezopotamya ve Mısırın erken zamanlarında kullanıldı, Hindistan ve 4. yüzyıl sonundan sonra Çin’e ithal edildi ve Yunanistan’da yabancı bir araç olarak kabul edildi.</p>

        <figure>
            <img src="https://listelist.com/wp-content/uploads/2021/09/muzik-tarihi-1.jpg" width="600" height="400"/>
        </figure>

        <br>

        <p>Avusturyalı yazar öte yandan Richard Wallaschek, ritim temel öğe olmasına rağmen, borunun önce geldiğini, ardından şarkının ve ardından davulun geldiğini ileri sürmüştür. Sachs kronolojisini arkeolojik kazılara ve içinde bulunan aletlerin coğrafi dağılımına dayandırdı. Bu yöntemi takiben üç ana katman kurdu. Tüm dünyada bulunan ilk tabaka, basit idiofonlar ve üflemelilerdi. Daha az yaygın olarak dağılmış olan ikinci tabaka, davul ve basit telli çalgılardı ve üçüncüsü, sadece belirli bölgelerde görülen, ksilofonlar, bagetler ve daha karmaşık flütlerdi.</p>
    </section>

    <br>

    <!-- Footer -->
    <footer>
        <p>Müzik Dükkanı Tanıtım &copy; 2023. Tüm hakları saklıdır.</p>
    </footer>

</body>
</html>
