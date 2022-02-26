# snowflake-template
A [BastilleBSD](https://bastillebsd.org) template to bootstrap snowflake from the [TOR Project](https://www.torproject.org/)

[Snowflake](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/snowflake/-/wikis/home) is a pluggable transport that proxies traffic through temporary proxies using WebRTC, a peer-to-peer protocol with built-in NAT punching. It aims to work kind of like flash proxy, but without flash proxy's problems with NAT.

# Bootstrap

```sh
bastille bootstrap https://github.com/ddowse/snowflake-template
```

# Apply & Run

```sh
bastille template TARGET ddowse/snowflake-template
```

## Info

Logfile: `/var/log/snowflake.log`
