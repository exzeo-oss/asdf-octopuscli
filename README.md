# asdf-octopuscli

[Octopus Deploy CLI](https://github.com/OctopusDeploy/cli) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add octopuscli https://github.com/exzeo-devops/asdf-octopuscli.git
```

### Environment Variable Options

- ASDF_OCTOPUSCLI_OVERWRITE_ARCH: force the plugin to use a specified processor architecture rather than the automatically detected value. Useful, for example, for allowing users on M1 Macs to install `amd64` binaries when there's no `arm64` binary available.

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of Octopus CLI.
