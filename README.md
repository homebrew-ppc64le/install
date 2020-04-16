# Homebrew (un)installer for Linux PPC64LE

## Install Homebrew

```bash
export HOMEBREW_DEVELOPER=1
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/homebrew-ppc64le/install/master/install.sh)"
```

More installation information and options at https://docs.brew.sh/Installation.html.

## Uninstall Homebrew

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/homebrew-ppc64le/install/master/uninstall)"
```

Download the uninstall script and run `./uninstall --help` to view more uninstall options.
