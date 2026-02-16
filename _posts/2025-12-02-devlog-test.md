---
layout: post
title: "Тест подсветки и лейблов"
categories: [devlog]
---

Сейчас проверим, как работает наша система. Вот скрипт движения игрока на **JavaScript**:

```txt
const player = {
    x: 10,
    y: 20,
    hp: 100
};

function update() {
    // Простая логика
    if (player.hp > 0) {
        player.x += 1;
    }
}
```