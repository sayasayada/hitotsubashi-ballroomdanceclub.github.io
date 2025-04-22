# hitotsubashi-ballroomdanceclub.github.io
ALL一橋競技ダンス部のHP
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ALL一橋大学競技ダンス部</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- ナビゲーションバー -->
  <header>
    <nav class="navbar">
      <div class="logo">ALL一橋大学競技ダンス部</div>
      <ul class="nav-links">
        <li><a href="#about">活動紹介</a></li>
        <li><a href="#members">部員紹介</a></li>
        <li><a href="#contact">お問い合わせ</a></li>
      </ul>
    </nav>
  </header>

  <!-- トップ（Heroセクション） -->
  <section class="hero">
    <div class="hero-text">
      <h1>ようこそ！ALL一橋大学競技ダンス部へ</h1>
      <p>情熱と仲間がここにある。</p>
    </div>
  </section>

  <!-- 活動紹介 -->
  <section id="about" class="section">
    <h2>活動紹介</h2>
    <p>私たちは週3回、一橋大学東体育館で練習し、大会やイベントに出場しています！</p>
  </section>

  <!-- 部員紹介 -->
  <section id="members" class="section">
    <h2>部員紹介</h2>
    <p>個性豊かな仲間たちを紹介します！（写真付きにしても◎）</p>
  </section>

  <!-- お問い合わせ -->
  <section id="contact" class="section">
    <h2>お問い合わせ</h2>
    <p>見学・体験は大歓迎！お気軽にInstagramのDMまで📩</p>
  </section>

  <footer>
    <p>&copy; 2025 一橋大学競技ダンス部</p>
  </footer>

/* 全体リセット */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', sans-serif;
}

body {
  line-height: 1.6;
  background-color: #fff;
  color: #333;
}

/* ナビゲーション */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #222;
  padding: 1rem 2rem;
  position: sticky;
  top: 0;
  z-index: 10;
}

.navbar .logo {
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.nav-links li a {
  color: white;
  text-decoration: none;
  transition: color 0.3s;
}

.nav-links li a:hover {
  color: #f0a500;
}

/* ヒーロー画像セクション */
.hero {
  background-image: url("your-image.jpg"); /* 写真を入れよう！ */
  background-size: cover;
  background-position: center;
  height: 100vh;
  position: relative;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.hero-text h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.hero-text p {
  font-size: 1.2rem;
}

/* 各セクション */
.section {
  padding: 4rem 2rem;
  max-width: 800px;
  margin: auto;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  text-align: center;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #222;
  color: white;
  font-size: 0.9rem;
}



