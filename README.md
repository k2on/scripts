# Scripts

All my shell scripts.

[video-httpc]: https://www.youtube.com/watch?v=byKC9kLIWtE
[video-srcn]: https://www.youtube.com/watch?v=v8DgcWftsWE


## Index

- [bye](#bye)
- [httpc](#httpc) [[🎥](video-httpc)]
- [rain](#rain)
- [src](#src)
- [srcn](#srcn) [[🎥](video-srcn)]

## bye

Put computer to sleep. Bye bye 👋

## httpc

Search HTTP status codes. [Video](video-httpc)

```sh
httpc 200
# 200	OK

httpc not found
# 404   NOT FOUND
```

## rain

Display a doppler radar with [mpv](https://mpv.io/). Inspired from [this video](https://www.youtube.com/watch?v=qNtjud8zNa0). Pass in a flag to select from a list of places using [fzf](https://github.com/junegunn/fzf).

```sh
cat lib/places
# Home    CODE
# Away 1    CODE
# Away 2    CODE
```

```sh
# Use first code in places list
rain
# Select from list
rain -a
```

## scr

Find and edit a specific script.

## scrn

Create a new shell script. [Video](video-srcn)

```sh
# create an open in vi
scrn greet

# create with command
scrn greet "echo hello world"
```

## unix

Original artwork by [http://www.sanderfocus.nl/#/portfolio/tech-heroes](http://www.sanderfocus.nl/#/portfolio/tech-heroes)

Converted to shell by #nixers @ irc.unix.chat

