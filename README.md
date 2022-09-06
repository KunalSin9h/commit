# commit
Git commit simulator using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) conventions.


## Installation
### Debian/Ubuntu
```bash
curl -fsSL https://kunalsin9h.dev/commit | bash
```
After Installing, add the following to your `.bashrc` file
```bash
export COMMIT_INSTALL="$HOME/.commit"
export PATH="$COMMIT_INSTALL/bin:$PATH"
```

## Usage
Go to your project directory and run `commit` command.
```bash
$ cd my-project
$ commit
```

## Inspiration
This project is inspired by [gum](https://github.com/charmbracelet/gum)

## License
[MIT](https://github.com/KunalSin9h/commit/blob/master/LICENSE)

