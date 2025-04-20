---
layout: default
---

.navbar {
  background-color: #222;
  overflow: hidden;
  font-family: sans-serif;
}
.navbar a, .dropdown .dropbtn {
  float: left;
  font-size: 14px;
  color: white;
  text-align: center;
  padding: 12px 16px;
  text-decoration: none;
}
.dropdown {
  float: left;
  overflow: hidden;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #333;
  min-width: 200px;
  z-index: 1;
}
.dropdown-content a {
  float: none;
  color: white;
  padding: 10px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #555;
}

/* ホバーで表示 */
.dropdown:hover .dropdown-content {
  display: block;
}
</style>

<div class="navbar">
  <div class="dropdown">
    <button class="dropbtn">キャラクター強化要素一覧 ▼</button>
    <div class="dropdown-content">
      <a href="#">装備更新ガイド</a>
      <a href="#">装備強化</a>
      <a href="#">チューニング</a>
      <a href="#">コスチューム</a>
      <a href="#">アクセサリー/コンビネーション</a>
      <a href="#">リベレーションオーラ</a>
      <a href="#">PNA</a>
      <a href="#">突然変異PNA</a>
      <a href="#">チップ/強化アダプター</a>
      <a href="#">ペット</a>
      <a href="#">称号</a>
      <a href="#">スキルキューブ</a>
      <a href="#">チームワークパワ</a>
    </div>
  </div>
</div>

# ここは？

CLOSERSのガイドやデータが書いてある物置です

## 目次

- [キャラクター一覧](./characters.md)
- [スキル](./skills.md)
- [装備品](./items.md)
