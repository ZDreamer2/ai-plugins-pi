# AI Plugins for Pi

This repository contains the generated Pi distribution of [AI Plugins](https://github.com/ZDreamer2/ai-plugins).

## Install

Requires Pi and Git. This repository contains two independent packages, so clone it to a permanent location and install the package directories you need:

```sh
git clone https://github.com/ZDreamer2/ai-plugins-pi.git
pi install ./ai-plugins-pi/ai-doc
pi install ./ai-plugins-pi/ai-marketplace
```

Install either package or both, then start a new Pi session. These are local-path installs: keep the checkout in place. To update, run `git -C ai-plugins-pi pull --ff-only` and start a new session. The repository root is not itself a Pi package.

## Usage and documentation

See the [main repository](https://github.com/ZDreamer2/ai-plugins) for available plugins, examples and documentation. Building from source is unnecessary for installation.

## Source and changes

This repository is replaced automatically during publication. Report issues and propose changes in the [source repository](https://github.com/ZDreamer2/ai-plugins), rather than editing generated files here.

## License

See `LICENSE` and the bundled third-party license notices.
