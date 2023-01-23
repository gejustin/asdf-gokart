# asdf-gokart [![Build](https://github.com/gejustin/asdf-gokart/actions/workflows/build.yml/badge.svg)](https://github.com/gejustin/asdf-gokart/actions/workflows/build.yml) [![Lint](https://github.com/gejustin/asdf-gokart/actions/workflows/lint.yml/badge.svg)](https://github.com/gejustin/asdf-gokart/actions/workflows/lint.yml)

[gokart](https://github.com/gejustin/asdf-gokart) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

## Install

Plugin:

```shell
asdf plugin add gokart https://github.com/gejustin/asdf-gokart.git
```

gokart:

```shell
# Show all installable versions
asdf list-all gokart

# Install specific version
asdf install gokart latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gokart latest

# Now gokart commands are available
gokart version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gejustin/asdf-gokart/graphs/contributors)!

## License

See [LICENSE](LICENSE) © [Gary Justin](https://github.com/gejustin/)
