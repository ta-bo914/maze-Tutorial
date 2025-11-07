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
player.onChat("run", function () {
    if (true) {   
    }
})
```
これを使うよ！

