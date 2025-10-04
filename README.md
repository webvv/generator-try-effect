
<h1 align="center">
  <br>
  <a href="">
  <img src="https://raw.githubusercontent.com/webvv/generator-try-effect/main/assets/try_icon_purple_orange.png" alt="My image" onerror="this.onerror=null; this.src='./assets/try_icon_purple_orange.png';" alt="try-effect" width="200">
  </a>
  <br>
  Try Effect
  <br>
</h1>

<h4 align="center">Yeoman generator to scaffold an ephemeral playground for quickly experimenting Effect.</h4>


<p align="center">
  <a href="#requirements">Requirements</a> •
  <a href="#how-to-use">How to Use</a> •
  <a href="#how-to-develop">How to Develop</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a> •
  <a href="#credits">Credits</a>
</p>

## Requirements

This generator assumes you have these already setup:
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/)
- [Yeomon](https://yeoman.io/)

## How to Use

> **Note:** The idea behind this generator is to simply open a terminal in any directory, and run `yo try-effect`. It immediately opens a playground in your favorite editor.

>**Can't see your favorite editor?** Open the configuration file located at `~/.yo-rc.try-effect.json` and edit the editors field.

Install the generator:

```sh
npm install -g generator-try-effect
```

Run below and answer questions one by one:
```sh
yo try-effect
```
Or answer everything at once:
```sh
yo try-effect --projectParentPath ~/try \  
            --projectName try_effect \
            --selectedEditorId vscode
```

## How to Develop

> **Note:** You can reset the config file by running `yo try-effect:reset`.

Clone and link the project:

```sh
git clone https://github.com/webvv/generator-try-effect.git
cd generator-try-effect
npm install
npm link
```

You are now ready to scaffold from your local try-effect generator:

```sh
yo try-effect
```

## Support ♥️

If you like this project and it helped you, please consider supporting me on <a href="https://www.patreon.com/webvv" target="_blank">Patreon</a>.

## License

MIT

## Credits
> Author [Sahand Javid]() &nbsp;&middot;&nbsp;
> GitHub [@webvv](https://github.com/webvv) &nbsp;&middot;&nbsp;
> Youtube [webvv](https://youtube.com/webvv)

