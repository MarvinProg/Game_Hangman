# Игра Виселица

"Виселица" - классическая игра на угадывания слов для всей семьи!

[Статья на wikipedia](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))

# Правила

- Компьютер загадывает слово и показывает сколько в нём букв игроку
- Игрок вводит буквы по одной
- Если буква в слове есть, она показывается в слове игроку
- Если слово отгадано полностью игрок победит
- После каждой ошибки, дорисовывается виселица
- У игрока всего 7 ошибок

# Скриншот

![Hangman!](./img/68747470733a2f2f692e696d6775722e636f6d2f6f534b374c544a2e706e67.png)

# Как запустить

```
git clone git@github.com:MarvinProg/Game_Hangman.git
cd Game_Hangman
bundle install
ruby main.rb
```

# Добавление новых слов

Новые слова добавляются в `data/words.txt`. **Обязательно заглавными буквами**

# Версия

ruby 2.7.2
