# 迷路 レベル２

## Step 1

最初にエージェントを前に進めてみよう！

```blocks
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
```

## Step 2

迷路をゴールしてみよう！

```blocks
player.onChat("run", function () {
    agent.move(FORWARD, 4)
    agent.move(RIGHT, 3)
    agent.move(FORWARD, 3)
})
```

## Step 3

次は条件分岐を使用してゴールしてみよう！
```blocks
if (true) {   
}
```
これを使うよ！

![迷路条件分岐](https://github.com/ta-bo914/maze-Tutorial/blob/5590ab88d20512e1f11718d43a21ae1ff5666da0/images/maze1.png "迷路")