<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Spotify Clone</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="app">
    <aside class="sidebar">
      <div class="logo">
        <svg viewBox="0 0 24 24" width="32" height="32" fill="white"><circle cx="12" cy="12" r="12"/></svg>
        <span>Spotify</span>
      </div>
      <nav class="nav">
        <a href="#" class="nav-item active">
          <svg viewBox="0 0 24 24" width="24" height="24" fill="currentColor"><path d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-4 0a1 1 0 01-1-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 01-1 1"/></svg>
          Home
        </a>
        <a href="#" class="nav-item">
          <svg viewBox="0 0 24 24" width="24" height="24" fill="currentColor"><path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
          Search
        </a>
        <a href="#" class="nav-item">
          <svg viewBox="0 0 24 24" width="24" height="24" fill="currentColor"><path d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"/></svg>
          Your Library
        </a>
      </nav>
      <div class="library">
        <div class="playlist-card">
          <div class="playlist-icon liked">♥</div>
          <div class="playlist-info">
            <p class="playlist-name">Liked Songs</p>
            <p class="playlist-desc">Playlist • 42 songs</p>
          </div>
        </div>
        <div class="playlist-card">
          <div class="playlist-icon chill">☁</div>
          <div class="playlist-info">
            <p class="playlist-name">Chill Vibes</p>
            <p class="playlist-desc">Playlist • 18 songs</p>
          </div>
        </div>
        <div class="playlist-card">
          <div class="playlist-icon workout">⚡</div>
          <div class="playlist-info">
            <p class="playlist-name">Workout</p>
            <p class="playlist-desc">Playlist • 32 songs</p>
          </div>
        </div>
        <div class="playlist-card">
          <div class="playlist-icon focus">🎯</div>
          <div class="playlist-info">
            <p class="playlist-name">Focus Mode</p>
            <p class="playlist-desc">Playlist • 25 songs</p>
          </div>
        </div>
      </div>
    </aside>
    <main class="main-content">
      <header class="topbar">
        <div class="topbar-nav">
          <button class="nav-btn">‹</button>
          <button class="nav-btn">›</button>
        </div>
        <div class="user-menu">
          <div class="avatar">M</div>
        </div>
      </header>
      <section class="greeting">
        <h1>Good evening</h1>
      </section>
      <section class="quick-picks">
        <div class="pick-card">
          <div class="pick-img" style="background-color:#e13300;">♥</div>
          <span>Liked Songs</span>
        </div>
        <div class="pick-card">
          <div class="pick-img" style="background-color:#1e3264;">☁</div>
          <span>Chill Vibes</span>
        </div>
        <div class="pick-card">
          <div class="pick-img" style="background-color:#e8115b;">⚡</div>
          <span>Workout</span>
        </div>
        <div class="pick-card">
          <div class="pick-img" style="background-color:#148a08;">🎯</div>
          <span>Focus Mode</span>
        </div>
        <div class="pick-card">
          <div class="pick-img" style="background-color:#8c1932;">♫</div>
          <span>Road Trip</span>
        </div>
        <div class="pick-card">
          <div class="pick-img" style="background-color:#608108;">♪</div>
          <span>Acoustic</span>
        </div>
      </section>
      <section class="section">
        <h2>Made For You</h2>
        <div class="card-row">
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #7358ff, #a855f7);">♫</div>
            <p class="card-title">Daily Mix 1</p>
            <p class="card-sub">Artist 1, Artist 2 and more</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #1db954, #148a08);">♪</div>
            <p class="card-title">Daily Mix 2</p>
            <p class="card-sub">Artist 3, Artist 4 and more</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #e8115b, #b5179e);">☁</div>
            <p class="card-title">Daily Mix 3</p>
            <p class="card-sub">Artist 5, Artist 6 and more</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #f59e0b, #d97706);">⚡</div>
            <p class="card-title">Discover Weekly</p>
            <p class="card-sub">Your weekly mixtape</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #06b6d4, #0284c7);">🎯</div>
            <p class="card-title">Release Radar</p>
            <p class="card-sub">New from artists you follow</p>
          </div>
        </div>
      </section>
      <section class="section">
        <h2>Recently Played</h2>
        <div class="card-row">
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #dc2626, #991b1b);">🎸</div>
            <p class="card-title">Rock Classics</p>
            <p class="card-sub">Queen, Led Zeppelin, AC/DC</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #7c3aed, #4f46e5);">🎹</div>
            <p class="card-title">Lo-Fi Beats</p>
            <p class="card-sub">Chill beats to relax</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #059669, #047857);">🎤</div>
            <p class="card-title">Top Hits</p>
            <p class="card-sub">Today's top 50</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #ea580c, #c2410c);">🎧</div>
            <p class="card-title">Indie Mix</p>
            <p class="card-sub">Indie vibes playlist</p>
          </div>
          <div class="card">
            <div class="card-img" style="background: linear-gradient(135deg, #db2777, #9d174d);">💃</div>
            <p class="card-title">Dance Party</p>
            <p class="card-sub">Feel the beat</p>
          </div>
        </div>
      </section>
    </main>
  </div>
  <footer class="player-bar">
    <div class="player-left">
      <div class="player-thumb" style="background: linear-gradient(135deg, #1db954, #148a08);">♫</div>
      <div class="player-track">
        <p class="track-name">Placeholder Song</p>
        <p class="track-artist">Placeholder Artist</p>
      </div>
      <button class="player-btn like-btn">♥</button>
    </div>
    <div class="player-center">
      <div class="player-controls">
        <button class="ctrl-btn">⇄</button>
        <button class="ctrl-btn">⏮</button>
        <button class="ctrl-btn play-btn">▶</button>
        <button class="ctrl-btn">⏭</button>
        <button class="ctrl-btn">⇄</button>
      </div>
      <div class="progress-bar">
        <span class="time">0:00</span>
        <div class="progress-track">
          <div class="progress-fill"></div>
        </div>
        <span class="time">3:42</span>
      </div>
    </div>
    <div class="player-right">
      <button class="ctrl-btn">♫</button>
      <button class="ctrl-btn">🔈</button>
      <div class="volume-track">
        <div class="volume-fill"></div>
      </div>
    </div>
  </footer>
</body>
</html>
