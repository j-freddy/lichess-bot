# MirroredBot

Forked from [lichess-bot][lichess-bot].

[lichess-bot]: https://github.com/lichess-bot-devs/lichess-bot

## Run

Create `.env.local` file and set `LICHESS_API_TOKEN` variable. See
[lichess-bot][lichess-bot] for run instructions. Add `MirroredBot.exe` to `engines/`. See my [engine][chess-ai] for the file.

[chess-ai]: https://github.com/j-freddy/chess-ai

```py
python lichess-bot.py -v
```

## Contribute

```
pip freeze > requirements.txt
```
