# ssb handbook ![Hermes the hermit crab](assets/hermes.png)

A work-in-progress guide to the ssb-verse and key concepts and influences

## What Is Scuttlebutt?

Historically, sea-slang for gossip - a scuttlebutt is basically a watercooler on a ship.

Scuttlebutt is a decent(ralised) secure gossip platform.

> This seems like a silly name, but I assure you, this is real science. Read this: http://www.cs.cornell.edu/home/rvr/papers/flowgossip.pdf
>
> Or, if you're lazy: http://en.wikipedia.org/wiki/Scuttlebutt (laziness will get you nowhere, btw)

## How To Get Started

The easiest way to get started is using [patchwork](https://github.com/ssbc/patchwork), a classic social networking [application](./applications.md).

![screenshot of patchwork](./assets/patchwork.jpg)

## Download and Install Patchwork

Download installers for Windows, macOS and Linux from [patchwork/releases](https://github.com/ssbc/patchwork/releases)

Or you can build from source with [node and npm installed](https://github.com/creationix/nvm):

```shell
$ git clone https://github.com/ssbc/patchwork
$ cd patchwork
$ npm install
$ npm start
```

On Linux you'll need some more dependencies. On Debian:

```shell
sudo apt-get install libxext-dev libxtst-dev libxkbfile-dev g++ m4 automake libtool
```

### Be Invited To A Pub

In order to gossip outside your local network, you'll need to connect to a [Pub](./concepts/pub.md).

You can find an invite to an available pub at the [Pub servers registry](https://github.com/ssbc/scuttlebot/wiki/Pub-Servers).

Get an invite, then in `patchwork`: click "+ Join Pub" and paste the invite code.

This will cause you to follow the Pub and vise versa. If you haven't synchronized to this social network yet, prepare to wait a few minutes while your local server synchronizes.

## About This Handbook

To view the public handbook, browse to <http://scuttlebutt.nz>.

You can also build and serve this with gitbook locally.


The `SUMMARY.md` is the manifest on which the compiled gitbook is based. Edit that if you want content in/out of the book.

### Contributing With `git-ssb`

To use the public portal for the handbook code, browse to <https://git.scuttlebot.io/%25lJsDWwnF4bDxHWYuSjw%2FbW37xg%2BsaF8WtPZYZsefKj0%3D.sha256>.

To use your local scuttlebot server to clone the handbook code:

```bash
npm install git-ssb -g
git clone ssb://%lJsDWwnF4bDxHWYuSjw/bW37xg+saF8WtPZYZsefKj0=.sha256 ssb-handbook

cd ssb-handbook
npm install
npm start
```

To contribute to the handbook code, make a pull request with

```
git ssb pull-request
```

### Contributing with GitHub

Our public GitHub repository is at [ssbc/ssb-handbook](https://github.com/ssbc/ssb-handbook)

Feel free to make an issue or pull request here if you see something that needs doing.

## Other Projects

Scuttlebutt is not the only project working on [decent](glossary.md#decent) systems:

- [Matrix](http://matrix.org/)
- [Bitcoin](https://bitcoin.org/)
- [Ethereum](https://www.ethereum.org/)
- [Zerocoin](http://zerocoin.org/)
- [MaidSafe](http://maidsafe.net/)
- [IPFS](https://ipfs.io/)
- [Dat](http://datproject.org/)
- [Solid](https://github.com/solid/solid)
- [cjdns](https://github.com/cjdelisle/cjdns)
- [Syncthing](https://syncthing.net/)
- [Indie](https://ind.ie/)
- [Twister](http://twister.net.co/)
- [WebTorrent](https://webtorrent.io/)
- [StrongLink](https://github.com/btrask/stronglink)
- [RetroShare](http://retroshare.sourceforge.net)
- [ZeroNet](http://zeronet.io)
