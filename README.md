<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rammstein Fan Site</title>
    <link rel="icon" href="images.png" type="image/x-icon">
    <link rel="shortcut icon" href="images.png" type="image/x-icon">

    <style>
        /* Основные стили */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #181818;
            color: #f5f5f5;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .cards-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .member-card {
            padding: 16px;
            margin: 1px;
            width: 100px;
            text-align: center;
            flex-shrink: 0;
        }

        .member-card img { 
            width: 150px; 
            height: auto;
            border-radius: 10%; 
        }
        .member-card h3 {
            margin-top: 8px;
            font-size: 1.2em;
        }
        .member-card p { 
            font-size: 0.9em;
            color: #666;
        }
        nav {
            background-color: #ff0000;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #f5f5f5;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            color: #0000ff;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: 20px auto;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border: 2px solid #333;
            border-radius: 5px;
            cursor: pointer;
        }
         
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать на фан-сайт Rammstein</h1>
        <p>Просто фанатский сайт :)</p>
    </header>
    <nav>
        <a href="#history">История</a>
        <a href="#facts">Интересные факты</a>
        <a href="#gallery">Галерея</a>
        <a href="#member">Участники группы</a>
        <a href="#song">Популярные песни</a>
    </nav>
        
    <section id="history">
        <h2>История группы</h2>
        <p>Rammstein — немецкая метал-группа, основанная в 1994 году. Их уникальный стиль сочетает тяжелый звук, глубокие тексты и эпатажные шоу.</p>
    </section>
    <section id="facts">
        <h2>Интересные факты</h2>
        <ul>
            <li>Название группы происходит от города Рамштайн в Германии.</li>
            <li>Их концерты славятся невероятными пиротехническими эффектами.</li>
            <li>Песни исполняются преимущественно на немецком языке.</li>
        </ul>
    </section>
    <section id="gallery" class="gallery">
        <h2>Галерея</h2>
        <img src="rammstein-koncert-engel-angle.jpg" alt="Engel" onclick="enlargeImage(this)">
        <img src="929532-rammstein-in-concert.jpg" alt="From_concert" onclick="enlargeImage(this)">
        <img src="maxresdefault.jpg" alt="Puppe" onclick="enlargeImage(this)">
        <img src="627610.jpg" alt="Pasti" onclick="enlargeImage(this)">
        <img src="54375_ZNYYTb0H9LpMeQL1_30579.jpg" alt="Ich_du_dir_weh" onclick="enlargeImage(this)">
        <img src="_JK_8604.jpg" alt="Intro" onclick="enlargeImage(this)">
        <img src="7301a92cc1b392f14f82e2fdcd4fa0ab.webp" alt="molodue" onclick="enlargeImage(this)">
        <img src="Lmq4A934_oA.webp" alt="all_member" onclick="enlargeImage(this)">
        <img src="old-rammstein-live-video-v0-8cisrkbzcav91.webp" alt="Till" onclick="enlargeImage(this)">

    </section>
 
    <section id="member">
        <div class="cards-container">
            <div class="member-card">
                <img src="till.jpg" alt="Till."> 
                <h3>(Till Lindemann)</h3>
                <p>06/01/1963</p>
            </div>
      <div class="member-card">
         <img src="paul.jpg" alt="Paul."> 
         <h3>(Paul Landers)</h3>
         <p>09/12/1964</p>
        </div>
        <div class="member-card">
         <img src="richard.jpg" alt="RZK."> 
         <h3>(Richard Zven Kruspe)</h3>
         <p>24/06/1967</p>
        </div>
        <div class="member-card">
         <img src="doom.jpg" alt="Doom."> 
         <h3>(Christoph Schneider)</h3>
         <p>11/05/1966</p>
        </div>
        <div class="member-card">
         <img src="olli.jpg" alt="Oliver."> 
         <h3>(Oliver Riedel)</h3>
         <p>11/04/1971</p>
        </div>
        <div class="member-card">
         <img src="flake.jpg" alt="Flake."> 
         <h3>(Christian Lorenz)</h3>
         <p>16/11/1966</p>
        </div>
    </section>

    <section id="song" class="song">
        <h2>Популярные песни</h2>
        
        <div class="audio-track">
        <audio controls>
        <source src="Rammstein – DU HAST.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Du hast</p>   
        </div>
        <div class="audio-track">
        <audio controls>
        <source src="Rammstein – SONNE.mp3" type="audio/mpeg">
        </audio>
        <p>Rammstein - Sonne</p>
        </div>
          <div class="audio-track">
        <audio controls>
        <source src="Rammstein – DEUTSCHLAND.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Deutschland</p>   
        </div> 
        <div class="audio-track">
        <audio controls>
        <source src="Rammstein – ENGEL.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Engel</p>   
        </div>
        <div class="audio-track">
        <audio controls>
        <source src="Rammstein – Mein Herz brennt.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Mein Herz brennt</p>   
        </div>
         <div class="audio-track">
        <audio controls>
        <source src="Rammstein – ICH WILL.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Ich Will</p>   
        </div>
         <div class="audio-track">
        <audio controls>
        <source src="Rammstein – Feuer frei!.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Feuer Frei!</p>   
        </div>
         <div class="audio-track">
        <audio controls>
        <source src="Rammstein – AMERIKA.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Amerika</p>   
        </div>
         <div class="audio-track">
        <audio controls>
        <source src="Rammstein – AUSLÄNDER.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Ausländer</p>   
        </div>
        <div class="audio-track">
        <audio controls>
        <source src="Rammstein – RADIO.mp3" type="audio/mpeg">
        </audio>
        <p> Rammstein - Radio</p>   
        </div>

    </section>
    <footer>
        <p>© 2024 Фан-сайт Rammstein. Все права защищены.</p>
    </footer>
    <script>
        function enlargeImage(img) {
            const modal = document.createElement('div');
            modal.style.position = 'fixed';
            modal.style.top = '0';
            modal.style.left = '0';
            modal.style.width = '100%';
            modal.style.height = '100%';
            modal.style.backgroundColor = 'rgba(0, 0, 0, 0.9)';
            modal.style.display = 'flex';
            modal.style.alignItems = 'center';
            modal.style.justifyContent = 'center';
            modal.onclick = () => modal.remove();

            const modalImg = document.createElement('img');
            modalImg.src = img.src;
            modalImg.style.maxWidth = '90%';
            modalImg.style.maxHeight = '90%';

            modal.appendChild(modalImg);
            document.body.appendChild(modal);
        }
    </script>
</body>
</html>
