# Dockerized IRC ( InspIRCd )

![logo](https://avatars0.githubusercontent.com/u/1560750?s=200&v=4)

![Github](https://github.com/hatamiarash7/Docker-IRC/workflows/Github/badge.svg?branch=master) ![Dockerhub](https://github.com/hatamiarash7/Docker-IRC/workflows/Dockerhub/badge.svg?branch=master)

InspIRCd is a modular Internet Relay Chat (IRC) server written in C++. It was created from scratch to be stable, modern and lightweight. It provides a tunable number of features through the use of an advanced but well documented module system. By keeping core functionality to a minimum we hope to increase the stability, security and speed of InspIRCd while also making it customisable to the needs of many different users.

## Usage

Pull image :

```bash
docker pull hatamiarash7/irc-server
```

Configure `irc.conf` and :

```bash
docker run -p 6667:6667 -v irc.conf:/inspircd/conf/inspircd.conf hatamiarash7/irc-server
```

## Support

[![Donate with Bitcoin](https://en.cryptobadges.io/badge/micro/3GhT2ABRuHuXGNzP6DH5KvLZRTXCBKkx2y)](https://en.cryptobadges.io/donate/3GhT2ABRuHuXGNzP6DH5KvLZRTXCBKkx2y) [![Donate with Ethereum](https://en.cryptobadges.io/badge/micro/0x4832fd8e2cfade141dc4873cc00cf77de604edde)](https://en.cryptobadges.io/donate/0x4832fd8e2cfade141dc4873cc00cf77de604edde)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/D1D1WGU9)

<div><a href="https://payping.ir/@hatamiarash7"><img src="https://cdn.payping.ir/statics/Payping-logo/Trust/blue.svg" height="128" width="128"></a></div>

## Contributing

1. Fork it !
2. Create your feature branch : `git checkout -b my-new-feature`
3. Commit your changes : `git commit -am 'Add some feature'`
4. Push to the branch : `git push origin my-new-feature`
5. Submit a pull request :D

## Issues

Each project may have many problems. Contributing to the better development of this project by reporting them.
