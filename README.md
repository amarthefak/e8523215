<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>привет</title> 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #1f1f1f;
            border-bottom: 2px solid #444;
        }
        .navbar .logo {
            font-size: 24px;
            font-weight: bold;
        }
        .navbar .menu {
            display: flex;
            gap: 20px;
        }
        .navbar .menu a {
            text-decoration: none;
            color: #fff;
            font-size: 16px;
        }
        .navbar .menu a:hover {
            color: #f39c12;
        }
        .navbar .search {
            background-color: #333;
            border-radius: 5px;
            padding: 5px;
        }
        .navbar .search input {
            border: none;
            background: none;
            color: #fff;
            padding: 5px;
            width: 200px;
        }
        .navbar .search input::placeholder {
            color: #ccc;
        }
        .movie-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .cartoon-gallery {
    display: flex; /* Выравнивает элементы в строку */
    gap: 20px; /* Добавляет промежуток между картинками */
    padding: 20px;
}

.movie-card {
    background-color: #1f1f1f;
    border-radius: 8px;
    overflow: hidden;
    width: 100%; /* Убирает нежелательное сжатие картинок */
}

.movie-card img {
    width: 100%;
    border-bottom: 2px solid #444;
}

.movie-card .info {
    padding: 10px;
    text-align: center;
}

.movie-card .info h3 {
    margin: 0;
    font-size: 18px;
}

.movie-card .info p {
    margin: 5px 0;
    color: #ccc;
}

        
        .movie-card .info p {
            margin: 5px 0;
            color: #ccc;
        }
        .video-player {
            position: relative;
            background-color: black;
            max-width: 900px;
            margin: 20px auto;
            border-radius: 8px;
            overflow: hidden;
        }
        .video-player video {
            width: 100%;
        }
        .video-controls {
            position: absolute;
            bottom: 10px;
            left: 0;
            right: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            background: rgba(0, 0, 0, 0.6);
        }
        .video-controls button {
            background: none;
            border: none;
            color: #fff;
            font-size: 18px;
            cursor: pointer;
        }
        .video-controls button:hover {
            color: #f39c12;
        }
        .progress-container {
            flex: 1;
            margin: 0 10px;
        }
        .progress-bar {
            width: 100%;
            height: 5px;
            background: #444;
            cursor: pointer;
            position: relative;
        }
        .progress-bar div {
            height: 100%;
            width: 0;
            background: #f39c12;
            position: absolute;
        }
        section {
            padding: 20px;
        }
        
        .advertisement {
  width: 500px;
  margin: 20px auto; /* Центрирование баннера */
}
.advertisement img {
  width: 100%;
  height: auto;
}
body {
  background-image: url("photo_2024-11-30_17-40-00.jpg"); /* Путь к вашему изображению */
  background-size: cover; /* Заполняет весь экран, обрезая изображение */
  background-repeat: no-repeat; /* Не повторяет изображение */
  background-attachment: fixed; /* Фон не прокручивается вместе со страницей */
}

    </style>    
