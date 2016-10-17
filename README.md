# What is tsiv-ccminer-cryptonight?

tsiv-ccminer-cryptonight is a modification of Christian Buchner's & Christian H.'s ccminer project by tsiv for Cryptonight mining.

## Links

- [Discussion](https://bitcointalk.org/index.php?topic=656841.msg7487737#msg7487737)
- [Source Code](https://github.com/tsiv/ccminer-cryptonight)
- [Dockerfile](https://github.com/minecoins/docker-tsiv-ccminer-cryptonight)

# How to use this image

Run in background:

```console
$ docker run -td --name some-tsiv-ccminer-cryptonight minecoins/tsiv-ccminer-cryptonight -o stratum+tcp://monerohash.com:3333 -u 49TfoHGd6apXxNQTSHrMBq891vH6JiHmZHbz5Vx36nLRbz6WgcJunTtgcxnoG6snKFeGhAJB5LjyAEnvhBgCs5MtEgML3LU -p x
```

Fetch logs of a container:

```console
$ docker logs some-tsiv-ccminer-cryptonight
```

# Donations

Donations for work on dockerizing are accepted at:

- BTC: `1NUMFM6UTv9iRVVzjsfhzbAGjwNxQRA8Qz`
- XMR: `49TfoHGd6apXxNQTSHrMBq891vH6JiHmZHbz5Vx36nLRbz6WgcJunTtgcxnoG6snKFeGhAJB5LjyAEnvhBgCs5MtEgML3LU`
