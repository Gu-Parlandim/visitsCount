# counter

#### Deploying on your own server

```shell
$ git clone https://github.com/journey-ad/Moe-counter.git
$ cd Moe-counter
$ yarn install

$ yarn start
```

### Confignation

`config.yml`

```yaml
app:
  port: 3000

db:
  type: mongodb # sqlite or mongodb
```

If you use mongodb, you need to specify the environment variable `DB_URL`

```shell
# eg:
export DB_URL=mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count
```

```
DB_URL="mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count"
```

## Credits

- [repl.it](https://repl.it/)
- [A-SOUL](https://www.asoulworld.com/) <sup>(非官方导航站)</sup>
- [moebooru](https://github.com/moebooru/moebooru)
- rule34.xxx NSFW
- gelbooru.com NSFW
- [Icons8](https://icons8.com/icons/set/star)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-counter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-counter?ref=badge_large)
