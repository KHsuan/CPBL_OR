## Latex link
https://www.overleaf.com/1249432627gtwdjcnbcwyt

## How to Get Parameters

### A\_{ij}

- def: if player $i$ can play position $j$
- 使用方式
  ```
  player.canPlay
  # player: class Player
  # return: 長度為 9 的陣列
  ```

### V\_{ij}

- def: score of player $i$ on position $j$
- 使用方式
  ```
  calcV(game, player, pos)
  # game: Dictionary game
  # player: class Player
  # pos: int(0~8)
  # return float
  ```

## Todos

- 2022 年在 27 人名單上的球員，若 2021 年沒有他的資料怎麼處理
- objective function 簡化成一行（否則完全沒辦法跑）
- 完成限制式
- debug