</head>
<body>
    <header class="navbar">
        <div class="logo">
            
        </div>
        <nav class="menu">
            <a href="#tv-series"> СЕРЕАЛЫ</a>
            <a href="#movies">Movies</a>
            <a href="#cartoons">МУЛЬТИКИ</a>
            <a href="#">Profile</a>
        </nav>
        <div class="search">
            <input type="text" id="searchInput" placeholder="Search movies..." oninput="searchMovies()">
        </div>
    </header>

    <section id="adsense-ads">
        <ins class="adsbygoogle"
             style="display:block"
             data-ad-client="YOUR_ADSENSE_CODE"
             data-ad-slot="YOUR_ADSENSE_SLOT"
             data-ad-format="auto"></ins>
        <script>
          (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
      </section>

      <section class="advertisement">
        <a href="реклама.html" target="_blank"> 
          <img src="i (8).webp" alt="Реклама 1">
        </a>
      </section>
      
    <section id="tv-series">
        <h2>TV Series</h2>
        <div class="movie-gallery" id="tvSeriesGallery">
            <div class="movie-card">
                <a href="vovcetahki.html" target="_blank">
                <img src="Снимок экрана 2024-12-01 133113.png" alt="TV Series 1">
            </a>
                <div class="info">
                    <h3>во все тяжкие</h3>
                    <p>описание: короче там пиздец</p>
                </div>
            </div>
            <div class="movie-card">
                <a href="igracol.html" target="_blank">
                <img src="Снимок экрана 2024-12-01 133752.png" alt="TV Series 2">
            </a>
                <div class="info">
                    <h3>игра в кальмара</h3>
                    <p>описание: хуйня не советую</p>
                </div>
            </div>
        </div>
    </section>

    <section id="movies">
        <h2>Movies</h2>
        <div class="movie-gallery" id="movieGallery">
            <div class="movie-card">
                <a href="gari.html" target="_blank">
                <img src="Снимок экрана 2024-12-01 132712.png" alt="Movie 1">
            </a>
                <div class="info">
                    <h3>гарри поттер</h3>
                    <p>описание: имба</p>
                </div>
            </div>
            <div class="movie-card">
                <a href="budushee.html" target="_blank">
                <img src="Снимок экрана 2024-12-01 132920.png" alt="Movie 2">
                </a>
                <div class="info">
                    <h3>назад в будущее</h3>
                    <p>описание: хз не играл</p>
                </div>
            </div>
        </div>
    </section>

    <section id="cartoons">
        <h2>Cartoons</h2>
        <div class="cartoon-gallery">
            <div class="movie-card">
                <a href="shrek.html" target="_blank">
                    <img src="Снимок экрана 2024-12-01 171913.png" alt="Cartoon 1">
                </a>
                <div class="info">
                    <h3>Шрек</h3>
                    <p>описание: Rampage</p>
                </div>
            </div>
    
            <div class="movie-card">
                <a href="luntik.html" target="_blank">
                <img src="Снимок экрана 2024-12-01 134715.png" alt="Cartoon 2">
            </a>
                <div class="info">
                    <h3>лунтик</h3>
                    <p>описание: сын скарлупы</p>
                </div>
            </div>
        </div>

    </section>
    

    <section class="video-player">
        <video id="moviePlayer" src="Dota 2 2024-11-01 22-02-30.mp4"></video>
        <div class="video-controls">
            <a href="file:///C:/code/sait.html" target="_blank"></a>
           
            <button id="playPauseBtn"><i id="playPauseIcon" class="fas fa-play"></i></button>
            <div class="progress-container">
                <div class="progress-bar" id="progressBar">
                    <div id="progress"></div>
                </div>
            </div>
            <button id="fullscreenBtn"><i class="fas fa-expand"></i></button>
        </div>
    </section>

    <script>
        const moviePlayer = document.getElementById('moviePlayer');
        const playPauseBtn = document.getElementById('playPauseBtn');
        const playPauseIcon = document.getElementById('playPauseIcon');
        const progressBar = document.getElementById('progressBar');
        const progress = document.getElementById('progress');
        const fullscreenBtn = document.getElementById('fullscreenBtn');
        const movieGallery = document.getElementById('movieGallery');
        const tvSeriesGallery = document.getElementById('tvSeriesGallery');
        const cartoonGallery = document.getElementById('cartoonGallery');
        const searchInput = document.getElementById('searchInput');

        playPauseBtn.addEventListener('click', () => {
            if (moviePlayer.paused) {
                moviePlayer.play();
                playPauseIcon.classList.remove('fa-play');
                playPauseIcon.classList.add('fa-pause');
            } else {
                moviePlayer.pause();
                playPauseIcon.classList.remove('fa-pause');
                playPauseIcon.classList.add('fa-play');
            }
        });

        moviePlayer.addEventListener('timeupdate', () => {
            const percentage = (moviePlayer.currentTime / moviePlayer.duration) * 100;
            progress.style.width = percentage + '%';
        });

        progressBar.addEventListener('click', (e) => {
            const clickX = e.offsetX;
            const width = progressBar.offsetWidth;
            const newTime = (clickX / width) * moviePlayer.duration;
            moviePlayer.currentTime = newTime;
        });

        fullscreenBtn.addEventListener('click', () => {
            if (!document.fullscreenElement) {
                moviePlayer.requestFullscreen();
            } else {
                document.exitFullscreen();
            }
        });

        function searchMovies() {
            const query = searchInput.value.toLowerCase();
            const galleries = [movieGallery, tvSeriesGallery, cartoonGallery];

            galleries.forEach(gallery => {
                const movies = gallery.getElementsByClassName('movie-card');
                for (let i = 0; i < movies.length; i++) {
                    const title = movies[i].querySelector('h3').textContent.toLowerCase();
                    if (title.includes(query)) {
                        movies[i].style.display = 'block';
                    } else {
                        movies[i].style.display = 'none';
                    }
                }
            });
        }
    </script>
</body>
</html>
