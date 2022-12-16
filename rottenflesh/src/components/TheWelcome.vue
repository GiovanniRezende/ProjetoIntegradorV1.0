<template>
  <header class="header">
    <img class="icon" src="img/icon.jpg" alt="" />

    <h1>SpotifyApp</h1>
  </header>
  <div class="container">
    <h1 class="title">Músicas</h1>
    <div class="row_music">
      <div class="row_music_right">
        <div class="music_id"></div>
        <div class="music_icon"><img src="img/mayhem.jpeg" alt="" /></div>
        <div class="music_info">
          <div class="music_title">Chainsaw Gutsfuck</div>
          <div class="music_author">Mayhem</div>
        </div>
      </div>
      <div class="row_music_left">
        <div class="music_duration">3:20</div>
      </div>
    </div>
    <div class="row_music">
      <div class="row_music_right">
        <div class="music_id"></div>
        <div class="music_icon"><img src="img/bathory.webp" alt="" /></div>
        <div class="music_info">
          <div class="music_title">A Fine Day To Die</div>
          <div class="music_author">Bathory</div>
        </div>
      </div>
      <div class="row_music_left">
        <div class="music_duration">6:20</div>
      </div>
    </div>
    <div class="row_music">
      <div class="row_music_right">
        <div class="music_id"></div>
        <div class="music_icon"><img src="img/gorgoroth.jpeg" alt="" /></div>
        <div class="music_info">
          <div class="music_title">Profetens Apenbaring</div>
          <div class="music_author">Gorgoroth</div>
        </div>
      </div>
      <div class="row_music_left">
        <div class="music_duration">7:20</div>
      </div>
    </div>
    <div class="row_music">
      <div class="row_music_right">
        <div class="music_id"></div>
        <div class="music_icon"><img src="img/chakal.jpeg" alt="" /></div>
        <div class="music_info">
          <div class="music_title">May Not The Mankind Suffer</div>
          <div class="music_author">Chakal</div>
        </div>
      </div>
      <div class="row_music_left">
        <div class="music_duration">4:40</div>
      </div>
    </div>
  </div>
  <div class="containeraside">
    <aside class="aside">
      <p>sidebar</p>
    </aside>
  </div>
  <div class="footer">
    <footer
      class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top"
    >
      <p class="col-md-4 mb-0 text-muted">&copy; 2022 Company, Inc</p>

      <a href="/">
        <svg class="bi me-2" width="40" height="32">
          <use xlink:href="#bootstrap" />
        </svg>
      </a>

      <div class="bottom-bar">
        <div class="player">
          <div class="player-controls">
            <span class="player-prev">Prev</span>
            <span class="player-play">Play</span>
            <span class="player-pause">Pause</span>
            <span class="player-stop">Stop</span>
            <span class="player-next">Next</span>
          </div>
          <div class="player"></div>
          <div class="player-timeline">
            <div class="player-timeline-control"></div>
          </div>
          <div class="player-display">
            Playing: <span class="player-current-track"></span>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.player {
  margin: auto;
  width: 960px;
}
.bottom-bar .player-controls {
  float: left;
}

.bottom-bar .player-controls span {
  cursor: pointer;
  padding: 0 5px;
  -webkit-transition: all linear 0.2s;
}
.bottom-bar .player-display {
  float: left;
  float: right;
  margin-left: 50px;
}
.bottom-bar .player-controls span:hover {
  color: #eee;
}
.bottom-bar .player-display .player-current-track {
  color: white;
}
.bottom-bar .player {
  float: left;
}
.bottom-bar .player-timeline {
  float: left;
  max-width: 200px;
  width: 200px;
  height: 4px;
  margin-top: 13px;-*
  background: #555;
  margin-left: 20px;
}
.bottom-bar .player-timeline-control {
  height: 4px;
  background: #999;
}
.bottom-bar {
  padding: 0;
  margin: 0;
  font-family: sans-serif;
  width: 100%;
  height: 30px;
  background: #141414;
  color: #888;
  line-height: 30px;
}
.nav-item {
  text-align: center;
}
.footer {
  background-color: rgb(124, 101, 101);
  align-items: center;
}
.aside {
  grid-area: barra-lateral;
  background-color: #e0d475;
  padding-left: 3%;
}
.title {
  font-size: 40px;
  color: white;
  padding-top: 10px;
  text-align: center;
}
.row_music {
  padding: 25px;
  padding-top: 10px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  color: white;
  font-size: 16px;
}

.row_music_right {
  display: flex;
  flex-direction: row;
}

.music_icon img {
  width: 50px;
  border: 2px solid black;
}
.music_title {
  padding-left: 9px;
}
.music_author {
  padding-left: 9px;
}
.header {
  font-size: 20px;
  font-family: Impact;
  text-align: left;
  display: flex;
  flex-direction: row;
  align-items: center;
  background-color: rgb(54, 49, 49);
  padding: 20px 20px;
}
.icon {
  width: 80px;
  border: 2px solid black;
  border-radius: 55px;
}
</style>
