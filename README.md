[![primary](https://github.com/trallnag/asdf-kubectx/actions/workflows/primary.yaml/badge.svg)](https://github.com/trallnag/asdf-kubectx/actions/workflows/primary.yaml)

# asdf-kubectx

[kubectx](https://github.com/ahmetb/kubectx/) plugin for the
[asdf version manager](https://asdf-vm.com).

This plugin installs kubectx. It does not setup shell auto completion nor
installs required OS dependencies like kubectl itself.

## Install

### Plugin

Use one of the following two commands.

    asdf plugin add kubectx
    asdf plugin add kubectx https://github.com/trallnag/asdf-kubectx

### kubectx

Show all installable versions.

    asdf list all kubectx

Install specific version.

    asdf install kubectx latest

Set a version globally (in your `~/.tool-versions` file).

    asdf global kubectx latest

Now kubectx commands are available.

    kubectx --help

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on
how to install & manage versions.

## Links

- [Central plugin repo for asdf](https://github.com/asdf-vm/asdf-plugins)
- [Code repository of this plugin](https://github.com/trallnag/asdf-kubectx)
- [Kubectx homepage](https://kubectx.dev)
- [Kubextx repository on GitHub](https://github.com/ahmetb/kubectx)
