# Guess the Number (Ow)

A console number-guessing game. The computer picks 1-100; you guess.

Written in **[Ow](https://github.com/OW-Programing-Language/ow-lang)** in an
object-oriented style — **one class per file**.

## Structure

```
src/
  Game.ow      # class Game — secret number, tries, guess() logic
  main.ow      # entry point (main) — the input loop
```

## Run it

Install Ow (download from the
[ow-lang releases](https://github.com/OW-Programing-Language/ow-lang/releases) —
the native installer needs no Java), then:

```sh
ow run src/main.ow
```

Or open `src/main.ow` in **OwIDE** and press **Run ▶** (or **UI Native ▶** /
**UI Web ▶** for the graphical versions).

## License

[MIT](LICENSE).
